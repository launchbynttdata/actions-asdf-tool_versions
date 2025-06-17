# Github Action to Inspect asdf .tool-versions files

## About

This action is designed to inspect the .tool-versions file and return the version of a specified tool, if it exists.

## Usage

```workflow
...
  steps:
  - name: Inspect .tool-versions
    uses: launchbynttdata/actions-asdf-tool_versions@<commit hash>
...
```

## Compatibility

This action has only been tested on GitHub.com.
