---
include: head
layout: post
title:  "Questions"
date:   2019-11-16 06:12:03 -0600
categories: jekyll 
author: Emil
---
<h3>What do you think of pre-compiling your CSS?</h3>
This function is basically takes the code that you have done in scss (that im using) and converts it to CSS. The preprocessed CSS gives you features like <a>nestings</a>, <a>@import</a>, <a>mixins</a>, and <a>varible</a>, it's also less css to maintain. What i think is most is usefull is varibles, you can make varible in css files with $ to reuse it, it gives you less code to maintain and better structure. 
<h4>Compare to regular CSS</h4> 
I think css preprocessing is better so far, it compiles all sass files together to a singel file for the site, and as mentioned above its less code to maintain, using varible so it makes DRY better. 
<h4>Which techniques did you use?</h4>
I mostly used varibles, witch i really liked because it doesn't change a small portion, it changes everything you like to easy with just changing the varible, sure you probably want to change some small stuff around it too but it's way quicker then normal css. Since we use Jekyll aswell it takes some time to see what changes what.
<h4>Pros and cons?</h4>
I think pre-compiling has more pros then cons today, as we learned on our first lecture, most things that pre-compiling made it better then css also is added to css slowly, but while thats not done yet, i think pre compiling is better. It's effcient, saves you time and hold better for DRY.
<h3>What do you think of static site generators?</h3>
I like static site generators, when it comes to private person or small company that whants to create a site i belive its better to do with static site generator, performance we dont need to wory about performance, if your site gets huge and alot of people want to use it static site generators will help have proper servers to handle it, aswell as security, we dont have to worry about intrusion in our database. 
<h4>What type of projects are they suitable for?</h4>
I think they are suitable for every one that doesnt have a small server they can put their website on, and even if they do it still more work for you because then you have to think about updates, security etc. That static site generators does for you. If there is a larger company i think they probably got better equipment and people to handle the load of the site then. 
<h3>What is robots.txt and how have you configure it for your site?</h3>
it's a text based file for robots, it's for robots that wants to enter your site, so if they do first thing they do is check http://example.com/robots.txt and i have set my rules to <a id="boxcomment">user-agent: *</a> (meaning this is set for all robots) and <a id="boxcomment">disallow: /</a> (meaning all files under / they not go to)
<h3>What is humans.txt and how have you configure it for your site?</h3>
It's the team of workers who created the site, first you start with /*TEAM*/ and add person for person with contact info like, your title, in my case BOSS, Email adress, twitter if you have it, location witch is kalmar, Sweden in my case. Then you move over to /*THANKS*/ if you got anyone els who has help you or given you information to create the site, i dont have anyone because this is an examination. Last you write /*SITE*/ witch is the information about creating the site like, when it was last updated, what standards you used to create it, language you used and last your sofware you used.
<h3>How did you implements comments to blog posts</h3>
I used <a href="https://disqus.com/">Disqus</a> for my comment section, it was very easy to use and configure on their site to enable for example emoji's. All you needed is an universial code tho add and add font matter <a id="boxcomment">comments: true</a> for the sites you want it on.
<h3>What is Open Graph and how do you make use of it?</h3>
Open Graph is used for how you want to present your website when shared in social media. In my work here i needed to use <a>title</a>, <a>url</a>, <a>type</a> and <a>image<a> and those are explained well on <a href="https://ogp.me/">Open Graph Protocol site</a>. All you need to to is to put them in <a>meta</a> tags in your <a>head</a> tag. 

* og:title - The title of your object as it should appear within the graph

* og:type - The type of your object.

* og:image - An image URL which should represent your object within the graph.

* og:url - The canonical URL of your object that will be used as its permanent ID.
