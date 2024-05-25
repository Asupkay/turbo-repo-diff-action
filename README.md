# Turborepo Diff Check
This action checks if there are differences in a particular package from main to the previous commit or tag. This allows you to gate certain workflows on whether or not there is a change in the relevant package.

## Usage
```
- uses: actions/turborepo-diff-check
  with:
    # Name of the package that should be checked
    package: ''

    # Whether the action should check against the last commit
    # or the last tag
    # Default: false
    use-last-tag: ''
```
