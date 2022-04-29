# Interslavic layouts for Linux

## Usage

1. Copy layout file to `/usr/share/X11/xkb/symbols`:

```shell
cp interslavic /usr/share/X11/xkb/symbols
```

2. Navigate to `/usr/share/X11/xkb/rules/`, merge the content of `snippet.xml` into `evdev.xml` and `base.xml` under `<layoutList>`.


3. Logout and login back, go to system keyboard settings, then you can see the 'interslavic' listed under every slavic languages.

## References

- [XKB configuration files](https://www.charvolant.org/doug/xkb/html/node5.html)
- [List of Unicode characters](https://en.wikipedia.org/wiki/List_of_Unicode_characters)
- [List of ISO 639-1 codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)
- `/usr/include/X11/keysymdef.h` - the keysym definitions on your computer.