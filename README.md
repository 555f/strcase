# StrCase lib

- ToCamel(s string) string - `CamelCase`
- ToLowerCamel(s string) string - `lowerCamelCase`
- ToSnake(s string) string - `snake_case`
- ToSnakeWithIgnore(s string, ignore uint8) string - `snake_case`
- ToScreamingSnake(s string) string - `SCREAMING_SNAKE_CASE`
- ToKebab(s string) string - `kebab-case`
- ToScreamingKebab(s string) string - `SCREAMING-KEBAB-CASE`
- ToDelimited(s string, delimiter uint8) string - `delimited.snake.case`
- ToScreamingDelimited(s string, delimiter uint8, ignore uint8, screaming bool) string - `SCREAMING.DELIMITED.SNAKE.CASE`

For add acronym use `AddAcronym(acronym, v string)`