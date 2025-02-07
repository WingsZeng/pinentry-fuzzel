# pinentry-fuzzel

A Bash script that provides a pin entry dialog using [`fuzzel`](https://codeberg.org/dnkl/fuzzel) and integrates with the D-Bus notification system to display messages and errors.

## Requirements

- `bash`
- `fuzzel`
- `dbus`

## Installation

1. Ensure you have the required dependencies installed.
2. Download or copy the `pinentry-fuzzel` script to a directory in your PATH, e.g., `/usr/local/bin/`.
3. Make the script executable:
    ```sh
    chmod +x /usr/local/bin/pinentry-fuzzel
    ```

## Usage

You know how to use this.

## Limitations

- This is a minimal implementation of a PIN entry dialog, and it does not fully comply with all [pinentry program guidelines](https://github.com/gpg/pinentry/blob/master/doc/pinentry.texi).
- `fuzzel` is unable to display buttons, so user interaction is limited.
- Not all possible messages or edge cases are handled.
