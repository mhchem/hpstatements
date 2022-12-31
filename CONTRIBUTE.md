# How to Contribute Content

Language      | Status              |
--------------|---------------------|
bg Bulgarian  | Contributors needed
cs Czech      | Contributors needed
da Danish     | Contributors needed
de German     | Content complete
el Greek      | Contributors needed
en English    | Content complete
es Spanish    | Contributors needed
et Estonian   | Contributors needed
fi Finnish    | Contributors needed
fr French     | Content complete
hr Croatian   | Contributors needed
hu Hungarian  | Contributors needed
it Italian    | Contributors needed
lt Lithuanian | Contributors needed
lv Latvian    | Contributors needed
mt Maltese    | Contributors needed
nl Dutch      | Contributors needed
pl Polish     | Contributors needed
pt Portuguese | Contributors needed
ro Romanian   | Contributors needed
sk Slovak     | Contributors needed
sl Slovenian  | Contributors needed
sv Svedish    | Contributors needed

If you want to contribute – and put your work under the [Creative Commons Attribution 4.0 International licence​​](<https://creativecommons.org/licenses/by/4.0/>) – write an email to the author (assemble the address from these three parts: mhchem, MartinHensel, de).

Have  a look at the file [enhancements-en.json](enhancements/enhancements-en.json). This is what is needed for every language.

The task is to add similar lines for your language.
- Keep parameter numbers (`{1}`, `{2}`, ...) aligned with the English contribution file.
- When inserting parameters (e.g. `{1}`), you are allowed to change surrounding spacing. For instance, `"Keep wetted with…"` will become `"Keep wetted with {1}"`.
- Do not change any other spacing, punctuation or errors, rather mention it in the [potential-errors.md](potential-errors.md) file.
- Parameters that replace `state route of exposure` are added *without* preceding space, because this parameter might begin with a comma.