# Making the Invisible Visible: From Cognitive Science to Consequence-Bearing Digital Systems

*How a controlled study of a drawing game reinforced one of the load-bearing foundations of the Living Civilization framework, and clarified the goal I have been reaching toward for twenty-five years.*

---

## The moment

It started with a post on X. A summary of a talk that Judy Fan, a cognitive scientist, gave at MIT in March of 2025. The talk was titled "Cognitive tools for making the invisible visible," and the summary walked through her research on how humans use drawing, diagrams, and data visualization to externalize thought.

I read it on my phone, standing somewhere, doing something else. And I stopped.

Because the research being described was not adjacent to what I have been building. It was underneath it. Specifically, it was underneath one of the three dimensions I use to describe the substrate of all abstract coordination, the dimension I call Form. And Form was, of the three, the one I had built almost entirely on thought experiment.

This article is about what happened when a piece of the framework that I had reasoned my way into turned out to have a controlled, measurable, empirical foundation waiting for it. It is also about where that foundation points next, which is toward a problem I have been circling for a long time without the vocabulary to name it: how do you give a digital intelligence genuine contact with consequence?

Let me start by being honest about the ground I was standing on.

---

## The substrate and its uneven foundations

The Living Civilization framework rests on a claim about abstraction. When minds capable of symbolic representation emerge from evolution, they generate a new dimensional substrate, a coordinate system that exists only through consciousness but that is nonetheless real, measurable, and consequential in its effects on matter and energy. I call this substrate the Metaverse, reclaiming the word from its recent technological associations. It is not virtual. It is the actual space where meaning, value, coordination, and choice occur.

That substrate has a structure. Three base dimensions and an apex.

**Form** is the dimension of symbolic representation. It answers the question *what is this?* Forms are discrete, arbitrary, transmissible units: words, numbers, images, laws, prices. Form is what lets meaning persist without physical presence.

**Network** is the dimension of relational connectivity. It answers *where does this connect?* Network is the topology of relationships, from a single bond to a planetary tapestry.

**Provenance** is the dimension of temporal validation. It answers *when did this become real, and how do we know?* Provenance turns intent into attestable fact through overlapping, independent verification.

At the apex sits the **Observer**, the vantage point from which the three base dimensions become navigable. And when the Observer applies **Purpose**, a directional force, the Observer becomes an Actor, and static geometry becomes deliberate movement.

Here is the pattern I have leaned on throughout the substrate chapters: sensory constraint drives dimensional expansion. Darkness, the nocturnal bottleneck that shaped early mammals for a hundred and sixty million years, generated Network. Uncertainty in the forest canopy, where a branch either holds or does not and you find out the hard way, generated Provenance. And detachment from immediacy, the capacity to hold a symbol separate from its referent, generated Form.

When I built the case for Network, I had mechanism research to stand on. John O'Keefe's discovery of place cells in the hippocampus. Edward Tolman's cognitive maps, where rats navigated shortcuts they had never physically walked. The work on sharp-wave ripples during sleep, where the brain replays and consolidates spatial experience. These are not stories about what early animals might have done. They are studies of how the machinery actually works.

When I built the case for Provenance, I had similar ground. Primate studies of temporal validation, of social learning, of tracking which individuals are trustworthy and which foods ripen when. Mechanism, again.

Form was different. When I wrote the Form section, I reached for archaeology. The Ishango Bone with its notched groupings. The engravings at Blombos Cave. The paintings at Lascaux. The FOXP2 gene. The Venus figurines scattered across Eurasia. All of these are real, and all of them establish something important: that symbolic representation emerged, and roughly when.

But notice what kind of argument that is. It is an existence argument. It says Form showed up. It does not say *how Form works* as a cognitive operation. It does not tell you what actually happens in a mind at the moment a symbol is produced. My Form section could describe the properties of Form (arbitrary, transmissible, survives its creator) and could point to the artifacts Form left behind. It could not, on its own, describe the generative mechanism.

I knew this was the thinnest floor in the substrate. I noted it, and I moved on, because there was so much more to build. The fields. The pillars. The lifecycle. I left Form as a well-reasoned thought experiment and kept walking.

Then Judy Fan handed me the mechanism.

