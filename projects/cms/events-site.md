---
layout: page
title: CMS Project: Events Site
subtitle: CMS Events site - display and manage events at three locations
use-site-title: true
permalink: /projects/cms/events-site
---
# Events Site

## Brief from the client

A client has come to your agency as they want a basic Events site. They have outlined to the sales team the key deliverables that needed. However the client has also requested some ‘nice to have’ items to be included, if there is remaining time available within the budget.

They use meetup.com to manage attendance so the site does not need to replicate that functionality such as handling signups but they will need to link to the specific event on meetup from the Drupal site.

They have 3 venues where events are held, however as they are a growing company they will be looking to expand this number in the future.

There will also be differnt groups of people using the admin side of the site - promotors who run a particular event, venue managers who are responsible for a particular venue.

# Key deliverables

* Homepage: A homepage explaining the events we run and showcasing the next upcoming event.
* ‘Contact us’ page: A page explaining how people can get in touch if they would like to run an event - use a contact form on this page.
* A page at www.example.com\/events showing upcoming events with the next one first and future events
* Each event needs its own page
* Each event must have:
    * A title
    * A venue
    * A start and end time
    * A single date on which it occurs (no events are on multiple days)
    * A location address and postcode
    * An image \(optional\)
    * A short description about the event
    * A link to sign up on meetup.com

# Tech Lead says:

You’ll need a new content type with some new fields, there is a module for date field which you will find invaluable.

You will need to create a view for the upcoming events using the date field as the filter (so that you can exclude past events from being shown) and also for the sort order (so you can order the events next first). You’ll need to add a block view as well as the page view so that you can add that block to the homepage. The positioning could be done with the blocks administration or with the context module - ask a mentor to explain the difference.

You could use field rendering or node rendering for the views - ask a mentor about the difference and the pros and cons of each.

**hook\_form\_alter** will be useful for adding in custom validation methods. Events and their venues cannot clash i.e. you cannot create 2 separate events on the same day at the same venue. The Devel modules will help you in the development of custom modules and theme functions.

# Bonus points

* Add functionality to tag events as Live music, comedy or DJ events - add pages in the main menu that list events under those headings
* The title must automatically include the venue name
* Create a view of previous events on a different page
* Show a map with the event location on each event page
* A ‘Back to events page’ link on separate events
* Add a dropdown select to the contact form to specify which venue the person is enquiring about.
* Send the contact form to additional different email addresses based on which venue the user selects on the contact form.
* A contact page that does not use the webform module. Instead it uses a custom form using Drupal’s form api.
* Add functionality to show on how long a event runs for.
* When creating an event its date needs to be at least 1 week in the future from the current date.
* Add an xml sitemap

# Site map

* Homepage
* Events
* Contact us

## User roles

* Event Organiser
* Event Attendee
* Venue Manager
* Main Admin

## Resources

The client has three venues that host events - addresses below.

### Venues

[**The Wardrobe**](https://www.leedsgigs.co.uk/w_venue_The_Wardrobe%7CLeeds.html)
6 St Peters Square, Leeds, LS9 8AH

[**Brudenell Social Club**
](https://www.leedsgigs.co.uk/w_venue_Brudenell_Social_Club%7CLeeds.html)33 Queens Road, Leeds, LS6 1NY

[**Headrow House**](https://www.leedsgigs.co.uk/w_venue_Headrow_House%7CLeeds.html)
Bramleys Yard, Leeds, LS1 6PU

### Content

You’ll need some dummy content for those events, you could use a plugin or module to generate content but you site will look better, and more real, if you take the time to add some yourself.

Here is a list to get you started but the mentors may have their own favourites.

#### Copy

* [html-ipsum.com](http://html-ipsum.com/)
* [blindtextgenerator.com](http://www.blindtextgenerator.com/snippets)
* [Chrome apps](https://chrome.google.com/webstore/search/dummy text?hl=en)

#### Images

* [flickr.com creativecommons](https://www.flickr.com/creativecommons/)
* [Google image search](https://www.google.co.uk/imghp)
