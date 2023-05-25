# Project bb{ .Project.Name }

This is a compatible butler template. Based on Visual Studio 2017 .NET Core 2.0 React Template.<br>
**This template is for template experiments only.**

# Description

bb{ .Project.Description }

# Survey results

1. bb{getDrink}
2. bb{getColor}
3. bb{join getLang ", "}
4. bb{getDb}
5. bb{getDbPassword}
6. bb{getPrintNode}

## Custom variables

- bb{ .Vars.test }
- bb{ .Vars.db }
- bb{ .Vars.projectName }

## Environment variables

- bb{ env "BUTLER_CONFIG_URL" }

## Current cwd

- bb{ cwd }

## Regex

- bb{ (regex "[0-9]+").FindString "I'm 26 years old" }

## Generators

- bb{ randomInt 5 10 }
- bb{ uuid }
