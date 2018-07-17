# UserProfile
Hello Everyone. I have written the code to help me build an awesome CV, and I have used responsive HTML and CSS. The same HTML and CSS is used to generate a PDF version, using wkhtmltopdf. Based on a design by Zack Grossbart.

Setup
For PDF generation, you need to install wkhtmltopdf:
[macOS] brew cask install wkhtmltopdf
[Debian-based] sudo apt-get install wkhtmltopdf

Building
Generate the PDF with:
bin/build.sh

Watching
Automatically generate the PDF and refresh the browser when files change (macOS only):
brew install entr
bin/watch.sh


Fonts:
Open Sans: Apache
Merriweather: OFL
