# SF-X Developer Tools
This repository contains various scripts that support the distribution and development of the [SF-X Logic](https://github.com/groupby/sfx-logic) and [SF-X View](https://github.com/groupby/sfx-view) repositories.

## Scripts

### `setup.sh`
This script installs dependencies and builds all the packages contained within an SF-X monorepo. This script assumes that a [yarn workspace](https://yarnpkg.com/lang/en/docs/workspaces/) is set up and that the root of the workspace is one directory above the directory containing this script.

### `build.sh`
This script builds a single package. It is meant to be run at the root of an SF-X package.
