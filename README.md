# GroupBy Elements Developer Tools
This repository contains various scripts that support the distribution and development of the [GroupBy Elements Logic](https://github.com/groupby/elements-logic) and [GroupBy Elements View](https://github.com/groupby/elements-view) repositories.

## Scripts

### `setup.sh`
This script installs dependencies and builds all the packages contained within a GB Elements monorepo. This script assumes that a [yarn workspace](https://yarnpkg.com/lang/en/docs/workspaces/) is set up and that the root of the workspace is one directory above the directory containing this script.

### `build.sh`
This script builds a single package. It is meant to be run at the root of a GB Elements package. It is assumed that `typescript` is installed as a devDependency and this script is being run as an npm script.
