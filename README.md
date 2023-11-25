# A Suggested Curriculum for Web Frontend Fundamentals

## Why This Document?

The state of today's discourse around frontend web technologies is not in a good place. Many managers assume that they must adopt React (or similarly heavy and slow) tools because _"that's what we can hire for"_. Students are simultaneously told that they need to learn legacy frameworks _"because that's what employers want"_. These narratives elide the primary role of professional frontend work: to serve users and the organisastions that serve them. They also underplay the power of the web platform, and how advanced widely deployed browsers have become.

We reject these narratives, and assert that students and businesses are best served when they focus on web platform fundamentals. These fundamentals provide a lifetime of value to those who learn them and drive success for the products and services based in them.

## Resources 

### Essentials

Building for the web is to be building for/on Browsers. It is common for Browsers to be an after thought or taken for granted when learning frontend fundamentals. Having a strong intuition for how Browsers work will build bridges for developers, new and seasoned, to reach new heights in their career. 

 - ["MDN"](https://developer.mozilla.org/en-US/docs/Web); the canonical repository of web API references
 - ["Getting Started With the Web"](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web) on MDN
 - Browser DevTools; vary by browser, but all provide similarly powerful inspection capabilities.
   - ["Firefox"](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Tools_and_setup/What_are_browser_developer_tools)
   - ["Chrome"](https://developer.chrome.com/docs/devtools/overview/)
   - ["Edge"](https://learn.microsoft.com/en-us/microsoft-edge/visual-studio-code/microsoft-edge-devtools-extension/open-devtools-and-embedded-browser)
   - ["Safari"](https://developer.apple.com/documentation/safari-developer-tools/web-inspector)

### HTML Structure

To build for the web is to author HTML. It is not uncommon to hear seasoned developers who look into HTML again to say something like, "I didn't know this existed." HTML has incredible capabilities and much of the things we build to "work around HTML" are unnecessary. 

 - ["Learn HTML"](https://web.dev/learn/html/) on web.dev
 - ["HTML basics"](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics) on MDN

### CSS

To build for the web is to work with CSS. Beautiful design and web pages rely on CSS and not enough developers are aware of it's capabilities. The teaching and instruction in the industry around CSS has gotten really good in the past few years. Features are being added to CSS frequently that therefore allow for further leaning into it's capabilities as a standard. 

 - ["Learn CSS"](https://web.dev/learn/css/) on web.dev
 - ["CSS basics"](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics) on MDN
 - ["Getting started with CSS"](https://frontendmasters.com/courses/getting-started-css/) by Jen Kramer

### JavaScript & Interactivity

Interactivity is probably the trickiest concept to grasp. At face value it is very simple. However, JavaScript is meant to _"add"_ interactivity to the site _NOT_ be the thing applications are dependent upon. 

 - ["JavasScript basics"](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics) on MDN
 - ["Getting Started with JavaScript, V2"](https://frontendmasters.com/courses/getting-started-javascript-v2/) by Kyle Simpson

#### Paid Courses

There are an incredible amount of resources ranging from free - thousands of dollars. Everyone has their preference. Below are a few recommendations. If you are looking for feel free to message me, Ben, on [LinkedIn](https://www.linkedin.com/in/benjaminapatton/)

 - ["Web Component Engineering"](https://www.bluespire.com/p/web-component-engineering) by Rob Eisenberg
 - ["Frontend Masters Web Components Workshop"](https://daverupert.com/projects/frontend-masters-web-components/) by Dave Rupert
 - ["Intermediate HTML and CSS"](https://frontendmasters.com/courses/intermediate-html-css/) by Jen Kramer

#### Free Comprehensive Courses
- ["Responsive Web Design"](https://www.freecodecamp.org/learn/2022/responsive-web-design/) by FreeCodeCamp

## Paths

We understand there is no 'one size fits all' when it comes to people who are either learning web development or coming to this document to understand web standards and best practices. Our aim in outlining the paths below is to provide a suggested path for those at various stages of their journey or coming from different engineering backgrounds. 

### Brave New Explorer (Beginner to this Web Developer journey)

You have decided what you want to do. Whether you are changing careers or you are deciding what to do as a career path, you are setting out into the world wide web as an architect and artisan, not simple a consumer. The suggested path here may seem daunting but do not fear, there are resources a plenty on your path to help you along the way. 

As you go you may be wondering if you should "specialize". We think this is best left to after you have started working and can start to zero in on the aspects of being a web developer or software engineer that will become available to you within a workspace. The resources we have above are not the resources that would make you a "full-stack" engineer. That is intentional for the purpose of this document. We want you to become excellent with web standards technology so that when you add the other skills to become 'full-stack' you will be able to do that with excellence and confidence and not over reliance on tools to make that so. 

### Investigator of Web Standards (Are you coming from React background?)

Inevitably we know this is difficult, for many reasons. Some reading this may initially be repulsed or find some mild anger rising. Some may be utterly confused. And some may be thinking, "finally somewhere to find out more." For these reasons and more, the first set of resources and links we want to provide here are links to help us think more critically about how we build web applications. Let us be clear, there are many, many incredibly skilled wonderful engineers who use React and love it. 

The purpose of what is being laid out here is to "present the data", as it were, to help frontend developers, agencies, and so on understand the choice that is being made when React and associated frameworks are the "obvious" choice. The standard here which we are setting forth is Progressive Enhancement. This inevitably raises the question in many a React developer's mind, "but who isn't using JavaScript these days." Whereas we concede that is likely to be true, that most people do not have JavaScript disabled, the more telling marker is to ask, "will this break if JavaScript is turned off?" 

Progressive Enhancement is about providing a first class User Experience to all users of your app. If your application or site will work without JavaScript and JavaScript is only used to sweeten the experience of your users, it will be more performant and a delight. 

The more JavaScript shipped to the page, the greater impact it will have on performance. Many of us Web Developers have iPhone's and a Macbook or other high end devices. The vast majority of the population does not. Meaning on high end devices the app with more JavaScript may not have a perceived difference but as the app scales, performance drops. If you make it work without JavaScript and Enhance it with JavaScript, your work will be more resilient. Resilience isn't revisiting your work every 6 months to year and updating your dependencies. Resilience is writing your app knowing it could continue to run without ever being updated. 

This is not a dream. It is a present reality that many of us are ignorant to and don't take advantage of. We want you to have longevity in your career and work. Knowing standards means you are flexible and can adapt to the new thing should a job require it. Knowing the standards means that you have confidence in your work. 

### TODO: Coming From a Alternate Universe (Skilled Engineer interest in Web Development) 

## About The Authors

 - [Alex Russell](https://infrequently.org/about-me) makes browsers
 - [Ben Patton](https://benapatton.com) optimistic builder and dreamer for the web
