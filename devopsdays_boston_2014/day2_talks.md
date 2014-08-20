## The Power of Conflict
 @nkatsimpras
 - poem of six blind men who went to see an elephant
 - Master of Science in Negotiation and Conflict Resolution
 - We know that we need to work with other people to be effective, but we don't end up doing it
 - "Insanity is repeating the same mistakes and expecting different results"; Attributed to Einstein, but first appears in the intro to a handbook for Narcotics Anonymous from 1980
 - Addictions to familiar solutions to complex problems?
 - Yes but ... we are experiencing a Cultural Transition Pandemic
 - Across fields, people are breaking down walls and coming together to solve problems
 - "Vertical specialization from horizontal collaboration"
 - We have negative connotations attached to the word conflict, but there is both productive and destructive conflict - every day examples of productive conflict include sports and sex.
 - We need conflict to avoid groupthink
 - Four levels of conflict in organizations:
  1. Individual vs organization
  2. Individual vs Individual
  3. Part vs Part
  4. Organization vs Organization
 - Over our life we form mental maps that drive actions: "It is these maps that guide people's actions rather than the theories they explicitly espouse"
 - We have inherent cognitive and perpetual distortions:
  - Anchoring bias
  - Fundamental Attribution error
  - Selective perception
  - Halo Effect - 1 trait of an individual is over extrapolated
  - Memory Bias
  - Hindsight Bias
 - Perceptual Biases:
  - Duplex Perception -
  - McGurk Effect - what we hear is what we see
 - Single loop learning has results effect strategy; this is the common type
 - Double loop learning has results effect assumptions (which drive strategy)
 - Deconstructive Taxonomy of conflict
  - Relative degrees of power
  - Type of dependence (cooperative to competitive)
  - Degree of dependence
 - Conflict Intelligence: Nelson Mandela demonstrated immense adaptivity in styles of handling conflict for large effectiveness
 - Such adaptivity derives from the transformational power of reflection
 - Back to Tech: Conflict at Github was much more of a news story than the same type of thing happening in finance
  - There was an understanding of a different psychological contract:
    - Appreciation of Individual contribution
    - Effective Utilization of Skills
    - Lifelong learning - Personal Development
 - Intrinsic motivation and Drive (Daniel Pink 2009 TED talk)
   - Autonomy
   - Mastery
   - Purpose
 - Two types of intrinsic motivation
  - Promotional
  - Preventative
 - Superordinate identity
 - Institutionalization of systems thinking is effective, if tailored to the particular case of the organization
 - Making an institutional culture is a participatory action
 - "Devops are bridge-builders..." ~DeBois
 - "... and network weavers" ~@nkatsimpras
    - Mediation
    - Facilitation
    - Conflict Intelligence
    - EQ
 - Exercise 1: Nonlinear causation, feedback mapping
 - Exercise 2: 6x iteration prisoners dilemma
 - []
 - Takeaways:
  - Each one of you is touching a different part of the elephant
  - More than developers or operators, you are mediators and me

## Intro to CoreOS: Get Ahead of The Curve, New Ways to Deploy and Manage Applications at Scale
Kelsey Hightower (@kelseyhightower)

Note: I think I've seen this demo several times now, so I am only really gonna take notes if something strikes my fancy as new and exciting. Sorry

- devops is like the biggest group therapy session ever
- computers have driven us so crazy we think the problem is each other
- CoreOS hopes to ease that pain by letting you go back to focusing on the application
- CoreOS goals include Secure the internet

## Metrics Driven Development
@davejosephsen

 - Librato is a distributed team and chatops shop
 - Chat:
  - errors errors erros
  - "I'm putting some graph in the war room"
 - At first glance the graphs look like wild goose chase, but its actually a process of very solid human intuition and thought
 - People want to think in terms of flow charts and tagging them with questions about whats wrong and what to do
 - Once you do this, graphs fill in the answers to those questions
 - Data leads to questions leads to data in a tight feedback loop

 - "In turns out that at Librato, monitoring isn't really a thing anymore ... its inherent to the development process"

 - Don't Measure Everything: "Interesting metrics prove systems hypotheses"

 - MDD unlike TDD continues to test the code in production, continuously
 - Instrumentation is not debugging, its part of the production code, in perpetuity.

 - Telemetry data needs a single source of truth, that is easy to get to

 - Instrumentation as code
 - Alert on what you see

## Running Graphite at Scale

TL;DR Stock Graphite is hard to manage and scales poorly - they ripped out the backing store and replaced it with Cassandra
