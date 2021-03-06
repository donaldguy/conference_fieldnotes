the first DevOps Summit at Cloud Expo

#A New State of the Art for Application Development and Delivery
http://devopssummit.sys-con.com/event/session/2238

me-summary: "We should build software like planes"

 - "DevOps" is a bad name, he'll take suggestions
 - CTO of CA
 - "Software is Eating the World" -> "Business, rewritten by software"
 - Entertainment delivery industy is being differentiated by software features (DVR and mobile apps)
 - Automative industry: Tesla OTA - changed behavior of incline braking; (pic: in-dash touch and radio)
    - Cycle time Feb forums to car feature
 - Insurance: StateFarm mobile application, describing accidents
 - CVS: prescription checking mobile app prevents preventable death from mismedication
 netflix and hulu, bitcoin, airbnb
 APIs Give us Access to Critical Ecosystems We Don't Have To Build Ourselves "API economey"
 native apps beats mobile web
 consumer realm to business realm (mobile apps, software updates) IoT
 CA promo video "Business rewritten by software" ("I saw the future, the geeks were right" song)

Cycle time and speed. Months/weeks -> Days/Hours
(me: c.f. Adrian Cockcroft @ FlowCon - https://www.youtube.com/watch?v=wyWI3gLpB8o )

Seeing the big picture and seeing it quick

Software projects as early flying machines (With video (gif?))

healthcare.gov McKinsey & Co. comparison to ideal (alltechconsidered 2013/11/19)

me: "The Need for Speed!"
25% of users with abandon page after 3 seconds of load time (Dodge lost to Ford on track configuration for his son)
80%-90% of all apps are only tried 1 time
$500M cost of trading lost in Facebook IPO to 'system problems'

DevOps: How to increase the "touch time" and reduce "idle time". horizontal integration

New State of the Art Requires New Thinking From All

Development (modularity! Build Real Components of a Composite Arch):
 - Stubbing is cheating -- build realistic simulation that all can leverage
 - Good design at the interface boundaries is critical for parallel dev
 - Instrument everything - you should never run code you cannot understand post mortem,
 - Must understand the operating context - key use cases & scale requirements

Quality Engineering (You Engineer, let Machines do the work):
 - Don't test, build test engineering
 - Over-reliance on end-to-end environment shows lack of discipline
 - -ilities are as critical as the most important functional requirement
 - SLA budgeting, component performance test, ever-break discovery

Operations - (Can't say no anymore. Your Job is to Speed the Delivery of Apps)
  - Don't deploy, build employment engineering
  - Never, ever make your team wait on an environment, data scenario, scalable back end system

Key practices:
 - Implement Continuos Delivery, Dev to Prod
 - Monitor Continuously with Feedback Loop
 - Automate All Validations
 - Leverage simulation and Producer/Consumer Governance (Solve the parallel development challenge)

Eliminate Constrains with Modeling and Simulation or Virtual Services (we build planes with wind tunnels these days)
The virtual service needs to follow expected behavior change -> dependencies can be checked
"modular integration testing"

Testing is machine work. Continuous Delivery. Rollbacks need to be easy.

Complete monitoring enables Greater Operational Understanding and a Critical Feedback Loop to Dev.
If a plane goes down, you need a black box! It's a necesarry overhead.
"Instrumentation is cheap compared to the consequence of not doing it well"

Repeatable load patterns for real world testing.

http://www.slideshare.net/cainc

--------------------
# Managing Drift and Cross-Silo Collaboration, ITInvolve
http://devopssummit.sys-con.com/event/session/2315

me:The Danger of Silo-ed thinking

"Disrupted Delivery and Deployment"
 - Different Tools
 - Scattered Tools
 - People left out
: duplication and disconnection - lack of knowledge about dependencies

disambiguated in side conversations that are lost or need to be repeated

Automation and tools are duplicated/overlap across silos
me: Optimizing what doesn't work doesn't help

vs In Context Collaboration

Tools:
Aggregation
Value Stream Mapping: Goals <- requirements <- projects ("perspective")
activity stream - contextualizes communication
channel - virtual scrum

Agile stats pulled out to side

Perspectives: Gantt, Kanban, Work Type,

-----------------------
#The Essence of DevOps / Are We Doing DevOps right?
http://devopssummit.sys-con.com/event/session/2265

IT is being asked to operate on a new level
post-industrial economy
services are replacing products as main driver of value
Value is co-created between customer and service provider (not at product creation time)
Physic is merging with virtual (software is eating the world); e.g. Nest ?
Internal systems connect to external experiences
Success means responding fastr than your competitors ("speed wins")

Familiar structures and boundaries are dissolving
 - Functionality and operability are inseparable. Quality is not granular
 - Systems of record and systems engaged with customers aren't seperate

How to respond?
 - (not) new tools, new orgs, new titles, "full-stack" engineering (new recruiting)
 - empathy! (specific definition)
   : not understanding someone else's needs
   : but seeing from another's perspective - seeing one's self from another's perspective
   doctor, patient example
   Empathy bridges differences
   Empathy lubricates systems thinking
Empathy with the customer, empathy with the each other

but, but silos and segregation of duties and geographical distrubtion and outsourcing
(me: specialization?). Separation builds distrust. Gaps gan be briged

There is a reason high-quality consultants embed.

T-shaped people. Communication.

Distributed vs concentrated - security checks example.

Ethnography: term from anthropology; understanding that variant needs lead to
variant solutions by observing and learning WITHOUT judgement

SHARED tools, practices, and information CREATE (allow) empathy.
 - If everyone is using something a new shared vocabulary is built from shared experience
 - (me: if they aren't, they don't )

No "they" - "we"; no "their", "our"

"Everyone is responsible for the sucess of the customer experience" - Major Hayden

(me: SLA ideology:) moving work off your desk is not the goal - solving the problem is the goal.
Empathy builds this desire. The service experience is rewarding and reinforcing.

Good news and bad news: IT transformation is a wicked problem -> The journey is the destination.

Best practices are signposts, not destinations.

Empathy enables conversation. conversation enables adaptation.

Transforming legacy systems and practices. Leden hall building in London - cannot obscure view of other building
 - Accept heterogeneity
 - Practice continuous refactoring
 - Challenge assumed constraints and solutions!

IT-as-Design! (Anticipation + Ethnography + Creativity + ...)

"Design is empathy made tangible" - Irene Au
The biggest challenge -> we are asking people to think and behave in different ways.
"align themselves with the business"

--------------------
hand-written notes:

- [today-business-tomorrow-apps_1.jpg](https://github.com/donaldguy/conference_fieldnotes/blob/master/devops_summit_at_cloud_expo_east_2014/today-business-tomorrow-apps_1.jpg)
- [today-business-tomorrow-apps_2.png](https://github.com/donaldguy/conference_fieldnotes/blob/master/devops_summit_at_cloud_expo_east_2014/today-business-tomorrow-apps_2.jpg)

http://devopssummit.sys-con.com/event/session/2241

--------------------
# Is DevOps Really Changing How IT is Working? Panel
http://www.cloudcomputingexpo.com/event/session/2214

Moderator, Larry Carvalho, PaaS researcher (M:)

M: Can Enterprise companies really duplicate what born in the cloud companies do?

- John Willis (JW:) - Good IT performance is a predictor of making money. There are now certiain practices that have been shown to lead
to this competitive advantage

- Randy Bias , CTO of CloudScaling (RB:) - Kaiser Permanente, $35b company figuring out cloud strategy in 2009. IT leadership disappeared kp.org had 3 outages
in a month, disappeared during development. Siloing has been shown to go against the grain towards making the leap to webscale.
The goal is stability and quick recovery?

- Andi Mann, CA Technologies (AM:) - Clients have many examples of how they're doing devops. The large enterprises are unique and are going to have
to adapt patterns to make them work within their business. SEC compliance is not a concern of "webscale startups". And their freedom
from those constraints will let them eat your lunch if you can't move as fast

- Vasu Sankhavaram, HP (VS:) - Large enterprises _are_! taking this journey. I look at DevOps as a connected system. Think about it as Yin and Yang. You need
to take into account the culture, the current legacy

- Bernard Golden, ActiveState (BG:)- "They are adopting it quite rapidly." Driven by the  - "speed of cloud " is a forcing function, asking you to speed up the
rest of your process.

M: When companies are doing this, what are they doing?

BG: It's a forcing function. The impetus is companies find out they have a pretty important app working out of the cloud and
other requirements have to play catch up, which leads to a reactive process of rapid adaptation. Which is chaos

VS: Get the grassroots movement getting going. Unless there is a commonality of understanding, everything will grind to a stop

AM:. When you think of DevOps as speedy delivery, its about finding what is slowing you down and fixing it. They think stability
means no change. Removing constraints in the dev/test cycle. A different pace of change for different layers of your environment
is acceptable (?).

RB: The idealist in me wants to say "operate like the webscale guys". The pragmatist says "there exists a contract mismatch
between managing risk vs delivering value". Fidelity has rewritten their dev-contract, developers can do anything they want so
long as they use the common tools and follow the common process, to allow mixins of common policy.

JW: There is no shortcut. Enterprise wants to hear you can fake it, but you can't. FB- how did FB get to a billion users,
and its not a technology problem, its a culture problem. People say they want to be like Google or FB by doing more with less
but those companies do more with MORE. Job satisfaction being the number one indicator for IT performance.

M: How do you see continuous integration and deployment fitting in with devops?

JW: theres certain fundamentals to that flow:
  - Source control. Manage your artifacts at every step of the process. Keep track of it all and don't lose work.
  - Collaborative workflow for peer review
  - Github has been very useful for this.
  - You don't have to start at the end. its a process

RB: The ops firefighting mess was of our own creation - heterogeneity is the enemy; you can't manage that much complexity.
We need more genericisity. More homogenous and less legacy systems open up headroom to improve the situation cause you aren't
spending as much energy on maintenance. Fear of change prevents innovation. "My first job was in 1990. I was the junior sysadmin
on the team. I had taught myself unix. I learned to code and do ops at the same time, I didn't understand there was a difference.
When I started automating stuff, the older guys were pissed. They were trying to do their minimum of understood work."

AM: DevOps starts with planning. What am I doing in my business that is mission critical? What isn't? If it isn't, give it up.
(i.e. outsource it). Some of the things you are doing, you shouldn't be doing! It's taking your resources that you could use
for something else.

VS: What do you mean my these things? You need clarity. Looking at things as a value change, you can find the points for optimization.
Baselining and streamlining.

BG: There's pressure to remove the legacy - you need an exit plan. Sunset what you can, rework the core you can't. 60% can be
outsourced.

M: ms and aws claim putting things in the cloud will allow continous measurement. "What's the deal with that?" whats the toolchain

AM: automation is key to this. increasing speed of flow and making clean handoffs. Closing the feedback loop.

JW: It's git. It's Jenkins. This is the model thats driving whats on your phone - there is a reason for that. Puppet or chef,
hopefully looking to us for network configuration

RB: pets vs cattle - 9s of reliability come from assuming lack of reliability. Dragging old baggage to new game is gonna hold
you back. You have to be able to deal with failure. You need a plan

VS: communication and Collaboration tools - culture works on a virtual water cooler. frictionless tools

BG: most enterprises won't build an infrastructure from open source tools - they want off the shelf
and ready to go. 10x scaling is to be expected. You have to anticipate 10x cost for that scaling.

RB: When you were saying this, it sounded like you were saying don't be distracted by the shiny tools and focus on the culture?

JW: That's pretty much right. When I worked for PuppetLabs, people would ignore me and tell me they simply didn't need it.
there was a 3% club you could get in who had this right. Now its more like 18 or 19%. You can learn from what others do with
the tools and how the tools come to reflect that. The skillets have been commeditized

M:Do Universities have a role in moving these thought patterns into the new school? Are they still teaching the old ones?

JW. It drives me nuts that a CS student never hears about Demming and Goldratt.

VS: I think there are constructs that are being taught around business agility. I don't know how the technology side is being taught

BG: the traditional complaint is that the curricula lag the way things are. People are coming out with the idea that resources
are easy at hand - open source, off the shelf. They focus on the app - they are good customers

AM: It's tough to hire people - we aren't looking for knowledge - we are looking for ability. Skills and knowledge are taught,
not ability and attitude. Path and Snapchat made terrible assumptions because the attitudes of governace were not taught.

RB: Cynicism . In the early 90s, you couldn't learn from a university. Running production systems is totally unrelated to
anything you do in school. You aren't taught to avoid problems.

M: do you see this as complimentary to DevOps or no? Do you see it convergent?

BG: Did I mention that ActiveState is a platform as a service company? Businesses got to move faster. Somehow. PaaS for development
DevOps for deployment

VS:  Service needs to dominate logic?

AM: I'm not convinced by PaaS yet. From an Ent perspective, I see PaaS as a reaction against the intertia of an ops department
that can't satisfy the needs of development so automate it out of the way. But specialization remains a requirenment, so the
ops team need to deliver.

RB: there's a spectrum between role your own (netflix) to all of the shelf; in the middle you can embed some practices

JW: Containers. The new plastics

Audience: what would you recommend for a university program

AM: Students need an internship experience - real world experience

RB: Do it at a startup

JW: Deming

------
notes from last slide of "High Tempo, High Consequences"

top half of [devops-networks.jpg](https://github.com/donaldguy/conference_fieldnotes/blob/master/devops_summit_at_cloud_expo_east_2014/devops-networks.jpg)

------
# Alice In Wonderland - Is the Network the Next Frontier for Devops?
http://devopssummit.sys-con.com/event/session/2266

Intro
SDN opportunities
devops lesons learned
networking and devops

Stateless Networks - Webscale networking

who is JW?
ibm Mainframe Dude
Tivoli Guy
Chef/Cloud runner
Network dude??

Down the Network Rabbit Hole
 SDN is the Decoupling of Control from the Data Plane
 The network layer (2) was bad at abstraction.
   - Management Plane
   - Control Plane
   - Data Plane
  Centralizing the control plane - Openflow : SDN :: HTTP : Web
  Overlay, intelligent tunneling - VXLAN, STT, GRE

"Network Tectonics".
The world is changing for the network folks
There is a lot of work to be done
Switches are adopting linux - Arista pushed it forward. Cisco is catching up.
Cumulus will sell you software without the hardware. Bare Metal Switches (BigSwitch & Pica8)
Facebook has promised Open Compute Project

software based opportunity
Networks are becoming more open
Virtualization is a disruptor
Private clouds are driving a lot of new opportunities

Devops History Review
 - "sounds like the war is won"
 - What were the objections:
   - Bob's scripts
   - Doit 5 ... ssh'ing things
   - I don't trust this thing
   - You don't understand my application
   - You can never "ever ever ever" break my application
   - I am afraid I will lose my job
  - What changed
    - server based commodity infrastructure: Linux on x86
    - servers became ephemeral infrastructure
      - Elastic compute (East-West traffic)
      - Fast Provisioning/Ephemeral

 The Network "Early Observations"

- What were the objections:
  - Bill's scripts
  - Expect scripts / TCL
  - I don't trust this thing
  - You don't understand my network
  - You can never "ever ever ever" break my network
  - I am afraid I will lose my job

switched to paper - [devops-networks.jpg](https://github.com/donaldguy/conference_fieldnotes/blob/master/devops_summit_at_cloud_expo_east_2014/devops-networks.jpg)

--------------------
# DevOps, The Pager, and The Dawning of Continuous Support
http://devopssummit.sys-con.com/event/session/2272

Work/Life has changed:
 - Life has changed, people are now more holistic about work/life
 - The speed of internet demands 24x7 business
 - For many, a balance is not a divide between the two but harmony between them

VictorOps using continuous partial attention to resolve incidents faster
