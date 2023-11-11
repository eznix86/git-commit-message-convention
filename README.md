# Git commit message convetion

Convention:

- `feat`: A new feature
- `fix`: A bug fix
- `docs`: Documentation only changes
- `style`: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
- `refactor`: A code change that neither fixes a bug nor adds a feature
- `perf`: A code change that improves performance
- `test`: Adding missing tests or correcting existing tests
- `chore`: Changes to the build process or auxiliary tools or creating folders and libraries such as documentation generation

## Format
```
<type>(optional scope): <description>

[optional body]

[optional footer]
```
Example:

```
chore(user): create folder structure for users
```

_Note_: a scope is not necessary.

## Description format
The description should always be in this format:

If applied, this commit will `<description>`

Example:
```
chore(user): create folder structure for users
chore(infra): scale the service in kubernetes
feat: added pagination
style: make button cooler
perf: optimize imports
🐛 fix login for administrators
✅ add new tests
```

## Cool stuff
Some repository uses emojis as convention:

Example: [gitmoji](https://gitmoji.dev/)

- `feat`: ✨
- `fix`: 🐛
- `docs`: 📝
- `style`: :art:
- `refactor`: :recycle:
- `perf`: :zap:
- `test`: :white_check_mark:
- `chore`: *any other emoji*

A vscode extension for ya! [Gitmoji extention](https://github.com/seatonjiang/gitmoji-vscode)
