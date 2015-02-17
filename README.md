# H1 Ready to use jekyll-compass template

This template was made by running `jekyll new .` and then `compass create -r jekyll-compass` in an empty folder. 
Jekyll works with sass so I had to remove css and _sass folder, now all styles are served from _compass. The output folder is _site.

# H2 Hot to use it

I used and tested this template with 
* ruby  1.9.3
* Ruby DevKit for 1.9

Install jekyll by running `gem install jekyll` in terminal.
Clone this repository to some folder and run `jekyll serve` in it. Navigate to http://127.0.0.1:4000/ in your browser. Make changes to scss files in _compass folder and/or html files. Jekyll will compile everything to _site folder.
In order to use sprites place your images to images/icons folder in project root. Sprite image and relevant classes will generated as usual when using compass.
