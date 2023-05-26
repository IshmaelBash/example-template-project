# Project bb{ .Project.Name }

This is a compatible BashBuilder template.<br>
**This template is for template experiments only.**

# Description

bb{ .Project.Description }

# Survey results

1. bb{ getDrink }
2. bb{ getColor }
3. bb{ join getLang ", " }
4. bb{ getDb }
5. bb{ getDbPassword }
6. bb{ getPrintNode }

## Custom variables

- bb{ .Vars.test }
- bb{ .Vars.db }
- bb{ .Vars.projectName }

## Environment variables

- bb{ env "BASH_CONFIG_URL" }

## Current cwd

- bb{ cwd }

## Regex

- bb{ (regex "[0-9]+").FindString "I'm 26 years old" }

## Generators

- bb{ randomInt 5 10 }
- bb{ uuid }
