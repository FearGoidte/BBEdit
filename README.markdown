# BBEdit settings

Some of the clippings and scripts that are lurking in the `Application Support` folder for my [BBEdit](http://www.barebones.com/products/bbedit/) installation.

Locally, I’m using the rather fetching [‘BB Edit Icon’](http://www.softicons.com/folder-icons/isuite-revoked-icons-by-prax-08/bb-edit-icon) icon by [PraX-08](http://www.softicons.com/designers/prax-08) for my folder.

You are free to with or without as you please. Where content has been shamelessly filched from elsewhere, I have tried to note the fact.

## Clippings

### Placeholder clippings

[Ryan Wilcox](https://github.com/rwilcox)’s [bbedit_clippings_clippings](https://github.com/rwilcox/bbedit_clippings_clippings).

### Ruby clippings

From [Andrew Carter](https://github.com/ascarter)’s [BBEdit-ApplicationSupport](https://github.com/ascarter/BBEdit-ApplicationSupport).

### Font stacks

From George Butler’s [10 Definitve Web Font Stacks for designers](https://web.archive.org/web/20141004075536/http://georgebutler.com/blog/typography/10-definitive-web-font-stacks-for-designers/), [The Erudite Theme by Soma Design](http://somadesign.ca/projects/the-erudite/), and [Keith Huston’s Shady Characters](http://www.shadycharacters.co.uk/).

## Previews

### GitHub flavoured Markdown

I have reformatted and optimized [Gavin Aiken](https://github.com/gavinaiken)’s [Github Flavored Markdown parser and <abbr title="Cascading Style Sheets" class="initialism">C.S.S.</abbr> for BBEdit](https://github.com/gavinaiken/bbedit-scripts) styles out of habit rather than utility.

The parser is used when [Markdown](https://daringfireball.net/projects/markdown/) files are previewed using BBEdit rather than a browser.

## Scripts

### go here in Terminal

[Isao Yagi](https://github.com/isao)’s [<cite>Go Here in Terminal.applescript</cite>](https://github.com/isao/shell/blob/master/bbedit/Scripts/Go%20Here%20in%20Terminal.applescript) to go to the directory that containins the current text document open in BBEdit in Terminal.

Uses an existing window/tab if possible (BBEdit’s built-in command always opens a new Terminal window).

I modified this to create scripts to launch [Middleman](https://middlemanapp.com)’s development server; as well as to build, or deploy, a site.

### Grab mark-up

[<cite>John Gruber’s Grab <abbr title="Hypertext Mark-up Language" class="initialism">H.T.M.L.</abbr> Script for BBEdit, Redux</cite>](http://daringfireball.net/2003/07/grab_html_script_for_bbedit_redux)

### Middleman

Scripts for the [Middleman static website generator](https://middlemanapp.com) to launch the preview server, build a website, or to deploy it using [Middleman Deploy](https://github.com/middleman-contrib/middleman-deploy).

## Stationary

### Syntax highlighting stylesheet for code examples

Based upon [Tom Preston-Werner’s `syntax.css`](https://github.com/mojombo/tpw/blob/master/css/syntax.css).

## Text filters

### Automatic non-breaking spaces text filter

Implemented Anton Bryl’s [`poemnobr.pl`](http://blog.epubbooks.com/898/formatting-poetry-for-small-screens) script as a text filter for automatically inserting non-breaking spaces between.

### Convert hex colours to <abbr title="red, green, and blue" class="initialism">R.G.B.</abbr>

[Ryan Wilcox](https://github.com/rwilcox)’s [`html_hex_colors_to_rgb.py`](https://github.com/rwilcox/html.bbpackage/blob/master/Contents/Text%20Filters/HTML%20in%20BBEdit/html_hex_colors_to_rgb.py).

Perl filters to encode and decode strings into *Base64*.
