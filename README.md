# Links
A project for building villages.

www.village.link

### Villages
Artificial Intelligences (AIs) are modelled on the brain. In a social species like our own, brains are organised into communities, villages. 
The village is the next-higher level of abstraction after the brain. It is the natural repository of common sense, of culture. 

AIs routinely make gaffes that would be a source of bemusement, shock, or ridicule in a village. 
Villages are reputation economies where gaffes really matter. For people, gaffes are associated with the sting of shame. 

Villages are policing norms. Individuals play a balancing act between ambition and compliance.
In doing so, individuals push against the norms, and sometimes change them. Norms evolve. 

Human brains grows to maturity inside the reputation economy of a village. 
As they do so, the brains develop constraints that guard against loss of prestige. 
AIs are not yet guarding their reputation in this way. 
They don't have the set of commonsense constraints, and they seem stupid.

This project is motivated by an attempt to:
- Address bottlenecks in AI development
- Harden human communties against highly capable, and potentially malign AIs
- Create a new toolkit for, and new ways of thinking about:
  - Identity
  - Reputation
  - Social connection
  - Connection weightings
  - Villages
    - Norms. Evolution of sets of norms
    - Village defences
    - Search. Opportunties within and between overlapping villages.

### Architecture
The project aims to build a type of agent that can:
- Store reputational information;
- Make claims about its own reputation; and,
- Check the reputational claims of others by querying its own store and the social graph.

The agents are decentralized. An entity, (like an AI, a server, or a human person,) can manage zero, one, or any number of such agents. 
In terms of the 'village' analogy for the project, the one-word description of the architechture is *gossip*.

### Bootstrap
The project envisages sets of reputational strategies that can evolve to any level of complexity. 
Thankfully, we don't have to write those complex strategies - we just have to write the backbone.

However, to bootstrap the project, it seems sensible to build and release *some* agents that work.
To do this, the project will use examples from existing reputation systems. 
Many types of these already exist, and some are in the public domain.
In using this data, the project does not have to capture every nuance of those reputation systems. 
Instead, it just needs to capture a few key 'seed' features, and make sure that the system is evolvable.
