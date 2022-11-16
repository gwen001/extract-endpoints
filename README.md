<h1 align="center">extract-endpoints</h1>

<h4 align="center">Extract endpoints from source files.</h4>

<p align="center">
    <img src="https://img.shields.io/badge/php-%3E=5.5-blue" alt="php badge">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="MIT license badge">
    <a href="https://twitter.com/intent/tweet?text=https%3a%2f%2fgithub.com%2fgwen001%2fextract-endpoints%2f" target="_blank"><img src="https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2Fgwen001%2Fextract-endpoints" alt="twitter badge"></a>
</p>

<p align="center">
    <img src="https://img.shields.io/github/stars/gwen001/extract-endpoints?style=social" alt="github stars badge">
    <img src="https://img.shields.io/github/watchers/gwen001/extract-endpoints?style=social" alt="github watchers badge">
    <img src="https://img.shields.io/github/forks/gwen001/extract-endpoints?style=social" alt="github forks badge">
</p>

---

## Install

```
git clone https://github.com/gwen001/extract-endpoints
```

## Usage

```
Usage: php extract-endpoints.php -f/-d <source file/directory> [OPTIONS]

Options:
	-b	beautify javascript files before parsing (requires js-beautify)
	--bb	beautify and update source file (requires js-beautify)
	-c	search for comments instead of urls
	-d	set source directory (required or use -f)
	-e	file to load (example: js,php,asp) (default: js)
	-f	set source file (required or use -d)
	-g	set regexp source file
	--gg	set regexp
	-h	force host if none
	-i	extensions we don't want to display separated by a comma (example: gif,jpg,png)
	-k	search for keywords instead of urls
	-l	follow location
	-n	extensions file we don't want to parse separated by a comma (example: gif,jpg,png)
	-r	also scan subdirectories
	-s	force https if no scheme
	-t	test the urls found
	-u	remove duplicates (at your own risk!)
	-v	verbose mode: 0=all, 1=findings, 2=remove extra text
```

---

<img src="https://raw.githubusercontent.com/gwen001/extract-endpoints/main/preview.png" />

---

Feel free to [open an issue](/../../issues/) if you have any problem with the script.  

