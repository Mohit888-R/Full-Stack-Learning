## Conventional Commits

### What are Conventional Commits 
Conventional Commits offer a lightweight framework for organizing commit messages. It is have distinct types like features, fixes, and other breaking changes.


### Anatomy of a Great Commit Message
<type> [optional scope]: <description>
[optional body]
[optional footer(s)]


### Types of Commits 
- feat     : Add new rating component
- fix      : resolve issue with features
- build    : Changes related to build process or tools.
- chore    : Regular maintenance or administractive tasks
- ci       : update in CI/CD
- docs     : docs related changes
- style    : formatting changes not functionality
- refactor : code modification without changing it's behaviour
- perf     : Performance improvements
- test     : Adding or modifying test


### Can add optional scope

`feat(api): prevent racing features`


### Rules :
1. Add prefix in commit messages  feat, fix etc. and followed scope, option !, required terminal colon and space
2. scope and ! is the option after type 
3. description is the sort summary of the written code and it should immediatly after the colon
4. For more contextual information, can add in body. Must begin one blank line after the description.


For more reference check out official website : https://www.conventionalcommits.org/en/v1.0.0/