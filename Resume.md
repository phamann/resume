# Resume

Hi there, my name is Patrick and I currently work at *The Guardian* as a lead developer  and technical lead for their core website [theguardian.com](http://www.theguardian.com/?view=responsive). Our goal is to create the next generation platform and infrastructure for *The Guardian*’s front-end rendering tier.

I'm passionate about the web and creating elegant architectures and user experiences. I've worked the whole technical stack from Unix to UX, back-end to front-end, and thrive by helping innovative companies realise their best ideas.

---

You can find me online at the following locations:

- [github.com/phamann](https://github.com/phamann)
- [twitter.com/patrickhamann](http://www.twitter.com/patrickhamann)
- [LinkedIn](http://uk.linkedin.com/pub/patrick-hamann/2a/673/a53)

---

## Table of Contents

- [The Guardian processes](#the-guardian-processes)
- [The Guardian highlights so far…](#the-guardian-highlights-so-far)
- [Skills](#skills)
- [Talks](#talks)
- [Articles](#articles)
- [Open Source Projects](#open-source-projects)
- [Previously](#previously)
- [Summary](#summary)

---

## The Guardian processes

I joined the *The Guardian* as a client-side specialist, although now work across their entire publishing platform both front-end and server-side. This has given me an understanding, appreciation and knowledge of the "full stack" workflow. My job at *The Guardian* generally involves the following (agile) processes and tools…

### tooling

- [Vagrant](http://www.vagrantup.com/)
- Continuous Integration
	- [TeamCity](https://travis-ci.org/)
- [GruntJS](http://gruntjs.com/)
- [Glup](http://gruntjs.com/)
- [Git](http://git-scm.com/) Version Control System
	- Workflow involves: 
		- Ruthlessly small PRs
		- Peer reviews
- [Trello](http://www.trello.com/) for tasks and workflow
- [Slack](https://slack.com/) for project collaboration

### back-end

- [Scala](http://www.scala-lang.org/)
	- MVC based micro-service applications using the [Play!](https://www.playframework.com/) framework. 
	- AWS ([CloudFormation](http://aws.amazon.com/cloudformation/), [EC2](http://aws.amazon.com/ec2/), [S3](http://aws.amazon.com/s3/), [DynamoDB](http://aws.amazon.com/dynamodb/), [SQS](http://aws.amazon.com/sqs/))
	- Basic Linux administration (shell scripting)
- [Puppet]
	- Provisioning of server dependencies
- [Varnish](https://www.varnish-cache.org/)
	- Custom VCL logic for advanced routing at the edge
	- Integration with [Fastly](http://www.fastly.com/) CDN
- [nginx](http://nginx.org/en/)
- [ImageMagivk](http://www.imagemagick.org/)

### front-end

- Building interfaces and components that are:
	- [Mobile first](http://www.abookapart.com/products/mobile-first)
	- [Responsive](http://www.abookapart.com/products/responsive-web-design) 
	- Performant ([networking](http://shop.oreilly.com/product/0636920028048.do) and [behaviour](http://shop.oreilly.com/product/9780596802806.do))
	- [Reusable](https://github.com/stubbornella/oocss/wiki)
		- Specifically using [BEM](http://www.integralist.co.uk/posts/maintainable-css-with-bem/)
		- We also use the [Sass](http://sass-lang.com/) CSS pre-processor
		- Semantic and well structured HTML
	- Simple
- Constructing behaviours with:
	- Modular JavaScript
		- [AMD](https://github.com/amdjs/amdjs-api/blob/master/AMD.md)
		- [RequireJS](http://requirejs.org)
	- Patterns: 
		- Mediator (for complex modules that require a mediator to handle interactions)
		- PubSub (for simpler modules to help them stay decoupled)

## The Guardian highlights so far…

### 2014
- Formed an integral part of a three-person developer team who re-architected and redesigned the homepage for the responsive website.
	- Abstracted layout into reusable atomic design system
	- Utilise CSS flex-box for complex layout patterns
- Re-wrote the HTML5 video player to use [video.js](https://github.com/videojs/video.js/) and open-sourced multiple plugins for [advertising](https://github.com/guardian/videojs-vast-plugin) and [embedding](https://github.com/guardian/videojs-embed)
- Implemented new “attention” tracking within our real-time analytics platform [Ophan]()
- Increased social sharing conversion by 20% across all content pages
- Implemented our client-side error tracking system
	- Initially written using the ELK stack ([elastic search](http://www.elasticsearch.org/), [logstash](http://logstash.net/), [kibana](http://www.elasticsearch.org/overview/kibana/))
	- Ported over to use [Sentry](https://getsentry.com/welcome/)
	- Encouraged and enabled other teams within the department to do the same
- Founded and host the cross-team bi-weekly client-side developer meetings. With the aim to share knowledge and project work across the department
- Co-host the [London Functional JavaScript](http://lanyrd.com/series/funjsldn/) meetup at the Guardian offices
- Invited to speak at 8 international conference around the subject of performance optimisation
- Architected the decoupling of our large JavaScript application into smaller & fault tolerant deliverables
- Helped the native application teams to debug and instrument rendering and performance issues within their application webviews
- Selected to become a member of the Guardian’s support working group

### 2013
- Given the opportunity to take on the acting Tech Lead role for the frontend content team
- Our team managed to reach a level of Continuous Delivery that was previously not possible within the organisation
- Wrote the client-side development principles which all features should adhere to
	- Evangelised principles across multiple teams
- Ensured all core performance metrics were instrumented and made visible cross the entire department
- Co-designed, developed and open-sourced our [Sass-mq](https://github.com/sass-mq/sass-mq) a Sass mixing for elegantly handling media queries
- Introduced GruntJS to help different teams automate their processes
- Designed and built a CI workflow around static asset compilation
	- Complex [RequireJS](http://requirejs.org/) setup, including sub-modules and exclusion
	- File hashing system for cache-control
	- Dashboard to monitor trends in file size and complexity
- Co-designed responsive image resizing service
	- Initially with [ImageMagick](http://www.imagemagick.org/)
	- Ran tests with WebP & SPDY
	- Currently using nginx’s image module
- Designed and built the process to inline critical CSS into our documents
	- Led to sub 1000ms page rendering 
- Helped develop multiple pattern libraries for modular/responsive components.
	- guss
	- pasteup
- Developed and extend our port of [grunticon](https://github.com/filamentgroup/grunticon) to generate sprite fallbacks using PhantomJS 

## Skills

### Primary

- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Node](http://nodejs.org/)
- Client-side performance and optimisation
- Object-Oriented Code Design
- Refactoring
- Design Patterns
- Architecture design
- Test-Driven Development
- Team leadership and management
- Being a professional

### Secondary

- [Scala]
- [PHP](http://php.net/)
- Shell Scripting
- AWS infrastructure

### Interested in (but have not built anything substantial, yet)

- [React](http://facebook.github.io/react/)
- [Functional Programming](http://en.wikipedia.org/wiki/Functional_programming) (immutable state, referential transparency, currying and partial application etc)
- Workflows with Docker

### Past experiences

> This would be stuff I've used in the past and could probably pick up again if necessary

- JS libraries such as Backbone & jQuery
- ActionScript 3.0
- PHP

---

## Talks
Over the past two years I have given multiple talks at web development conferences around the world to evangelise the performance optimisation techniques and responsive web design best practices we use at the Guardian. 

### [Building theguardian.com](https://speakerdeck.com/patrickhamann/building-theguardian-dot-com)

> This talk will be a deep-dive case study into the issues they’ve had to overcome whilst building a website that is accessed by over 7000 different devices from 105 million unique users.

### [CSS and the Critical Path](https://speakerdeck.com/patrickhamann/css-and-the-critical-path-cssconfeu-september-2014)

> Using new research and real world examples, I cover a range of techniques – from the controversial to bleeding edge – the Guardian are using to make the CSS of their next generation website load as fast as possible, and ultimately taking it off the critical path.

### [Breaking News at 1000ms](https://speakerdeck.com/patrickhamann/breaking-news-at-1000ms-velocity-eu-2014)

> During the talk you discover why performance matters, what are the common performance bottlenecks in the browser from networking to painting and learn how to best optimise and monitor each stage of the critical path.

### [Ship it!](https://speakerdeck.com/patrickhamann/ship-it-re-develop-conference-august-2014)

> A story of continuous delivery at theguardian.com. In which I will be sharing how the Guardian has managed to change culture and overhaul their systems to enable both rapid delivery, and deployment of their products and how you can too.

---

## Articles

### [.Net](http://www.creativebloq.com/netmag/guardian-redesign-71412518)

I was interviewed for the June edition of .Net magazine about the responsive redesign

### [FastCo Labs](http://www.fastcolabs.com/3038017/what-the-guardian-gained-by-redesigning-its-website-in-the-open)

Interview and article about what we gained by redesigning theguardian.com in the open.

### Smashing Book
I was am technical reviewer for the upcoming Smashing Book 5.

---

## Open Source Projects

### Frontend

[https://github.com/guardian/frontend](https://github.com/guardian/frontend)

> The entire code base for the Guardian’s fronted rendering tier

### sass-mq
[https://github.com/sass-mq/sass-mq](https://github.com/sass-mq/sass-mq)

> A Sass mixin that helps manipulating media queries in an elegant way.

### grunt-asset-monitor
[https://github.com/guardian/grunt-asset-monitor](https://github.com/guardian/grunt-asset-monitor)

> Grunt task to analyse and log simple metrics of static assets to Amazon CloudWatch.

### grunt-css-metrics
[https://github.com/phamann/grunt-css-metrics](https://github.com/phamann/grunt-css-metrics)

> Grunt task to analyse css files and log simple metrics.


### videojs-embed
[https://github.com/guardian/videojs-embed](https://github.com/guardian/videojs-embed)

> A plugin for Video.js that adds a control bar button to toggle an embed code overlay.

---

## Previously

Prior to the The Guardian I worked for a digital agency called [UVd](http://www.uvd.co.uk) from July 2009 - August 2012.

At UVd I was a lead fronted developer which included the following responsibilities… 

- Programming
	- front-end development
	- prototyping using latest tools and technologies
- UX design
	- wire-framing
	- user research
- Information Architecture
	
UVd predominantly focused on helping startups and large businesses realise their potential using technology. I had the opportunity to work with brands such as: Standard Chartered, SPAR, Holland America Line & Imagem.

 In 2012, I was part of a team which built a web and mobile energy savings calculator for global lighting specialists HavellsSylvannia. Sales penetration was improved across their international markets. I led the development of user access to desktop, laptop, tablet and smartphone by the major marketplace training company, bookacourse.com. Using a solution with responsive design principles, I developed a clean, intuitive user interface improving the process and access of its thousands of users.

Whilst there we built our own custom CMS using the Symfony PHP framework, my core focus was to add helper functions for the templating system using Twig.

While managing the fronted team I looked after a team of two other developers.
---

## Summary

I ideally want to get across two fundamental things about me:

1. I'm very passionate about programming and the openness of the web.
2. I love getting the chance to learn and experience new things.
3. I love evangelising best practices and inspiring other groups and individuals to the same.