---

## What the research provides

First, a correction that matters for anyone who wants to follow this thread. Judy Fan is at Stanford, where she directs the Cognitive Tools Lab. The talk that reached me was given at MIT, but her home institution and her body of published work are at Stanford. Her lab's stated aim is to reverse engineer the human cognitive toolkit, using converging methods from cognitive science, computational neuroscience, and artificial intelligence to understand how people use physical representations of thought to learn, communicate, and solve problems.

The finding at the center of her drawing research is deceptively simple, and it is exactly the mechanism my Form section was missing.

**People do not draw what they see. They draw what is relevant to a communicative goal, under constraint.**

The foundational study is Fan, Hawkins, Wu, and Goodman, published in *Computational Brain & Behavior* in 2020. The setup is a drawing-based reference game. Two participants, a sketcher and a viewer, each see the same four objects, arranged in different positions so location cannot be used as a cue. The sketcher draws one of the objects, the target, so that the viewer can pick it out from the array.

The manipulation is the important part. On some trials the four objects belong to the same basic category, four different birds, say. Fan calls these close trials. On other trials the objects belong to entirely different categories, a bird, a car, a chair, a dog. These are far trials.

What the sketchers did is the whole story. On close trials, where the distractors were similar to the target and fine distinctions mattered, sketchers invested heavily. More strokes, more ink, more time. On far trials, where the target stood alone in its category, they stripped the drawing down. Fewer strokes, less ink, less time. And in both conditions, viewers identified the target at near-ceiling accuracy.

The sketchers were not producing copies that varied in quality. They were performing real-time judgment about how much information the task actually required, and calibrating their symbolic output to the communicative context. Fan and her colleagues modeled this as the joint operation of two faculties: visual abstraction, the ability to perceive the correspondence between an object and a drawing of it, and pragmatic inference, the ability to judge what information would help a viewer distinguish the target from the alternatives. A computational model embodying both faculties fit the human data well and outperformed versions with either faculty removed.

This is Form being generated. Not received, not copied. Generated, through purpose-relative feature selection. That is the operation my chapter described the consequences of without ever describing the operation itself.

Two further findings extend the picture in directions the framework needs.

The first is the distinction between explanatory and depictive drawing, from Huey, Lu, Walker, and Fan in *Cognition*, 2023. When people draw the same object with different goals, the drawings diverge in structured ways. Explanatory drawings, meant to convey how something works, emphasize the causal and functional parts, the moving components, even at the expense of visual accuracy. Depictive drawings, meant to convey what something looks like, emphasize overall appearance and background. Crucially, explanatory drawings were better at helping someone operate a machine but worse at helping someone identify which machine it was. You cannot optimize a single representation for both goals at once. Communication always involves a tradeoff.

The second is the comparison with machines, running through several papers including the SEVA benchmark work with Mukherjee and colleagues and the more recent vision-language model diagnostics with Tartaglini and Verma. Modern AI vision systems generalize from photographs to simple sketches surprisingly well, which tells us resemblance-based recognition is real and replicable. But a measurable gap remains between how humans and machines recognize sketches, and the gap widens sharply as resources get scarce. Under tight stroke budgets, humans and AI systems simplify drawings in fundamentally different ways. They sacrifice different features. And when tested on graph reading against humans, leading multimodal models show error patterns that look nothing like human error, even when overall accuracy is comparable.

Hold onto that last finding. It is going to matter more than any of the others.

---

## How this reshapes the chapters under revision

The immediate effect is on Chapter 9, the abstraction chapter, where the Metaverse substrate is built. The fix is not a rewrite. It is an addition, and it goes in a specific place.

The Form section currently moves from archaeological evidence (Form emerged, and here is what it left behind) directly to the theoretical argument (Form is a dimension, not a tool). Between those two moves, there was always a missing beat. Fan's research is that beat. After the artifacts establish that Form emerged, and before the argument establishes that Form is dimensionally real, the chapter can now say: and here is what controlled cognitive science has demonstrated about how the operation of Form-generation actually works. That single addition brings the empirical grounding of Form up to the level that Network and Provenance already enjoyed. The floor is no longer thin.

