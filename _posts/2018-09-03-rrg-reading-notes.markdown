---
layout: post
title: "2018-09-03 RRG Notes (with commentary)"
date: 2018-09-03 19:00 -0500
categories: rrg_notes
slug: "2018-09-03_rrg_notes_with_commentary"
---


## [The Costly Coordination Mechanism of Common Knowledge](https://www.greaterwrong.com/posts/9QxnfMYccz9QRgZ5z/the-costly-coordination-mechanism-of-common-knowledge)

* What do the following three things have in common
  * Dictatorships universally seek to suppress freedom of speech and press; Enlightenment thinkers defended free speech absolutely
  * When two people wish to sleep with one another, the conversation will often move towards sex but will never get there
  * Why do so many religious rituals look the same, across communities and across religions?
* All of these three things are attempts to create *common knowledge*

### Prisoners' Dilemmas vs. Coordination Problems

* The prisoner's dilemma
  * Setup
    * Two people are in a situation where they cannot coordinate with one another
    * They may either choose to cooperate, or they may choose to defect
    * If they both cooperate, they each get a moderate payoff
    * If one defects while the other cooperates, the defector gets a high payoff while the cooperator gets a steeply negative payoff
    * If both defect, they both get a moderate negative payoff
    * Prisoners' dilemma payoff matrix:

        ```
                  Cooperate Defect
        Cooperate   3/3       4/0
        Defect      0/4       1/1
        ```

  * Examples:
    * Nuclear disarmament 
      * Both the US and Russia would prefer that they not have thousands of nuclear weapons pointed at each other
      * However, neither the US nor Russia is willing to be without nuclear weapons while the other side has nuclear weapons
      * Therefore, both the US and Russia point nuclear weapons at each other for decades
      * *Is this actually a prisoner's dilemma? I don't think Schelling would have described it as such*
    * Military spending more generally
      * No country wants to spend as much as it does on its military
      * However, any country that doesn't spend a lot on its military risks being invaded and taken over by a country that does spend a lot on its military
      * So all nations spend more than they want to on their militaries
      * *This is **so** wrong! Sometimes countries **want** to be aggressive. Sometimes countries want to establish an "international order" that benefits themselves, and overinvest in their militaries to do so. Moreover, there are many instances of countries that spend relatively little on their militaries fending of countries that have spent far more. Defense is a lot easier than offense, so you don't actually have to spend that much in order to have a defensible nation.*
      * *This works as a setup for a toy problem in economics, but not as a way of explaining actual historical events or behaviors*
    * Doping in athletics
      * Players would rather not dope
      * However, the players who dope will do better than the players who do not dope
      * So, in the absence of anti-doping enforcement, all players will dope
  * The scaled up version of the prisoners' dilemma is the *free-rider problem*
    * There is a public good that takes some amount of resources from everyone to maintain
    * Any individual who doesn't pay their share of the maintenance can do better at little cost to themselves, since they've passed on the maintenance costs to everyone around them
    * However, if no one pays their share of maintenance costs, then the shared resource collapses, leaving everyone worse off
* Coordination Problems
  * With the prisoner's dilemma in mind, let's look at a slightly different payoff matrix:

      ```
                  Cooperate   Defect
      Cooperate     3/3         0/0
      Defect        0/0         1/1
      ```

  * The important thing to note here is that defecting doesn't net a higher payoff for either side; if anyone defects, *both* lose
  * So why doesn't everyone choose `cooperate`?
  * If everyone is currently choosing `defect`, it hurts you to be the first one to choose cooperate
  * You need everyone to switch to `cooperate` at the same time, otherwise no one wins anything
  * The reason that coordination problems are difficult is because `defect`/`defect` is an equilibrium state - no party can unilaterally improve it on their own
    * That is, it's a Nash Equilibrium
