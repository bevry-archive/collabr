
# Collabr<br/>Crowd Sourced Web Editing

Copyright 2011 [Benjamin Arthur Lupton](http://balupton.com) &lt;contact@balupton.com&gt;
Lincesed under the [Attribution-ShareAlike 3.0 Australia (CC BY-SA 3.0)](http://creativecommons.org/licenses/by-sa/3.0/au/deed.en)

## Introduction

### Background

The web is growing dramatically more social, interactive - but why? Why has services like [Facebook](http://facebook.com), [Twitter](http://twitter.com) and [Github](http://github.com) reached success? **They make it trivial to collaborate.** Facebook - Information, Twitter - Knowledge, GitHub - Code.

### The Current State of Web Editing

#### Content Editing

Content Editing on the web currently requires a dedicated [Content Management System](http://en.wikipedia.org/wiki/Cms) to save changes or at the very least a [Version Control System](http://en.wikipedia.org/wiki/Revision_control) - both of which require installation procedures as well as experience and training before they are usable.

#### Design Editing

The design editing process generally starts with prototyping your changes in the browser by editing them **inline** with tools like [Firebug](http://getfirebug.com/whatisfirebug). Once satisfied, you would then **remember and re-apply* those changes in your desktop editing software such as [TextMate](http://macromates.com/) or [DreamWeaver](http://www.adobe.com/products/dreamweaver/). Once re-applied, you would save and publish the changes - this step would involve adding, committing and pushing the changes to a Version Control System, then deploying the changes via [FTP](http://en.wikipedia.org/wiki/File_Transfer_Protocol) to your [web host](http://en.wikipedia.org/wiki/Web_hosting_service).

#### Web Collaboration

The state of web collaboration currently requires users to post comments or send emails to the author about the changes they would like to see (for example, a word is misspelt) - the website author would then review the request for the change ("fix this typo") and add it to a to-do list. When they get around to applying the change, they login to their CMS, make it and save it. At this point the contributor has left the site, moved on and forgotten about the issue - never to learn it was actually fixed.

## The Problem

These solutions are complicated and time consuming which hinders collaboration because of it. Especially when it takes one week for a typo to get fixed on a website that a user spotted, which that user could easily have applied themselves if they had the access and experience to do so.

Let's restate that, the current state of web editing is hindered due to it's complicated and time consuming nature, it needs to be accessible to everybody and trivial enough so everybody can use it (trivial - requires no experience or training to know how to use it).

## A Better Way

### A Typo is Found

A user finds a typo on your website, anywebsite. They notice a **toolbar** up the the top right, that contains an **edit** button, they click it.

*Alternatively they click the Collabr **browser extension** and load in this functionality instead of it being included by the website itself.*

### The Website is now Editable

They notice that the text surrounding the typo now displays the **text cursor**, they click the text and the **blinking cursor** appears allowing them to edit the text as they would in normal editor.  A **floating bar** also appears allowing them to apply formatting to the text.

They fix the typo and **save** it via a button in the **toolbar**, they are prompted to add a **commit note** describing the changes, they click okay and the changes are now saved.

### Sending the Changes to the Author

As soon as they saved the page, a new prominent button appears in the toolbar titled **send changed to the website author**, they click it and are presented with the options for **not yet *(keep these changes local)*** or **yeah sure *(send them away)***. They choose the later option and are asked to provide their **contact details*.

The website author then **receives an email** containing **previews** and *diffs** of the changes and the contributors contact details. The website author is grateful and amazed and sends the contributor a lovely thank you email.

## More Power / Advanced Use Cases / Roar

### More Power

_With this new power the user feels empowered and liberated. They can now edit this website, have the changes applied and at their digression send them to the website author. The website has just become crowd-sourced._

They notice that they can also:

- Edit the CSS of the Website
- Re-Arrange content items including blocks, images, and widgets.
- They can customise the attributes for elements, images and widgets.
- They can edit the HTML directly via a **inspector** like tool.
- View the revision history of their changes with the new, old, and diff visible with each change.

They make a few more changes. They then click

### Sending the Changes


## Status

### Proof of Concept

Benjamin Lupton is an active [Aloha Editor](http://aloha-editor.com/) Team Member. Aloha Editor offers the inline editing functionality described as well as the floating toolbar.

### Monetization

Even though the product will be free, the community and support plans is where the money is.


This is **currently under active development** and **will be presented at** the **[Aloha Editor DevCon](http://aloha-editor.org/wiki/index.php/Aloha_Editor_Dev_Con_11)**.