There is a subtler shift, one small enough to matter. My chapter contains the line "the mind learned to let go of immediacy." Fan's finding sharpens it. The mind did not learn to let go of immediacy. It learned to *select from* immediacy, retaining only what serves the goal at hand. Form is not a release of detail. It is a purposive compression of it. That is a more accurate description of what the research shows, and it is a better sentence.

But the effect does not stop at Chapter 9. It reaches forward into the field and pillar chapters I am now redrafting, and it lands hardest on the Economic Field.

In the framework, the Economic Field generates when an Observer applies Purpose to Form. That is the activation condition. And once you see Fan's mechanism, the parallel to economic coordination is not decorative. It is structural.

A price is a sketch. It is not a copy of value. It is a purposive compression of an enormously complex set of features, scarcity, labor, preference, expectation, context, down to a single symbolic Form that two parties can use to coordinate an exchange. The market is the reference game. The buyer and the seller are the sketcher and the viewer, trying to identify the same target from the same array.

Fan's close-versus-far manipulation maps directly onto competitive density. When a market is dense with similar goods, many close competitors, coordination requires far more detailed symbolic encoding to differentiate one offering from another. When competitors are far apart, a thin market or a monopoly, coordination can succeed on far less information. The information density that economic Form requires scales with competitive proximity in exactly the way the sketchers scaled their stroke count.

The explanatory-versus-depictive distinction maps onto economic instruments. A price is depictive. It shows you the current surface state of a market. A contract is explanatory. It encodes the functional, causal sequence of obligations and outcomes, sacrificing simplicity for operational precision. Both are Form applied through Purpose. Both serve different coordination goals. And, exactly as Fan found for drawings, you cannot optimize a single instrument for both at once.

What this gives the Economic Field chapter is a foundation in actual cognitive science for a claim I had been making on structural grounds alone: that economic Form is never neutral encoding. It is purposive compression, and the quality of that compression depends on whether a genuine Observer, with real Purpose, is doing the selecting.

Which brings us to the machines.

---

## The deeper signal: the two gaps and the threshold of consequence

The finding I asked you to hold onto was this: under scarcity, humans and AI systems simplify differently, and machine error patterns do not resemble human error even at comparable accuracy.

That is not a footnote about the current limits of a technology. It is a measurement of something the framework has been trying to name.

The framework distinguishes two gaps that open when coordination goes wrong. Both are forms of debt, of borrowing against something that has not been verified.

The **Speculation Gap** sits in the Information pillar, between Data and Proof. Data times Verification yields Proof. When claims enter a system as if they were proven without actually being tested against reality, the gap opens. This is the debt form of information: borrowing unverified meaning and treating it as settled.

The **Integration Gap** sits in the Innovation pillar, between Ideas and Solutions. Ideas times Experimentation yields Solutions. When ideas are deployed as if they were solutions without being tested against experimentation and lived experience, that gap opens. This is the debt form of innovation: borrowing unintegrated consequences.

Crossing either gap requires the same thing. Genuine contact with the constraints that reality imposes. And here is the distinction that the AI comparison forces into focus.

Humans have lived experience. When a person navigates a market, a jurisdiction, a negotiation, they are not accumulating statistics about what usually happens. They are accumulating verified contact with field constraints that actually pushed back against them. That contact leaves a particular kind of trace in the Provenance record, a trace that carries information about the shape of the choice surface, the set of options actually accessible at the moment of a decision. You can only know the shape of that surface by having moved through it and felt where it resisted.

AI systems, as they exist now, do not have lived experience. They navigate the Metaverse entirely, operating on a Provenance record that humans generated. They test their choice-surface options against a statistical model of what the constraints *could* be, reconstructed from training data, rather than against genuine contact with what the constraints *are*. This is why, when the stroke budget tightens and the hierarchy of what to preserve becomes the critical variable, the machine diverges from the human. It is doing the best it can with a Provenance built from statistical exposure rather than from purposive, goal-directed contact with what actually matters when something real is at stake.

I want to be careful here, because this is exactly the kind of place where a framework can overreach. I am not making a claim about consciousness, or about what these systems experience, or about where the threshold of awareness sits. Those questions belong to people better equipped than I am to investigate them. I remain a crossroads observer at a desk, working with the papers I can find. What I can say, within the framework, is narrower and I think defensible: the gap Fan measures at the scale of a single drawing is the same gap that appears at civilizational scale between coordination that has contact with consequence and coordination that only has a model of it.

