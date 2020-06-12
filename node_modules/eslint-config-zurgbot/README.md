# Zurgbot ESLint Config

An opinionated ESLint config.

## General

### Rules

Including but not limited to:
- ✅ End of Line
- ✅ Indent 2 spaces
- ✅ Semicolons 🔥
- ✅ Single Quotes (with exceptions)
- ✅ Whitespace
- 🚫 Console Logs
- 🚫 Eval
- ⚠️ Warning Comments (TODO/FIXME)
- and more...

### Extends
- `eslint:recommended`

## React
If `eslint-plugin-react` is installed, it loads the below.

### Rules
- ✅ Whitespace around curly braces

### Extends
- `plugin:react/recommended`
