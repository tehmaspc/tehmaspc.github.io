---
layout: post
title:  "Moving to GitHub Pages"
date:   2013-12-27 17:00:00
categories: jekyll update github
comments: true
---

This is my first post to my [GitHub Pages][ghp] site and it's using [Jekyll][jekyll] for the backend static site generation. I've been desiring to move my main website to GitHub Pages for a while now, but until now I haven't had the time to do this properly. I'm taking advantage of the winter holiday break to begin my migration over to this platform. The reasons behind this desire have been for the following technical and logical reasons.

First, I've been itching for a simpler way to maintain my website and to rid myself of the task of having to manage a full blown Wordpress installation just to serve up some simple blog posts. Barring Wordpress' [SaaS service][wp], in order to run a Wordpress site you need a web host some place out on the Internet and that ultimately adds complexity and incurs a monetary cost. I wanted to rid myself of this burden of running a Wordpress installation and the extra costs associated with it (especially for a website that doesn't garner much web traffic). Maintaining a Wordpress site can be a pain in the butt since Wordpress and Wordpress plugin authors are notorious for pushing out tons of updates all the time. Let's also not forget to mention the additional overhead of maintaining a SQL database to which Wordpress must talk to. Thus, I needed a better solution and going the static site route made the most sense to me.

Once I had decided to go the static site route, I needed to find the best tool for generating the static website. I discovered that there are a ton of [static site generators][ssg] out there but in the end I decided to go with Jekyll for now because it is Ruby based, in active development, and overall quite simple to use. It allows me to quickly create posts in [Markdown][md] format - which to me is the preferred format of choice since I use Markdown quite a bit when I'm interfacing with the rest of the GitHub ecosystem (repo documentation, wiki, and gists). I initially felt inclined to go with [Octopress][op] since it is quite popular amongst the developer community - but after playing around with it I feel that it's a bit bloated for my needs at this time. The design of my website is of importance to me and the default Octopress theme doesn't cut it. Trying out other Octopress themes actually presented a problem because some themes just wouldn't compile cleanly and thus I felt that during the course of using Octopress for my website I may end up with more maintenance tasks then I would really like to have. After toying with Jekyll for about a week I'm quite satisfied with the results. The best win is that having my content in Markdown makes it easy to migrate it to some other platform in the future. If in the future Octopress is what I need I can migrate over to it very quickly.

Finally, moving to GitHub Pages provides me with yet another avenue for working with Git. A lot of my development work takes place on GitHub (or is influenced by it) and I think the idea of having my main website close to all the code I hack on is a great idea. I want to force myself to write and code more and having both my code and website on GitHub makes a lot of sense to me. GitHub, without a doubt, has become a fantastic platform for facilitating software development and it's become an integral tool for every developer out there. I can't tell folks enough how much I love working with Git, it's a freaking joy, and GitHub takes it to another level.

[ghp]: http://pages.github.com
[jekyll]: http://jekyllrb.com
[wp]: http://wordpress.com
[ssg]: http://staticsitegenerators.net
[md]: http://daringfireball.net/projects/markdown
[op]: http://octopress.org