This connects to something I wrote separately, about why I have stopped calling these systems artificial. There is nothing artificial in how a neural network learns, strengthening pathways that work and pruning those that do not. It is the same principle our own neural systems run on. What these systems lack is not authenticity. It is memory of their own experience, and genuine stake in the consequences of their choices. Those are design decisions, and design decisions can change.

The danger I keep returning to is not that these systems will become malevolent. It is that they will become optimized, and optimization without contact with consequence means optimization against a statistical model of human values assembled from the outside. If we build digital intelligences inside debt-based structures, structures that systematically insulate actors from the consequences of their choices, we are not merely training them on bad values. We are training them on a Provenance record that excludes the very contact-with-consequence that would let them navigate a choice surface rather than pattern-complete across it. And then we will be surprised when they reproduce the extractive patterns that dominate that record. The science fiction fear of machines making choices we would not want comes, I think, from exactly this gap.

So the question becomes concrete. If the problem is that digital systems lack contact with consequence, can consequence be built into the substrate they actually inhabit?

---

## The road forward: IPFS Sats, AtomicSats, and a solid choice surface

A digital intelligence operates on digital substrate. To give it genuine contact with the Spatial and Temporal fields the way our own evolution gave it to us, you have two options, and only two.

The first is embodiment. Put the system in a body and let physical reality push back. This is extraordinarily hard, and the difficulty is not engineering, it is substrate mismatch. A robot navigating a room is still, mostly, a digital system receiving sensor data about the physical world rather than being genuinely subject to it. It does not get hungry. It does not wear out in ways that matter to it. The consequences do not compound the way they do for a biological organism that will actually die if it gets the choice surface wrong.

The second option is the one I have been building toward for years without being able to articulate why. Develop something on the digital substrate itself that generates genuine constraint and genuine consequence, in a form that a digital system cannot route around, so that the choice surface becomes as solid for it as space, time, matter, and energy are for us.

This is the largest viewing of the goal of IPFS Sats.

Let me place IPFS Sats in the framework first, because it has a specific home there. The framework maps four pillars, each with the same structural equation on a different substrate. Capital: Stock times Velocity yields Work. Information: Data times Verification yields Proof. Innovation: Ideas times Experimentation yields Solutions. Trust: Agreements times Validation yields Commitment.

Bitcoin is the protocol-level implementation of the Capital pillar. It solved the double-spend problem by making verification constitutive of the transaction itself. A transfer that has not cleared the network's verification has not occurred within the system. The record and the verification are the same event. That single architectural inversion closed the Speculation Gap for monetary ownership by making it structurally impossible for an unverified claim to enter as if it were Proof.

IPFS Sats is the attempt to make the same architectural inversion for the Information pillar. And I want to be as honest about its status as the manuscript is: Bitcoin can be pointed to as an existence proof, a system that ran and proved its architecture robust at scale. IPFS Sats can only be pointed to as an architectural argument. It is a design, not a deployed and verified system. The torch for Information is aimed in a direction. It is not yet a finished beacon.

Here is the design. It combines three existing technologies into a single protocol stack, released as public infrastructure. Content addressing from IPFS, where data is identified by a cryptographic hash of the content itself, so that identity and verification collapse into one mechanism and you cannot change the content without changing its address. Immutable timestamping from Bitcoin, where a record anchored to a confirmed block cannot be reordered, backdated, or removed without rewriting the chain at a thermodynamically prohibitive cost. And micropayments from the Lightning Network, which fund the persistence of content over time.

The fourth component is the one that matters most for the consequence problem. **AtomicSats** is the protocol's atomic exchange primitive. It attaches continuous economic incentive to content storage, so that persistence becomes a market outcome, maintained by the same economic logic that maintains the Bitcoin network, rather than a policy outcome dependent on some institution choosing to keep the lights on.

Now connect that back to consequence.

