---
README: >
  as soon as we know the date for the next meetup, `cp _drafts/stay-tuned.md
  _posts/YYYY-MM-DD.md`, remove this README, and add a `when` property to this
  section. the front page will update to let folks know that we've got
  something in the works.
title: Stay Tuned&hellip;
author: aaron
layout: post
permalink: "/:categories/:year/:month/:day/"
categories:
- posts
- meetups
---

We have a meetup planned for <x-date>{{ site.categories.meetups[0].when | date_to_xmlschema }}</x-date>, but we haven't announced any more details.

Check back here or <a href="{{ site.twitter.url }}">follow us on Twitter</a>
for updates.
