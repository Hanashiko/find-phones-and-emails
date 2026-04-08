# find-phones-and-emails

A simple Python script that extracts phone numbers and email addresses from your clipboard text.

## How it works

1. Reads text from the clipboard
2. Finds all US phone numbers (with optional extensions) and email addresses using regex
3. Copies the results back to the clipboard and prints them

## Usage

```bash
pip install pyperclip
python main.py
```

Copy some text containing phone numbers or emails to your clipboard, then run the script.

## Dependencies

- [pyperclip](https://pypi.org/project/pyperclip/)
