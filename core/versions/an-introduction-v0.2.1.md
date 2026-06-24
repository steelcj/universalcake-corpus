# Universal Cake -- An Introduction

Version: 0.2.0
Status: Draft
Style Guide: style-guide--plain-language-for-general-audiences-v0.2.0

## Abstract

This document introduces Universal Cake, a framework for thinking about technology in human terms. It explains where the idea came from, what the name means, and how it can help anyone — technical or not — ask better questions about the tools they use every day.

## Inspirations

Universal Cake began in 1999 as a personal checklist. Christopher Steel was looking for web software and wrote down the questions that mattered to him: Does it come in my language? Does it work on my system? Does it work in the browsers my users have? Is it accessible to people with disabilities? Is it supported? Is it maintained? Does it have the qualities needed for longevity? Is it worth investing in? That list was not borrowed from anywhere. It came from experience — from working with real people who were being left out by technology that was not designed with them in mind.

Over time, the questions on the that checklist changed with the times, the advent of more better approaches to browser compatibility and the technology at the time the list started. The list adapted and changed and today has become more of a framework or eve a praxis. Christopher also encountered others who had been asking similar probing questions from their own directions. Some he was not even aware of until recently, but it has become clear that a lot of parallel thinking that has emerged since and some prior work that he was not aware of reflects his work on refining his list into something kid of special.

