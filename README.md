<h1 align="center">
  anydub
</h1>

## anydub is a starter and demo you can follow to get a fast free or cheap website up in one hour fast if you own a website domain name. 

## anydub - splainin sum stuff
anydub and is a vlog about building a vlog. 

## anydub - goal

The goal is to teach and learn and to open and grow and share how to open and grow community, many types, but in this context about how to implement these amazing technologies, and into further development and features additions to anydub. I was thinking about splainin whatever I feel like splainin, but if you got some requests or just appreciate me for me tear patreon.

## anydub - running

#requires node 18 - punycode error messages in later versions
#npm install 
<sub>or yarn, nvm... </sub>
#npm start 
<sub>will also launch proxy server running on port 8000 for netlify/ cms login on localhost</sub>

## anydub quick technical explanation
anydub is the best and only functional gatsby 4, netlify cms, and typescript website starter you'll currently find. anydub is a mash up, with a lot of code from  [gatsby-starter-lumen](http://github.com/alxshelepenok/gatsby-starter-lumen), with a jumpstart from @syfxlin/blog, and custom stylized with images inspired from gatsby-calpa-blog along with some other custom feature additions. 

## anydub manifesto - agile manifesto

<h4 align="center">
  Individuals and interactions over processes and tools
</h4>
<sub>so don't get caught up in the tool, but instead the function. We learn with tools, but we get work done understanding eachother</sub>
<sub>and don't make a big deal about what doesn't have to be a big deal<sub> - with agile


## anydub tech stack
easy automated builds and staticly generated sites , the netlify jamstack CMS is the most valuable and flexible piece of software being demonstrated. A lightweight, configuration based, react CMS that uses a git repo in lieu of database and for source control 

This app is built with gatsby, netlify cms, react javascript, node, graphql, netlify jamstack cms, jamstack, and git. Look ma, no database!

### anydub custom features

+ One and only current mash up of gatsby 4, netlify cms, with typescript
+ Enhanced styling and design inspired by
    + [gatsby-calpa-blog](http://github.com/alxshelepenok/gatsby-starter-lumen)
+ Capability to render images by remote url incorporating:
    + gatsby-plugin-remote-images
    + gatsby-remark-relative-images
+ Post feed and post page header image display
+ npm package.json start script with concurrent launch of netlify-cms-proxy-server
  (requires port 8001 not in other use)

### anydub todos backlog

+ Finish documentation and cleanup links
+ Modal template, video components, and implementation with modal connecting appealing to blog content read
+ Verify operational or, if necessary, update rss feed to operational
+ Proof of concept automating social media post from anydub rss feed with metricool
+ netlify CMS preview templates functioning
+ Improve css layout and design
+ Link instagram feed to webpage 
+ theme support
+ runtime theme toggling
+ PoC migration to vercel if/when free build/bandwidth limits neared
+ Implement custom netlify CMS widgets
+ Unit test & test coverage eval and demo
+ evaluate lint use and impliment lint with autofix
+ Change from flow to typescript, not that it's better, just more ubiquitous and if we build matching mobile apps, sharing domain object model types in a library could come in handy
+ PoC mdx editor
+ dev environment 
+ componentize anydub to npm package
+ develop yeoman cli npm package for configuring anydub via cli
+ expand domain model for netlify cms data in static/admin/config.yml

## License

### reference license for just gatsby-lumen project use TODO - add to

The MIT License (MIT)

Copyright (c) 2016-2022 Alexander Shelepenok

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.