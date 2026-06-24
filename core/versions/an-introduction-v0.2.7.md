# Universal Cake -- An Introduction

Version: 0.2.6
Status: Draft
Style Guide: style-guide--plain-language-for-general-audiences-v0.2.0

## Abstract

This document introduces Universal Cake, a framework for thinking about technology in human terms. It explains where the idea came from, what the name means, and how it can help anyone — technical or not — ask better questions about the tools they use every day.

## Inspirations

Universal Cake began in 1999 as a personal checklist. Christopher Steel was looking for web software and wrote down the questions that mattered to him: Does it come in my language? Does it work on my system? Does it work in the browsers my users have? Is it accessible to people with disabilities? Is it supported? Is it maintained? Does it have the qualities needed for longevity? Is it worth investing in? That list was not borrowed from anywhere. It came from experience — from working with real people using the technology available at the time.

Over time, the questions on that checklist changed with the times — with the advent of better approaches to browser compatibility and the rest of the evolving technology landscape. The list adapted and changed and today has become more of a framework, or perhaps even a praxis. Christopher also encountered others who had been asking similar probing questions from their own directions. Some he was not even aware of until recently, but it has become clear that a lot of parallel thinking has emerged since that initial list was developed, and some prior work that he was not aware of reflects his own work in refining his list into something kind of special.

