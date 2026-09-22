testing tool for VAPT

Generates random Philippine mobile numbers across Globe, TM, Smart, TNT and DITO
prefixes and writes them to `philippine_mobile_numbers.txt`, one per line. They are
filler for forms and datasets, not real subscribers.

# Usage
```
python3 phmobilenumgenerator.py
```

That writes 1000 numbers in the 10-digit format, `9XXXXXXXXX`.

# Options
| Flag | What it does |
| --- | --- |
| `--gen N` | How many numbers to write. Defaults to 1000. |
| `--full` | Write the full 11-digit format with a leading zero, `09XXXXXXXXX`, instead of the 10-digit `9XXXXXXXXX`. |
| `-h`, `--help` | Show the flags and exit. |

```
python3 phmobilenumgenerator.py --gen 250
python3 phmobilenumgenerator.py --gen 250 --full
```

Requires Python 3. No third-party packages.

Also published at https://evanricafort.com/tools/phmobilenumbergenerator/
