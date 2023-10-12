# Commit Prefixes
## why using conventioal commits messages is important?
- It give you the information about what and why without diving into the code.
- it enable us to use the automated tools for building the releases notes for our repository.
- Improve collaboration among the team as all are following the same conventioal.

### Do you ask yourself how can you make a clear and meaningful git commits messages?<br>
Let me support you with My personal style guide for writing git commit messages using prefixes based on [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/#examples). Prefixes should be written in the following format:

```html
<<prefix>[optional scope]: <description>

[optional body]

[optional footer(s)]
```



✨ **This is a Work in Progress!** ✨

|No. |prefix                        |When to use                                                |
|:---|:---------------------------|:------------------------------------------------------------|
|01  |`feat`                      |`: add a new code related to a new feature `               |
|02  |`fix`                       |`: fix a wrong behavior - a bug- `                         |
|03  |`refactor`                  |`:fix something in the code but no the behavior-not a bug-`|
|04  |`chore`                     |`: refactoring`                                            |
|05  |`docs`                      |`: add new field or chapter to the documentation`          |
|06  |`ci`                        |`: update somehting realted to the CI`                     |
|07  |`build`                     |`: fix broken control header (#4)`                         |
|08  |`style`                     |`: clean and organize you code`                            |
|️️09  |`merge`                     |`: merge pull request from user/patch-1`                   |
|10  |`security`                  |`: move exposed API key to .env file`                      |
|11  |`legal`, `markdown`         |`: update contributing guide`                              |
|12  |`restructure`, `rework`     |`: redesign port forwarding implementation`                |
|13  |`label`, `tag`              |`: release v0.1.1`, `🏷️: v1.0.2`                           |

---

## Scopes and BREAKING CHANGE
- Using ! after the prefix means : it's a Breaking Change
- You can also provide an explaination in the commit message as exampe:
    ```
    chore!: drop support for Node 6

    BREAKING CHANGE: use JavaScript features not available in Node 6.
    ```
---
**You can use this file as reference for the prefixe types and scopes.** <br>
**For more details and examples i sugget reading  this documentation: [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/#examples)**