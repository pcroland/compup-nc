# compup-nc
### Comparison feltöltő nCore-ra és BitHUmenre.
## Telepítés
* `pip install requests`
* `install -D -m 755 <(curl -fsSL git.io/JYTTu) ~/.local/bin/compup-nc`\
(Ha a `~/.local/bin` nincs benne PATH-ban, akkor írjuk be a `.bashrc`/`.zshrc` fájlunkba hogy: `PATH="$HOME/.local/bin:$PATH"`.)
* `hash -r`
## Kapcsolók
```sh
❯ compup-nc -h
usage: compup-nc [-h] [-v] [-i [IMAGES ...]] [-c COMPARES] [-n NUMBER]
                 [-w WIDTH] [-o] [--bithumen]

options:
  -h, --help                              show help message
  -v, --version                           show version
  -i [IMAGES ...], --images [IMAGES ...]  image sources.
                                          (default: *.png)
  -c COMPARES, --compares COMPARES        compare names, comma separated.
  -n NUMBER, --number NUMBER              number of images in a row. (default: number of compare names)
  -w WIDTH, --width WIDTH                 width of the image row
  -o, --oxipng                            use oxipng before uploading
  --bithumen                              generate bithumen compatible bb code
```
## Működés közben
![image1](https://i.kek.sh/SYoTg3jMfk2.gif)
