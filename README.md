# mkpm
A simple tool for creating Python modules. For lazies.

## Installation
mkpm can be easily installed via pip:
`pip install mkpm`

## Usage
`mkpm [--help] [--version] [--ignore-pep8] [--executable] modules [modules ...] [--add [file-names [file-names ...]]]`

## Examples
`mkpm --executable my_module1 ~/Projects/Python/my_module2 some-dir/my_module3 --add config`
`mkpm app`
`mkpm --executable program1`
`mkpm app --add config utils`