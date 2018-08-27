---
layout: page
title: CMS Project: Multi-user Blog
subtitle: CMS blog with many users and groups with different levels of access and privilege
use-site-title: true
permalink: /projects/cms/multi-user-blog
---
# DIY Charity Websites - a multi-user blog community

## Client Brief

We need a site for our community blog, we want to encourage new people to join up and start blogging but we are worried about spam signups so need to retain some sort of sign up approval process. It’s important that people can see a photo of the author of the post when they are reading it - put a face to a name. There's also a lot of jargon involved so we could do with some sort of glossary to explain them all.

## Key Deliverables

    * Homepage: A homepage explaining what the blog is about and showcasing the latest three promoted posts
    * ‘About us’ page: with more details about our organisation
    * ‘Blog topics’ page explaining the five topics we blog about
    * ‘Get involved’ page: A page explaining how people can get in touch if they would like to become a blogger on the site
    * A page at /blog showing a teaser list of all the published posts, latest first
    * Each blog post must show:
        * A title
        * An image (optional for users)
        * Byline of the author with name and photo
        * Date the post was posted
        * List or tags and topics linking to the tag or topic page
    * New users need to be able to sign up easily but the administrator needs to approve their membership before they can start blogging
    * A Glossary of terms at /glossary - this should display all terms alphabetically
    * Profile page of each blogger

## Tech Lead says

The blog set up should be pretty familiar to you - we just need more users and good visibility of their bios - you'll need to look at contextual filters and relationships in views to get that info displayed on their blog posts. For the blog post views themselves you could use field or rendered node views, usually for blogs rendered content is better. You can use the content type display to hide or show the different fields when you are looking at the node as a teaser or a full node - ask a mentor about this. It’s a good idea to create your dummy users first \(I’d say 6 - 8 would be enough for starters\) that way when you create your dummy content it will be easy to attribute the different users to their blog posts. For the Glossary you could look for a module or build it yourself with a new content type and views to display entries alphabetically. The glossary items could be terms in a taxonomy vocabulary or

## Bonus points

* A way to navigate the glossary by the first letter of the term - e.g. jump to all terms that begin with s
* Add a signup block to the get involved page but only if the user is not logged in
* Spam protection for the signup form ~ mollom, honeypot, captcha or Recaptcha
* Twitter link on profile page
* View of posts on profile page of that bloggers posts only
* Amend the emails that Drupal sends out on signup to be more personable
* Replace the standard Drupal comments with Disqus social commenting

# **Main Info**

| **Site name** | **Charity Websites DIY** |
| --- | --- |
| Site slogan | ‘A community blog for building and maintaining your own website as a charity or nonprofit’ |
| Intro | This site is a wealth of articles tips and advice about web design and development. All the posts are with specific reference to charity and nonprofit work, aimed at people who look after a charity website but maybe are not web professionals themselves or are looking to break into that area. The bloggers are all web professionals who volunteer their time and knowledge free of charge - please comment on the posts as it encourages participation and helps us to spread the word. |

# Site map

* Homepage
* About us
* The Blog
* Get involved
* Blog Topics

## List of Topics

### UX, Usability and Accessibility

User experience and usability are fundamental to the success of your website - These posts talk about how people use you site and what you can do to make it better for everyone.

### Donations

Donation systems, integrations, widgets, payment providers - posts about one of the most important functions of a charity website.

### SEO

You’ve built your site now it needs to be found - these are all the posts that talk about increasing your rankings in search results.

### CRO

Conversion Rate Optimisation - get more people to click. These posts talk about methods to encourage visitors to your site to achieve the goals you set for example getting them to sign-up to your newsletter or donate to your cause.

### CMS

Most websites these days have a content management system or framework. These posts explain what they are and review functions and differences between the many different ones there are to choose from.

### Open Source

Open Source software is great for charities - these are all the posts introducing or talking about different open source solutions.

## Resources

You’ll need some dummy users and dummy content for those blog posts, you could use a module or plugin to generate content and users but you site will look better, and more real, if you take the time to add some yourself.

Here is a list to get you started but the mentors may have their own favourites.

## Profile details

* [randomuser.me](http://randomuser.me/)
* [fakenamegenerator.com](http://www.fakenamegenerator.com/)

## Copy

* [html-ipsum.com](http://html-ipsum.com/)
* [blindtextgenerator.com](http://www.blindtextgenerator.com/snippets)
* [Chrome apps](https://chrome.google.com/webstore/search/dummy text?hl=en)

## Images

* [flickr.com creativecommons](https://www.flickr.com/creativecommons/)
* [Google image search](https://www.google.co.uk/imghp)

## Glossary Terms

* [Glossary of web terms](http://www.thinkingit.com.au/glossary-of-website-terminology)
