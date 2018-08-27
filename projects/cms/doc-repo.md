---
layout: page
title: CMS Project: Doc Repo
subtitle: CMS document store, display, manage and download a collection of binary documents
use-site-title: true
permalink: /projects/cms/doc-repo
---
# Doc Repo - a filterable document repository

# Client Brief

We need a site to showcase the 24 resource documents we have, the docs are a mixture of word and pdf and are free to download to the public. We would like to give people the opportunity to comment on the documents on the website as well. The documents are organised under 6 topics and we would like visitors to the site to be able to filter by topic to find the documents they need.

# Key Deliverables

* Homepage: A homepage briefly explaining what the site is about and showcasing the latest three promoted documents
* ‘About us’ page: with more details about our organisation
* ‘Resource topics’ page: explaining the five topics we talk about
* A page at **/resources** showing a list of all the resources, latest first
* Each resource post must show:
* A title - automatically includes the document type (e.g. docx, pdf, etc)
* An image (optional)
* Download link
* Date the resource was published
* A List of tags or topics linking to the tag or topic page


# Tech Lead says

First up you are going to need a new taxonomy vocabulary for the topics.

You’ll also need a specific ‘resource’ content type to attach the document to - that way you will be able to list them easily in a view and have people comment on them without having editing access to the actual document or web page.

Drupal hooks are powerful tools, that may help you.

In the main view of the resources you'll be wanting to set an **exposed filter** of the topic - this means we can give users options for filter rather than set it ourselves behind the scenes.

One of the most used contributed modules is the link module which would be an obvious candidate for this project.

# Bonus points

* Add a slider for the three promoted documents displayed on the home page
* Custom Report\(s\) for the documents, e.g. number of views, number of comments, etc
* Add access control for the documents, have some which are publically viewable, and others which require a login to view
* Add a blog to the site that uses the same taxonomy as the resources
* Showcase specific resources by attaching one or more to specific blog posts with entity reference.
* Add a block to show related resources by taxonomy term on blog posts and resource pages
* Add a block to show related blog posts by taxonomy term on resource pages

# Main Info

| Site name | Open Source Doc Repo |
| --- | --- |
| Site Slogan | ‘Resources for people interested in Open Source and CMS’ |
| Intro | This site contains useful documents for anyone wanting to know more about Open Source software, in particular Open Source content management systems and frameworks. |

# Site map

* Homepage
* About us
* Resource topics
* Resources

# Suggested List of Topics

* Drupal
* Wordpress
* Magento
* Other Frameworks
* Open Source
* Content Management

## Resources

Resources for this project are available on [Google Drive](https://drive.google.com/drive/folders/0By9KqisVw_3lQXJJcVdubnBiNVk?usp=sharing)