* Solving problems and resolving dilemmas
  * A good way to contrast free-rider problems and coordination problems is to look at the equilibrium states in each
  * In the free rider problem `cooperate`/`cooperate` is not a Nash equilibrium - there is always an incentive for individuals to defect, so the only Nash equilibrium is `defect`/`defect`
  * In the coordination problem, there are two Nash equilibria, `cooperate`/`cooperate`, and `defect`/`defect`
    * The challenge here is getting everyone to move away from `defect`/`defect` to `cooperate`/`cooperate`
  * Free rider problems are solved by creating new incentives against defecting
    * In sports, for example, there are anti-doping regulations and enforcement bodies
    * Moreover, doping is made out to be *dishonorable*
  * Coordination problems can be solved by changing incentives, but they can also be solved by improving information flow

### Three coordination problems

* *Common knowledge* is having the confidence that someone else will act the same way that you will, even when you have exchanged a small amount of information (like a knowing look)
* With this in mind, we can look at the problems above as problems of determining common knowledge
  * Dictators and freedom of speech
    * Many people in dictatorships want a revolution that will overthrow the current government
    * However, such a revolution will only succeed if enough people join in
    * If some people start a revolt, but not enough, the result is just pointless bloodshed
    * Therefore, dictatorships suppress media, so that people won't know whether others will join them if they attempt to start a revolution
  * Uncertainty in romance
    * In romantic contexts, people often conceal their true intentions, and e.g. ask to come over on a pretext
    * Explicit rejection is a loss of status, so people put a lot of effort into plausible deniability
    * So in romance, people are attempting to move a Nash equilibrium that involves a higher level of intimacy, but *without* common knowledge
    * *Plausible deniability allows people to "sound each other out" about their intentions without making those intentions explicit*
  * Communal/religious rituals
    * Rituals are a space to create common knowledge in a community
    * Rituals create common knowledge about what is rewarded and what is punished
    * These rituals make it easier for a community to punish transgression -- there is no space for the accused to say that they didn't know that they were not supposed to do the thing that they are accused of doing
    * The reason that religion and politics are often connected is that because religion and politics are the only two things that have been reliably able to create common knowledge at scale
    * *For more on this, see [Authority](https://www.interfluidity.com/v2/6970.html) by Stephen Randy Waldman*

### Common Knowledge Production In Society At Large

* The News
  * Modern society is too large to build common knowledge by having a single room in which everyone speaks
  * So we've built certain channels of information, like the news media which we can refer to as sources of common knowledge
  * The problem is that the Internet has eroded the common-knowledge status of news outlets like the New York Times, to the detriment of everyone who wishes to establish common knowledge when discussing news events
* Advertising
  * Chwe distinguishes brands as being individual brands or social brands
  * Social brands are brands you buy because you think other people will like them
  * Examples:
    * Wine -- when you bring win to a party, the brand of wine you bring is one that you think other people will like
    * Computer software -- you want to use software that others use, so that you know that the documents you write will be compatible with other people's machines
  * Social brands will pay extra to advertise to large number of viewers at once, in order to build up that common knowledge about their product as the "standard" product that everyone uses
* Academic research
  * The use of textbooks is to create common knowledge that practitioners in the field can rely on when explaining ideas
  * If you can trust that everyone you're talking to has read the same textbooks with the same terminology, you can just start using that jargon without incurring the cost of explanation
  * This allows you to build on others' abstractions, which, in turn, makes progress much easier
* Startups
  * Startups are companies where people have a lot of common knowledge
  * One of the reasons that startups are able to innovate so much more quickly than larger companies is because they can build common knowledge more quickly
  * This is why advisors to startups emphasize thinking explicitly about culture and how to sustain that common knowledge once the company grows
  * When a company grows, there are three ways of sustaining common knowledge:
    * Name: if a company's name describes what it does, that's a very powerful way of creating common knowledge about the company, both inside and out
    * Mission statement: it's possible to predict what an organization will accomplish by what its mission statement concretely communicates
      * *Unfortunately most mission statements are completely muddled*
      * *A good mission statement is like Microsoft's original mission statement: "A computer on every desk, running Microsoft software"*
      * *A bad mission statement is like Microsoft's current mission statement: "To empower every person and organization on the planet to achieve more"* 
      * *The downside of having a good mission statement is that it leaves you vulnerable if you actually accomplish your mission -- what do you do when you've successfully put a computer on every desk, with your software? What do you do when you've successfully organized the world's information and made it universally accessible and useful? What do you do when the Mars colony is built?*
    * Values: a way of building common knowledge is to pick 4-8 core values, and then emphasize those values every day
      * *Even this can get muddled, however*
      * *The problem with using core values is that people will interpret and reinterpret those core values to mean whatever serves their current purpose*
      * *"Core values" in a corporate setting are **dangerous**; they create the **illusion** of common knowledge without actually creating common knowledge*
      * *As a result, you can end up with what looks like religious conflict, as people quote core values and their interpretation of the core values at each other, without actually solving the problems at hand -- I saw this at Amazon*

### At What Cost

* The production of common knowledge is **expensive**
* Our instincts for the cost of creating common knowledge are calibrated for groups of Dunbar's Number or less
* As a result when we have coordination failures due to lack of common knowledge, our most common reaction is exasperation, rather than understanding that the problem is difficult
* The problem is that indignation is ineffective when attempting to solve coordination problems at scale
* When trying to solve coordination problems among large groups, instead of becoming indignant, it's much more effective to study incentive structures and information flows


## [It's Not What It Looks Like](https://medium.com/@ThingMaker/its-not-what-it-looks-like-cde2c6104455)

* The representativeness heuristic is when we think that something is what it looks like
* As a society, we've slowly learned that in certain situations, using the representativeness heuristic is wrong, and that things aren't what we think they are
* The problem is that we're doing this in the form of a blacklist, rather than a whitelist
* The vast majority of the time, when representativeness causes a problem, it goes unnoticed
* Example
  * People posting party pictures on Facebook
  * Why are party pictures frowned upon?
  * Do people think that others don't drink and party on weekends?
* *Okay, so I already disagree with this post*
  * *The vast majority of the time, representativeness isn't actually a problem*
  * *Most things are actually **exactly** what they seem/feel like*
  * *If someone feels like a creep, 95% of the time, he's **actually** a creep*
  * *95% of the time, when you feel like someone is trying to cheat you, they're actually trying to cheat you*
  * *95% of the time, when you see someone posting drunk pics of themselves on Facebook, they're not a rationalist trying to cleverly countersignal, they're a dude who'll come in to work hung over on Monday, and call in sick on Friday*
  * *I get what Duncan is getting at -- that this is a coordination problem, but I disagree that it's a problem. I **don't** want to see what kind of stupid drunken escapades my friends are getting up to when they're blacked out*
  * *For me, the "other" equilibrium, where everyone is posting photos of themselves drinking and partying, is **not** a better one*
* So how does this dynamic get started?
  * Somebody posts a picture of themselves doing something really dumb while out partying
  * They get fired because of it
  * As a result, the cautious people stop posting photos of themselves partying
  * This means that the people continue to post photos of themselves partying are more likely to be unreliable workers
  * Meanwhile employers catch on to this trend and ratchet down the level of things they find objectionable, until even photos that would have been considered innocuous in the past are now considered objectionable
  * *Once again, I disagree*
    * *The problem isn't that the standards have changed, the problem is that the standards **haven't** changed*
    * *A decade ago, two decades ago, those photos would have been private -- they would not have ended up on a site where everyone could see them*
    * *As a result, the employer would never have seen nor heard about their employee's drunken weekend escapades*
    * *Today, however, thanks to Facebook, employers can and do hear about these things*
* Other examples of this dynamic
  * Parenting
    * Some bad things happen to children who are left unattended
    * The more cautious parents don't leave their kids unattended
    * So what happens is that the parents who leave their children unattended are more likely to be *actually* neglectful parents
    * This leads to an feedback loop of ever increasing standards where people are getting arrested for leaving their children alone for 5 minutes while they go get a coffee
    * *Duncan goes on and on about base rates, etc. when talking about leaving kids alone, etc. But he seems to completely **ignore** base rates when he's talking about the approbation faced by the parents*
    * *What percentage of parents who leave their kids alone while they get a coffee actually get arrested?*
  * Using shorthand from mythic and mystic traditions when teaching rationality
    * The terms are evocative and memorable
    * They point at real phenomena
    * However, because it sounds like what crazy mystics say, one has to spend half their time proving that they're not a crazy mystic
    * *Once again, this isn't a **bad** thing*
    * *If you use examples from mythic traditions, you **should** be forced to prove that you're not a crazy mystic*
    * *You **should** be forced to prove that you're using the terms in a very narrow context, and that you aren't smuggling in, via connotation or implication, the more crazy things that the terms you're using are associated with*
  * Using the "wrong" sources to defend your argument
  * Single fathers are often mistaken for pedophiles, simply because they pattern match to most people's image of pedophiles
    * *Again, while critiquing others for base rate fallacy, he's falling to base rate fallacy himself -- I know a single dad who takes his kids to the park all the time*
  * Dismissing defensive people just for being defensive
* So what can we do about the representativeness heuristic run amok?
* Split and commit
  * Split your impression
    * What if the situation is what it looks like
    * What if the situation is not what it looks like
  * Commit to a different course of action in each scenario
  * What this leads to is a culture where there is a bit more critical thinking at critical moments
  * It prevents people from waffling, saying, "We don't know the full facts so we can't do anything"
* *The problem I have with this article is that it's a non-solution to a non-problem*
  * *Non-solution:*
    * *"Split and commit" won't save you from the puritans who rush to judgement*
    * *"Split and commit" will end up being used against the person who is splitting and committing*
    * *This is especially true in the bias/harassment cases that he's pointing at -- splitting and committing in that scenario is a dangerous move, since you're admitting the possibility that the accuser is wrong*
    * *Situations where splitting and committing can be used are situations where everyone involved is a "reasonable" person, and thus splitting-and-committing isn't necessary*
    * *Situations where splitting and committing are necessary are situations where people are being unreasonable and are not willing to take your statements as being made in good faith - in such a situation, splittinga and committing cannot be used*
  * *Non-problem:*
    * *I think Duncan is drastically overestimating the failure rates involved*
    * *Like I've said above -- the vast majority of the time, things are as they seem to be -- if you think someone means you ill, they probably do, and you should listen to that instinct*
* *And the article isn't even talking about the representativeness heuristic -- it's talking about **correspondence bias***

## [Common Knowledge and Miasma](https://medium.com/@ThingMaker/common-knowledge-and-miasma-20d0076f9c8e)

### Common Knowledge

* There are 3 things that are necessary for a piece of information to be considered common knowledge
  * Everyone knows the information
  * Everyone knows that everyone knows the information
  * Everyone knows that everyone knows that everyone knows the information
* Example:
  * Dinner party with Alice, Bob, Carol and Doug
  * Alice, Bob and Doug are a trio of friends who often hang out
  * Carol is only a friend of Alice, but she's a classmate of Bob's
  * At some point in the dinner, Bob makes a risque joke
    * Alice and Doug have heard such jokes before, from hanging out with Bob
    * Carol has heard such jokes before, by being in class with Bob
  * Alice calls out Bob on the joke, even though she has never done so before
  * Alice is responding to the lack of common knowledge in the group
    * Alice, Carol and Doug all know that Bob isn't *actually* sexist
    * However, since Alice hasn't interacted with Carol before, she doesn't know what Carol knows
    * She might be thinking that when Carol didn't immediately laugh, she was forming a negative opinion of Bob
    * Thus Alice feels the need to step in and say something that's normatively good
    * Alice feels the need to show that she's not supportive of Bob when he makes a risque joke, in order to show that she believes in holding up society's broader rules
    * Bob misses this dynamic and feels hurt because he's being called out for something that he thought was okay, since neither Alice nor Carol have objected to his jokes in the past
    * Even if everyone knew that Bob isn't a sexist, Alice still might feel compelled to call out Bob
      * Alice knows that Bob isn't a sexist, but she doesn't know if Carol knows that she knows that Bob isn't a sexist
      * Without that third layer of knowledge, Alice might feel compelled to call Bob out, to ensure that Carol knows that she isn't the type of person to let sexist jokes slide
    * *Alternative scenario, which is equally plausible:*
      * *Alice was **never** okay with Bob making risque jokes*
      * *Neither was Carol*
      * *Alice played along because Bob and Doug would laugh, and she didn't want to be a spoilsport*
      * *Carol played along because she didn't want to risk the embarrassment of calling Bob out in the middle of class*
      * *The presence of Carol, who doesn't immediately laugh, gives Alice the common knowledge that Bob's conduct is unacceptable, thus giving her the courage to call Bob out*
      * *In other words, the system behaved in a normatively **good** manner, reprimanding Bob for saying things that made Alice and Carol uncomfortable*

### Miasma

* People are able to consciously track about three layers of "meta"
* However, unconsiously, they track many more
* *Miasma* is what happens when we track and respond to those higher layers of meta, unconsciously
* When we describe people reacting "for no reason", we're usually talking about miasma
* Example: Valentine's use of fake frameworks
  * Even though he blankets his presentations on fake frameworks with disclaimers, he still has people objecting to them
  * The objections often take the form of people saying that while they're okay with it, others might not be
  * *Alternative explanation: the people who are saying that they're okay with the discussion of fake frameworks are not okay with the discussion of fake frameworks*
  * *However, they know that they're dealing with someone who is presenting, and bluntly saying to them, "I think your presentation was dumb and a waste of time," might not go over well*
  * *So they couch their disagreement by referring to a nonspecific other, allowing them to register their objection without necessarily sparking an argument with the presenter*
* Miasma puts pressure on us to take preventive action, even when there might not be anything to prevent
* So how do we fight miasma?
  * Bother to notice
  * Ask yourself, am I worried about some nonspecific other, or can I name specific people who might object?
  * Then, once you've identified that you're dealing with miasma, you can determine next steps to adjust expectations or take preventive measures

### *My Thoughts*

* *I really **want** to agree with this piece, but its examples are just criminally bad*
* *Many of the examples, like Val's use of fake frameworks, or Bob's sexist jokes, are cases where I think that miasma is doing a **good** thing*
* *I object to using fake frameworks. I object to sexist jokes. I don't want to see their use become normalized or acceptable. So to me, a "miasma" that makes them unacceptable in all settings is a normative good*
* *I think Duncan is falling hard for the typical mind fallacy*

## [Unrolling Social Metacognition: Three Level of Meta Are Not Enough](https://www.greaterwrong.com/posts/K4eDzqS2rbcBDsCLZ/unrolling-social-metacognition-three-levels-of-meta-are-not)

* Conceptual Introduction By Example:
  * Alex leaves the milk out
  * Bailey observes Alex leaving the milk out and thinks it's bad
  * Alex feels judged by Bailey's observation
  * Alex reflects on being judged, doesn't like it and concludes that Bailey is a "downer"
  * *Okay, but it seems like the problem here is that Alex concludes that Bailey is a downer, instead of just putting the milk away; that's not Bailey's problem*
* Higher levels of meta
  * These higher levels of metacognition get distilled into simple judgments like "is a downer" or "is welcoming"
  * These perceptions track reality, but they are oversimplifications
* People don't usually unroll things in this way. Why?
  * People aren't aware that it makes sense to ground out meta-cognition like this
  * Requires a lot of working memory slots to do so, usually requires something like a shared Google doc or a whiteboard
* Why can't this be replaced with a simple apology
  * Sometimes you're really okay with making someone feel judged, because you really think they did something wrong
  * Saying that you're sorry might come off as a platitude
    * *What kind of a situation would have enough social trust to make this unrolling process work, but not have enough social trust to make apologies seem sincere*
* How generalizable is this unrolling technique?
  * Has been used with multiple people
  * Works even if people don't have a background in symbolic reasoning
* Relation to miasma and hype
  * "Miasma" can be viewed as negative ungrounded social metacognition
  * "Hype" can be viewed as positive ungrounded social metacognition


