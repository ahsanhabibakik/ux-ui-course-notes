# Start Your Journey With UX - Course Notes

Course: [Start Your Journey With UX](https://instructory.net/courses/start-your-journey-with-ux) (Instructory)
Instructor: Rifat M Huq (UX researcher and UI designer, built Instructory itself)
Length: 21h 54m, 90 lectures, beginner level
My status: completed

## Course contents (instructor's own TOC slides)

The instructor's "Contents of this Course" slides, captured from the course videos. Full curriculum with durations is in [curriculum.md](curriculum.md).

| | |
|---|---|
| ![Sections 1-5](slides/contents-01-sections-1-5.png) | ![Sections 6-7](slides/contents-02-sections-6-7.png) |
| ![Sections 8-10](slides/contents-03-sections-8-10.png) | ![Sections 10-13](slides/contents-04-sections-10-13.png) |

## How this course is organized (my mental map)

Three blocks:

1. **UX theory** (Sections 1 to 13): what UX is, roles, interaction design, human centered design, a full real case study on Instructory, common errors, myths, and core principles.
2. **UX methods and process** (Sections 14 to 23): the actual tools of the trade. KWHL, user personas, site maps, POEMS, MVP, Agile and A/B testing, usability testing, UX laws, and the different UX job roles.
3. **Hands-on with Adobe XD** (Sections 24 to 30): the tool itself plus one big freelancing project, a full multi-page website design from requirement analysis to prototype.

Below are my notes per block.

---

## Block 1: UX theory

### What is UX (Section 3)

![UX vs UXD](slides/s03-ux-vs-uxd.png)

First, the terms:

- **UX** stands for **User Experience**: the experience itself, what the user feels and goes through when using a product. Every product already has a UX, good or bad, whether anyone designed it or not.
- **UXD** stands for **User Experience Design**: the practice of shaping that experience on purpose. UX is the outcome, UXD is the work.

So "I do UX" really means "I do UXD". The distinction sounds small but it matters: you cannot directly build an experience, you can only design the conditions (interface, flow, content, speed) and the experience happens in the user's head.

A website or app is not just pages connected with links. It is an interface where the user and the product meet and affect each other. That interaction creates an experience, and UX design is the job of making that experience as good as possible.

Key distinction that clicked for me:

- **UI** = what the user sees and touches (layout, colors, typography, buttons).
- **UX** = how the whole thing feels and works for the user (can they find what they need, do they trust it, do they come back).

Good UI with bad UX is a pretty thing nobody can use. UX comes first, UI expresses it.

### UX role (Sections 4 and 23)

UX is not one job. The course breaks it into:

- **UX Researcher**: talks to users, runs interviews and surveys, finds the real problems.
- **UX Designer**: turns research into flows, wireframes, and structure.
- **UX Writer**: the words in the interface. Microcopy matters more than I expected, button labels and error messages are part of the experience.
- **UX Manager**: coordinates the above, owns the process.
- **Web Developer**: implements it. As a frontend dev this is me, and the point of the whole course for me is that developers who understand UX build better products without waiting for a designer.

In small teams (like ours) one person wears several of these hats, so knowing the boundaries helps me know which hat I have on.

### How interaction design works (Section 5)

The course frames interaction design as a chain:

1. **User need**: everything starts here. No need, no product. Find the need before designing anything.
2. **Case study**: look at how others solved the same need. Learn from existing solutions before inventing.
3. **Product design**: design the solution around the need, not around what looks cool.
4. **User attraction**: how the design pulls users in. First impressions, visual hooks, clear value.
5. **Users accustomed**: the end goal. Users build a habit around the product. When people use it without thinking, the interaction design worked.

My takeaway: attraction gets users in the door, but "accustomed" is what retention actually is. Design for the habit, not just the landing.

### Human centered design and the DND concept (Section 6)

Human centered design (HCD) means the human is the starting point of every decision, not the technology and not the business.

The instructor teaches it through his DND concept with a worked example (an HCD walkthrough video). The pattern I took away: observe real people, find what frustrates them in their real context, design for that context, then test with the same people. Design decisions get justified by "the user needs it", never by "I like it".

### Case study: Instructory itself (Section 7)

Best section of the theory block. The instructor built Instructory (the platform the course runs on) and walks through the entire startup thinking as a UX case study:

1. **Brainstorming, business proposal, pitch deck**: UX work starts before any screen exists, at the level of what the business is.
2. **Problem and solution**: Bangladesh-context problem, students and professionals need income and skills, instructors need a platform to teach and earn. The solution is the marketplace connecting them.
3. **Context and overview of the case**: who the players are, what already exists locally.
4. **Features and competitor analysis**: compare against Udemy-style global platforms, find the local gap (payment methods, language, pricing).
5. **Market size and target audience**: size the market before building. Target audience definition feeds directly into personas later.
6. **Business model**: how the platform earns (revenue share on courses). UX must support the model, checkout and instructor payout flows are UX problems.
7. **Current status and traction**: numbers as proof the design decisions worked.
8. **Team and gameplan**: who builds it and the 5 year plan.

Takeaway for AI Buddy work: this maps almost one-to-one to how we should present client projects. Problem, solution, competitors, market, model, traction. A design pitch is a business pitch.

### UX errors (Section 8)

Common mistakes designers make. The ones I noted:

- Designing for yourself or the client's taste instead of the user.
- Skipping research because "we already know what users want".
- Cluttering the interface, trying to show everything at once.
- Inconsistent patterns between pages, the same action looking different in different places.

### UX myths (Section 9)

Five myths the course breaks down, each is a "people think X is enough":

1. **"Need to focus"**: focus alone is not enough.
2. **"Need more research and thinking"**: research alone is not enough either.
3. **"Need more concentration"**: same.
4. **"Need more creative thinking"**: creativity without user grounding is decoration.
5. **"Need to design based on user demand"**: even this is a myth when taken alone, because users cannot always articulate what they need (the classic faster-horses problem).

The pattern behind all five: no single ingredient makes good UX. It is the combination of research, focus, creativity, and user input, checked against real behavior through testing.

### UX principles (Section 10)

The core checklist of the course. Eight principles:

1. **Know your user**: user need, user research. Everything else builds on this.
2. **Useful, credible, authentic information**: content must be true and trustworthy, trust is a UX feature.
3. **Easy to use, easy to find, accessible**: if users cannot find it, it does not exist. Accessibility is part of usability, not an add-on.
4. **Hierarchy**: visual and information hierarchy guide the eye. Most important thing biggest and first.
5. **Clarity and simplicity**: ignore complex design. If a simpler version communicates the same, the simpler version wins.
6. **Coordination and consistency**: elements look and behave the same across the product. Consistency reduces learning cost.
7. **Familiarity**: use patterns users already know. A cart icon means cart. Innovation in the wrong place is friction.
8. **Confirmation**: for destructive or important actions, confirm. Users make mistakes, good UX makes mistakes cheap.

These eight are the part I expect to reuse weekly in frontend work. Hierarchy, consistency, familiarity, and confirmation are directly implementable in code without any designer involved.

### Who can learn UI/UX, prerequisites, next courses (Sections 11 to 13)

Anyone can start, no design background required. The course positions itself as course 1 of the instructor's track (next is the UI Design course, which is my course 2). Bonus lessons get added over time.

---

## Block 2: UX methods and process

This block is the toolbox. One method per section.

### KWHL (Section 14)

A structured way to start any project:

- **K**: what do we Know already
- **W**: what do we Want to find out
- **H**: How will we find it (research methods)
- **L**: what did we Learn (filled after research)

Simple table, forces the team to admit what is assumption vs knowledge before designing. I want to try this on the next AI Buddy client kickoff.

### User Persona (Section 15, 2 parts)

A fictional but research-based profile of a target user: name, age, context, goals, frustrations, tech comfort. Personas keep the team designing for "Rina, 24, student, uses bKash on a budget Android phone" instead of "the user", which quietly becomes "me".

Rule I noted: personas come from research data, not imagination. An invented persona is worse than none because it gives false confidence.

### Site Map (Section 16)

The page hierarchy of the whole product drawn as a tree before any page is designed. Shows navigation depth, orphan pages, and duplicate paths. Cheap to fix here, expensive to fix after build.

### POEMS (Section 17)

Observation framework for field research:

- **P**: People
- **O**: Objects
- **E**: Environments
- **M**: Messages
- **S**: Services

When observing users in context, log what you see under these five headings. Turns vague observation into structured data.

### MVP (Section 18, 2 parts)

Minimum Viable Product. Build the smallest version that tests the core value hypothesis with real users. Key correction to how I used to think about it: MVP is not "a bad version of the product", it is the fastest honest test of whether the need is real. The skateboard-then-bike-then-car idea, each stage is usable on its own.

### Agile and A/B testing (Section 19)

- **Agile**: design in short cycles, ship, learn, adjust. UX fits inside sprints, research feeds the next cycle.
- **A/B testing**: two versions live, real users split between them, data decides. Opinions end where A/B data begins.

### Usability Testing (Section 20, 2 parts)

Watch real users try to complete real tasks on the product, without helping them. Even 5 users find most of the big problems. Notes:

- Test the task, not the user. If they fail, the design failed.
- Do not explain the interface first, the interface must explain itself.
- Record what they do, not what they say they would do.

### UX Laws (Section 21)

Three (well, four) named laws:

- **Fitts's Law**: the time to hit a target depends on its size and distance. Big, close buttons are fast. Practical: touch targets big enough, primary action nearest the thumb.
- **Hick's Law**: more choices, slower decisions. Cut options, group the rest. Practical: shorter menus, fewer form fields per screen (one screen per question, which is exactly the survey UX style I already prefer).
- **Jakob's Law**: users spend most of their time on other sites, so they expect your site to work like the ones they know. Matches the Familiarity principle from Section 10.
- **Miller's Law**: people hold about 7 plus or minus 2 items in working memory. Chunk information, do not make users remember.

### UX perspective of the user (Section 22, 3 parts)

Seeing the product through the user's eyes instead of the builder's. The builder knows where everything is and why, the user knows nothing and cares only about their goal. Every review of my own work should start with forgetting what I know.

---

## Block 3: Adobe XD hands-on (Sections 24 to 30)

The practical half of the course hours. Notes are shorter here because this block is learn-by-doing.

### Tool basics (Sections 24 to 29)

- XD overview, install, plans, and the artboard concept per device (mobile, tablet, desktop sizes).
- Interface and basic tools, shapes, text, pen.
- Export and import between XD, Photoshop, Illustrator, and image formats. Save to cloud vs local.
- **Libraries and UI kits**: reusable component libraries and prebuilt kits. This is the design-side equivalent of a component library in code, same DRY idea.
- **Document assets**: shared colors and character (text) styles across the file, the design-side design-tokens concept.

### Project: freelancing website (Section 30, 19 lessons, ~10 hours)

One full client-style project, a multi-page service website (repair and maintenance service business), from brief to clickable prototype:

1. Requirement analysis from a freelance-style brief.
2. Grid system setup.
3. Plugins and repeat grid for fast repeating content, image tracing.
4. Components and prototyping, layers and grouping.
5. Hero section with video, hover states, tooltips.
6. Auto-animate, MP4 to GIF, client testimonial sections.
7. Multi-page prototype: FAQ with accordion, contact page, testimonial page, special offer page, service pages, appointment booking form, footer, inserted URLs.

Takeaway as a developer: the XD workflow (components, shared assets, grids, prototype links) maps directly onto how I structure React components, tokens, and routing. Reading a designer's XD or Figma file should now feel like reading a component tree. Note: the industry has largely moved to Figma (course 3 covers it), but the concepts transfer one-to-one.

---

## My overall takeaways from course 1

1. UX starts at the business level, not the screen level. The Instructory case study proved a pitch deck is a UX document.
2. The 8 principles (Section 10) plus the 4 laws (Section 21) are a practical review checklist I can apply to any frontend PR without needing a designer.
3. Research before design, always. The myths section exists because everyone (including me) wants to skip to drawing screens.
4. "Users accustomed" reframed retention for me: the goal is habit, not just attraction.
5. One screen per question, big touch targets, fewer choices: the laws confirmed patterns I already use in survey work, now I know why they work.

Next: course 2, Start Your Journey with UI Design, applying these UX foundations to visual design.
