# DevOp With Me: Changing Culture to Continuously Deliver
http://devopssummit.sys-con.com/event/session/2270

@nathenharvey, cohost of the food-fight show

As Farmer Nathen: http://bit.ly/farmer-nathen

Breakfast Cereal:
 - In working for supply chain, we got to visi plants and to
 - talk abou the plant manager's objectives
- He made his bonus by tonnage of cereal, so faced between the
choice of puffed rice and Rasain Bran, the latter always wins
 - And thus his incentives were not aligned with business and the customer

What Is DevOps?:

 (me: https://medium.com/devops-programming/what-is-devops-1150f318a567)
  - DevOps Days. they have open sessions
    - open sessions allow each person to start a conversation about a
    topic they are passionae about
    - you get out what you put in.
    - A community of people is brought together to share ideas and talk about processes
    - That is DevOps
  - Cultural and professional movement
  - Development and Operations (and others) working together toward a common goal
  - Leveraging ideas and practices
  - Culture AND Tools

- Culture and Tools are inseperable. They are intertwined and reinforce one another
  @adamjacob: the goal of a system is to enhance the safety, contentment, knowledge, and freedom of both the authors and users of the system

  Safety:
   - Human safety
   - Information safety
   - Avaliability of the system as a possible link to both
   - The ability of users to act without feat of unintended consequences

  Contentement:
   - about being satsified with what you have

   Knowledge:
    - Access to knowledge is a leading indicator of social progress
    "you may hear someone say implement chef and it will be great and you don't need to understand. They are lying
    You can't automate that which you do not understand"
    - Don't minimize needed knowledge - its about providing access to welath of it, when we need
    It's not telling people to do new stuff its allowing them to work togeter

    Freedom:
    - Empowerment of individuals
    - Automation frees people to act

  Some Humane Systems:
  - Version Control System
      - cp a a.bak
      - cp a a.$(date)
      - cp a a.$(date)-$USER

        DVCS as humane systems:
         - safety in duplication and integrity checks
         - contentment in flexibiity of work flow
         - knowledge in full history
         - freedom in allowing to work ucoupled

         - people are afraid to switch, but they are happy they did

  - Infrastructure as Code
      - Humane
          safety: reliable, repeatable process for management of systems
          contentment: minimize repetitive tasks
          knowledge: code that makes it easy to reason about infrastructure is visible to all (me: executable documentation)
          freedom: frees authors to focus on higher-value and more interesting work

          when things fail you want it to be able to fix it easily

    Continous Delivery
    All code in mainline should be able to be shipped to a customer at any time, easily

      safety: reacting to new situations is as easy as clicking ship it
              safety is what CI/CD is often really about - "the safety net of added value"
              easy reversion
      knowledge: focus action on the moment of external value.
      ....


  - Post-mortems
      We hold post mortems to understand the reasons for failure, to learn from our mistakes, and to prioritize the work we need to do to ensure we don't fail repeatedly

      - Post-mortems should be blameless, of course
      - Post-mortems should be open to EVERYONE
         - more knowledge more better
         - app and infrastructure like tools and culture
         - someone may have a better solution than you
         - "you need the right people in the room"

      -  Figure out the timeline
      -  Look for causes
      -  Reduce mean time to detect AND mean time to recover

  Incident Management:
    - Your systems ARE going to break
    - Picture of emergency stop button locked in case
    - When Nathen goes to pediatrics, he asks what the emergency stop button stops, but the people behind the desk with access don't know what it does
    - If your team doesn't understand the emergency procedures, they are useless

  The 80s: The Decade That Made Us
    - Show on Nathen's DVR
    - first segment he saw was Run DMC and Aerosmith collaboration
    - Back in the 80s there were rock bands and there were rappers, and never the twain shall meet
    - Run DMC heard the song, "this is hilbilly gibberish"
        - Sounds like ops: "I don't understand this code"
    - Aerosmith was all "what the hell are they doing to our song"
        - Devs say: "works on my machine"
      But when they came together in the studio "It was crazy good"
    - In the video they literally tear down the wall.
    - No one asked the rockers to rap or the rappers to rock, but together they could better delight the customers

    - And now I have to explain that rock and rap used to be fully seperate. In the future we won't talk about devops


  To-do list:
    - Version control if you don't
    - Put dev and ops in the same room
    - Take a humane systems view of your technology platform and process
    - Reinforce the culture with appropriate tools

  To not do:
    - mislabel
    - hoarding information
    - look for someone to blame
    - wait for someone else to transform your business: you know your team best.


  Gartner: by 2017 web scale IT will be found in 50% of enterprises
   - continuous experimentation
   - you can be fast AND safe

-----
# The Great Debate: DevOps from the C-Suite to the Weeds
http://devopssummit.sys-con.com/event/session/2271

Rajat Bhargava of JumpCloud

Practiciner of practices, Provider of tools, Investor in DevOps companies , Leader - founding sponser of DevOps.com

Why I care about devops?
  - Create high performance organizations
  - Mine. Yours. Others

Dev + Ops ≠ DevOps.
  - it can be made about that
  - but to so constrain your thinking is dangerous

Devops is about better serving the customer
  - its nots optional
  - its not just tools and tech

History
  - Industrial revolution
    - Automation
    - Greater Productivity
    - Integration
  - DevOps is a parallel story
      - if you don't get on bored, you will be passed

    2nd order effects:
      - new industrties
      - new tools
      - increased knowledge
      - more efficient economies
      - increase in quality of life & wages

The DevOps debate
  -  Dev + Ops ≠ DevOps.
      - there's an overarching theme you can miss
  - DevOps isn't only for unicorns and startups
      - the WSJ says webscale won't work for enterprise
      - but it hass and it will
      - it requires more thinking
      - They also said big companies wouldn't get the internet
  - DevOps ≠ Developers
      - it may work in small organizations
      - it won't work in larger ones
      - you can't wear all the hats for long
    DevOps ≠ Tools
      - Tools are important
      - but so is the rest

Why you should care about DevOps

  the devops equation:
    DevOps = ^P (product and market fit)

  Common mythical promises:

  - You'll sell more
  - Quicker time to market
  - More efficient costs
  - Fewer defects

  These things may be true in the long term, but they may or may not be true in the short term

  "Creating call options, cost-effectively":
    - options your features
    - invest to win if "the market" indicates
    - or cut your (small) losses

DevOps in action
  - Craftsy – educational site for customers
     - they talk about devops as delivering a better experience to those customers
    - Mocavo
      - Operational execution matters - better, richer data

    - Rackspace
      - faster time to market outcompetes

It's hard:
 -   It requires:
    - people working close together
    - more management / coordination - not less
    - move to te middle - experts vs generalists
    - unrealistic expectations

Unicorns have done it: Google, Facebook, Twitter, Etsy, Netflix
but so have horses: Disney, EA, Bank of America, The Gap
and mice: startups not at web scale

What is coming:
   - more commercial solutions
   - more solutions to tie decesions to business results
   - Training, certification (me: gag), and standards
  - Why? Too much is at stake, too much to gain

Why they care:
  - executives: competitive advantage and the bottom line. If your competitors are doing it, you need to. If they are going to, you should first
  - techies: greater knowldege, less duplicated problems means more interesting problems. Focus on innovation

  Brad Feld of Foundary Group, VC says he is hesitant to invest in companies that are not practicing devops

What you can make happen:
  - Understand the punch-lines: its about better sercing the customer and its not optional. And it can't be bought
  - Lead, share, contribute, and execute

Audience member: what about organizations not on the web? is it needed? are there good examples?
  - Yes (me: see also, the phoenix project)
  - Bank of America presumably uses extensively for internal infrastructure
  - You don't need cloud, but it can help (OpenStack can be used internally)
  - You need to test and evaluate changes with your customers.

Audience: We have people in different timezones and overseas. Someone yesterday mentioned that its better to do face-to-face, in the whiteboard. So what?
  - Business has changed. it's not always done face to face
  - There are technologies for this
  - Dealing with a remote can be an advantage by catalyzing communication
  - You may need to explicitly allocate more work (points in sprint) for the communciations overhead.
  - Extra effort but not necissarilly a hinderance

Audience: You mentioned certifications. Like six-sigma...?
  - There will be certifications and training
  - Its too important not to be picked up
  - Purists will be upset, but its going to happen.
  - Devops.com will move into that space.

Audience: are developers or operations more ready to adopt DevOps practices without complaint?
  - Stage matters:
    - at startups early devs are picking it up
    - at bigger orgs in varies more
  - I don't think there is a particular rule
  - More and more the head of ops is the QB of the devops effort.
  ----
  # Oracle Keynote: Cloud Odyssey: A Hero's Quest
  http://www.cloudcomputingexpo.com/event/session/2217

  Sandra Cheevers, Cloud Product Marketing

  Animated science fiction movie experience

  "journey to private cloud"

  &lt;snark&gt;
  - What if the Mass Effect engine was used _only_ for marketing purposes?
  - Questionable geopolitical climate in this metaphor
  - What if movies were interrupted between acts for a total recap of the action,
    as well as telling you _other_ things you already know.

    .... snark continues here:

  ---
  .... tired, too snarky to take notes, or really pay a lot of attention ..

  ----
  # Is Orchestration the Next Big Thing in DevOps?
  http://devopssummit.sys-con.com/event/session/2273

  Two part talk - first relatively high-level, second more technical

  DevOps through the Car Industry Analogy:
   - The biggest revolution?
      - gasoline engine
      - sports car
      - Model T <--- this one was generalizable
    - Model T production as mass standardization (mass production)
    - Led to mass adoption of automibles, allowed raising of standard of living, and broadening of middle class in America
    - Increased pay let workers be customers quickly, build mindshare

  Configuration, compute, network can be automated... What's the missing piece?
    - The software defined operator
    - - human operator:
       [Email, Docs --> GUI, CLI]-Monitoring, SMS
      - software operator:
       [DSL -> API]- Policy Engine
     - reduce impact of human error:
       - 80% of mission-critical outages caused by people and process issues
       - 50% of those outages will be caused by change/configuration/release intergration and hand-off issues

   Orchestration =: Software Operation
     - cloud-config.yml
     - cloudify on vms
     - TOSCA standard (Gigaspace is one implementaion)

---
#DevOps: Security's Last Best Hope

http://devopssummit.sys-con.com/event/session/2333

- Room survey: few security people in the room

- Talking more about security than devops

- Talking about how devops can help some issues security has been dealing with
in the last few years

- Security is a 67.2 billion dollar industry, expected to grow to $86B by 2016
  - Total cost of cybercrime and cyber espionage to global economy is hundreds of billions
  - We could kill it with money-fire but that wouldn't make sense - Security is about managing risk!

  Target: 70 million cards stolen, but who cares?
   - Everyone in this room has had financial information breached at some point.
   - The problem is taking those all and piling them together, its barely a blip in terms of statistical
     significance. .5% of gross sales only.

  - At the end of the day, when the calculations done, security looks like a rounding error.


The security industry, in spite of our best efforts has not stemmed the tide of breach, cybercrimes, and espionage
This sounds like failure as an industry.
Why?
  - "The Usual Suspects"
    - Lack of Resources
    - Security is an afterthought
    - Security is a a separate silo from Dev & Ops
    - Security is too hard, the bad guys are too smart
    - Just not important enough to the business

We need a new hope: DevOps represents a tremendous opportunity to change the game for security.
  - In technology there are watershed moments that change everything.
  - We are in the midst of the tectonic shifts of tablets and big data


DevOps: the great enabler
  - Integrate the security team into the DevOps team
    - Security needs to work with Ops, network, QA, and Dev
  - Include security in the planning, architecture process as well
  - Built in security, not bolted on security: security at every step
  - Move security earlier in the process
    - Test code early and often
    - Automate, automate, automate
  - Make security everyone's responsibility
    - We are all on the security team

Security is not immune from technical debt,
but with the added dimension that incorrect cleanup can be letting in the enemy
(e.g. proliferation of firewall rules)

What can devops do?
 - Give security a seat at the table
   - Even if your sec person looks like a crazy person :grin:
 - Security IS EVERYONE'S RESPONSIBILITY
   - there shouldnt be a sec team.

Developers think they are already doing security but they really arent

75% of security incidents could be stopped using basic controls! (e.g. password policies)

---
#Don't Go Chasing Unicorns!
###Science, Engineering, and Synthetic Thinking How to Use Three Different Viewpoints to Make Devops Work for Your Mission!
http://devopssummit.sys-con.com/event/session/2286

by @kevinbehr

Wrote Phoenix Project, Visible Ops, and about 5 books before that
People tend to conflate the various work that [he and coauthors] have done

People are trying too hard to reify the concept of devops, when it was just
a by word for desire to collaborate

- Survivor Bias
  - a tendency to focus on what is perceived as succesfuul (humans, methods, companies, software) while igoring those same things that fail
  - Paradigms are changing fast, but they aren't _really_ changing.
    - In the 70s we had full-stack engineers "dev/ops".
    - In the 80s we went client/server
    - Division of labor didn't really make sense, but everyone thought they needed a niche
  - In WWII, plane missions dropped down to about 50% survival rate. There was a desire to fortify the planes:
    - They couldn't make whole plane out of armament, it wouldn't fly
    - They looked to where the bullet holes were, but that's ONLY the planes that CAME BACK
    - In the end, it was mathematicians who had to figure out the answers through scientific testing and modeling from material properties and ballistic projections
    - Do you do this in your business? NO, you don't ... that's why you hire Kevin.
  - Pareto theory: theres a succesful shape you can observe
  - organizations are not software. Herding humans is harder than herding cats.
    - When we say "we are gonna roll out [devops/agile]", what does that even mean?
      - Your organization is made of individuals, with individual opinions and motives
    - Division of labor in the knowledge economy turns out to not be optimal at a certain granulariy

- Confirmation Bias
  - The tendency of people to favor information that confirms their belief or hypothesis over information that may refute it
  - Some people think this is the definition of "management"
  - Judging a successful manager as a good manager, you are embracing impending moral hazard.
  - Entrepeuners actually think they are more lucky than others
  - Engineers are especially given to confirmation bias

  - Be wary of
     - Case studies
     - Surveys as Unicorns - the unicorns weren't emulating, they were innovating. That they shared doesn't change this
     - Oversimplifications
     - "Logical" inferences

  - Tools we can use to help:
    - The Scientific Method
    - Hang a logical fallacy poster in your conference room
    - Build a portfolio of safe to fail experiments
    - Practice daily continuous improvement form (kata)

    _Doing what high performers do may not make you a magical unicorn_

  - Looking at "Lean" results doesn't teach you - they came from a process you didn't see - this is surviver bias
    - You go to Toyota they don't talk about it, cause its engrained.

  - Continuous experimentation can unlearn learned helplessness!

 (me: cargo culting - ) "Wait! You're telling me I'm not a unicorn"
  - That you have a solid deployment pipeline doesn't mean its not full of sewage

  GM saw labor strike, so they bought a bunch of robots:
    - They could have bought all their competitors instead.
    - The DevOps arm race hasn't even taken off yet

  IT is cheap like a puppy is free - its the vet bills!

- Engineering vs Scientific Method
       Science (Knowledge of general truths and laws)
          |
          v
       Engineering (Acquiring and Applying scientific knowledge to build/
                    design/create something)
          |
          v
      Technology (The sum of all the engineered tools/devices/processes avaliable)

  http://blog.auroracs.lk/2014/04/the-different-between-science-and.html


  Engineering is downstream from science and not used to disconfirming, its there
  to use the confirmed knowledge from science - but this primes engineers for confirmation bias

  You don't monitor the end of the production line, you monitor throughout cause the cost goes
  up as it gets closer to the end


  Synthetic Thinking:
   - The combination of ideas in to a complex whole
     - Science takes apart, but you are trying to put together
      - Your manager studied business science, and thus they fail to understand the whole
      - Understanding the humans form complex adaptive systems and are not machines
    - Seeing a broader whole a system
      - e.g. its not really doing "devops". It's a socio-technical system
    - Using multiple methods together
    - Important for expatation (innovation from innovation) and innovation

    Everything we are doing in devops was happening in coal mines in the 1940s.
      - As an industry, software doesn't understand history
      - it doesn't deep dive, it stays shallow
      - We don't research

    Synthetic thinking actually increases variance.
    3M got rid of their six-sigma

    Destroying variance, destroys serendipity

  "Art of Action" article recommendation

  Putting it all together in management:
   - Describe your intent to your teams
   - Frame boundaries of their work
   - Stop managing the tasks
   - Think from the end (me: "start with why")
   - Make sense out of the situation
   - Build a culture of experimentation
   - Give them form before they need it
   - Learn from deltas

   Teach skills before they are needed

   Cynefin - For Sensemaking (Harvard Business Review 1997)
    - Simple: Sense -> Categorize -> response [Best Practice]
    - Complex (makes sense in reverse) [Emergent Practice]
        Probe -> Sense -> Respond. Analysis is wrong
    - Chaotic [Novel Practice]: Analyze -> Sense -> Respond
    - Complicated [Good Practice]
        Sense -> Analyze -> Respond

    (http://interactioninstitute.org /blog/wp-content/import/2012/12/Collaboration-Diagram-.jpg)
    (anecdote.com)
