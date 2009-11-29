---
layout: demo
title: Analytics Visualizations for Google Analytics
thumbnail: /images/analyticsvisualizations.png
---
## {{ page.title }}

At Juice, we work with web analytics APIs large and small, from Google, comScore and Omniture. The Google Analytics API is our favorite. It powers the world's best, most widely deployed analytics site.  And it powers Juice products like [Concentrate](http://www.concentrateme.com) (innovative search analytics) and [Vasco de Gapi](http://vascodegapi.juiceanalytics.com) (a tool for exploring the Google Analytics API).

We were approached by the Google Analytics API team to find ways to explore new ways of looking at data with the API, and we were excited by the possibilities. We've been working on our own visualization framework, [JuiceKit](http://www.juicekit.org), that integrates the power of the [Flare Visualization Library](http://flare.prefuse.org/) with [Adobe Flex](http://www.adobe.com/products/flex/).

The result is [Analytics Visualizations](http://analyticsvisualizations.appspot.com), two visualizations powered by the [Google Analytics API](http://code.google.com/apis/analytics/docs/) that are free to use. You just need a Google account with access to Google Analytics data to explore your own data.

<p><a href="http://analyticsvisualizations.appspot.com"><img src="http://media.juiceanalytics.com/images/analyticsvisualizations.jpg" alt="Analytics Visualizations Home Page" title="Analytics Visualizations Home Page"></a></p>


### Referrer Flow

Curious about what sites are linking to you and what content is benefitting the most? Referrer Flow answers those question and shows how results change over time. Here is a brief video introduction:

<object width="580" height="465"><param name="movie" value="http://www.youtube.com/v/WkgFK2rshUk&hl=en_US&fs=1&"></param><param name="allowFullScreen" value="true"></param><param name="allowscriptaccess" value="always"></param><embed src="http://www.youtube.com/v/WkgFK2rshUk&hl=en_US&fs=1&" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="580" height="465"></embed></object>

Referrer Flow is a stream of daily treemaps showing pageviews and bounce rates for various groupings of your website's pages. You can group by combinations of page title, referrer and url. Clicking on the treemap will filter all the data by the page, referrer or url that you clicked on. Click again to clear your filter. 

### Keyword Tree

A list of top keywords isn't enough to really understand how people are searching and finding your site. Keyword Tree visually displays the most frequently used search keywords and how they are used together. Here's a video overview:

<object width="580" height="465"><param name="movie" value="http://www.youtube.com/v/Ap0Nsm08A9o&hl=en_US&fs=1&"></param><param name="allowFullScreen" value="true"></param><param name="allowscriptaccess" value="always"></param><embed src="http://www.youtube.com/v/Ap0Nsm08A9o&hl=en_US&fs=1&" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="580" height="465"></embed></object>

You'll see a frequently used search term at the center and the words and phrases that are most often used in combination with that word. Pick a different starting word by typing into the box in the upper right or selecting from the top word across the bottom of the screen. The words are sized by their frequency of use and colored by bounce rate (or % new visitors or average time on site). Roll over a word to see details about that combination of connected words.


### Depth and Discovery

In designing these visualizations we focused on the question: how can we let users uncover the unexpected? That means designing targeted visualizations focused on limited well-defined issues. The Referrer Flow monomaniacally focuses on a single question "What pages are people viewing on your site and where are they coming from?" The Keyword Tree is laser-focused on word ordering and what that means for keyword performance.

The Google Analytics reporting tool is a great general-purpose reporting solution. It gives the advanced users everything they need to answer specific questions. However, its generality means it has limited ability to focus on two issues; depth and discovery.

The Google Analytics API is Google's solution to this problem. It's an opportunity both for businesses like ours that can create new ways of analyzing data, and for large sites that can use the API for integration, custom analytics, and more. 

*Thanks to Nick Mihailovski at Google for his gracious support, help and encouragement and [Avinash Kaushik](http://www.kaushik.net/avinash/) for inspiring this idea.*