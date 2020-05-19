# Changelog

Updates to the AS2 Language Support project will be documented here as new versions are released.

## [1.3.1] - 2020-05-09
- Refresh dependencies and packages to match canonical vscode-lsp extension example
- Fix superclass member completion bug

## [1.3.0] - 2020-05-03
- Add hover and definition support for long-form class references ('import' and 'extends' statements)
- Fix method signature identification inside array and object literals

## [1.2.3] - 2020-02-06
Fix bug with tracking of nested method signatures

## [1.2.2] - 2020-01-24
Update format of repository url in `package.json`

## [1.2.1] - 2020-01-21
Addresses the following issues:
- Superclass members are not resolved when super declaration uses short type
- Local variables declared after string literals in the same statement are not indexed
- Npm task `parse-intrinsics` no longer runs successfully

## [1.2.0] - 2020-01-21
Add definition support (jump to definition, peek definition)

## [1.1.0] - 2020-01-19
- Removes the requirement that the active vscode workspace directory must match the root class-path of any open files
- Improves handling of wildcard imports
- Fixes bug where parse queue halts upon encountering a missing file

## [1.0.1] - 2020-01-08
Addresses the following issues:
- No method signature support for the super constructor
- Type casts trigger completions for static instead of instance properties
- Parentheses triggers signature completion for class constructor
- No differentiation between called methods and accessed properties

## [1.0.0] - 2020-01-01
Initial release