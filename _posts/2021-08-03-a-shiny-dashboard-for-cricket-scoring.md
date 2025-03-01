---
layout: post
title: A Shiny Dashboard for Cricket Scoring
---

As I said in my previous blog post, I am a cricket fanatic. I've always wanted to find a resource where I could see the scorecard of professional cricket matches - as an example see the scorecard [here](https://en.wikipedia.org/wiki/Scoring_(cricket)#/media/File:Cricketscoredcard1b.png).
However there did not appear to be anywhere that did this, so I decided to create a web application myself to do this. As a strong R programmer, Shiny seemed like a great tool that would allow me to do this. The app can be found [here](https://bfern.shinyapps.io/cricket-scorecard-writer/).

## How to use

The `Matches` tab gives you a list of Twenty20 matches for the specified date range, competitions and even a certain team if you decide to. For the match that you would like to view, then click on the "Go to Scorecard" button and the scorecard will open in the `Scorecard` tab. You can also toggle which innings you would like to see. To change the match, go back to the `Matches` tab and click on a new game.

Please be aware that if you have not yet selected a match by clicking the "Go to Scorecard" button in the `Matches` tab, then the `Scorecard` tab will be full of errors.

## Future to dos
* More formats other than just Twenty20.
* Use different colours for different bowlers, so you can see how each batsman fared against the different bowlers.
* Add the ability to click on a player and see an analytical overview of their stats broken down by year, competiton, etc.