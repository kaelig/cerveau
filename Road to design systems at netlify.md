- What about ecosystem (integrations hub)
- What about marketing?

# intro

# Where we are 

Timing wrong for a full fledged multi disciplinary design system.
Technically, heavy lift
Culture of quick iteration (separate component library repo = longer feedback loops)
As a business we're still figuring out a lot of pieces and our big bets for 2022+ still have to find product market fit
Design maturity: redesign coming up

# Known unknowns and other considerations
- new JS tooling
- CSS getting more powerful (why build a component library for the old world, considering next year will change so many things: color module 4, container queries, subgrid...)
- Future of ecosystem and WorkflowUI (need for an open source developer-facing design system?)
- Fast iteration on brand, navigation, IA...
Pace layers model (see Jeremy Keith talk)

At our scale, let's favor adaptability and optionality.

# What's the plan 

Short term: build components in the product codebase directly

Only abstract pieces that definitely need to be consistent across Figma and multiple products: such as colors, icons. This is cheap and easy to set up, for big returns short term and long term.

Content / Microcopy: We do have guidelines but UX content isn't nearly as good as it could be (error messages, etc.). It's a huge differentiator for international audiences, and can lead to lower volumes of support requests.
This is particularly hard to systemize and can't be automated, so that's the one area where I believe we need to invest.


# Notes

# Todo
- Close design council channel
- Close design system project channel
- Clean up notion and GitHub to remove design system tasks. https://www.notion.so/netlify/Projects-c58da31f4acb43fe9615ca7e200a6f01?p=54de451b46294c88b6ee56a62d4e9768&pm=s
- 



# Email

Hi team,

**The foundations and design team have decided to halt all previously started design system projects.** With the rebrand coming, we don't want to systematize what's old.

tl;dr: our priority is to roll the new brand out, then systematize as we learn and grow.
Also: we must build a product content strategy discipline.

---

As Netlify's brand is evolving, we find ourselves at a crossroads: how should we invest in nurturing what exists already, versus elevating what marks a new age in Netlify's journey?

On the product side, we have satisfying foundations in place for our current scale: industry-standard frontend practices, a dependable Figma library, and a shared language between design and engineering thanks to design tokens.

On the marketing side, we aim to be more expressive. While we don't require the level of consistency seen in the product, we're exploring design tokens to accelerate the new design rollout.

Essentially, we're in a good spot!

We're executing on all of the aforementioned points in industry-leading ways.

With that said, our play-to-win priority is to support the new design language rollout:

- Defining the product/comms/support rollout strategy
- Empowering designers to submit simple cosmetic code fixes themselves (and there will be a lot of those!)

Does this mean we're stopping all design system work? Fuck no.

Disclaimer: this is an ambiguous topic, because there are so many unknowns (on my mind: integrations hub, WorkflowUI, in-product docs, collaborative deploy preview, hiring bandwidth, additionnal acquisitions...)

### So, what will we do?

As we roll out the new language, we'll systematize its foundations (principles, colors, spacing, typography...), and then step by step, from basic components all the way to complex patterns and research insights, with the appropriate governance processes... we'll build a design system that grows organically to serve our needs, and helps us build the best developer platform in the world, because that's why we're here!

### Who will be responsible for driving this work?

On the brand side, nothing changes: Justin and Daniel.
On the marketing side: Teresa Carter.
On the product foundational technical and design side: I'll be driving future design systems initiatives.

### Any questions?

Ask away in #project-design-system !

Kaelig Deloumeau-Prigent

Thanks to {{add thank you notes here}} for their insights and review. 

---

One more thing: content strategy.

As [Relly Annett-Baker's thorough content & usability product review](https://drive.google.com/file/d/1-XJhdfYRCQM2sJTHU4TKk0G03U4nejuD/view?pli=1) showed, we need experts to help us define taxonomy, UX microcopy, information architecture... in ways that meet our ambitions and the needs of our growing audience.

At the minimum: 1 manager, 1 staff+, 1 entry-level.

This expertise is crucial in our journey delivering differenciated experiences that beat our competition. Let's make this happen.

---

## References
Amazing review of our current content and general usability practices: [Relly Annett-Baker Content strategy recommendations](https://drive.google.com/file/d/1-XJhdfYRCQM2sJTHU4TKk0G03U4nejuD/view?pli=1)
Unfinished but useful: [Rafa's Product style guide](https://www.notion.so/netlify/Product-Styleguide-WIP-b33403c1f8a34e568c3d8bf01be8dfb2)
Detailed view of where we come from and where we are: [Netlify Design System: The state of play](https://www.notion.so/netlify/Netlify-Design-System-The-state-of-play-d0411d856d6d4be8902b22f6dd1202a5) (by Kristy)
Relevant talk, especially this slide – "The anatomy of a design system isn't a game of design system cover-all bingo" https://youtu.be/-X4gT3mcb0M 
![[Screenshot_20221109-121817 1.png]]
Ben Callahan: [# The Anatomy of a Design System](https://sparkbox.com/foundry/design_system_makeup_design_system_layers_parts_of_a_design_system)