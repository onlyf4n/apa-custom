# APA 7th Custom (CSL)

A modified **APA 7th edition** citation style for Mendeley Cite. It is based on the official `apa.csl` from [citation-style-language/styles](https://github.com/citation-style-language/styles).

## Differences from the original APA 7th

Only the italic formatting of journal articles in the reference list is changed:

| Element | Original APA 7th | APA 7th Custom |
|---|---|---|
| Article title | Normal | *Italic* |
| Journal name | *Italic* | Normal |
| Volume | *Italic* | Normal |

Example output:

> Doe, J., Smith, A. B., & Lee, C. (2024). *An Example Title of a Journal Article*. Journal of Example Studies, 12(3), 45–67. https://doi.org/10.0000/example.2024.001

In-text citations, element order, and all other rules are unchanged.

## Usage in Mendeley Cite

1. Copy the raw URL of the style file:
   ```
   https://raw.githubusercontent.com/onlyf4n/apa-custom/main/apa-custom.csl
   ```
2. In Word, open the **Mendeley Cite** tab and click **Citation Style**.
3. Choose **More Styles** and look for the option to add a style from a URL (*Add custom style*). The menu name may vary by version.
4. Paste the URL, then select **APA 7th Custom**.
5. Click **Refresh** to update the bibliography.

## Usage in Zotero

1. Download `apa-custom.csl`.
2. Go to **Edit → Settings → Cite → Styles → +** and select the file.

## Notes

- The repository must be **public**, otherwise Mendeley cannot read the file.
- After editing and committing the `.csl` file, click **Refresh** in Mendeley Cite. If nothing changes, reselect the style.
- Automatic hyphenation and DOI line breaking are handled in Word, not by this style file.

## License

Derived from APA Style 7th edition by Brenton M. Wiernik and Andrew Dunning, licensed under [Creative Commons Attribution-ShareAlike 3.0](http://creativecommons.org/licenses/by-sa/3.0/). As the license is ShareAlike, this derivative uses the same license.
