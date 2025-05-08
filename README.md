# Awesome  Dev Fonts [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## By Big Tech
| Font            | Ligatures | Open Source | Repo                              | Official Site |
| --------------- | --------- | ----------- | --------------------------------- | -------------- |
| Cascadia Code   | ✅         | ✅           | [microsoft/cascadia-code](https://github.com/microsoft/cascadia-code)             |  N/A |
| IBM Plex Mono   | ❌         | ✅           | [IBM/plex](https://github.com/IBM/plex) | [IBM/plex](https://github.com/IBM/plex) | [ibm.com](https://www.ibm.com/plex) |
| JetBrains Mono  | ✅         | ✅           | [JetBrains/JetBrainsMono](https://github.com/JetBrains/JetBrainsMono)             | [jetbrains.com](https://jetbrains.com/mono) |
| MonaSpace       | ✅         | ✅           | [githubnext/monaspace](https://github.com/githubnext/monaspace)                   | [monaspace.githubnext.com](https://monaspace.githubnext.com)
| Roboto Mono     | ❌         | ✅           | [googlefonts/RobotoMono](https://github.com/googlefonts/RobotoMono)               | [fonts.google.com](https://fonts.google.com/specimen/Roboto+Mono) |
| Source Code Pro | ❌         | ✅           | [adobe-fonts/source-code-pro](https://github.com/adobe-fonts/source-code-pro)     | [fonts.adobe.com](https://fonts.adobe.com/fonts/source-code-pro) |
| SF Mono         | ❌         | ❌           | [unofficial?](https://github.com/supercomputra/SF-Mono-Font)                      | [apple.com](https://developer.apple.com/fonts/) | 
| Gofont          | ?          | ?             | [golang/image](https://github.com/golang/image/tree/master/font/gofont/ttfs)      | [go.dev](https://go.dev/blog/go-fonts) | 

## Special Mentions / by dev for dev
<!-- | Fira Code       | ✅         | ✅           | [tonsky/FiraCode](https://github.com/tonsky/FiraCode)   | N/A |  -->
- [Fira Code](https://github.com/tonsky/FiraCode)
- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous/)
- [Victor Mono](https://github.com/rubjo/victor-mono) -  [Site](https://rubjo.github.io/victor-mono/)
- [fantasque-sans](https://github.com/belluzj/fantasque-sans) - [Site](https://fontlibrary.org/en/font/fantasque-sans-mono)
- [Comic-mono](https://github.com/dtinth/comic-mono-font) - [Site](https://dtinth.github.io/comic-mono-font/)  
Repo  [brabadu/awesome-fonts](https://github.com/brabadu/awesome-fonts) & [powerline/fonts](https://github.com/powerline/fonts)  
Site  [programmingfonts.org](https://www.programmingfonts.org/)  & [free-for.dev](https://free-for.dev/#/?id=font)

### Using in VS Code
To apply custom fonts in VS Code, press <kbd>Ctrl</kbd>/<kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>, search for “Open User Settings (JSON)”, and add the following line:  
`"editor.fontFamily": "'Fira Code', 'Monaspace Argon', 'Cascadia Code', monospace"`  
This is a font fallback list, used in CSS and VS Code to define which fonts to try in order:

1. Individual Font Names
These are specific fonts. They must be installed on your system, or they won't apply:  
'Fira Code' — a popular monospaced font with ligature support.  
'Monaspace Argon' — part of the Monaspace family by GitHub, another modern mono font.  
'Cascadia Code' — a monospaced font from Microsoft with ligature support, designed for coding.  
Each is wrapped in quotes because the names contain spaces.

2. Generic Font Family  
`monospace` — this is a generic fallback. If none of the specific fonts are available, the system will use the default monospace font (e.g., Courier on many systems).