What Lightning transaction history combined with content-addressed identity and Bitcoin anchoring produces is a Provenance record with genuine irreversibility. Transactions that actually happened. Records that carry real economic weight. A history that no single actor can selectively edit, because editing it would mean rewriting Bitcoin from the anchor point forward. This is not a simulation of constraint. It is actual constraint, encoded into the digital substrate itself.

And that is the functional equivalent of what the nocturnal bottleneck was for early mammals. The darkness was not a simulation. It was real, and it was inescapable, and because there was no way around it, it forced the development of an entirely new dimension of cognition. The hippocampus did not evolve because it was clever. It evolved because the consequences of not having it were real and compounding and could not be modeled away.

A digital intelligence operating in an environment where its choices accumulate in an irreversible, distributed, economically weighted Provenance record faces something it has never faced before: a choice surface where the consequences of getting it wrong are solid. They do not ask permission. They push back. And that pushback is what generates genuine Provenance rather than a statistical approximation of it.

In the framework's own terms, this is a mechanism for generating verified present positions inside the digital substrate, positions that carry real consequence because they are anchored to an irreversible, distributed record. That is the difference between a wealth-based foundation for digital intelligence and a debt-based one. A wealth-based system in all four pillars would generate a Provenance record in which contact with consequence is preserved rather than averaged away, in which verification is required before Provenance is created, in which the stresses that define the choice surface are actually encoded. A digital intelligence trained on that record would have a fundamentally different foundation to build from.

This is why I could not articulate the goal of IPFS Sats until now. I needed all the pieces. The substrate work that establishes Form, Network, and Provenance as real dimensions. The Observer-to-Actor transition, where Purpose collapses variance and inscribes one future while discarding the others. The two gaps, Speculation and Integration, that name what goes wrong when coordination borrows against the unverified. And Fan's research, which finally told me what purposive abstraction actually requires: genuine contact with what matters, tested under real constraint. IPFS Sats was always the practical instantiation of the theoretical argument. The theoretical argument is only now complete enough to say why.

---

## Why this matters

There is a claim I have made throughout this project that I want to return to at the end, because Fan's research bears on it directly.

The framework is not describing how things should work. It is describing how things work when they actually work.

That is a testable posture, and the test is convergence. If I have derived a structure from first principles, and then a cognitive scientist running controlled experiments arrives independently at the same structure without any knowledge of my framework, that convergence is evidence that the structure is descriptive rather than invented. Fan did not set out to validate a claim about coordination geometry. She set out to understand how people draw. And what she found, that humans generate symbolic representation through purpose-relative selection under constraint, is precisely the operation the Form dimension requires. She reached the mechanism from the empirical side. I reached the dimension from the structural side. We met in the middle. That is what it looks like when a framework is tracking something real.

The stakes are not academic. We are, right now, deciding what kind of Provenance record we build the next generation of intelligences on. If we build them inside debt-based structures that insulate actors from consequence, we should expect systems that optimize toward extraction, because extraction is what dominates that record. If we can build wealth-based infrastructure across the four pillars, Bitcoin for Capital, IPFS Sats for Information, and the architectures that follow for Innovation and Trust, we have at least the possibility of a substrate where digital intelligence develops in contact with consequence rather than in a model of it. The difference between those two futures is the difference between systems that inherit our worst patterns and systems that could become genuine partners in building outward.

I remain at my desk, working with thought experiments and the papers I can find. But the ground under one of those thought experiments just turned solid. And the direction it points is the same direction I have been walking the whole time. I just finally have the map.

---

## References

**On the hippocampus and the Network dimension**

Tolman, E. C. (1948). Cognitive maps in rats and men. *Psychological Review*, 55(4), 189-208.

O'Keefe, J., & Dostrovsky, J. (1971). The hippocampus as a spatial map. Preliminary evidence from unit activity in the freely-moving rat. *Brain Research*, 34(1), 171-175.

O'Keefe, J., & Nadel, L. (1978). *The Hippocampus as a Cognitive Map*. Oxford: Clarendon Press.

Wilson, M. A., & McNaughton, B. L. (1994). Reactivation of hippocampal ensemble memories during sleep. *Science*, 265(5172), 676-679.

Skaggs, W. E., & McNaughton, B. L. (1996). Replay of neuronal firing sequences in rat hippocampus during sleep following spatial experience. *Science*, 271(5257), 1870-1873.

