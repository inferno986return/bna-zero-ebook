# bna-zero-ebook

An ePub of the translation of *BNA Zero*. I've made some adjustments to the text (see ConversionNotes.md).

Thanks very much to NightRunners for translating this light novel. I'd love to see TRIGGER adapt this into a movie!

![Adobe Digital Editions preview](https://github.com/inferno986return/bna-zero-ebook/blob/main/Prologue_preview.jpg)


## Development

### Pull requests

Feel free to fork and send pull requests for this ePub for mistakes and improvements.

### Environment

I use Windows Subsystem for Linux (WSL) on Windows 11 with the Ubuntu distro. You will need to install Python 3 and Java onto WSL:

1. Install WSL using this guide: https://docs.microsoft.com/en-us/windows/wsl/install
2. Install Ubuntu from the Microsoft Store
3. Set the root account and password.
4. Run `sudo apt update`.
5. Run `sudo apt install python3`.
6. Run `sudo apt install jdk`.

If you use macOS or GNU/Linux you should be able to directly run these commands below.

### Compiling and testing

1. Change directory to the e-book folder: `cd e-book`
2. Run ebookbuild.py and then epubcheck using: `python3 ebookbuild.py && java -jar epubcheck.jar BNAZero.epub`
3. Open the ePub in Adobe Digital Editions (ADE) or upload to Google Play Books (via https://play.google.com/books/).

## Licencing

`ebookbuild` is licenced under GNU GPLv3

The CSS, XHTML and JSON files are licenced under Creative Commons Zero (CCO).

## Credits

PLEASE SUPPORT THE OFFICIAL RELEASE

JAPANESE PAPERBACK – <a href="https://www.amazon.com/dp/4086313642">HERE</a><br/>
ENGLISH PAPERBACK – TBD

TRANSLATED BY R/BNA | NIGHT-RUNNERS

FOR UPDATES, PLEASE SUBSCRIBE TO THE FOLLOWING

– DISCORD –<br/>
<a href="https://discord.gg/bna">DISCORD.GG/BNA</a>

– REDDIT –<br/>
<a href="https://reddit.com/r/BrandNewAnimal">r/BrandNewAnimal</a>
	
– MANGADEX –<br/>
<a href="https://mangadex.org/group/15025/night-runners">https://mangadex.org/group/15025/night-runners</a>
