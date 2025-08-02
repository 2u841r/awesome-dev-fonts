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
| Google Sans Code | ❌        | ✅           | [googlefonts/googlesans-code](https://gitub.com/googlefonts/googlesans-code)      | [fonts.google.com](https://fonts.google.com/specimen/Google+Sans+Code) | 

## Special Mentions / by dev for dev
<!-- | Fira Code       | ✅         | ✅           | [tonsky/FiraCode](https://github.com/tonsky/FiraCode)   | N/A |  -->
- [Fira Code](https://github.com/tonsky/FiraCode)
- [Hack](https://github.com/source-foundry/Hack) - [Site](https://sourcefoundry.org/hack/)
- [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous/)
- [Victor Mono](https://github.com/rubjo/victor-mono) -  [Site](https://rubjo.github.io/victor-mono/)
- [fantasque-sans](https://github.com/belluzj/fantasque-sans) - [Site](https://fontlibrary.org/en/font/fantasque-sans-mono)
- [Comic-mono](https://github.com/dtinth/comic-mono-font) - [Site](https://dtinth.github.io/comic-mono-font/)  
Repo  [brabadu/awesome-fonts](https://github.com/brabadu/awesome-fonts) & [powerline/fonts](https://github.com/powerline/fonts)  
Site  [programmingfonts.org](https://www.programmingfonts.org/)  & [free-for.dev](https://free-for.dev/#/?id=font)  


<details>
  <summary>Using Custom Fonts in VS Code</summary>
  <h3> Using Custom Fonts in VS Code </h3>
To apply custom fonts in Visual Studio Code, follow these steps:

Press <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>  
Search for “Open User Settings (JSON)”  
Add or update this line:  
`"editor.fontFamily": "'Font Name', 'Backup Font', monospace"`  

Example:
I personally use Fira Code, so my basic setting looks like this:  
`"editor.fontFamily": "'Fira Code', monospace"`  
My full font fallback list is:  
`editor.fontFamily": "'Fira Code', 'Monaspace Argon', 'Cascadia Code', monospace"`  
> If I want to use Monaspace Argon without deleting Fira Code from my device and without removing it from the VS Code settings JSON file, I have to move Monaspace Argon to the beginning of the list.

<h3> How It Works </h3>
This setting defines a font fallback list — similar to how CSS handles fonts. VS Code tries each font from left to right:

#### Specific Font Names  
These must be installed on your system:  
- 'Fira Code' — a developer-friendly font with ligatures.  
- 'Monaspace Argon' — part of GitHub’s modern monospaced font family.  
- 'Cascadia Code' — Microsoft’s coding font with ligature support.  
(Quotes are needed for names with spaces.)

#### Generic Font Family

`monospace` — a system default monospaced font (e.g., Courier).  
Used only if none of the specified fonts are available.  

This ensures your editor always uses a monospaced font — even if some aren't installed.

</details>


<details>
  <summary> Ligatures </summary>
  I didn’t know how symbols like !== and => change their appearance. Since I didn’t even know the name of this feature (ligatures), it was hard to search for it.

On Windows, VS Code’s default fonts like Consolas, Courier New, which already have ligature support. So you don’t have to install Fira Code. (You can if you want to, but it’s not mandatory — that’s what I’m saying.)  
To on Ligatures- Press <kbd>Ctrl</kbd> / <kbd>Cmd</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>  
Search for “Open User Settings (JSON)”  
Then just search for “ligatures” in json file, go to Edit in settings.json, and set:
`"editor.fontLigatures": true`
That’s it — you're done! (By default, it’s set to false.) 
</details>


![](https://repostats.deno.dev/2u841r/awesome-dev-fonts)
