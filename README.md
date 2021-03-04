# swap_workspaces

This is a simple bash script to swap all windows between two workspaces on Linux.

This may be useful when you want to change the order of the workspaces but your
DE doesn't have such feature (XFCE as an example).

## Requirements

* wmctrl
* awk
* grep

## Usage

	swap_workspaces [<1>] <2>

If the first workspace is not specified, current workspace is assumed.
Workspace numbering starts with 0.

## License

BSD-2c
