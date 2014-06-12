# DevOps Gold: What the Olympics teaches us about agile development and release
Dave Roberts
http://devopssummit.sys-con.com/event/session/2317

[note: I walked in late to this talk, but he reviewed so fuzzy at first]

Medals are worth less

DO Lesson #1: Find and articulate motivation for doing DevOps

U.S. speed skaters had
Mach-39 speed skating skin Specialized speed skating suit
Details focused on
 - neck doesn't zip over adam's apple to prevent unzipping
 - vented back
 - ArmourFlide reduces the coefficient of friction by 65%

Stephan Groothuis, a dutch skater without such specialized equipment, won anyway

 U.S. Team gave up on UnderArmour suits due to negative publicity over this

 Davis paired with Zbigniew Brodka of Poland in his heat who won

 DevOps Lesson #2 - tools are tools

 "Your tools alone will not make you successful" ~ Patrick Dubois

 The speed skating skin was not enough to make you win

 DevOps projects succeed or fail based on organization change issues

  - Mikaela Shiffrin, U.S. Skier, Youngest Olympic Slalom champion
   at 19, second most globaly accomplished US woman slalomer

   Why?
     - early start?
     - natural talent?
    Yes these, but mostly her parent's training of fundamentals. She didn't
    get into bad habbits from early competition -- she stayed focus on the basics
    until she mastered them


  DevOps Lesson #3 - make sure your fundamentals are solid

  What are the fundamentals?
   - Programming
   - Automation
   - {Server, Middleware, DB, Network, Program, Process, Change, Defect and incident} management

  - Shiffrin also works out in the summer. She knows that she can't wait til prime time to start

    When was the last time you released an application when you didn't need to, just for the experience & practice

DevOps Lesson #4: Practice, practice, practice

  "So right now I'm dreaming of the next Olympics, winning 5 gold medals. Which sounds really crazy. Sorry I just admitted that to you all"  ~Shiffrin

DevOps Lesson #5: Don't underestimate how far you can go

Marlie Schild, Austria  \
Ted Ligety, USA         |
Maria H                 |   -- Shiffrin studies film of these people's races, 3 of whom are her competitors
Tina Maze              /

Thus she can try to be the best of each of these

DO Lesson #6: Benchmark yourself and incorporate every best-practice you can find

There's always another bottleneck behind the most visible one you see today

DO Lesson #7: Make benchmarking and best practice adoption a repeating habit

Bobsledding - bobsleds are assisted in building by high end automative companies

Michael Scully, BMW DesignWorks USA was asked to build US bobsled with no direct experience
  - Step 1: He took runs in the existing US bobsled
    - he almost passed out
  - Step 2: Threw away the work and went back to basics
     - Modeling
     - Wind tunnel testing
     - Carbon fiber saved 15lbs
       - ended up undershooting required weight, but they could then distribute weight intentionally
   - 69 different prototypes, real world testing
     "In theory, there is no difference between theory and practice. But in practice, there is." ~anon

  Bronze. After no medals in 62 years in mens
  Silver and Bronze in womens

  "This has been the most intensive project of my career. I will confess, I loved it"

DO Lesson #8: Don't be afraid to change your process
 - Automating a bad existing process cannot fix it
 - Break it down step by step, and re-evaluate

Quiz: who is the greatest olympian of all time, by medal count?
Michael Phelps - 22 medals, 18 gold
Next closest are 18, {9,7} from USSR

fourth most is winter: Ole Einer Bjørndalen, Biathalon 13 medals, 8 gold
 - Duality of high intensity speed sport, focus and stability shooting
 - Sochi: two gold medals
 - first olympics in 94 came 7th
 - He's 40.

 "This is my 20th year in the sport. I've known swimming and that's it. I don't want to swim past age 30. ..." Phelps

 Silver in biatholon in Sochi 26

 DO Lesson #9: Not just for the young whipper-snapper startups
 but you have to train hard
 don't underestimate the amount of calories you're going to burn compared to competition

 in 2010 winter olympics, ice dancing vs 2014, US and Canada flipped gold and silver
  - they train together at the university of Michigan
  - they have the same coach - she had to change jackets between events
   - she trained in USSR, but never went to olympics

DO Lesson #10: you need a good coach
 - The most important thing is not so much their experience, as having an outside perspective
 - And having an ability to motivate and keep you going

----
# Velocity and Volume (or Speed Wins)
@adrianco

"Baffling-lae-adopters as a service"

Typical reactions to my Netflix talks...
 "You guys are crazy! Can't believe it" - 2009 : no one belived we were doing it
 "What Netflix is doing won't work" - 2010 : they belived we were doing it, but thought we were wrong
 "It only works for 'unicorns' like Netflix" - 2011 : They believed it worked for us, but couldn't for others
 "We'd like to do that, but can't" - 2012 : they believe it worked for many, but not them
 "We're on our way using Netflix OSS" - 2013 : They think they are doing it but just need time
 Last Netflix data center being shut down this year

 adrian moved from Netflix to Battery cause the tech had moved out of netflix to the world

 What I learned from my time at Netflix:
  - Speed wins in the marketplace
  - Speed is gained by removing friction from the product development practice
  - High trust, low process, no hand-offs between teams
    - Requires a freedom and responsibility culture
  - Don't do your own undifferentiated heavy lifting
    - if buying it works as well as building it, buying is faster
  - Use simple patterns automated by tooling
    - smart people allowed to do what they want, "emergent architectuire"
    - someone on the team had read about the best practices
    - once you have something working, make it automatic
    - provide standard options, but allow people to use what they want
  - Going outside of your company to present something gets more attention than just trying to present internally
    - Conference talks and books
  - Self-service cloud "makes impossible things instant"

