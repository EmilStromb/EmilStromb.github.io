---
layout: post
title:  "Questions"
date:   2019-11-12 05:26:03 -0600
categories: jekyll update
---
<h3>What do you think of pre-compiling your CSS?</h3>
This function is basically takes the code that you have done in scss (that im using) and converts it to CSS. The preprocessed CSS gives you features like nestings, @import, mixins, and varible, it's also less css to maintain. What i think is most is usefull is varibles, you can make varible in css files with $ to reuse it, it gives you less code to maintain and better structure. 
<h4>Compare to regular CSS</h4> 
I think css preprocessing is better so far, it compiles all sass files together to a singel file for the site, and as mentioned above its less code to maintain, using varible so it makes DRY better. 
<h4>Which techniques did you use?</h4>
<h4>Pros and cons?</h4>
I think pre-compiling has more pros then cons today, as we learned on our first lecture, most things that pre-compiling made it better then css also is added to css slowly, but while thats not done yet, i think pre compiling is better. It's effcient, saves you time and hold better for DRY. 
<h3>What do you think of static site generators?</h3>
I like static site generators, when it comes to private person or small company that whants to create a site i belive its better to do with static site generator, performance we dont need to wory about performance, if your site gets huge and alot of people want to use it static site generators will help have proper servers to handle it, aswell as security, we dont have to worry about intrusion in our database. 
<h4>What type of projects are they suitable for?</h4>
I think they are suitable for every one that doesnt have a small server they can put their website on, and even if they do it still more work for you because then you have to think about updates, security etc. That static site generators does for you. If there is a larger company i think they probably got better equipment and people to handle the load of the site then. 
<h3>What is robots.txt and how have you configure it for your site?</h3>
it's a text based file for robots, it's for robots that wants to enter your site, so if they do first thing they do is check http://example.com/robots.txt and i have set my rules to user-agent: * (meaning this is set for all robots) and disallow: / (meaning all files under / they not go to)
<h3>What is humans.txt and how have you configure it for your site?</h3>
It's the team of workers who created the site, first you start with /*TEAM*/ and add person for person with contact info like, your title, in my case BOSS, Email adress, twitter if you have it, location witch is kalmar, Sweden in my case. Then you move over to /*THANKS*/ if you got anyone els who has help you or given you information to create the site, i dont have anyone because this is an examination. Last you write /*SITE*/ witch is the information about creating the site like, when it was last updated, what standards you used to create it, language you used and last your sofware you used.
<h3>How did you implements comments to blog posts</h3>
I used Disqus for my comment section, it was very easy to use and configure on their site to enable for example emoji's. All you needed is an universial code tho add and add font matter comments: true for the sites you want it on.
<h3>What is Open Graph and how do you make use of it?</h3>