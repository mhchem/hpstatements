# How to Contribute Content

Language|Status|
---|---|
BG | Contributors needed
ES | Contributors needed
CS | Contributors needed
DA | Contributors needed
DE | Content complete for latest versions
EN | Content complete for latest versions
ET | Contributors needed
EL | Contributors needed
FR | Contributors needed
HR | Contributors needed
IT | Contributors needed
LV | Contributors needed
LT | Contributors needed
HU | Contributors needed
MT | Contributors needed
NL | Contributors needed
PL | Contributors needed
PT | Contributors needed
RO | Contributors needed
SK | Contributors needed
SL | Contributors needed
FI | Contributors needed
SV | Contributors needed

If you want to contribute – and put your work under the [Creative Commons Attribution 4.0 International licence​​](<https://creativecommons.org/licenses/by/4.0/>) – write an email to the author (assemble the address from these three parts: mhchem, MartinHensel, de).

Have  a look at the file [enhancements-en.json](enhancements/enhancements-en.json). This is what is needed for every language.

The task is to fix the lines containing `#fixme` for your language.
- Keep parameter numbers (`{1}`, `{2}`, ...) aligned with the English contribution file.
- When inserting parameters (e.g. `{1}`), you are allowed to change surrounding spacing. For instance, `"Keep wetted with…"` will become `"Keep wetted with {1}"`.
- Do not change any other spacing, punctuation or errors, rather mention it in the [potential-errors.md](potential-errors.md) file.
- Parameters that replace `state route of exposure` are added *without* preceding space, because this parameter might begin with a comma.