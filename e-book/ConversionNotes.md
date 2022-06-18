# Conversion Notes
## General
* Used Metropolis font rather than Monserrat - medium looks really good.
* Used Noto Sans JP for the Japanese text. It looks good but takes up a lot of space in the .epub file.
* Used "BNA Pink" colour #fc28a7 as the accent colour for hyperlinks and initial letters.
* Resized large images to 600px wide to save space.
* Indented paragraphs are more readable, then spaced out.
* The ellipses are all over the place, shouldn't they be more consistent?
* Replace multi-hyphen dinkus with the more presentable 3 asterisk for scene breaks, using "</p>\n\t\t<p>----", followed by "</p>\n\n\t\t<p class="scenebreak">*&#160;*&#160;*</p>\n\n\t\t<p>".
* Used several regex to join paragraphs that have been severed in the conversion process:
    * "([a-z])</p>\n\t\t<p>([A-Z])", followed by "$1 $2"
    * ",</p>\n\t\t<p>([a-z])", followed by ", $1"
* This regex is useful for correcting apostrophes in words "(\w)'(\w)", followed by "$1’$2".

## Chapter specific
* Removed the vertical text front matter as it's not applicable to this book.
* Shortened Amazon link to the Japanese paperback to: https://www.amazon.com/dp/4086313642 (Note: Amazon links can be shortened just to the ASIN)
* In chapter 1, added full-stop to "Shirou spoke bluntly."
* In chapter 1, remove unneccessary apostophe "“'They're all safe, and waiting in the forest with Kuro, as planned.”
* In chapter 2, added double left quote to "<p>'Whoa there, Mister. Yes you, Mister.”</p>
* In chapter 4, removed this "<p>was as smooth as gave off an air of was nothing but at the same time,</p>"