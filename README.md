# MJML
MJML is a resonsive email framework.
It's used to buid a responsive email.

### Requirements

* Node >= 4.2.x

### Installation

* npm install -g mjml


### Getting Started

* Create the file with .mjml extensions for example (index.mjml)

* Code your mailer in MJML file

* After complete your coding compile the MJML file to get the HTML file

* Once we get the generated HTML we can send it with an email service provider.

### Commands to compile the MJML file

* Compile the MJML file and output the result in .html 'mjml -r filename.mjml'

* Redirect the result to a file 'mjml -r fileName.mjml -o fileName.html'

* Watch a file and compile every time the file changes 'mjml -w fileName.mjml -o fileName.html'
