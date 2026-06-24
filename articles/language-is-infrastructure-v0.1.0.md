# Language Is Infrastructure

Version: 0.1.0
Status: Draft
License: CC BY-SA 4.0

## Abstract

Most technology treats language as a cosmetic layer — a translation applied on top of a finished product. This article argues that language is load-bearing infrastructure, and that weak language infrastructure produces structural exclusion that no amount of later translation can repair.

---

## Not cosmetic — load-bearing

Language infrastructure is the structural layer that determines which communities can communicate within and through a system. It includes translation coverage, plain language standards, multilingual documentation, and the assumptions baked into interfaces about what a "default" user reads and thinks in.

Universal Cake treats language as infrastructure in the same way roads and power grids are infrastructure — not cosmetic, not optional, but load-bearing. If language infrastructure is weak, entire communities are structurally excluded regardless of their willingness to engage.

---

## The numbers

Around 380 million people speak English as their native language — roughly 5% of the world's population (Eberhard et al., 2024). Even including everyone who speaks English as a second language, more than 4 in 5 people in the world do not understand English. Yet 54% of websites worldwide are in English (Statista, 2024).

There are some 7,170 living languages in the world. Roughly 44% are now endangered, often with fewer than 1,000 users remaining (Eberhard et al., 2024). Every one of those languages represents a community of people, a way of understanding the world, a body of knowledge that exists nowhere else.

The technology industry's default assumption — that English is sufficient — is an infrastructure decision. It determines who can participate and who cannot, as surely as a road that stops at the edge of town determines who can reach the market.

---

## The reinforcing loop

Language infrastructure operates as a reinforcing loop. It runs in both directions — virtuous or vicious — depending on the investment decisions made at the beginning.

**Virtuous direction:**

Language infrastructure enables community engagement. Community engagement generates diverse knowledge — different problem framings, different use cases, different failure modes, different solutions. Diverse knowledge strengthens the system. A stronger system can invest in better language infrastructure.

**Collapse direction:**

Weak language infrastructure limits community engagement to whoever already speaks the dominant language — typically the group that built the system. Limited engagement produces homogeneous knowledge. Homogeneous knowledge creates a fragile system that has been tested against a narrow range of conditions. Fragile systems generate less capacity to invest in language infrastructure. The loop continues downward.

Most technology systems are in the collapse direction. They launched in one language, optimised for one community, and produced knowledge that reflects only that community's experience. The resulting fragility appears as poor adoption, unexpected failure modes, and inaccessibility — all of which are systemic outputs of the language decision made at the beginning.

---

## What weak language infrastructure produces

A system with low diversity of knowledge is brittle. It has been tested against a narrow range of conditions. When conditions outside that range emerge — different languages, different abilities, different contexts — the system fails in ways its builders did not anticipate because they never had access to the perspectives that would have revealed the failure modes.

This is not a theoretical concern. It is the explanation for why so many technology products fail when they attempt to expand beyond their initial market. They were not built on language infrastructure that could support expansion. The architecture assumed a single language community. Everything downstream of that assumption — documentation, interface patterns, data models, support processes — reflects a single perspective.

Translation applied after the fact does not fix this. A system designed around English-language assumptions does not become multilingual by adding a translation layer. The assumptions are structural — embedded in the information architecture, the interaction patterns, the documentation hierarchy, and the cognitive models the system expects its users to share.

---

## Language and accessibility

Language is the first accessibility gate. Before device compatibility, before bandwidth requirements, before screen reader support — before any of those questions can even be asked — comes the question of whether the system communicates in a language the person understands.

A perfectly accessible interface in a language the user does not read is inaccessible. A perfectly standards-compliant system that documents itself only in English is inaccessible to 80% of the world's population.

This is why Universal Cake places language at the foundation of accessibility, and accessibility upstream of everything else. The cascade priority — protect human capacity, then open participation, then build knowledge — begins with language. If people cannot read the system, they cannot participate in it or improve it.

---

## Language and sovereignty

Language infrastructure is also a sovereignty concern. When an organisation depends on a platform that operates only in English — or that provides machine translation without human verification — the organisation's ability to serve its community in its community's language depends on an external actor's priorities.

If the platform decides that a language is not economically viable to support, the community served in that language loses access. If machine translation produces errors in critical content — legal documents, healthcare information, government services — the consequences fall on the people who depend on accurate communication, not on the platform that provided the translation.

Sovereign language infrastructure means the organisation can produce, verify, and maintain communication in the languages its community needs, without depending on an external actor's willingness to continue supporting those languages.

---

## The Quebec context

Quebec operates in an environment where language infrastructure is not abstract. The province's language requirements create natural alignment with a multilingual-first approach to technology. Organisations serving Quebecois communities must function in French. Many must also function in English. Some serve Indigenous communities with their own language needs.

This is not a compliance burden. It is a design reality that produces stronger systems — systems that have been built from the beginning to handle multiple languages, multiple communities, and multiple perspectives. The organisations that treat this as infrastructure rather than overhead are the ones that build technology capable of serving their full community.

---

## What building on language infrastructure looks like

**At the design level:** Language is the first question, not the last. Before features, before interface patterns, before data models — which languages must this system support, and how will that support be maintained over time?

**At the architecture level:** Multilingual capability is a structural requirement, not a layer added to a finished product. Information architecture, content models, and interface patterns are designed to accommodate multiple languages from the beginning.

**At the documentation level:** Documentation exists in the languages of the people who will use it. Plain language standards ensure that even within a single language, the broadest possible audience can understand the content.

**At the maintenance level:** Language infrastructure is maintained as infrastructure — with the same priority and resources given to servers, networks, and security. Translation coverage is monitored. Documentation currency is tracked. Language gaps are treated as infrastructure failures, not feature requests.

---

## The investment logic

Language infrastructure is not a cost. It is the gate that determines how many communities can engage with a system, how much diverse knowledge those communities can generate, and how strong the resulting system becomes.

A system that invests in language infrastructure builds a broader participation base, generates more diverse knowledge, becomes more resilient, and develops the capacity to invest further in language infrastructure. The loop compounds.

A system that treats language as cosmetic builds a narrow participation base, generates homogeneous knowledge, becomes fragile, and has less capacity to expand. That loop also compounds — in the wrong direction.

The choice is made once, at the beginning. The consequences compound across the life of the system.

---

## Resources

- Eberhard, D. M., Simons, G. F., & Fennig, C. D. (Eds.). (2024). *Ethnologue: Languages of the World* (27th ed.). SIL International.
- Statista. (2024). Most common languages used on the internet as of January 2024.
- Steel, C. (2026). *Universal Cake -- An Introduction* (v0.3.2). CC BY-SA 4.0.
- Treviranus, J. (2019). *Inclusive Design: The Bell Curve, the Starburst and the Virtuous Tornado*. IDRC, OCAD University.

---

*Language Is Infrastructure* by Christopher Steel / Universal Cake, with AI assistance from Claude (Anthropic), is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Content draws from *Universal Cake -- An Introduction* (v0.3.2).