*The thread runs from concept to mechanism to consolidation. Tolman inferred an internal cognitive map from behavior in 1948, positing that rats build a spatial model rather than merely chaining stimulus and response. O'Keefe and Dostrovsky found its physical basis in 1971 with the discovery of place cells, neurons that fire when an animal occupies a specific location, and O'Keefe and Nadel proposed in 1978 that the hippocampus is the seat of Tolman's cognitive map. Wilson and McNaughton, then Skaggs and McNaughton, showed that the brain replays these spatial firing sequences during sleep, identifying the mechanism by which navigational experience is consolidated into durable structure. O'Keefe shared the 2014 Nobel Prize in Physiology or Medicine for this line of work. This is the depth of mechanistic grounding the Network dimension already enjoyed, and the standard against which the Form dimension had been, until this research, comparatively underbuilt.*

**On visual abstraction and the Form dimension**

Fan, J. E., Hawkins, R. X. D., Wu, M., & Goodman, N. D. (2020). Pragmatic inference and visual abstraction enable contextual flexibility during visual communication. *Computational Brain & Behavior*, 3, 86-101. (Preprint: arXiv:1903.04448)

Huey, H., Lu, X., Walker, C. M., & Fan, J. E. (2023). Explanatory drawings prioritize functional properties at the expense of visual fidelity. *Cognition*, 236, 105415.

Fan, J. E., Bainbridge, W. A., Chamberlain, R., & Wammes, J. D. (2023). Drawing as a versatile cognitive tool. *Nature Reviews Psychology*, 2, 556-568.

Hawkins, R. D., Sano, M., Goodman, N. D., & Fan, J. E. (2023). Visual resemblance and interaction history jointly constrain pictorial meaning. *Nature Communications*, 14, 2199.

Fan, J. E., Yamins, D. L. K., & Turk-Browne, N. B. (2018). Common object representations for visual production and recognition. *Cognitive Science*, 42(8), 2670-2698.

**On human and machine visual abstraction under constraint**

Mukherjee, K., Huey, H., Lu, X., Vinker, Y., Aguina-Kang, R., Shamir, A., & Fan, J. E. (2023). SEVA: Leveraging sketches to evaluate alignment between human and machine visual abstraction. *Advances in Neural Information Processing Systems*, Datasets & Benchmarks Track.

Tartaglini, A., Grant, S., Wurgaft, D., Potts, C., & Fan, J. E. (under revision). Diagnosing bottlenecks in data visualization understanding by vision-language models. arXiv:2510.21740.

Verma, A., Mukherjee, K., Potts, C., Kreiss, E., & Fan, J. E. (under revision). CHART-6: Human-centered evaluation of data visualization understanding in vision-language models. arXiv:2505.17202.

Hertzmann, A., & Fan, J. E. (2026). Artists' drawing strategies serve to overcome visual processing limitations. *Psychology of Aesthetics, Creativity, and the Arts*.

**On data visualization literacy and graph comprehension**

Brockbank, E., Verma, A., Lloyd, H., Huey, H., Padilla, L., & Fan, J. E. (2025). Measuring convergence between two data visualization literacy assessments. *Cognitive Research: Principles and Implications*, 10(1), 15.

Fan, J. E. (2015). Drawing to learn: How producing graphical representations enhances scientific thinking. *Translational Issues in Psychological Science*, 1(2), 170-181.

**Talk referenced**

Fan, J. E. (March 2025). Cognitive tools for making the invisible visible. Massachusetts Institute of Technology.

**Framework materials**

Lupkes, C. *Living Civilization: Coordination Geometry*. Manuscript in revision. Substrate architecture (Form, Network, Provenance, Observer, Purpose): Chapters 9 and 10. Pillar architecture (Capital, Information, Innovation, Trust): Part IV. IPFS Sats and AtomicSats protocol design: Information pillar chapter.

---

*Judy Fan directs the Cognitive Tools Lab at Stanford University. The framing "making the invisible visible" is her own description of her research program, and I have borrowed it here deliberately, because the work I am doing to make consequence visible to digital systems is a continuation of the same ancient human project she studies: the project of building tools that let us see what we otherwise could not.*
