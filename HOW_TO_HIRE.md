# How To Hire Frontend Talent

## Why Trust This Guide?

[The author](https://infrequently.org/about-me/) has worked professionally on the web for more than 20 years, helped to design many features now in heavy use on the web platform, and interviewed hundreds of software engineering candidates -- many for frontend roles -- while working at Google for a dozen years.

This experience informed a multi-year collaboration ('14-'17) among senior managers and engineers to reform Google's internal hiring policies, interview rubrics, recruiter guides, candidate collateral, hiring committee documentation, job descriptions, and promotion ladder criteria to better weight the skills embodied by the best frontend engineers and signpost differences between the frontend discipline and that of "general" software engineering. Frontend is wicked hard, and to hire well organisations must think differently about what skills and values should be top-of-mind.

The author has also [consulted widely](https://infrequently.org/2022/05/performance-management-maturity/) with frontend teams across industry since 2015 as they worked to build [Progressive Web Apps](https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/) and improve their sites with the help of the Chrome team's expertise. 

Since joining Microsoft in 2021, this consulting work has continued but is now focused on improving Microsoft's most prominent web properties (e.g., Bing, Copilot, Office, Teams, Loops, etc.). This consulting has provided a broad view into the practices, beliefs, and pathologies of both high-functioning and poorly executing frontend teams, as well as the habits of both managers and engineers that make the difference to the user experience.

## Essential Skills

Critical skills to test for and value in frontend development are:

  - Well-structured HTML
  - Accessibility
  - CSS (particularly responsive design)
  - Design/UX team collaboration
  - HTTP and networking
  - Fonts
  - Performance
  - Image format tradeoffs
  - DOM

> Note: JavaScript doesn't even make the list, let alone JS frameworks, but DOM does. This is because JavaScript knowledge untethered to the internals of the browser (via DOM) is worse-than-useless. In the current era of inverted values, JavaScript and framework skills have become valued over the user experience, leading to large-scale losses for businesses that invest in JS-driven UI.

This guide prescribes neither a specific interview style or methodology nor a specific set of model technical questions. Still, it is recommended interviewers test the above list of skills _in order_ to allow candidates to fail-fast, reducing time spent on non-essential skills, whilst concentrating time in indispensible areas.

Your organisation may also require that frontend developers work to integrate their work into backends built in various stacks. Testing for these skills, or the aptitude to learn them, is reasonable. Skilled frontend developers are polyglot, as multiple languages are required just to deliver a document with styling applied.

## Resume Filtering and Credentials

The last decade of JS-first web development has atrophied the skills of recruiters and managers looking for web development fundamentals. In their place, new proxies for seniority have been invented and promulgated. To attract the right skills, you will now need to cast a somewhat wider net and work to see through "modern" resumes to spot the deeper experience hiding in a candidate's CV.

Some "old skool" skills to look for include:

 - "Responsive Design" or "Responsive Web Design"
 - "Progressive Enhancement"
 - "WCAG" (Web Content Accessibility Guidelines) or "W3C Accessibility"
 - "HTML 5" and/or "CSS 3"
 - "Web Standards"
 - "jQuery" or PrototypeJS

Newer skills that indicate platform-centric understanding:

 - "CSS Grid"
 - "CSS Variables"
 - "Container queries"
 - "dark-mode theming"
 - "Web Animations API" (WAAPI)
 - "View Transitions" (2024 onward)
 - "Web Components", "Shadow DOM", or "Declarative Shadow DOM"

### What to Advertise

Many folks with great platform skills will feel they need to modify their resumes to highlight Angular or React-based experience and de-emphasise these attributes. Be clear in job postings that you are looking for developers with standards-based development in mind. Also, be clear that interviews will be conducted without assuming frameworks, transpilers, or pre-processors (either for CSS or JS).

Even if your team has not yet adopted them, ensure that your job postings include skills like:

 - Semantic HTML
 - Progressive Enhancement
 - WCAG and accessibility
 - Modern CSS
 - CSS Grid
 - Web Components
 - Core Web Vitals

These aren't perfect but they will signal to applicants the attitude towards frontend your organisation values.

## "Full-Stack" Is Not What You're Looking For

The goal of interviews is to determine which skills a candidate is deepest (rather than weakest).

Frontend skills, like any other deep and wide technical domain, are not about solving a specific problem on repeat, but rather involve creating applications of disparite techniques to synthesize the best outcomes for the problem at hand. This doesn't mean that any specific applicant will, or even can, master every skill. Much the opposite! Some folks have skills with broad overlap in areas considered to be design and UX (historically, "web designers"), whilst others may be programmer-style "UI plumbers", tending towards networking, scripting, and the back-end. 

Each of these styles has a different "home row". Your job as a hiring manager is to look for folks who are versed in the basics, deep in at least one area, and then to characterise their depth in adjacent skills. The more adjacent skills a candidate has, and the stronger they are in multiple areas, the deeper the problems they can tackle; this often [comes from experience](https://norvig.com/21-days.html).

In software it's possible to solve problems from multiple angles, so the quality of a solution is found in its economy, rather than its existence. This is why fundamentals matter: they help developers understand the economy of their solution, and provide a deep repertoire of patterns to apply. The challenging part for hiring frontend skill is that the fundamentals in a browser look nothing like those of traditional programming. 

Understanding the Big-O of a loop has almost no applicability to the problem of constructing web pages that load efficiently, and the assumptions of server programmers about the availability of resources like compute, networking, and storage are almost always wrong on the client (regardless of stack).

Sadly, the name given to aspiration for [deep skill across multiple layers](https://carlos.bueno.org/2010/11/full-stack.html), "full-stack", has been eroded by marketing and bootcamp salesmanship. The phrase "full-stack programmer", or more recently "full-stack developer," is now so thoroughly denatured that it has become synonymous with a junior developer that can write JavaScript on both the client and the server.

For folks looking to hire for quality, the annotation "full-stack" has lost any positive connotations. Today's best developers avoid putting it on their resumes or do so through gritted teeth to avoid being passed over in keyword searches. On the hiring side, only managers without the experience to know better treat it as a mark of skill or seniority.

## Build for Building for The Real World

Better, then, as a hiring manager to consider what sort of team you're trying to build. 

Your goal probably isn't to hire an army of junior developers who don't know they're junior, it's probably to deliver the best products at the lowest cost. This, in aggregate, means hiring for deep _differentiated_ skills, collaboration, and effective team structure.

Your team will need folks who can move code reliably, but that's not the reason to hire for frontend skill specifically; hiring for frontend about hiring folks you trust to _set constraints_ and _maintain standards_ for the bits of your products that users experience on their own devices.

This problem is unique, and in some important ways harder, than traditional development. Hiring generalists for this role has been an industry-wide disaster, and so you should be conscious that the folks you're hiring in this area will need to be empowered to say "no" to backend and "full-stack" engineers with different ideas. That's just how it has to be if your product is going to be great. The job of your senior frontend folks is to compromise and negotiate, but always in service of the user. They will push back, they may even be ornery, but that's only because delivering great experiences to the client requires uncommon discipline.

### Attitudes and Values

Frontenders play a unique role in organisations, translating design and product goals to delivered code; but not without adjustments along the way. 

Design and product intent are conversations. Skilled frontend developers understand this and partner with UX designers, PMs, and backend engineers, helping to nudge their thinking towards solutions that will work best in-browser; e.g. at multiple resolutions and zoom levels, with differing accessibility configurations, and the like.

The best frontend developers are advocates for the user because the code they write is _closest_ to the user. Your hiring process should look for, and prize, advocacy of this sort. Interview problems that provide multiple potential solutions are a great way to tease out how candidates think about tradeoffs and how they pick approaches.

All great engineers have sympathy for the machine, but strong frontenders negotiate the technical constraints of limited resources with _intent_: their goal is to avoid leaving users behind. This is valuable to organisations that strive to deliver effective, reliable services and digital products as it creates a culture that prioritises what will work best over what is popular.

### HTML + CSS First

Interview loops for frontend candidates should pose problems that are best solved multiple ways, with the highest scorings given to pure HTML + CSS answers. Some candidates may solve problems in this style by proposing a bit of backend templating plus some HTML and CSS; this is a sign of relative strength too.

Probe candidates with HTML and CSS skills on accessibility, responsive design, and how they prefer to work with design teams. 

Lastly, spend time discussing the tricky tradeoffs of web fonts. 

Only if there's additional time or space in your interview loop, consider posing questions that requires DOM and JS skill in order to best achieve accessibility goals.

### JS: Maybe?

Until and unless your product [demonstrates exceptionally long, login-gated, high-interactivity sessions](https://infrequently.org/2023/02/the-market-for-lemons/#fn-amortised-interaction-costs-3), avoid explicitly hiring for JavaScript skills. 

Most HTML-centric developers with any sort of programming background can pick up JavaScript should they need to, but because JS is the most expensive way (both from a budgetary and from a user-experience) way to deliver solutions, it is an essential goal for your team [not to employ JS specialists until and unless you've built management capacity to manage it _explicitly_](https://infrequently.org/2022/05/performance-management-maturity/).

If you _do_ hire for JS talent, ensure that interviewers look only for "low-level" DOM skill. Do not hire folks who cannot write code that uses the DOM without a framework. Be clear with candidates that they will be expected to avoid frameworks ahead of an interviews so that you can avoid wasting everyone's time. 

Avoid candidates that spout nonsense about how they need a framework because "DOM is slow." These folks are more junior than they understand, and may be fine in a backend role, but should not be allowed near the client where the costs of misjudging system constraints area incredibly high. 

The best candidates may suggest solutions in HTML &amp; CSS to problems that are posed as DOM questions. This is a reason to pass, rather than fail, a candidate.

### Networking, Performance, and Advanced Topics

When hiring for more senior roles, expect a wider breadth of experience and working familiarity with many levels of the client and server-side stack, including their interplay. Also expect more specialisation and depth in the candidate's "home row". Each area of client-side stack (markup, a11y, CSS, design, storage, networking, security, graphics, media, and DOM) can be arbitrarialy deep, and the strongest candidates will exhibit both confident command of one area, as well as advanced skill in others.

A colleague recently asked what to look for when promoting or hiring a frontend candidate to "Staff" level, and it seems reasonable that such a person should be able to describe, in good detail, the steps that take place between hitting "enter" in the URL-bar of a browser (or clicking on a link) and when content is finally painted on screen.

This involves an understanding of browsers, networking, parsing, and much else. A non-exhaustive answer would discuss:

 - DNS lookup
 - TCP connections
 - TLS handshaking
 - HTTP request/response (including some understanding of the most important headers)
 - server handling of requests
 - server generation and flushing of content
 - HTML parsing and sub-resource request initiation
 - construction of DOM from HTML
 - parsing of CSS
 - layout deriving from constructed DOM + CSS
 - a discussion of style recalc, layout, and raster steps (optional)

This sort of skillset isn't common, but it _is_ valuable. Candidates with this sort of depth should also be able to talk about how they interact with design teams, how to think about system performance, and be able to talk through real-world web application security.

## Notes on Frontend Teams

Frontend is not a stand-alone discipline; it fundamentally depends on collaboration and negotiation to best manage the interplay of design intent, system constraints, and user experience. Managers of sizeable products will construct (or adopt) "stacks" that include some amount of frontend technology.

The role of frontend folks in a team is not to accept technology, or slot into it. First and foremost, you hire frontend skill to _improve on the defaults_ of your stack. To do this, frontend engineers apply constraints unique to your product to develop _more_ constrained patterns and practices that help the overall organisation succeed.

### AI and Frontend

The near-future of heavily automated frontend construction will not reduce the need for skill in fundamentals, but it may centralise this skill into fewer people in an organisation. This will become a litmus test for product values, as the role of the human "in the loop" of an AI-assisted system is to reject bad answers, rather than to fully construct good ones.

From this perspective, the role of skilled folks in your teams will be to nudge the iterative process of product development into alignment with the ethos and received goals of your organisation. This raises, rather than lowers, the stakes for being able to judge solutions to be appropriate. In short, ML and AI will create more demands for discernment, not fewer. Hire wisely; hire for fundamentals.