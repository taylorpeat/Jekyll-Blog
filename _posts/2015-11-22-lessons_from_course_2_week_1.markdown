---
layout: post
title:  "Lessons from course 2: Week 1"
date:   2015-11-22 03:33:00 -0500
categories: Tealeaf Academy
---

This week was primarily focused on picking up Rails syntax, understanding relational databases and understanding ActiveRecord.

ActiveRecord is Object Relational Mapping used by Rails that assists in creating and retrieving information from the database.

One piece of Rails syntax which was particularly useful was the ability to render an array of objects using partials. The code ` <%= render <collection> %>` automatically looks for a partial with the singular name of the collection inside a folder with the collection name within the views folder. The members of the collection are iterated through with each member being supplied as a local variable of name ‘collection_singular’ to the partial which is rendered each time.

The area noted as most important to memorize was the controller actions related to the URL and HTTP request methods. I combined some quick flash cards to ensure I had the routes memorized shown below:
<iframe class="studyStackFlashcardIframe" src="https://www.studystack.com/inewflashcard-2065996" width="850" height="440" frameborder="0" scrolling="no" style="overflow:hidden"></iframe>