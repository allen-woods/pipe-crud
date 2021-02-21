# pipe_crud

## Description

This is a dev-ops utility written in `sh` intended to provide full CRUD functionality to named pipes and pseudo-anonymous pipes (file descriptors) on Alpine Linux.

Data is stored in the pipe as wrapping document IDs containing unique item names.

Pseudo-anonymous pipes are air-gapped by default.

## Disclaimer

Because of [this issue](https://github.com/moby/moby/issues/37182), this script should not be used inside of Docker images.

This script is currently provided as-is with no warranty. This project will be revisited and improved at a later, as yet undetermined, date.