Enterprise IT Adoption of Cloud:
-time-->
Ignore Ignore Ignore Ignore Ignore Ignore "no" "no" "NO!" "Oh No" "Oh %*&!"

Speed of Innovation:
 - New Ideas -> New Products

 Incumbents and disrupters both build stuff all the time, the difference is in
 assumptions and learned behavior.
 What you think you can do effects what you do

 "It isn't what we don't know that gives us trouble, it's what we that ain't so" ~Will Rogers

 Incumbents follow the $$$

 Disrupters find what used to be expiensive but is now cheap
 Learn to waste them to save money elswhere

 Assumption: Process prevents problems

 Linear non-cloud product development -- waterfalls / healthcare.gov takes weeks to months

 Taking out (outsourcing) steps:
  - starting with hardware procurement --> cloud
  - development and testing --> PaaS
  - software that are non-core competencies --> SaaS solutions (including "app builders")

  Reduce business need -> customer feedback

(me: changing steps to assumptions)

Rate of change increased as cost & size & risk of change reduced (seesaw/lever image)

OODA - Observe, Orient, Decide, Act

Observe: Innovation: Opportunity, need, complaint
Orient: Big Data: Analysis, Model Hypothesis
Decide: Culture: Share Plans, Plan Response, JFDI
Act: Cloud: AB Test, Automatic Deploy, Incremental Features

Non-destructive production updates.
 - "Immutable Code" Service Platform
   - Existing services unchanged
   - New to new, old to old
   - Transition as demanded
   - (cleanup)
- A|B test, feature flags, and version routing control traffic
   - Devs first
   - Test with data

Disrupter: Continuous Delivery

Development and Operations
 - old assumption: developers make, operators run
 - if operations is self-service then they do it, and feel responsible

 - Less down time by "peril in the right place"
 - lost times dealing with new concerns is outweighed by time gained from lack of coordination

"DevOps is a re-org, not a new team to hire"

When is it done? When its removed from production.
 - this leads to microservices to scope responsibility!
 - monolith broke, call everyone!

 Disrupter: High Trust Culture

 What you know that isn't so...


- Make your assumptions explicit
- Extrapolate trends to the limit
- Listen to non-customers
- Follow developer adoption, not IT spend
- Map evolution of products to services to utilities
- Re-organize your team for speed of execution

Q: What are your thoughts on implementing devops in companies where you need to silo for security/external concerns

 - Netflix does. There's general, SOCS-compliance, money-matters, and credit card access
 - They still support their code.

---
Stop hiring devops experts (and start growing them)
http://devopssummit.sys-con.com/event/session/2287

2014 State of DevOps report
 - -http://bit.ly/2014-devops-report

 "Firms with high-performing IT organizations were twice as likely to exceed
 .... "

 Everyone wants to hire a devop:
  - http://gun.io/blog/how-to-hire-devops
  - they don't exist.

  The game has changed what is the game?
  "Devops means giving a shit about your job enough to not pass the buck. Devops
  means giving a shit about your enough to not pass the buck... " http://bit.ly/2DkRhf

  Allspaw-Hammand was about making people work together cause they had the
  interests of their customers at heart.

  Devops report found a way to measure performance.
   - deployment frequency
   - lead time for changes
   - means time to recover
   - (also change fail rate)

 -Amazon May Deployment Stats:
  - 11.6 seconds
  - 1,079 max # of deployments in a single hour
  - 10,000 mean # of hosts simultaneously receiving a deployment
  - 30,000 max # of hosts simultaneously receiving a daployment

Everyone thinks their problem domain is more complex.

Amazon's core culture basically is to want to outcompete everyone else, that's why they
constantly innovate.

innovation culture:
 we grow systems and knowledge
  - trust
  - experimentation / improvisation
  - safe to fail
  - how well do we cultivate knowledge?

not very effective:
 - training - get people excited for a while but not long
 - buying tools - Continuous delivery is pretty effective with bash scripts
    - buying "agile tools" doesn't give agility
 - creating a "devops team"
   - devops report found that organizations that had a devops tool actually did better
   - but it depends what that means. A team that creates tools well to solve internal problems is good
     merely adding a new silo that isn't
  - hiring people - "bringing smart people into a broken system breaks the people, it doesn't fix the system"

top predictors of performance:
 - lightweight peer-reviewed change approval process
 - version control _everything_! (constrains complexity - that's a good thing)
 - proactive monitoring
 - high trust organizational culture
 - win-win culture between dev and ops

 high trust culture (is actually safer)

 changing culture:
 http://sloanreview.mit.edu/article/how-to-change-a-culure-lessons-from-nummi

 Toyota was taking over a plant in the US, GM had just shut down
  - they rehired everyone GM had just fired
  - they sent them all to japan and retrained them
  - it worked
  - why?
    - Andon cord: pull the cord, your manager appears and helps! or the line stops until its fixed
    - Quality is built into the system!

  What we Do rests on Values & Attitudes rests on Culture
  change can go this way -->

  improvement kata:
   - Understand the direction
   - Grasp the current condition
   - Establish the next (measurable) target condition
   - PDCA Toward the target (what is your next step?) [Plan. Do. Check. Act]
   - Summary reflection: what have we learned?

   You establish a goal, but you don't plan how you are going to do it:
   you encourage continuous experimentation

    Think about "when can we go and see what we learned from taking the step?"
    and make it soon

   Counter-measures to specific problems are not (always) best practices

   The ability to react, not the reaction is the real effective practice

- we work in Complex Adaptive Systems

Leadership:
  - you want a "highly aligned, loosely coupled" organization
  - leaders decision outcomes with a short horizon
  - people doing work discover how to achieve outcomes
  job of manager is to _enable_ their reports
  update vision, outcomes, metrics based on learnings

  Jesse Robin's rule "don' fight stupid, make more awesome"
