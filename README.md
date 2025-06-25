# ASUS (UM|M)5506 fan state script

Bash script to set the fan state on the ZenBook S 16 UM5506 and Vivobook M5506

Note: for the Vivobook S 16 S5606, edit `fan_state` and replace all instances of `0x5002f` with `0x110019`

## Usage

- `fan_state get`: gets current state
- `fan_state set <0-3|standard|quiet|high|full>`: set fan state to 0/standard, 1/quiet, 2/high, or 3/full

## Dependencies

- Linux kernel 6.11+
- `bash`
- `sudo` (or sudo shim with `doas`)

## Installation

- Other Linux: copy `fan_state` to a directory in `$PATH`, `chmod +x` if needed.
