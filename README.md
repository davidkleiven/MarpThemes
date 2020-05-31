# Usage With VSCode

Clone (or download a zip)  of the repository. Open VSCode and navigate to settings (for example by clicking CTRL+,).
Search for *marp-themes* add then location of the css files for the theme you want by clikcing *Add Item*.

Latest URLs

* https://github.com/davidkleiven/MarpThemes/raw/v1.0/themes/ntnu_plain.css
* https://github.com/davidkleiven/MarpThemes/raw/v1.0/themes/ntnu_vertical_stripe.css

![VSCode search](assets/marp_theme_vscode.png)

Alternatively, add the following to in *.vscode/settings.json*

```json
// Please put `.vscode/settings.json` on your workspace
{
  "markdown.marp.themes": [
    "https://github.com/davidkleiven/MarpThemes/raw/v1.0/themes/ntnu_plain.css",
    "https://github.com/davidkleiven/MarpThemes/raw/v1.0/themes/ntnu_vertical_stripe.css"
  ]
}
```

# Implemented Themes

* [ntnu-plain](examples/ntnu_plain.md)

<img src="examples/ntnu_plain_example.png" height=200px/>

* [ntnu-vertical](examples/ntnu_vertical.md)

<img src="examples/ntnu_vertical.png" height=200px/>

