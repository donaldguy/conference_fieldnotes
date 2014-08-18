#DevOpsDays Boston 2014

James Merckle intro - "Thanks for coming"

You may have wondered why your badge has a unicorn on it?
 - Unicorns have a special relationship with Boston - maybe you've seen the Boston athletic association or Boston Marathon logo with a unicorn on it. Ours is kind of a parody of that. That is a stylized version of the replica of the original lion and unicorn statues from the boston state house that was torn down in 1776 because they were symbols of the British monarchy. So that is a parody of a reference to a redesign of a replica of a statue of a symbol
 - There are also Devops unicorns. We can't all build the coolest thing. There's a little bit of an argument on twitter, whether we need unicorns to do devops or whether a devops transformation can be accomplished with just horses. Certainly unicorns are cooler than horse, but they aren't rare because they are rare, they are cool because of an inately special. People can become unicorns. Nobody starts off as a unicorn. It doesn't matter where you start off, it matters what you are willing to embrace

Sponsor pitch:
SumoLogic - we do log management as a service. In german unicorn is called einhorn, meaning one horn. Anyway, log management as a service in the cloud. We are very cost effective - we take care of a lot of the heavy lifting. You don't have to become an expert at running and scaling logstash

## From Hero to Zero
Jennifer Davis @sigje

Goals:
 - Communication - talk to me about it, I am interested
 - Collaboration
 - Change

 What and Why - Zero Culture
  - Formular for Suc(str)ess
  - 7 years ago she got a new job and was really excited
  - She worked really long hours to prove herself
  - In her extreme effort, she improved her efficiency, but kept increasing her responsibilities
  - Expectations built up on past performance. None stop build up to unreasonable place

  - The cure?
   - she tried documentation, and no one read it
   - She made checklists and people got lost
   - She made shell scripts for given situations, but it didn't work

  - 4 years ago her manager _made_ her take a vacation
   - Night before leaving she set up some more failsafe
   - But while she was gone everything caught on fire anyway
   - Manager explained he knew it was going to happen and it needed to
   - Jennifer _was_ the single point of failure

  - Our institutional cultures have adopted the premise of the "hero"
   - Campbell - "A hero is someone who has given themselves to something bigger thant themself"
   - We celebrate the extra mile, the late night hacking, the all weekend, and stepping up to do stuff no one wants
   - And thus "heroism" becomes "used to be"-ism ... we stop doing the things we used to do, for fun, for happiness
   - "Heroism results in degradation of relationships"
   - At the end of the day we all get old, and our work won't be there for us, but people can be

  - "Heroism" results in sleep deprivation
    - Walter Reed Army Institute of Research study found that sleep deprivation was comprable to brain damange
  - heroism results in dissatisfaction with our jobs
  - heroism results in loss of self-confidence
    - conflation of who you are and what you do coupled with degrading productivity is a recipe for disaster

  - 6 Areas result in burnout
   - Work overload
   - Lack of control
   - Insufficient rewards
   - Workplace community problems
   - Lack of fairness
   - Conflict between personal values and requirenments of the job
  - Marie Asberg, Burnout as "Fatigue Syndrome"
   - Symptoms include increased drinking
   - You can use RescueTime to track your productivity

  - Why do we even care about the hours we work?
    - Ernst Ab in 1908 showed decreasing from work day from 9 to 8 increased productivity
    - 40 hour workweek came from Ford study over years - but that was for manufacturing - knowledge work may be different
    - If you work more than 40 hours, you will degrade in productivity over time.

  - Railroad industry "No single employee crews"

  - Celebrate being Wrong
  - Think about Rites of Passage- allow people to grow, listen, speak

Exploring our myths
  - Superman
   - has lots of powers
   - recharge by the sun
   - strong but doesn't think that much
  - The Flash
   - He's fast
   - He misses context and it hurts people
  - Hulk
   - RageOps.
   - It can be effective but its not repeatable and it doesn't role back
  - Steel
   - Hero worships superman. Doesn't realize his potential because he constrains himself to another's vision
  - Batman
    - Works late in the night by himself, plays by his own rules
    - But he makes rash decisions, and doesn't let people who would be better suited do some jobs

  - Even our art shows these problems

Embrace "zero culture"
 - Stop relating through roles; relate as individuals and understand individuals capabilities and roles

