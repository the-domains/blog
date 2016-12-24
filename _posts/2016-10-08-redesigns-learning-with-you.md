---
datePublished: '2016-12-24T05:48:43.540Z'
sourcePath: _posts/2016-10-08-redesigns-learning-with-you.md
inFeed: true
hasPage: true
author:
  - name: 'October 7, 2016'
via: {}
dateModified: '2016-12-24T05:48:42.758Z'
title: 'Redesigns: Learning with You'
publisher:
  name: Henri Bergius
  url: 'https://twitter.com/bergie'
description: >-
  One important part of working with a web designer — whether AI or human — is
  to be able to try different designs of your site and be able to give feedback
  on them. With The Grid, this works by giving your friendly AI designer Molly
  some guidance through reviewing the designs you’ve received and rating various
  aspects of them.
starred: false
datePublishedOriginal: '2016-10-08T01:21:53.056Z'
url: redesigns-learning-with-you/index.html
_context: 'http://schema.org'
_type: Article

---
# Redesigns: Learning with You

One important part of working with a web designer --- whether AI or human --- is to be able to try different designs of your site and be able to give feedback on them. With [The Grid][0], this works by giving your [friendly AI designer Molly][1] some guidance through reviewing the designs you've received and rating various aspects of them.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/6d30a7eb-83b2-4947-afb1-42e547ab7691.png)

Today we rolled out a feature that makes these redesigns smarter.

Instead of just trying something different every time, we now look at the _whole history of redesigns_ you've received and how you've rated them. Design aspects you've liked in the past are likely to occur again, and things you didn't like get avoided.

## Improving, piece-by-piece

As explained in my [Lift Conference talk last February][2], The Grid's AI has been built up in a modular fashion out of many different pieces: [content analysis][3], propagation heuristics, [design systems][4], and so forth. This approach allows us to improve and adapt each part on its own lifecycle. In the current sprint one important part was the redesigns feature.

As users who have been with us through the beta days remember, originally the way you'd redesign a site was by giving a big bunch of strict parameters on things like formality and brand strength. Last spring we rolled out the new redesigns UI, first in our [web app][5] and soon afterwards [on Android][6].

With this you can see the designs made for your site and give them a rating. The design AI then makes the requested modifications and gives could of options to evaluate. Rinse and repeat. Once you've come to a design you like, you can make it live on your website. When the AI learns new tricks, we'll make those available and you can again explore the new possibilities using this feature.

Originally these new redesigns would be quite random. If you liked something, we'd lock that aspect down and explore the other areas of the design spectrum. Now, with the learning algorithm, we explore possibilities in a much wider fashion, but try to _prefer things you've liked and avoid things you disliked_.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/bfdb8ac9-e76d-4eca-a329-b6f7062fea88.jpg)

In our simulations of thousands of users doing redesigns, this improved the success rate of getting the design you like by _an order of magnitude_. In some runs I saw success rates as high as 96%.

## Getting started

Trying the new redesigns feature is easy: simply fire up our web or Android app, and go to the _Design_ section of your site. If you've already published something on your site, you'll see the current live design as the starting point:
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/b66ede6d-74b1-4e08-992e-f53633f67ddf.png)

Now you can preview that version, and give feedback. In our Android app you can even see the site in both mobile and desktop versions:
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/886de882-9abb-4457-872d-b003b0e6aecd.png)

After you've given your design review, the AI will look at the ratings as well as your previous designs, and come up with couple of new suggestions. You can keep refining them, and once you're happy with one, simply publish it. In couple of minutes, your freshly-redesigned site will be live.
![](https://the-grid-user-content.s3-us-west-2.amazonaws.com/24bdbda7-7636-4bbe-a45f-a0210f332e94.png)

We're excited to see what kind of new designs our users come up with!

[0]: https://thegrid.io/
[1]: https://blog.thegrid.io/the-wizard-of-gridsites-molly-your-new-ai-bff
[2]: https://youtu.be/v65HLBGLG_g
[3]: http://automata.cc/discovering-salient-regions
[4]: http://design-systems.github.io/basics/
[5]: https://app.thegrid.io/
[6]: https://blog.thegrid.io/the-new-android-app