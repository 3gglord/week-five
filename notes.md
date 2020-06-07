# Week Five Notes

## Sonification
- Sonification: visualization of historical data auditorially to achieve a particular sensory effect [source](http://songsoftheottawa.ca/index.html)
- used Two Tone's sample data, Honey production in the USA (1998-2012) to familiarize myself with the program
- different tones stand out more when you listen to them than others
  - ex. the piano is more noticable than the bass when played simultaneously because the bass has a lower tone
- when using the archaeological data, the program displays the qualitative data (where the materials were found) on the bottom
  - The duration of the song co-incides with the place where the materials were found
  - could help us see patterns in the change of the number of coins as it gets further along in the song
- lowered the volume of the count of other Roman materials because I wanted to notice when coins were found
  - I set it to 90% volume while the other stayed at 100%
  - also set the instrument for count of other Roman materials to piano and count of coins to trumpet
  - different intruments, volume settings, and sounds could change what the listener hears, thus changing the meaning of the song
[Roman data, sonified]()

## Mapping
### StoryMaps
- didn't have any location-based research in mind at first, so I just mapped a theoretical road trip I would have from my hometown to Ottawa
- [here](https://uploads.knightlab.com/storymapjs/bf5a196c6852db101445a82dee4321d5/story-map/index.html) is the link to my map
- really cool tool for showing narrative
  - could be useful for biographies or tracking the movement of materials
### web maps
- [open source map](http://revolt.axismaps.com/map/) made using leaflet.js
  - map is in the style of the maps from the time period
  - shows the movement of the battles, who was attacking from where, how they had to transport troops/resources
  - gives context and explanation on the side
- mapping with Leaflet
  - no errors with the initial map and python
  - tried adding more data using the instructions from [this link](https://subscription.packtpub.com/book/web_development/9781783554812/1/ch01lvl1sec12/adding-data-to-your-map#:~:text=You%20can%20create%20a%20marker,interact%20with%20it%20by%20name), but the instructions didn't work
   - after looking for other instructions and some experimentation (like adding "features" to point-data.geojson), I still didn't find a method that worked
    - I'll have to look for another way the next time I try to make a web map
  - error when adding animation
  ![leaflet-animation-error](leaflet-animation-error.png)
  - after looking up the error message and reading the answers on [this website](https://stackoverflow.com/questions/25490653/simplehttpserver-error-404-get-d3-d3-v3-js-http-1-1-404), I realized that I labeled my .js file incorrectly
  - fixed the misspelling and it ran perfectly
  - original webmap: http://0.0.0.0:8000/
  - map with layers: http://0.0.0.0:8000/index2.html
  - map with animation: http://0.0.0.0:8000/index3.html


From [this reading](http://www.themacroscope.org/?page_id=875): cartography is as much of an art as it is a science
- there can be many ways to map something
- each map can argue something different, even if it is depicting the same place as another

## Posters
- academic posters and infographics
- information visualization: mapping of abstract data to graphic variables to make a visual representation
Static visualizations are those which do not move and cannot be manipulated; dynamic visualizations are short animations which show change, either over time or across some other variable; interactive visualizations allow the user to manipulate the graphical variables themselves in real-time. [...] The key is striking a balance between clarity and flexibility.


## static site
- used other site-building platforms before, but have never made a static site using github
- easier than I expected
- https://help.github.com/en/github/working-with-github-pages/creating-a-github-pages-site
- [customize the theme layout](https://help.github.com/en/enterprise/2.14/user/articles/customizing-css-and-html-in-your-jekyll-theme)
https://github.com/onivim/oni/issues/1708
https://www.w3schools.com/cssref/sel_hover.asp
https://www.codesdope.com/blog/article/adding-outline-to-text-using-css/
https://paula-rodrigo.github.io/
