# format:check

Check for un-formatted files

## Usage

```bash
nx format:check
```

Install `@nrwl/cli` globally to invoke the command directly using `nx`, or use `npm run nx` or `yarn nx`.

## Options

### all

All projects

### apps-and-libs

### base

Base of the current branch (usually master)

### configuration

This is the configuration to use when performing tasks on projects

### exclude

Default: ``

Exclude certain projects from being processed

### files

Change the way Nx is calculating the affected command by providing directly changed files, list of files delimited by commas

### head

Latest commit of the current branch (usually HEAD)

### help

Show help

### only-failed

Default: `false`

Isolate projects which previously failed

### plain

Produces a plain output for affected:apps and affected:libs

### runner

This is the name of the tasks runner configured in nx.json

### uncommitted

Uncommitted changes

### untracked

Untracked changes

### verbose

Print additional error stack trace on failure

### version

Show version number