For example, <a name="apa-meadows-citation"></a>[Meadows (2008)](#apa-meadows-reference) and her work on systems thinking was a recent and satisfying discovery: the idea that healthy systems are made of interdependent parts that support one another maps directly onto the "recipe" required to create universal cake. The manuscript behind that book was written in 1993 and circulated informally for years before publication, meaning Meadows had already been working through these similar ideas for six years by the time Chris made his first, one page checklist, a researcher had recommend that Christopher read some of her work in the 2010's but he encountered her work again and to a deeper dive in 2026.

The human inspiration behind Universal Cake is wide and does not fit neatly into a reference list. It spans disability rights — including the work of <a name="apa-treviranus-citation"></a>[Jutta Treviranus at OCAD University](#apa-treviranus-reference), Catherine Roy at McGill University, and the advocacy of <a name="apa-rapliq-citation"></a>[RAPLIQ](#apa-rapliq-reference) — alongside philosophy, systems thinking, trauma-informed practices, and personal resilience. People like Alex Limi (and the Plone gang) Hugh Gallagher (Advocate), Massimo Di Pierro(Web2py.com), bell hooks, Donella Meadows, Pema Chödrön, Ed Roberts (activist), Michael DeHaan (Ansible). and Simone de Beauvoir have all shaped how Christopher thinks about people, systems, and what it means to build something that serves rather than excludes. Technology does not exist apart from these questions. It is shaped by them, and shapes them in return.

The plain language principles used in this document follow the <a name="apa-plain-language-citation"></a>[Plain Language Action and Information Network (2011)](#apa-plain-language-reference).

## 1. Where it started

In 1999, Christopher Steel needed to choose web software for a community that included people with disabilities, people who did not read or write English, and people using whatever hardware they had. He wrote down the questions that mattered. That list needed a name, something that would help him think clearly about what was on it and what the priorities were.

The name of that list came from an unlikely place. A few years earlier, Christopher and some artist friends had started a communications company. They came up with the name Universal Cake, designed an actual box for the product, and then could never quite figure out what should go in it. The company did not survive. The name did. It fit the list perfectly, and the rest is history.

Accessibility moved to the top of that list not as a political statement but as a logical one. If the software did not work in your language, or on your system, or for your users, then nothing else on the list mattered. Speed, stability, and sustainability were all important — but they were downstream of access. Without the door, the rest of the house is irrelevant.

Evaluating the options against the list, Christopher found Plone. It was not finished. But its commitments were clear: multilingual, open source, web-editable, with accessibility treated as a first-class concern rather than an afterthought. He chose it, and he waited for it to mature. That turned out to be a good investment. Plone is still here. Most of the software that competed with it in 1999 and 2000 is not. The list worked!

Plone's ambitions at the time seemed outrageous to many. No one had done this at scale in open source before, a web-based editor that anyone could use without technical training, in over fifty languages, built from the ground up with accessibility as a first-class concern rather than a feature added later. Out-of-the-box Plone installations in the early 2000s were documented as meeting WCAG 1.0 AAA, the highest level under the standard in force at the time — making Plone one of the very few mainstream content management systems to claim that distinction. WCAG 1.0 AAA meant satisfying all Priority 1, 2, and 3 checkpoints, which was achievable for a well-built default theme in that era. When WCAG 2.0 arrived in 2008, with a substantially revised structure and more rigorous requirements, the bar changed, but Plone's commitment did not. Plone's design went on to influenced Wikipedia's MonoBook skin, which was the default face of the world's largest encyclopedia for six years. The organisations that eventually adopted Plone, the United Nations, the FBI, and governments on multiple continents, had exactly the same requirements as that original checklist. They needed systems that worked across languages, across abilities, and across decades. The list was not unusual. It was just an honest assessment of the real world human needs and requirements that all humans have for  technology that serves them.

## 2. What the name means

The word *universal* describes the goal: technology that works for the widest possible range of people, languages, abilities, devices, and circumstances. Not technology designed for what is wrongly described as the comfortable 80% at the centre of the bell curve, but technology that keeps asking, in the words of <a name="apa-treviranus-bell-curve-citation"></a>[Treviranus (2019)](#apa-treviranus-bell-curve-reference), "who are we missing?", and works hard to refine the real answer.

<a name="apa-treviranus-bell-curve-citation-2"></a>[Treviranus (2019)](#apa-treviranus-bell-curve-reference) argues that the conventional reading of Pareto tells developers and designers to serve the easy 80% and ignore the "difficult 20%" at the margins. This is both a misreading and a disaster in addition to neglecting to acknowledge that the definition of the easy 80% is almost never the goal and that 80%  . The people at the margins — the vital few — cover 80% of the knowledge terrain. Designing for them does not cost you. It pays you back: systems that reach the edges of human diversity are more innovative, more resilient, and better for everyone. The dynamic that results from this commitment — a continuous, iterative process of asking who we are missing and expanding the design to reach them, creating a system that grows stronger and more capable with each cycle — is what Treviranus calls the Virtuous Tornado. Christopher was working from the same intuition in 1999, from his own experience as a person living with a disability, two decades before Treviranus named it. The convergence is not a coincidence. It is what happens when people think honestly about the same problem.

The word *cake* describes something everyone loves. A cake is made of ingredients. No single ingredient makes a cake — it takes all of them, in the right relationship with one another, to produce something worth eating. Universal Cake uses this image to describe how good technology is built: not as a single feature or a single metric, but as many qualities working together. Those qualities include accessibility, sustainability, transparency, resilience, and human well-being. Leave one out entirely and what you have is diminished — possibly inedible.

Marshall McLuhan argued that every technology is an extension of the human nervous system — a way of reaching further, sensing more, acting beyond the limits of the body alone <a name="apa-mcluhan-citation"></a>([McLuhan, 1964](#apa-mcluhan-reference)). Universal Cake takes that seriously. If technology extends what humans can do and experience, then the question of who gets to be extended — and who gets cut off — is not a technical question. It is a human one. And it has always been one.

## 3. The core idea

Technology is not neutral. Every tool makes choices. Those choices affect who can use it, how long it lasts, who controls it, and what it does to the people around it.

Wellbeing is not a feature. It emerges from the quality of our relationships — with our bodies, with our minds, and with the people and world around us. Those three relationships are not separate. They reinforce each other, or they undermine each other. A technology that respects one while degrading another is not a neutral trade-off. It has consequences that ripple outward in ways that are rarely visible in a feature list or a benchmark score.

Universal Cake proposes a simple shift: stop asking only "does it work?" and start asking "does it work in a way that supports the humans who depend on it — their ability to understand, to participate, to stay well, and to remain in control of their own lives?" That question does not have a single answer. It has layers. And attending to all of them, consistently, over time, is what Universal Cake is about.

That shift changes everything. A note-taking app is no longer just fast or slow. It is also asking: can I get my notes out if the company shuts down? Can someone using a screen reader actually use it? Will my notes be readable in ten years? Does the notification design respect my attention or exploit it? These are not technical questions. They are human ones. And they have always mattered more than the technical ones.

## 4. What Universal Cake evaluates

Universal Cake can be applied to almost any technology — software, hardware, infrastructure, documentation systems, or communication platforms. It evaluates them across a set of human-centered dimensions rather than purely technical ones. No technology scores perfectly across all of them. The goal is not perfection. The goal is honest, balanced evaluation — and a growing commitment to doing better.

**Accessibility** asks whether diverse people can actually use the system — including people living with disabilities, people using older hardware, people with slow internet connections, and people who speak languages other than English. Accessibility is not a feature to add later. It is the door. Without it, nothing else on the list matters.

**Sustainability** asks whether the system can last. This includes environmental costs like energy use, but also human costs: does it burn out the people who maintain it? Does it require constant expensive upgrades? Does it serve the organisation that depends on it, or does it slowly consume it?

**Interoperability** asks whether your data can move freely. Can you take your work elsewhere if you need to? Does the system use open standards that other tools can read, or does it lock you in — quietly, incrementally, until leaving becomes too costly to consider?

**Transparency** asks whether you can understand what the system is doing. Can you inspect it? Can you audit it? Or is it a black box that you simply have to trust — and that trusts you with nothing in return?

**Resilience** asks whether the system can survive disruption — a company closing, an internet outage, a change in political environment. Can it keep working when things go wrong? Can the people who depend on it keep going?

**Human well-being** asks what the system does to the people who use it. Does it reduce stress or increase it? Does it support healthy habits or undermine them? Does it respect human attention and limitation, or does it extract from them?

**Knowledge preservation** asks whether the information stored in the system will remain readable in the future. Will your files open in twenty years? Does the system depend on a proprietary format that could disappear — taking everything stored in it along with it?

## 5. Why this matters now

Most technology today is evaluated on a short list of criteria: speed, features, price, and popularity. These are not bad criteria. But they are incomplete. They describe what a tool can do. They say almost nothing about what it does to people.

They do not ask who gets excluded. They do not ask what happens when the company behind the tool changes direction, gets acquired, or closes. They do not ask what the tool does to the attention and mental health of the people who use it every day. They do not ask whether the knowledge stored in it will survive the next decade. They do not ask whether the people who maintain it will still be standing in five years.

The short list optimises for the centre of the bell curve and calls it good enough. Universal Cake does not reject the short list. But it does attempt to prioritise it and place it in the real world context in which technology actually operates. First among that context is language — human languages and dialects in all of their varieties, because without language nothing else can be communicated, preserved, or passed on. Beyond human language sits the vast and largely unrecognised communication of the myriad creatures with whom we share this planet — systems of meaning that predate human technology by hundreds of millions of years. The short list was written for one kind of person, in one kind of place, under one set of conditions. Universal Cake asks what happens when you take seriously the full scale of life on earth — and what our responsibility is to design with that scale in mind, rather than in spite of it.

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

### Plain language

- [Federal Plain Language Guidelines](#apa-plain-language-reference)

## References

<a name="apa-mcluhan-reference"></a>McLuhan, M. (1964). *Understanding media: The extensions of man*. McGraw-Hill.
[Return to citation](#apa-mcluhan-citation)

<a name="apa-meadows-reference"></a>Meadows, D. H. (2008). *Thinking in systems: A primer* (D. Wright, Ed.). Chelsea Green Publishing. (Original manuscript completed 1993.)
[Return to citation](#apa-meadows-citation)

<a name="apa-plain-language-reference"></a>Plain Language Action and Information Network. (2011). *Federal plain language guidelines*. United States Government. https://www.plainlanguage.gov/guidelines/
[Return to citation](#apa-plain-language-citation)

<a name="apa-rapliq-reference"></a>RAPLIQ. (2025). *Regroupement des activistes pour l'inclusion au Québec*. https://www.rapliq.org/
[Return to citation](#apa-rapliq-citation)

<a name="apa-steel-mission-reference"></a>Steel, C. (2026). *Christopher Steel — Personal mission statement* (v0.2.0). Unpublished manuscript.
[Return to citation](#apa-steel-mission-citation)

<a name="apa-treviranus-bell-curve-reference"></a>Treviranus, J. (2019). *Inclusive design: The bell curve, the starburst and the virtuous tornado*. Inclusive Design Research Centre, OCAD University. https://idrc.ocadu.ca/ideas/inclusive-design-the-bell-curve-the-starburst-and-the-virtuous-tornado/
[Return to citation](#apa-treviranus-bell-curve-citation)

<a name="apa-treviranus-reference"></a>Treviranus, J. (2025). *Inclusive Design Research Centre*. OCAD University. https://idrc.ocadu.ca/
[Return to citation](#apa-treviranus-citation)

## License

This document, *Universal Cake -- An Introduction*, by **Christopher Steel**, with AI assistance from **Claude (Anthropic)**, is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

![CC License](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)

## Changelog

| Version | Status | Notes |
|---------|--------|-------|
| 0.2.0 | Draft | Complete rewrite of sections 1–7; added Plone WCAG 1.0 AAA history; added Treviranus virtuous tornado and 80/20 critique; added McLuhan nervous system; added Three Supports wellbeing framing; added language as first context; added full question on vital services dependency; added Meadows manuscript provenance note; updated all references |
| 0.1.2 | Draft | Edited to reflect author's actual thinking regarding Universal Cake |
| 0.1.1 | Draft | Replaced Sources and acknowledgements with Inspirations; reframed origin as the 1999 checklist; added Meadows, Treviranus, RAPLIQ; corrected CC badge to BY-SA |
| 0.1.0 | Draft | Initial draft |
