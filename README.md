# Overview

This repository contains a script that builds a Che-Theia image with custom extensions, abstracting the configuration
of the host machine.

# How To Use?

In order to obtain a Che-Theia image with custom extensions, the steps below must be followed:

1. Run Docker.
2. Clone [this repository](https://github.com/unparallel-innovation/smartclide-che-theia-builder).
3. Open the directory in VS Code.
4. Press the "Reopen in Container" button to launch the devcontainer.
5. Copy the extensions source code into the _extensions_ folder.
6. Include the added extensions in the _che-theia-init-sources.yml_ file.
7. Provide a valid GitHub Personal Access Token in the _smartclide-build.sh_ file.
8. Run the _smartclide-build.sh_ script.