Path
 - 5 conditions of a happy work environent - "Henderson - Follow your bliss"
 - Communication - Identify your team
   - common goals, diversity of perspectives
  - Vision or Mission Statement
   - Clear statment of the problem
    - Direction, Identity management, and Team Cohesion
 - Kanban
  - Visualizing your work tracks it and lets communication happen passively
 - Versioned Software Releases
  - Repeatability
 - Infrastructure as code
  - Subject matter experts; bus number
 - Documentation as Code Evan Goer youtu.be/mEvvc80ZYU8
  - The whole team needs to work on the same environment
 - Testing and monitoring
  - false alarms have a cost
 - Pipelines
  - local test
  - never break the build

  Individuals empowered to do work and understand consequences
  - Cognitive costs we put on each other hurts each other

  - Zero culture, Empty culture is Empathy culture

  Q&A:
   - comment: being woken up in the middle of the night, people aren't effective

  Sponsor Pitch:
   - ruxit - full stack application monitoring with less/no waste - actionable dashboards, no false alarms; causation not correlation

  ## The Value of Feedback
  John Ryding @strife25

   2 types of feedback, both exciting and helpful:
   - "Experiencing the results of the actions you perform and making more choices"
   - "Giving and receiving constructive criticism from your colleauges"

  Both are more effective if you shorten the cycle time. Long feedback loops are less effective than short feedback loops
   - When you give a demo after a lot of work, you may receive a lot of criticism because expectations weren't checked and diverged
   -
  Feedback can be a positive experience!
   - frequency builds comfort
   - feedback when it is helpful is welcome

  Examples of feedback not going well and how they were fixed
  1. Collab between UI & QA
      - QA team uses Selenium
      - UI should use semantic CSS on interactive elements to make tests readable
      - UI & QA only interact directly when things are breaking
      - Reasonable change interacted with old code to break lots and lots of tests; demonstrated there was a problem in process
      - Feedback issues
        - No insight into what the other team was doing
        - UI didn't know what the tests did
        - QA didn't know what was coming
      - Solution
        - Code review was how UI team knew what was up - so add the QA team to the process as well :D
        - UI team members also included in QA code reviews; improved the code & the tests!
  2. Code reviews
    - They are a great venue to learn and collaborate
    - ... most of the time
    - Problems
     - Following Github flow, code reviewed right before merge
     - When someone has put a lot of energy into code, but it just is bad, everyone gets upset, relationships get strained
     - But GitHub themselves always opens a PR right after branching - allows feedback during development process.
     - Shifts reviewer/author relationship from criticism to collaboration
   3. UX Dailies
     - UI and UX teams come in and give demos of work in progress that is 25-75% done
    -  &gt; 25% the idea has solidified enough to explain to others
     - <75% work is avctive and feedback can actually be addressed
     - Open for anyone to attend
       - Great ideas can come from unexpected places
       - People can see what's coming

   Feedback is super important and lets us achieve a higher quality of work. Giving and recieving feedback should be a pleasant and helpful process.
   Focusing on the feedback loops is a great place to encourage collaboration.

   Q: For continuous code review, do you do code review on all the code or pick and choose based on risk
   A: We do it all. It definitely can be time-consuming, it needs to be estimated for.

   Q: what mechanisms do you use to give context around what a code review does?
   A: It's hard. I encourage small reviews, ask questions and encourage documentation.

Pitch: AppNeta - Fu

## Our long road to self service cloud management & deployment
Kevin Amorin @veritaskev

"Our long road to ... continuous improvement"

 - BitSight. 15 years exp in Enterprise & Startups
 - starting the journey:
    - "always make new mistakes"
    - do not re-invent the wheel
    - continous improvement
    - no silver bullet - its a journey not a destination

  - Greenfield project when he was hired
   - ... so he was told
   - but it doesn't take long to accumulate technical debt

   - first 100 days
    - ask questions and listen
    - hiring (co-ops / interns)
    - Marketing the message, ask the right questions, use the right ideas
    - Continuous improvement:
     - simple value stream mapping
      - Identify the steps the company needs to deliver the value to the customer
      - Ballpark how long each stop takes
        - until you get it down on paper, you have no idea
     - find bottleneck, optimize flow, repeat

     - identify the bottleneck: easier said than done
      - important to differentiate the symptom from the cause

 - infrastructe v1
    - "what does this server do?"
    - symptom: lost time in debugging/managing products in data center
    - cause: organic growth with little planning
    - improvement: redesign, starting with proces for naming, access, users, deployment

- build v1
  - "build is broken"
  - symptom: lost time in broken build debugging
  - cause: lack of uniform build environment, committed code with minimal testing and review
  - improvement: centralized build & CI, branching (branch naming convention), pull requests, additional unit tests

- deployment v1
 - "that system doesn't have my fix"
 - symptom: lost time debugging wrong code
 - lack of revisioned artifacts
 - improvement: central artifcat repo, each package with branch, time, commit

 - communication v1
  - "what new feature?"
  - symptom: lost time with misinformation
  - cause: silping of information
  - improvement: chat, single issue tracking & process, representatives in standup & retrospective
  - integrated hipchat into onboarding process + got everyone using it

- infrastructure v2
 - "thsat system is missing my pip modules"
 - config management, monitoring & alerting

 - build v2
  "ran in my local system"
  regression/functional testing

 - deployment v2
  - schema management

 - deployment v3
   - "new server didn't come up right"
   - semi-automated provisioning was not good enough; had to move towards actually automated

   infrastructure v3:
    - "can I grab a cluster"
    - symptom: who is using what? what state is it in?
    - cause: lack of visibility of ownership & stat of application
    - improvement: Atlas metadata system

  - Delivery pipeline

  - Lessons learned
   - devops messaging - be the evangelist
   - analyze the current state
   - use symptom to find cause
   - find the solution that fits
   - KISS then scale

## Infrastructure Testing: Grey Matter
Anthony Spring @devopsanthony

 - What is grey matter?
   - The area of your infrastructure where you have the least amount of confidence
   - there is a gap between configuration management and monitoring; and things provided by third parties

 - ServerSpec
  - Easy to use, extensible
  - only need ssh access

 - Integration testing
   - utilized test-kitchen and serverspec for testing chef cookbooks
  - Developer Environments
   - A spec was created for all the pieces of the developer stack
   - Organize the specs based off of a team
   - Two commands to evaluate the configuration of the environment, easy enough for non-technical users

  - Box creation and delivery
   - Packer + Racker
   - ServerSpecs verify it all, including the kickstart piece

  - Third party machines
   - Guarantee compliance with requirenments
   - Continious compliance, process, and system monitoring
   - Reduce the feedback loop for identifying issues - fail fast and all that

  - How can you reduce grey matter?

  Q&A:
    Windows support? yes
    Duplication? some, but not that bad
    Hints for determining what constitutes a good test?
     - does it address the problem
