testing tool for VAPT

Generates random Philippine mobile numbers across Globe, TM, Smart, TNT and DITO
prefixes and writes them to a text file, one per line. They are filler for forms and
datasets, not real subscribers.

The count leads the filename - `1000_philippine_mobile_numbers.txt` by default,
`250_philippine_mobile_numbers.txt` for `--gen 250` - so runs of different sizes do
not overwrite each other.

# Usage
```
python3 phmobilenumbergenerator.py
```

That writes 1000 numbers in the 10-digit format, `9XXXXXXXXX`.

# Options
| Flag | What it does |
| --- | --- |
| `--gen N` | How many numbers to write. Defaults to 1000. |
| `--full` | Write the full 11-digit format with a leading zero, `09XXXXXXXXX`, instead of the 10-digit `9XXXXXXXXX`. |
| `-h`, `--help` | Show the flags and exit. |

```
python3 phmobilenumbergenerator.py --gen 250
python3 phmobilenumbergenerator.py --gen 250 --full
```

Requires Python 3. No third-party packages.

Also published at https://evanricafort.com/tools/phmobilenumbergenerator/