For example, <a name="apa-meadows-citation"></a>[Meadows (2008)](#apa-meadows-reference) and her book *Thinking in Systems* was a recent and satisfying discovery: the idea that healthy systems are made of interdependent parts that support one another maps well with the recipe required to create Universal Cake. The manuscript behind that book was written in 1993 and circulated informally for years before publication, meaning Meadows had already been working through similar ideas regarding systems thinking for years by the time Christopher made his first one-page checklist. A researcher had mentioned that Christopher might be interested in her work sometime in the late 2010s. When he encountered her work again doing research in 2026, he took a deeper dive and discovered that the researcher was right — her ideas had a lot in common with his approach to creating Universal Cake.

The human inspiration behind Universal Cake is wide and does not fit neatly into a reference list. It spans disability rights work — including the research of <a name="apa-treviranus-citation"></a>[Jutta Treviranus at OCAD University](#apa-treviranus-reference), the ground-breaking real-world integration of inclusion by [Catherine Roy, Accessibility Advisor for the McGill University Equity Team](https://www.mcgill.ca/equity/catherine-roy), and the advocacy of organisations such as <a name="apa-rapliq-citation"></a>[RAPLIQ](#apa-rapliq-reference) and [Vie Autonome Montréal](https://va-m.org/) — alongside philosophy, systems thinking, trauma-informed practices, and personal resilience. People like Alex Limi and the Plone community, Hugh Gallagher, Massimo Di Pierro, bell hooks, Donella Meadows, Pema Chödrön, Ed Roberts, Michael DeHaan, and many others have all shaped how Christopher thinks about people, systems, and what it means to build something that serves rather than excludes. Technology does not exist apart from these questions. It is shaped by them, and shapes them in return.

The plain language principles used in this document follow the <a name="apa-plain-language-citation"></a>[Plain Language Action and Information Network (2011)](#apa-plain-language-reference).

## 1. Where it all started

In 1999, Christopher Steel needed to choose web software for a community that included people with disabilities, people who did not read or write English, and people using whatever hardware they had. He wrote down the questions that mattered. That list needed a name — something that would help him think clearly about what was on it and what the priorities were.

The name came from an unlikely place. A few years earlier, Christopher and some artist friends had started a communications company. They came up with the name Universal Cake, designed an actual box for the product, and then could never quite figure out what should go in it. The company did not survive. The name did. It fit the list perfectly, and the rest is history.

Accessibility moved to the top of that list not as a political statement but as a logical one. If the software did not work in your language, or on your system, or for your users, then nothing else on the list mattered. Speed, stability, and sustainability were all important — but they were downstream of access. Without the door, the rest of the house is irrelevant.

Evaluating the options against the list, Christopher found Plone. It was not finished. But its commitments were clear: multilingual, open source, web-editable, with accessibility treated as a first-class concern rather than an afterthought. He chose it, and he waited for it to mature. That turned out to be a good investment. Plone is still here. Most of the software that competed with it in 1999 and 2000 is not. The list worked.

Plone's ambitions at the time seemed outrageous to many. No one had done this at scale in open source before — a web-based editor that anyone could use without technical training, in over fifty languages, built from the ground up with accessibility as a first-class concern rather than a feature added later. Out-of-the-box Plone installations in the early 2000s were documented as meeting WCAG 1.0 AAA — the highest level under the standard in force at the time — making Plone one of the very few mainstream content management systems to claim that distinction.

WCAG 1.0 AAA meant satisfying all Priority 1, 2, and 3 checkpoints, which was achievable for a well-built default theme in that era. When WCAG 2.0 arrived in 2008 with a substantially revised structure and more rigorous requirements, the bar changed — but Plone's commitment did not.

Plone's design went on to influence Wikipedia's MonoBook skin, which was the default face of the world's largest encyclopedia for six years. The organisations that eventually adopted Plone — the United Nations, the FBI, and governments on multiple continents — had exactly the same requirements as that original checklist. They needed systems that worked across languages, across abilities, and across decades. The list was not unusual. It was just an honest assessment of the real-world human needs and requirements that all humans have for technology that serves them.

## 2. What the name means

The word *universal* describes the goal: technology that works for the widest possible range of people, languages, abilities, devices, and circumstances. Not technology designed for what is wrongly described as the comfortable 80% at the centre of the bell curve, but technology that keeps asking, in the words of <a name="apa-treviranus-bell-curve-citation"></a>[Treviranus (2019)](#apa-treviranus-bell-curve-reference), "who are we missing?" — and works hard to find the real answer.

<a name="apa-treviranus-bell-curve-citation-2"></a>[Treviranus (2019)](#apa-treviranus-bell-curve-reference) argues that the conventional reading of Pareto tells developers and designers to serve the easy 80% and ignore the "difficult 20%" at the margins. This is both a misreading of Pareto and a disaster.

Treviranus points out that the people at the margins — the vital few — actually cover 80% of the knowledge terrain. Designing for them does not cost you. It repays you in knowledge and understanding, and in systems that reach the edges of human diversity.

This is the very space in which innovation, resiliency, and significantly better systems that serve the real population are born. The dynamic that results from this commitment — a continuous, iterative process of asking who we are missing and expanding inclusive design practices to reach them — creates systems, like Plone, that grow stronger and more capable with each cycle. Treviranus describes this as the Virtuous Tornado.

Christopher, and many others, were working with similar intuitions in 1999 and before — but Treviranus put a highly descriptive name on the process. The convergence is not a coincidence. It is what happens when people think honestly about similar problems.

### 2.1 The 80/20 rule is not a law — and it was never about you

It is worth pausing on the 80/20 rule, because it has done enormous damage in the name of common sense — most especially in the field of software development.

Vilfredo Pareto was an Italian economist working in the 1890s. His original observation was specific: approximately 80% of Italy's land was owned by 20% of its population <a name="apa-pareto-citation"></a>([as cited in Wikipedia, 2024](#apa-pareto-reference)). Ironically, as <a name="apa-treviranus-bell-curve-citation-3"></a>[Treviranus (2019)](#apa-treviranus-bell-curve-reference) notes, Pareto had nothing to do with the development of the term that would come to bear his name. Literally nothing at all.

Pareto's observation was about wealth concentration in one country at one moment in history. It was not a universal law of nature. It was not a design principle. It was not an instruction or a rule.

Yet it inadvertently became all three to many of the individuals responsible for creating the code that runs many of the services we rely on. Applied to technology design, the 80/20 rule became a licence to ignore anyone who was not already well-served — to treat a comfortable majority as the only audience worth building for, and to call that efficiency.

The problem is that the 80% the principle describes was never the world's 80%. It was the 80% of a very specific and very narrow market — usually English-speaking, with high bandwidth, in possession of recent hardware, and already considered included.

The numbers tell a different story. Around 380 million people speak English as their native language — roughly 5% of the world's population <a name="apa-ethnologue-citation"></a>([Eberhard et al., 2024](#apa-eberhard-reference)). Even including everyone who speaks English as a second language, more than 4 in 5 people in the world do not understand English — yet 54% of websites worldwide are in English <a name="apa-statista-citation"></a>([Statista, 2024](#apa-statista-reference)). The technology industry did not design for 80% of the world. It designed for a small minority of it, gave that minority a name — "the majority" — and then applied a rule about Italian land ownership to justify ignoring everyone else.

There are 7,170 living languages in the world. Roughly 44% are now endangered, often with fewer than 1,000 users remaining <a name="apa-ethnologue-citation-2"></a>([Eberhard et al., 2024](#apa-eberhard-reference)). Every one of those languages represents a community of people, a way of understanding the world, a body of knowledge that exists nowhere else. The 80/20 rule, as applied to technology, has nothing to say about any of them. It cannot even see them.

The idea of having a target market is not wrong in every context. Applied carefully, within a clearly defined and honestly described market, it can be a useful tool for prioritisation. But it requires honesty about who that market actually is — and who it is not. When the target market is "English speakers on modern hardware with fast internet connections," the rule describes that market. It says nothing about humanity.

Universal Cake does not pretend the 80/20 rule does not exist. It insists on asking: 80% of whom, exactly? And what happens if we leave out everyone else? Is this efficiency? Is this helpful? Is this sustainable? Is this a good investment?

### 2.2 When every product ignores the same 20%, the same people lose everything

There is a second problem with the 80/20 rule that is harder to see but more damaging in practice. It is not just that any one product ignores 20% of its potential users. It is what happens when every product does this independently, each to its own version of the "majority."

Consider a person who speaks a minority language, lives in a low-income household, uses older hardware, has low or intermittent bandwidth, and has a visual impairment. Each of these characteristics places them outside the target market of a different set of products and services. The banking app is designed for smartphone users on current hardware. The government portal is available only in the dominant language. The healthcare platform requires a screen resolution the older device cannot produce. The job search tool assumes broadband speeds that are not available in the neighbourhood. Each product, in isolation, made a reasonable-sounding decision to serve its majority. But the cumulative effect on this one person is not a 20% reduction in access. It is near-total exclusion from the digital infrastructure on which modern life increasingly depends.

Researchers call this **compounded digital exclusion** — the phenomenon in which digital inequalities do not operate along independent axes of division, but overlap, interlink and interact, producing outcomes far more severe than any single exclusion would suggest <a name="apa-zheng-citation"></a>([Zheng & Walsham, 2021](#apa-zheng-reference)). When the 80/20 rule is applied independently across thousands of products and services, each drawing its target market from roughly the same centre of the bell curve, the people at the edges are not excluded from one thing. They are excluded from most things. The exclusions stack.

This is not a marginal problem. The people most likely to be at the edges of multiple target markets simultaneously are also the people who most depend on technology for access to vital services — healthcare, education, employment, government, banking, communication. The 80/20 rule, applied at scale across an entire technology ecosystem, does not produce a world where 80% of people are well-served and 20% are somewhat underserved. It produces a world where the same people are comprehensively excluded from nearly everything, while the comfortable centre is served by an abundance of competing options.

### 2.3 The edge — cost, capacity, and the price of ignoring both

There is a story from community organising that illustrates this clearly. Christopher once canvassed door to door for an environmental organisation. When the question came up of how to handle donors who already gave to other environmental groups — competitors, in the conventional sense — the answer from organiser Kevin Kintner was not what most organisations would have given.

Other groups talked about dividing the pie fairly — how to share a fixed pool of donors between organisations working in the same movement. Kintner's answer was different. The goal, he argued, was not to divide the pie. It was to make it bigger. When a canvasser encountered someone who already gave to another environmental organisation, the right response was to thank them — genuinely — for supporting the movement, and then to talk honestly about what this organisation did, how it worked, and what made it distinct. No competition. No zero-sum thinking. Just more information, more choice, and more trust.

The result was that donors could discover which organisations most closely matched their own values and commitments. Some gave to multiple groups. Some switched. Some increased their giving overall. The movement grew because the approach expanded the number of people who saw themselves as participants rather than simply harvesting the ones who already did.

This is exactly what <a name="apa-march-citation"></a>[March (1991)](#apa-march-reference) describes as the difference between exploitation and exploration — and what <a name="apa-putnam-citation"></a>[Putnam (2000)](#apa-putnam-reference) identifies as the distinction between bonding capital, strengthening existing relationships, and bridging capital, building new ones across social boundaries. The organisations that only work the known turf eventually run out of it. The ones that invest in the edges — in people not yet engaged — are the ones that grow.

The same pattern appears in ecology. An **ecotone** is the transitional zone between two ecosystems — the place where forest meets meadow, where river meets land. <a name="apa-odum-citation"></a>[Odum (1953)](#apa-odum-reference) first described what he called the edge effect: increased species richness and abundance in boundary regions, along with the presence of species found nowhere else. Species living in ecotones are constantly adapting to the dynamic conditions of life in the in-between — which makes them especially resilient to change. The comfortable centre of any ecosystem is well-served and well-optimised. It is also the most fragile. The edges have been asked to cope. They have developed capabilities the centre never needed.

One of the more unexpected confirmations of this idea in human intellectual life comes from the economist Thorstein Veblen. In 1919, <a name="apa-veblen-citation"></a>[Veblen (1919)](#apa-veblen-reference) attempted to understand why Jewish thinkers had made such disproportionate contributions to European intellectual life. His argument was not about inherent characteristics. It was about position — what he called hyphenate status: living simultaneously between two communities, belonging fully to neither. That position, he argued, produced a particular quality of critical and creative thought — the capacity to see from outside what those fully inside cannot question. His research did not fully succeed on its own terms and the essay has been largely set aside. But the core observation has not aged badly. It is the ecotone argument applied to human minds.

The research on human edge communities, however, runs in two directions simultaneously — and the honest version of this argument must hold both.

<a name="apa-meyer-citation"></a>[Meyer (2003)](#apa-meyer-reference) formalized what is now known as the minority stress model: the chronic, socially-based stress experienced by marginalized groups through stigma, discrimination, and exclusion produces measurable, serious, and well-documented health disparities. Historically marginalized populations incur a higher risk of developing chronic diseases across the course of life, with emerging evidence showing that the biopsychosocial effects of social stress shape rates of biological aging through the inflammatory process <a name="apa-brown-citation"></a>([Brown et al., 2020](#apa-brown-reference)). Living at the edge, under conditions of exclusion, makes people sick. That is not metaphor. It is measurable physiology.

The economic costs are equally well documented. <a name="apa-buckup-citation"></a>[Buckup (2009)](#apa-buckup-reference) for the International Labour Organization calculated that economic losses related to the exclusion of persons with disabilities from the labour force are large and measurable, ranging from between 3 and 7 per cent of GDP. Critically, people with disabilities are less productive not because they are "disabled" but because they live and work in environments that are "disabling." The cost is not in the people. It is in the systems that exclude them. Beyond the direct economic losses, the social and political costs compound: exclusion narrows the range of voices shaping decisions, concentrates power in the centre, and produces systems that serve an ever-smaller slice of the population while accumulating the costs of everyone left out.

And yet — resilience is not merely the absence of dysfunction following adversity, but rather an engagement with life that promotes personal growth and a deeper understanding of oneself and others. <a name="apa-tedeschi-citation"></a>[Tedeschi and Calhoun (1996)](#apa-tedeschi-reference) identified what they called post-traumatic growth: the positive psychological changes that can emerge from the struggle with significant adversity — new understandings of self and world, stronger relationships, heightened appreciation for life, and capabilities that would never have developed without the challenge. Research on multicultural experience confirms a related pattern: people who have had to navigate between worlds develop greater idea receptiveness and creative potential than those who have inhabited only one <a name="apa-leung-citation"></a>([Leung & Chiu, 2010](#apa-leung-reference)). Edge communities develop these capacities out of necessity. They learn to adapt, to read systems from the outside, to find solutions in the gaps between what was designed for them and what they actually need.

This is not a reason to celebrate exclusion or to treat suffering as a productive condition. There is a real danger in pointing to the resilience and creativity of edge communities without acknowledging what produced them — and without taking responsibility for changing the conditions that make those qualities necessary. The growth is real. The harm that preceded it was not inevitable or acceptable.

The science of fish stress offers one of the clearest illustrations of why systemic conditions matter — and why they are so difficult to address through conventional legal and regulatory frameworks. <a name="apa-sindermann-citation"></a>[Sindermann (1996)](#apa-sindermann-reference) documented how environmental stressors — pollution, overcrowding, temperature change, habitat degradation — do not kill fish directly. They compromise immune function. They weaken the animal's capacity to resist what it would otherwise survive. The fish then dies — officially of a pathogen, a parasite, or an infection that a healthy fish would have fought off without difficulty. The pollution did not kill the fish. It set up the conditions in which something else could.

This creates a profound problem for environmental law. Environmental claimants face an enormous burden in establishing both that a defendant's pollution is capable of causing the alleged injury, and that it was a substantial contributor in this particular case <a name="apa-harvard-law-citation"></a>([Harvard Law Review, 2015](#apa-harvard-law-reference)). You can sue the company that dumped the toxins. You cannot easily prove that those toxins — rather than the pathogen that delivered the final blow — caused the population to fail. The legal system requires a proximate cause. Living systems do not work that way. Cumulative stress creates conditions. Something opportunistic exploits them. The thing that set up the conditions walks free.

The same logic runs in the opposite direction — and this is where the analogy becomes something more than ecological. If you cannot point to the specific pollutant that killed the fish, you equally cannot point to the specific intervention that saved it. Wellbeing — in fish, in humans, in communities — is not produced by a single input. B12 supports stress resilience, but it does not clean the water. A change in socioeconomic status may eventually reduce chronic stress, but the transition itself introduces new pressures, and the benefits, if they come at all, are slow and diffuse. Even a dramatic improvement in circumstances does not immediately produce wellbeing, because the body and mind have been calibrated to a harder world, and recalibration takes time.

What improves wellbeing is what improves the fish: cleaner water, sustained across time, across the whole system. Not one intervention. Not one policy. Not one feature added to one product. The cumulative quality of all the conditions in which a life is lived — the relationships with body, mind, and world that either support or degrade the capacity to flourish. This is slow, systemic, unglamorous work. It does not produce a single attributable cause of improvement any more than pollution produces a single attributable cause of harm. But it is the only kind of work that actually changes the conditions rather than managing the symptoms.

This is what Universal Cake is asking for. Not a feature. Not a fix. A sustained commitment to cleaning the water.

### 2.4 Therefore...

Universal Cake asks designers, developers, and decision-makers to hold this full picture in mind — not just the target market for a particular product, but the full picture, including the cumulative effect of all the target markets together on the people who fall outside most of them.

The word *cake* describes something everyone loves. A cake is made of ingredients. No single ingredient makes a cake — it takes all of them, in the right relationship with one another, to produce something delicious and well worth eating. Universal Cake uses this image to describe how good technology is created: not as a single feature or a single metric, but as many qualities working together. Those qualities include accessibility, sustainability, transparency, resilience, and human well-being. Leave one out entirely and what you have is at the minimum diminished — and possibly inedible.

Marshall McLuhan argued that every technology is an extension of the human nervous system — a way of reaching further, sensing more, acting beyond the limits of the body alone <a name="apa-mcluhan-citation"></a>([McLuhan, 1964](#apa-mcluhan-reference)). Universal Cake takes that seriously. If technology extends what humans can do and experience, then the question of who gets to be extended — and who gets cut off — is not a technical question. It is a human one. And it has always been.

## 3. The core idea

Technology is not neutral. Every tool reflects the choices made by its owners, designers, and developers. Those choices affect who can use it, how long it lasts, who controls it, and the effects it has on the world around us.

Wellbeing is not a feature. It is a state that emerges from the quality of our relationships — with our bodies, with our minds, and with the people, technology, and world around us. It is reflective of all our relationships with our environment and is also part of that environment. These three vital relationships are not separate. They reinforce one another, or they undermine one another. That is just how it works.

Technology that respects one while degrading another is not a neutral trade-off. It has consequences that ripple outward in ways that are not immediately visible — unlike a feature list or a benchmark score.

Universal Cake proposes a simple shift: stop asking only "does it work?" and start asking "does it work in a way that supports the humans who depend upon it? Does it increase or decrease their ability to understand, to participate, to stay well, and to retain agency when it comes to their own lives and communities?" That question does not involve a single relationship. It has multiple layers — and attending to all of them, consistently, over time, is what Universal Cake is about.

This shift changes everything. A note-taking app is no longer just fast or slow. It is also asking: can my investment in note-taking be kept if the company that produced my application shuts down, changes owners, or changes the rules of access? Can I share my notes with my entire community if I choose to? Can my blind friends use a screen reader to read them? Will my notes be readable in ten years? Are the notifications designed to respect my attention or exploit it? These are not technical questions. They are very human ones — and they always matter more than the technical ones. Applications and data designed to endure are a sound investment, and the expected return on the hard work invested in building a personal knowledge base and relationships within a community.

## 4. What Universal Cake evaluates

Universal Cake can be applied to almost any technology — software, hardware, infrastructure, documentation systems, or communication platforms. It evaluates them across a set of human-centered dimensions and needs rather than purely technical ones. No technology will ever score perfectly across all of them. The goal is not perfection. The goal is honest, balanced evaluation — and a growing commitment to doing better by serving better.

**Accessibility** asks whether people can actually use the system — including people who communicate in a different language, people living with disabilities, people using older hardware, people with slow internet connections, and people who communicate in non-verbal languages. Accessibility also asks whether individuals and their communities can afford the application or service over time. This is not a feature to add later. This is the door to the house, and the introduction to everything inside it. Without it, nothing else on the list matters.

**Sustainability** asks whether the system can last. This includes environmental costs like energy use, but also human costs: does it burn out the people who maintain it? Does it require constant expensive upgrades? Does it serve the individuals and organisations that depend on it, or does it slowly reduce their agency and consume their resources — offering only short-term returns that can be exploited through vendor lock-in, or disrupted by an external actor who, for economic, political, or social reasons, decides to change the rules of engagement?

**Interoperability** asks whether your data can move freely and whether you can continue using your application or service on different devices. Can you take your work elsewhere if you need to? Does the system use open standards that other tools can read, or does it lock you in — quietly, incrementally — until you have invested so many resources that switching becomes too costly to consider?

**Transparency** asks whether you can understand what the system is doing and what the agreement with the product or service provider actually is. Can you inspect it? Can you audit it? Or is it a black box that you simply have to trust — and that trusts you with nothing in return?

**Resilience** asks whether the system, and the data within it, can survive disruption — a company closing, an internet outage, a change in the legal or political environment. Are you still able to access the resources you have created when things go wrong? Can the people who depend on the product or service keep going without an additional, significant investment?

**Human well-being** asks how the product or service affects the individuals who make use of it. Does it reduce or increase their stress? Does it support their healthy habits or undermine them? Does it respect the limited resource of human attention, or does it leverage and extract from it?

**Knowledge preservation** asks whether the information stored in the system will remain readable in the future. Will your files still open and be readable in twenty years? Does the system depend on a proprietary format that could disappear, be transformed, or take everything stored in it along with it?

## 5. Why this matters now

Most technology today is evaluated on a short list of criteria: speed, features, price, and popularity. These are not bad criteria. But they are incomplete. They describe what a tool can do right now. They say almost nothing about how it affects the users who adopt it wholeheartedly — how it affects them as they invest their work in supporting or complying with that system, and how it affects them as individual and highly diverse human beings.

Rarely do we ask who gets excluded and what effects that exclusion has on social, economic, and political life. We do not ask what happens when the company behind the tool changes direction, gets acquired, or closes. We do not ask what the tool does to the attention and mental health of the people who use it every day. We do not ask whether the investment in knowledge stored in it will survive the next decade. We do not ask whether the people who maintain it will still be standing in five years — and we rarely consider the naturally occurring events that could have historically devastating effects, such as solar flares or Carrington-scale events.

The short list optimises for the centre of the bell curve and calls it good enough. Universal Cake does not reject the short list. But it does attempt to prioritise it and place it within the context of the real world — the world in which humans, our communities, and our natural resources are found, the same world in which technology operates.

First among that context is language — human languages and dialects in all of their varieties, because without language nothing else can be communicated, preserved, or passed on. Beyond human language sits the vast and largely unrecognised communication of the myriad creatures with whom we share this planet — systems of meaning that predate human technology by hundreds of millions of years. The short list was written for one kind of person, in one kind of place, under one set of conditions. Universal Cake asks what happens when you take seriously the full scale of life on earth — and what our responsibility is to design with that scale in mind, rather than in spite of it.

## 6. Who Universal Cake is for

Universal Cake is for anyone who uses technology and wants to make better choices about it. That includes individuals choosing a note-taking app, organisations selecting infrastructure, educators building learning environments, and governments procuring public systems.

It is also for builders. Developers, designers, and architects who want to think more carefully about what they are creating, who it serves — and who it leaves behind.

The framework does not require technical expertise to use. Its most important questions are human ones. And human questions belong to everyone.

## 7. How to use Universal Cake

The simplest way to use Universal Cake is to ask the guiding questions whenever you are evaluating a tool or building a system. Start with language — can people use this in their own language? — and work outward from there.

- Who can use this? Who cannot?
- Does it work in the languages of the people who need it?
- Will this still work in ten years?
- Can I take my data with me if I leave?
- Can I understand what this system is doing?
- Does this system support or undermine the wellbeing of the people who use and depend on it for access to vital and less vital services?
- What happens if the organisation behind it disappears?
- Does it work for people with different abilities, languages, and devices?
- Who is still being left out?

These questions do not always have easy answers. But asking them changes the conversation. They shift the focus from "what can this do?" to "what does this do to people, and to the world they share?" That shift — from capability to consequence, from the centre of the bell curve to its edges, from the short list to the full picture — is the heart of Universal Cake. It is also, it turns out, just good design.

## Resources

### Universal Cake

- [Christopher Steel — Personal Mission Statement](#apa-steel-mission-reference)

### Systems thinking

- [Thinking in Systems](#apa-meadows-reference)

### Inclusive design

- [Inclusive Design: The Bell Curve, the Starburst and the Virtuous Tornado](#apa-treviranus-bell-curve-reference)
- [Inclusive Design Research Centre — Jutta Treviranus](#apa-treviranus-reference)
- [RAPLIQ](#apa-rapliq-reference)

### Technology and human extension

- [Understanding Media: The Extensions of Man](#apa-mcluhan-reference)

### Digital exclusion and compounded inequality

- [Inequality of what? An intersectional approach to digital inequality](#apa-zheng-reference)
- [The Price of Exclusion — ILO](#apa-buckup-reference)

### Edge communities, resilience, and post-traumatic growth

- [Exploration and exploitation in organizational learning](#apa-march-reference)
- [Bowling Alone](#apa-putnam-reference)
- [Fundamentals of Ecology](#apa-odum-reference)
- [The Intellectual Pre-eminence of Jews in Modern Europe](#apa-veblen-reference)
- [Minority stress model](#apa-meyer-reference)
- [Post-traumatic growth inventory](#apa-tedeschi-reference)
- [Multicultural experience and creativity](#apa-leung-reference)

### Stress, living systems, and the causation problem

- [Ocean Pollution: Effects on Living Resources and Humans](#apa-sindermann-reference)
- [Causation in Environmental Law](#apa-harvard-law-reference)

### Language diversity

- [Ethnologue: Languages of the World](#apa-eberhard-reference)

### Plain language

- [Federal Plain Language Guidelines](#apa-plain-language-reference)

## References

<a name="apa-brown-reference"></a>Brown, L. L., Mitchell, U. A., & Ailshire, J. A. (2020). Disentangling the stress process: Race/ethnic differences in the exposure and appraisal of chronic stressors among older adults. *Journals of Gerontology: Series B*, *75*(3), 650–660. https://doi.org/10.1093/geronb/gby072
[Return to citation](#apa-brown-citation)

<a name="apa-buckup-reference"></a>Buckup, S. (2009). *The price of exclusion: The economic consequences of excluding people with disabilities from the world of work* (Employment Working Paper No. 43). International Labour Organization. https://www.ilo.org/publications/price-exclusion-executive-summary-economic-consequences-excluding-people
[Return to citation](#apa-buckup-citation)

<a name="apa-eberhard-reference"></a>Eberhard, D. M., Simons, G. F., & Fennig, C. D. (Eds.). (2024). *Ethnologue: Languages of the world* (27th ed.). SIL International. https://www.ethnologue.com
[Return to citation](#apa-ethnologue-citation)

<a name="apa-harvard-law-reference"></a>Harvard Law Review. (2015). Causation in environmental law: Lessons from toxic torts. *Harvard Law Review*, *128*(7), 2256–2277. https://harvardlawreview.org/print/vol-128/causation-in-environmental-law/
[Return to citation](#apa-harvard-law-citation)

<a name="apa-leung-reference"></a>Leung, A. K. Y., & Chiu, C. Y. (2010). Multicultural experience, idea receptiveness, and creativity. *Journal of Cross-Cultural Psychology*, *41*(5–6), 723–741. https://doi.org/10.1177/0022022110361707
[Return to citation](#apa-leung-citation)

<a name="apa-march-reference"></a>March, J. G. (1991). Exploration and exploitation in organizational learning. *Organization Science*, *2*(1), 71–87. https://doi.org/10.1287/orsc.2.1.71
[Return to citation](#apa-march-citation)

<a name="apa-mcluhan-reference"></a>McLuhan, M. (1964). *Understanding media: The extensions of man*. McGraw-Hill.
[Return to citation](#apa-mcluhan-citation)

<a name="apa-meadows-reference"></a>Meadows, D. H. (2008). *Thinking in systems: A primer* (D. Wright, Ed.). Chelsea Green Publishing. (Original manuscript completed 1993.)
[Return to citation](#apa-meadows-citation)

<a name="apa-meyer-reference"></a>Meyer, I. H. (2003). Prejudice, social stress, and mental health in lesbian, gay, and bisexual populations: Conceptual issues and research evidence. *Psychological Bulletin*, *129*(5), 674–697. https://doi.org/10.1037/0033-2909.129.5.674
[Return to citation](#apa-meyer-citation)

<a name="apa-odum-reference"></a>Odum, E. P. (1953). *Fundamentals of ecology*. Saunders.
[Return to citation](#apa-odum-citation)

<a name="apa-pareto-reference"></a>Pareto principle. (2024). In *Wikipedia*. https://en.wikipedia.org/wiki/Pareto_principle
[Return to citation](#apa-pareto-citation)

<a name="apa-plain-language-reference"></a>Plain Language Action and Information Network. (2011). *Federal plain language guidelines*. United States Government. https://www.plainlanguage.gov/guidelines/
[Return to citation](#apa-plain-language-citation)

<a name="apa-putnam-reference"></a>Putnam, R. D. (2000). *Bowling alone: The collapse and revival of American community*. Simon & Schuster.
[Return to citation](#apa-putnam-citation)

<a name="apa-rapliq-reference"></a>RAPLIQ. (2025). *Regroupement des activistes pour l'inclusion au Québec*. https://www.rapliq.org/
[Return to citation](#apa-rapliq-citation)

<a name="apa-sindermann-reference"></a>Sindermann, C. J. (1996). *Ocean pollution: Effects on living resources and humans*. CRC Press.
[Return to citation](#apa-sindermann-citation)

<a name="apa-statista-reference"></a>Statista. (2024). *The most spoken languages: On the internet and in real life*. https://www.statista.com/chart/26884/most-spoken-languages-online-offline/
[Return to citation](#apa-statista-citation)

<a name="apa-steel-mission-reference"></a>Steel, C. (2026). *Christopher Steel — Personal mission statement* (v0.2.0). Unpublished manuscript.
[Return to citation](#apa-steel-mission-citation)

<a name="apa-tedeschi-reference"></a>Tedeschi, R. G., & Calhoun, L. G. (1996). The posttraumatic growth inventory: Measuring the positive legacy of trauma. *Journal of Traumatic Stress*, *9*(3), 455–471. https://doi.org/10.1002/jts.2490090305
[Return to citation](#apa-tedeschi-citation)

<a name="apa-treviranus-bell-curve-reference"></a>Treviranus, J. (2019). *Inclusive design: The bell curve, the starburst and the virtuous tornado*. Inclusive Design Research Centre, OCAD University. https://idrc.ocadu.ca/ideas/inclusive-design-the-bell-curve-the-starburst-and-the-virtuous-tornado/
[Return to citation](#apa-treviranus-bell-curve-citation)

<a name="apa-treviranus-reference"></a>Treviranus, J. (2025). *Inclusive Design Research Centre*. OCAD University. https://idrc.ocadu.ca/
[Return to citation](#apa-treviranus-citation)

<a name="apa-veblen-reference"></a>Veblen, T. (1919). The intellectual pre-eminence of Jews in modern Europe. *Political Science Quarterly*, *34*(1), 33–42. https://doi.org/10.2307/2141518
[Return to citation](#apa-veblen-citation)

<a name="apa-zheng-reference"></a>Zheng, Y., & Walsham, G. (2021). Inequality of what? An intersectional approach to digital inequality under Covid-19. *Information and Organization*, *31*(1), 100341. https://doi.org/10.1016/j.infoandorg.2021.100341
[Return to citation](#apa-zheng-citation)

## License

This document, *Universal Cake -- An Introduction*, by **Christopher Steel**, with AI assistance from **Claude (Anthropic)**, is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

![CC License](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)

## Changelog

| Version | Status | Notes |
|---------|--------|-------|
| 0.2.6 | Draft | Added closing paragraphs to section 2.3: Sindermann fish stress and cumulative stressors; Harvard Law Review causation problem; reciprocal argument that wellbeing cannot be attributed to a single intervention any more than harm can be attributed to a single pollutant; "living systems do not work that way" framing; "cleaning the water" as the closing statement of the section; added Sindermann and Harvard Law Review references and resources |
| 0.2.5 | Draft | Author edits for clarity throughout; version bump applied by author |
| 0.2.4 | Draft | Replaced section 2.3 placeholder with full text including Kevin Kintner story, March, Putnam, Odum, Veblen, Meyer, Buckup, Tedeschi and Calhoun, Leung and Chiu; added Brown et al. on inflammation; added all new references |
| 0.2.3 | Draft | Author edits for clarity; added Catherine Roy and Vie Autonome Montréal; restructured section 2 with subsections 2.1–2.4; Treviranus citation for Pareto naming point; spelling and grammar corrections throughout |
| 0.2.2 | Draft | Merged author edits to v0.2.0 with new sections 2.1 and 2.2; updated Inspirations; corrected section 1 voice and Plone narrative; added Eberhard, Pareto, Statista, and Zheng & Walsham references |
| 0.2.1 | Draft | Added sections 2.1 and 2.2 on 80/20 critique and compounded digital exclusion; fixed Meadows timing; added Ethnologue, Pareto, Statista, and Zheng & Walsham references |
| 0.2.0 | Draft | Complete rewrite of sections 1–7; added Plone WCAG 1.0 AAA history; added Treviranus virtuous tornado and 80/20 critique; added McLuhan; added Three Supports wellbeing framing; added language as first context; added vital services dependency question; updated all references |
| 0.1.2 | Draft | Edited to reflect author's actual thinking regarding Universal Cake |
| 0.1.1 | Draft | Replaced Sources and acknowledgements with Inspirations; reframed origin as 1999 checklist; added Meadows, Treviranus, RAPLIQ; corrected CC badge to BY-SA |
| 0.1.0 | Draft | Initial draft |
