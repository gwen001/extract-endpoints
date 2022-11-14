# extract-endpoints

Extract endpoints from source files.

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

<img src="https://raw.githubusercontent.com/gwen001/extract-endpoints/main/preview.png" />
