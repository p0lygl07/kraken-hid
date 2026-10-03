# Kraken HID — Usage

## A harmless first payload

This opens Notepad and types a message — safe to run on your own Windows machine.

```text
REM hello_kraken - safe demo payload
DELAY 1000
GUI r
DELAY 300
STRING notepad
ENTER
DELAY 600
STRING Ahoy from the Kraken.
```

### What each line does
- `REM` — a comment, ignored when run
- `DELAY 1000` — wait 1000 ms so the host is ready
- `GUI r` — press Win+R (the Run dialog)
- `STRING notepad` — type the word "notepad"
- `ENTER` — press Enter

> Keep payloads to machines you own or are authorized to test. See docs/SAFETY.md.

