# How To Hire Frontend Talent

## Why Trust This Guide?

[The author](https://infrequently.org/about-me/) has worked professionally on the web for more than 20 years, helped to design many features now in heavy use on the web platform, and interviewed hundreds of software engineering candidates -- many for frontend roles -- in while working at Google for a dozen years.

This experience informed a multi-year collaboration ('14-'17) among senior managers and engineers to reform Google's internal hiring policies, interview rubrics, recruiter guides, candidate collateral, hiring committee documentation, job descriptions, and promotion ladder criteria to better weight the skills embodied by the best frontend engineers and signpost differences between the frontend discipline and that of "general" software engineering. Frontend, it turns out, is wicked hard, and to hire for it well, we must think differently about what skills and values should be top-of-mind.

The author has also [consulted widely](https://infrequently.org/2022/05/performance-management-maturity/) with frontend teams across industry since 2015 as they worked to build [Progressie Web Apps](https://infrequently.org/2015/06/progressive-apps-escaping-tabs-without-losing-our-soul/) and improve their sites with the help of the Chrome team's expertise. 

Since joining Microsoft in 2021, this consulting work has continued, but is now focused on improving Microsoft's largest web properties (e.g., Bing, Copilot, Office, Teams, etc.). This consulting has provided a broad view into the practices, beliefs, and pathologies of both high-functioning and poorly executing frontend teams, as well as the habits of both managers and engineers that make the difference to the user experience.

## Essential Skills

The most important skills to test for and value in frontend development are:

  - Well-structured HTML
  - Accessibility
  - CSS (particularly responsive design)
  - Design/UX team collaboration
  - HTTP and networking
  - Fonts
  - Performance
  - Image format tradeoffs
  - DOM

> Note: JavaScript doesn't even make the list, let alone JS frameworks, but DOM does. This is because JavaScript knowledge untethered to the interals of the browser (via DOM) is worse-than-useless. In the current era of inverted values, JavaScript and framework skills have become valued over the user experience, leading to large-scale losses for businesses that invest in JS-driven UI.

This guide prescribes neither a specific interview style or methodology, nor a specific set of model technical questions, but it is recommended that the above list of skills be tested _in order_ to allow candidates to fail-fast, reducing interviewer time-spent on non-essential skills, whilst concentrating time in the most important areas.

Your organisation may also require that frontend developers work to integrate their work into backends built in various formats. Testing for these skills, or capacity to learn them, is not unreasonable. Skilled frontend developers are polyglot, as it's a require to master multiple languages just to deliver a document with styling applied.

## Resume Filtering and Credentials

The last decade of JS-first web development has atrophied the skills of recruiters and managers when it comes to looking for web development fundamentals. In their place, new proxies for seniority have been invented and promigulated. To attract the right skills, you will now need to cast a somewhat wider net and be look to see through "modern" resumes to spot the deeper experience hiding in a candidate's CV.

Some "old skool" skills to look for include:

 - "Responsive Design" or "Responsive Web Design"
 - "Progressive Enhancement"
 - "WCAG" (Web Content Accessibility Guidelines) or "W3C Accessibility"
 - HTML5 and/or CSS3
 - "Web Standards"
 - jQuery or PrototypeJS

Newer skills that indicate platform-centric understanding:

 - "CSS Grid"
 - "CSS Variables"
 - "Container queries"
 - "dark-mode themeing"
 - "Web Animations API" (WAAPI)
 - "View Transitions" (2024 onward)
 - "Web Components", "Shadow DOM", or "Declarative Shadow DOM"

Many folks with deep platform skills will feel they need to modify their resumes to highlight Angular or React-based experience and de-emphaise these attributes. If possible, be clear in your job postings that you are looking for developers with standards-based development in mind, a strong grounding in fundamentals and progressive enhancement, and that all interviews will be conducted without assuming frameworks, transpilers, or pre-processors (either for CSS or JS).

## "Full-Stack" Is Not What You're Looking For

Frontend skills, like any other deep and wide technical domain, are not about solving a specific problem on repeat, but rather involve create applications of disparite techniques to synthesize the best outcomes for the problem at hand. This doesn't mean that any specific applicant will, or even can, master every skill. Much the opposite! Some folks have skills with broad overlap in areas considered to be design and UX (historically, "web designers"), whilst others may be programmer-style "UI plumbers", tending towards networking, scripting, and the back-end. 

Each of these styles has a different "home row". Your job as a hiring manager is to look for folks who are versed in the basics, deep in at least one area, and then to carachterise their depth in adjacent skills. The more adjacent skills a candidate has, and the stronger they are in multiple areas, the deeper the problems they can tackle; this often [comes from experience](https://norvig.com/21-days.html).

The goal of interviews is to determine which skills a candidate is deepest (rather than weakest) in, and to probe for adjacent capabilities. Nobody knows everything, but those who can cross more layers, and have a larger repetoir of potential solutions, will be the most capable over time. This is because in softawre it's possible to solve problems from multiple angles; the quality of a solution is found in it's economy, rather than its existence. This is why fundamentals matter: they help developers understand the economy of their solution, and provide a deep repitoire of patterns to apply. The challenging part for hiring frontend skill is that the fundamentals in a browser _look_ nothing like the fundamentals in traditional programming. Understanding the Big-O of a loop has almost no applicability to the problem of constructing web pages that load efficiently, and the assumptions of server programmers about the aviability of resources like compute, networking, and storage are almost always wrong on the client (regardless of stack).

Sadly, the name given to aspiration for [deep skill across multiple layers](https://carlos.bueno.org/2010/11/full-stack.html), "full-stack", has been eroded by marketing and bootcamp salesmanship. The phrase "full-stack programmer", or more recently "full-stack developer," is now so thoroughly denatured that has become synonymous with a junior developer that can write JavaScript on both the client and the server.

For folks looking to hire for quality results, this means the annotation "full-stack" has lost all positive connotation. The best developers today avoid putting it on their resumes, or do so with gritted teeth to avoid being passed over in keyword searches. On the hiring side, only managers without the experience to know better treat it as a mark of skill or seniority.

## Build for Building for The Real World

Better, then, as a hiring manager to consider what sort of team you're trying to build. Your goal probably isn't to hire an army of junior developers who don't know they're junior, it's probably to deliver the best products at the lowest cost. This, in aggregate, means hiring for deep _differentiated_ skills, collaboration, and effective team structure.

### HTML + CSS First

Interview loops for frontend candidates should pose problems that are best solved multiple ways, with the highest scorings given to pure HTML + CSS answers. Some candidates may solve problems in this style by proposing a bit of backend templating plus some HTML and CSS; this is a sign of relative strength too.

Probe candidates with HTML and CSS skills on accessibility, responsive design, and how they prefer to work with design teams. 

Lastly, spend time discussing the tricky tradeoffs of web fonts. 

Only if there's additional time or space in your interview loop, consider posing questions that requires DOM and JS skill in order to best achieve accessibility goals.

### JS: Maybe?

Until and unless your product [demonstrates exceptionally long, login-gated, high-interactivity sessions](https://infrequently.org/2023/02/the-market-for-lemons/#fn-amortised-interaction-costs-3), avoid explicitly hiring for JavaScript skills. 

Most HTML-centric developers with any sort of programming background can pick up JavaScript should they need to, but because JS is the most expensive way (both from a budgetary and from a user-experience) way to deliver solutions, it is an essential goal for your team [not to employ JS specialists until and unless you've built management capacity to manage it _explicitly_](https://infrequently.org/2022/05/performance-management-maturity/).

If you _do_ hire for JS talent, ensure that interviewers look only for "low-level" DOM skill. Do not hire folks cannot write code that uses the DOM without a framework. Be clear with candidates that they will be expected to avoid frameworks ahead of an interviews so that you can avoid wasting everyone's time. 

Avoid candidates that spout nonsense about how they need a framework because "DOM is slow." These folks are more junior than they understand, and may be fine in a backend role, but should not be allowed near the client where the costs of misjudging system constraints area incredibly high. 

The best candidates may suggest solutions in HTML &amp; CSS to problems that are posed as DOM questions. This is a reason to pass, rather than fail, a candidate.

## AI and Frontend

The near-future of heavily automated frontend construction will not reduce the need for skill in fundamentals, but it may centralise this skill into fewer people in an organisation. This will become a litmus test for product values, as the role of the human "in the loop" of an AI-assisted system is to reject bad answers, rather than to fully construct good ones.

From this perspective, the role of skilled folks in your teams will be to nudge the iterative process of product development into alignment with the ethos and received goals of your organisation. This raises, rather than lowers, the stakes for being able to judge solutions to be appropriate. In short, ML and AI will create more demands for discernment, not fewer. Hire wisely; hire for fundamentals.