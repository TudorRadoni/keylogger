# Keylogger

![Keylogger Logo](docs/KeyloggerLogo.jpg)

Well, it logs your keystrokes. It uses raw input.

## Known issues

### Keylogger

- Date could not be real or valid, so validity should be ensured
- Weird warning ocurrs before build when using WriteFile(). After build, it goes away

### Interpreter

- Path handling is pretty much non-existent
- Backspaces are not treated well
- Some sort of isNumeric() function needs implementation
- Shortcuts need a bit of work
