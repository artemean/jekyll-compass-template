# Ready to use jekyll-compass template

This template was made by running `jekyll new .` and then `compass create -r jekyll-compass` ([plugin](https://github.com/mscharley/jekyll-compass)) in an empty folder. 
Jekyll works with sass so I had to remove *css* and *_sass* folders, now all styles are served from *_compass*. The output folder is *_site*.

## Hot to use it

I used and tested this template with 
* Ruby  1.9.3
* Ruby DevKit for 1.9
* jekyll 2.1.1

Install compass by running `gem install compass` in terminal.

Install jekyll: `gem install jekyll -v "=2.1.1"`. 
_The latest (2.5.3) version of jekyll was unstable on windows 7 so I had to install an earlier one._

Install jekyll-compass: `gem install jekyll-compass`.

Clone or download this repository to some folder and run `jekyll serve` in it. 

Navigate to http://127.0.0.1:4000/ in your browser. 

Make changes to scss files in *_compass* folder and/or html files. Jekyll will compile everything to *_site* folder.

In order to use sprites place your images to *images/icons* folder in project root. Sprite image and relevant classes will be generated as usual when using compass.
