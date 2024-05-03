# Visual Studio Code
Visual Studio Code ile kodlama yapmak için genel ayarları içerir.

# Kurulması Gereken Eklentiler
- [psioniq File Header](https://marketplace.visualstudio.com/items?itemName=psioniq.psi-header)
- [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- [FiraCode font - Professional Font for Developers](https://marketplace.visualstudio.com/items?itemName=SeyyedKhandon.firacode)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [Discord Presence](https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode)
- [JetBrains New Dark](https://marketplace.visualstudio.com/items?itemName=MoBalic.jetbrains-new-dark)

# Yapılması Gereken Ayarlar
settings.json içerisine;
```
{
  "editor.unicodeHighlight.includeStrings": false,
  "workbench.iconTheme": "material-icon-theme",
  "psi-header.templates": [
    {
      "language": "*",
      "template": [
        "\t\tDiscord AURORA BOT",
        "",
        "\tDosya:",
        "\t\t<<filename>>",
        "",
        "\tKodlama:",
        "\t\tBurak (Nexor)",
        "",
        "\tTarih:",
        "\t\t<<dateformat('DD.MM.YYYY, HH:mm:ss')>>",
      ]
    }
  ],
  "explorer.autoReveal": false,
  "editor.fontFamily": "Fira Code",
  "editor.smoothScrolling": true,
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorBlinking": "phase",
  "indentRainbow.colorOnWhiteSpaceOnly": true,
  "files.autoSave": "afterDelay",
  "editor.formatOnSave": true,
  "editor.formatOnType": true,
  "editor.fontSize": 13,
  "editor.fontLigatures": false,
  "editor.fontWeight": "350"
}
```

# Kısayollar
- **CTRL + SHIFT + -** → Terminali açar.
- **CTRL + SHIFT + x2 +** → Header kısmına not ekler.
- **CTRL + Ö** → Belirli satırlara // yorumlaması ekler ve siler.
- **CTRL + L** → Terminali temizler.
- **CTRL + C** → Terminali sonlandırır.
