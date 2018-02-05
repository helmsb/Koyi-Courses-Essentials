# Build a Koyi Course
Author: Blake Helms <bhelms@ebsco.com>
Level: Beginner
Tags: #LMS 
Short Description: We will review what a Koyi course is and how to build it?

## What is Koyi?
Time: 3 Minutes

Koyi is an easy-to-use, modern, federated Learning Management System designed from the ground-up to be easy to author, extend and is fully portable. 

You're never locked into Koyi since the authoring system uses industry standard Markdown and JSON. Build courses in the editor of your choice and simply upload them to Github to publish.

You can share your repo with other Koyi users and they can take advantage of your work and can even contribute back with pull requests!

In the rest of this course we will be the syntax and how to write our own course.

## Technologies
Time: 3 Minutes 

Koyi uses plain-text Markdown files for the course data and JSON for defining assessment questions.

### Markdown
Markdown is a set of plan-text syntax defined by blogger John Gruber for cleanly writing HTML. It uses hashes ( # ), ( * ) and other symbols to denote H1s, H2s, unordered lists, etc.

### JSON
JavaScript Object Notation or JSON is an open-standard file format that uses human-readable text to transmit data objects consisting of attribute–value pairs and array data types. In Koyi, JSON is used to define assessment questions. We will go into the specifics in a later chapter.

## Syntax
Time: 5 Minutes

The markdown syntax is simple and easy to learn. You can get a full overview of the available syntax [here](https://guides.github.com/features/mastering-markdown/)

In addition, there are some special keywords that must be in your document in order to be valid. 

### Introduction
The course file is made up of both standard Markdown and some special tags which are written as `Property:` and placed at the top of the file.

#### Title
Every file must begin with an H1 to define the title. This will be displayed at the top of the course details page and on the course card on the catalog page.
`# Course Title`

#### Author
We need to know who to thank for this course. It includes both a name and an email address.
`Author: Blake Helms <blake@blakehelms.net>`

#### Level
In order to properly sort the courses we need to define what level of student this course is targeted at. 

The available levels are:
1. Beginner
2. Intermediate
3. Advanced

`Level: Beginner`

#### Tags
For categorization Koyi uses tags. You can have any number of tags. Tags are defined with hashes `#` much like a hashtag `#hastag`

`Tags: #LMS #Learning`

#### Description
This is where you define a short description for your course. The description is limited to 280 characters or less. 

`Description: I am the course description`
