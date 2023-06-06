# Milestone Project 1

## UX

### Project goals

The primary goal of 'Nickelback' is to provide users with a brief but to the point description of the band and their history as well as information on the key players that make up the band. It was also to showcase a taster of their full catalogue of music and promote their 2023 tour.

### Strategy

At this first step it was vital to decide, what does a user look for in a Band page? What would generally be the first thing they see, what would be eye catching, how much information would I personally want to see on a band I liked. The process for deciding some of the key features was visiting numerous band pages that are attributed to the same genre and a quick feedback session with some friends on what they would hope to see on a bands webpage. The majority of people said:

* Some form of description
* List or taste of music
* Tour dates/Ticket access

### Scope

Once settled fown with a generic idea, it was time to refine out the key parts of the website that would work best and start to think on a large scale ways and means in which they could be presented.

* Bands about information
  This was the first decision to make. This needs to be short and sweet as not to overload the user with too much to read and take away from the actual purpose of the site. The majority of people go to a bands webpage to check on touring news or to look at merchandise. This doesn't however always suit potentially new listeners and so needs to target those.
* Meet The Band
  This isn't often part of a bands page but a potentially nice touch because the imagery used to show the band can make them look exactly how you want, are they fun on stage, do they look fun, are they cool, hip? first impressions on new users is what could draw them in to liking the music.
* Discography
  A few band pages hold YouTube video links to its content, so it was deciding here how do you make the music section eye-catching? How to you draw them in to play, how do you make sure this is a solid, working section. Is this Album image, track list, links to external sources? This was a two part decision and will be chosen further in the process based on future testing. It will either be album covers and a full track list or embedded players based on feel and look at a later date.
* Tour dates
  What is the best way to list the tour dates? Can you list by region, does each date have it's own ticket link? This will be toyed around with, however at first instinct, it's own table would probably be best suited to convey the information in the best way and one link at the bottom of the page.
  
### Structure

The decision of the web page layout comes from both research and feedback from initial design which will be noted in the skeleton section. Separate the web page into sections/pages (again the choice will depend on easability and friendliness) one with the about info and the meet the band, relatively short page all in all but enough to drag you in. Another with the music of the band so there is nothing taking away from it and then finally a tour dates page for the user to see if their are any gigs in their area. This choice of layout seemed best because it was a natural progression from learning about the band - engaging with the band - wanting more from the band.

### Skeleton

Below are images based on a draw up - idea is loose and open to adaptation depending on how the project starts to come together.
(Licence had ran out on the wireframes site and i was unsure of an alternative so i drew them by hand)
images-for-readme/images2
The choices were made again, based on a natural progression through the website and again making sure to keep content to a minimum whilst also not making the site look bare. The choice of imagery will be a large factor due to the nature of the band i.e. a Rock band, so this needs to be portrayed in any visuals the use will come across.

## Code

* Modal sign up from created from <https://www.w3schools.com/> used own knowledge combined with syntax on the website
* Originally attempted making an image a button from <https://slackcommunity.com/>> however the idea went unused
* Navlink idea based from <https://www.w3schools.com/>
* Footer content based on <https://codeinstitute.net/> Love Running module covered
* <https://open.spotify.com/> for code to embed players and then adapted by myself to change the css

## Sources

* Band information sourced from <https://www.wikipedia.org/> as well as information about the band members
* Google was used for various images used throughout the page
* <https://open.spotify.com/> was used to embed players
*Tour dates from <https://nickelback.com/>

## Testing and Bugging

Code was written and then previewed each time, there were times when the html and css wouldn't respond and so the styling wasn't acting right. Examples of this were on the headings for each section. Particularly the 'about' section. This was fixed by putting the 'about' in it's own mini section. However, this probably isn't the most ideal or short hand fix.
There were no issues with the players playing the music, but there was issues within the html that affected validation, this was solved by changing the lines in the html to be css.
Other problems, mainly varied around positioning of text. Like within the banner and above the table for the tour dates. This took some playing around with and editing the css with developer tools to find out what worked before throwing it into the style.css file.
There was also problems with not clearing cached data, this solved some css issues when all html and css issues were exhausted.
Error with modal when submitting the form as I hadn't entered the posting method, or action. So this was fixed ready for final deployment.
Testing heading sizes and how they looked together, mostly on 'albums' and the album title, with how the text looked next to one another. This was a simple <h#> playaround, so no major issues arose.
Wanted to make the banner clickable and take you to either bottom of page or ticketmaster but didn't manage to complete this; as well as this there is a long scroll, looked into a scroll to top button but when writing the code the button didn't appear, so I removed this.

### Progressing the idea

The idea went from 3 pages to one page after a review with my mentor saying it would be more aesthetically pleasing on one page especailly if using a mobile browser. The layout of the band members changed from 2x2 to having all 4 in a line on a desktop/laptop and then to 2x2 on a tablet and on top of one another on a mobile device. The albums page where originally was an image and a tracklist was changed to just be the embedded player as it had the scrollable tracklist, album cover and a background colour to suit each albums theme. Headings were added and styled and looked at in comparison to one another.
Tour dates was probably the only consistent idea to show them in a table with a button at the bottom. However, the idea was scrapped to make it look like a ticket.

## Deployment

To deploy this website you follow the follow steps:

* git add any changes to your document
* git commit the changes
* git push to your github
* go to github and go to settings and your new website link should exist

Website was deployed in 3 stages. Initial deployment was based for testing purposes to test on all different types of devices and getting feedback before tweaking.
Inital feedback was good. Recommendations on layout and functionality mainly. This was where some bugs or errors were spotted.
Second deployment was done after fixes to headings, sizing of the players and testing of all buttons and features.
Final deployment was done after all code was fixed with <https://validator.w3.org/> which checked both html and css. This is now the finished version and feedback on this has been good, positive advice on the players and the layout structure.

## Positives and Negatives

Upon reflection of the project, there are lots of things that i think worked very well and some things i believe could have been adapted had i had more time or a bit more time. There are features i could have added in like a scroll to the top button, however, i didn't feel fully comfortable implementing this.
The things i liked were:

* The albums section
* The layout of the tour dates

Things that could be improved:

* Showing the hero image on all resolutions
