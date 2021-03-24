# compup-nc
### Comparison feltöltő nCore-ra.
## Telepítés
* `install -D -m 755 <(curl -fsSL git.io/JYTTu) ~/.local/bin/compup-nc`\
(Ha a `~/.local/bin` nincs benne PATH-ban, akkor írjuk be a `.bashrc`/`.zshrc` fájlunkba hogy: `PATH="$HOME/.local/bin:$PATH"`.)
* `hash -r`
## Kapcsolók
```sh
usage: compup-nc [-h] [-v] [-i [IMAGES [IMAGES ...]]] [-c COMPARES] [-n NUMBER] [-w WIDTH] [-o]

optional arguments:
  -h, --help            show help message
  -v, --version         show version
  -i [IMAGES [IMAGES ...]], --images [IMAGES [IMAGES ...]]
                        image sources. (default: *.png)
  -c COMPARES, --compares COMPARES
                        compare names, comma separated. (default: source, encode)
  -n NUMBER, --number NUMBER
                        number of images in a row. (default: number of compare names)
  -w WIDTH, --width WIDTH
                        width of the image row (default: 500)
  -o, --oxipng          use oxipng before uploading (default: False)
```
## Működés közben
![image1](https://i.kek.sh/SYoTg3jMfk2.gif)