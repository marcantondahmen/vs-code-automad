# Automad Template Language 

This extensions adds *syntax highlighting* and *code snippets* for the [Automad](https://automad.org) template language.

## Snippets

The following snippets are available for autocompletion:

| Prefix | Description | Body |
| --- | --- | --- |
| `<@ `| statement block | `<@ $0 @>` |
| `<#` | comment block | `<# $0 #>` |
| `for` | for loop | `<@ for $1 to $2 @>\n\t$3\n<@ end @>` |
| `foreach` | foreach loop | `<@ foreach in $1 @>\n\t$2\n<@ end @>` |
| `foreachelse` | foreach else loop | `<@ foreach in $1 @>\n\t$2\n<@ else @>\n\t$3\n<@ end @>` |
| `if` | if statement | `<@ if $1 @>\n\t$2\n<@ end @>` |
| `ifelse` | if else statement | `<@ if $1 @>\n\t$2\n<@ else @>\n\t$3\n<@ end @>` |
| `with` | with statement | `<@ with $1 @>\n\t$2\n<@ end @>` |
| `withelse` | with else statement | `<@ with $1 @>\n\t$2\n<@ else @>\n\t$3\n<@ end @>` |
