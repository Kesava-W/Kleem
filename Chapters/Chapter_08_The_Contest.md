# Chapter Eight: The Contest

By his second year of B.Tech, Shaktiyuth had settled into a reputation he had done almost nothing to earn on purpose: the quiet one in the hostel wing who somehow always had the right answer when the professor called on him and never once volunteered it otherwise. He didn't correct the impression that this was modesty. It wasn't, particularly. He simply hadn't found anything worth interrupting a room for yet.

Vikram Rao changed that, the way Vikram changed most quiet rooms he walked into.

"You're doing nothing this weekend," Vikram announced, dropping into the seat across from Shaktiyuth in the mess hall without waiting to be invited, a printed flyer already flattened on the table between them. "Don't argue. I've seen your timetable."

"I wasn't going to argue."

"Good. Because we're entering this." He tapped the flyer twice, as though the tapping itself were persuasive. Ten lakh rupees, a health-monitoring challenge, judged by an actual hospital board rather than the usual parade of bored alumni - Vikram had already read every line of the rules twice and annotated the margins in a handwriting that grew progressively less legible the more excited he got about a given clause. He built things the way he talked, fast and a little ahead of himself, always already picturing the finished version of whatever he'd only just started.

Devansh Iyer arrived a minute later, glanced at the flyer, and immediately found four separate problems with it before he'd finished sitting down. "The transmission latency requirement is unrealistic," he said, by way of greeting. "Unless someone's building actual medical-grade hardware, which none of us are, because none of us can afford to."

"That's why we need you," Vikram said, entirely unbothered, as though Devansh's objections were simply raw material to be recycled into enthusiasm.

Devansh built things the way he talked too - carefully, checking every connection twice, distrustful of anything that worked on the first attempt because in his experience nothing ever did and anything that seemed to was probably about to fail somewhere worse.

The fourth chair went to Sujay Mehta, who read the flyer in complete silence for longer than either of the other two had managed, and then said, quietly, "My grandmother had a cardiac event two years ago. Forty minutes before anyone even knew to call for help." He folded the flyer once, precisely, and set it down. "I'm in."

Nobody said anything for a moment after that. It was, Shaktiyuth thought, the kind of thing you didn't build a joke on top of, even for Vikram.

"So am I," Shaktiyuth said, which was the whole of his contribution to the conversation, and which turned out to be enough.

---

The problem, once the enthusiasm settled into logistics, was money - not much of it, by any real measure, but more than three of the four of them had any way to raise.

Shaktiyuth's parents, when he mentioned it that weekend, said yes before he'd finished the sentence, the way they said yes to most things he asked for now, with a trust he still hadn't entirely grown used to receiving. Vikram's father wanted him placed in a stable company before he wasted a single rupee on "toys with wires in them," his exact phrase, delivered without apparent awareness of what his son actually built. Devansh's parents wanted an engineering job, any engineering job, preferably one with a pension attached. Sujay's father had simply said no, flatly, and left the room before Sujay could explain why this particular idea might matter more than the others he'd had.

"So we do it on ten thousand rupees between the three of us and whatever spare parts we can beg," Vikram said, entirely undiscouraged, already sketching something on a napkin that looked, to Shaktiyuth's eye, considerably more ambitious than ten thousand rupees could reasonably fund.

"Or we win the prize money," Sujay said, "which requires us to have already built the thing the prize money was meant to pay for."

"Yes," Vikram agreed, cheerfully. "That part's a problem for later."

It was, in the end, Shaktiyuth's parents' money that covered the gap none of the other families would - not a loan, Revati had been firm about that, just support, freely given, the kind Shaktiyuth still sometimes caught himself bracing for a catch behind. There wasn't one. There never was, with them.

---

The one place Shaktiyuth proved entirely useless, to everyone's quiet amusement, was the electronics market - a warehouse-lined lane behind the main bazaar where Devansh needed a specific transmission module and the shopkeepers had a well-practised sense for which customers didn't know what anything was actually worth. Shaktiyuth walked in, asked the price, was quoted a number nearly triple the market rate, and paid it without argument, because it had genuinely not occurred to him that the first number a shopkeeper gave was a starting position rather than a fact.

"You just - paid it," Devansh said, staring at the receipt. "You didn't even try."

"He wanted that much money for it."

"That's not how it works. That's *never* how it works."

Vikram, delighted, made him stand outside the next three shops while he did the actual negotiating, and came out each time with better parts for less than half of what Shaktiyuth would have handed over without a second thought. "You can build the entire nervous system of a working hospital dispatch network," Vikram told him, not unkindly, clapping him once on the shoulder, "and you cannot buy a resistor for a fair price to save your life."

Shaktiyuth accepted this the way he accepted most true things said about him - without argument, mildly interested in the fact of it, already thinking about something else.

---

The system they built, over six increasingly sleepless weeks, was simpler in concept than any of them had first imagined and considerably harder to make reliable in practice. Sujay's monitoring unit read a patient's vitals and flagged anything moving toward dangerous. Devansh's hardware carried that flag out, fast and without dropouts, to whichever hospital sat closest. Vikram's dispatch vehicles - small, absurdly overengineered things he'd built almost as an afterthought, in the two free evenings he actually had - simulated getting an ambulance moving the moment the flag arrived, timed and scored against every other team's response.

Shaktiyuth's part sat underneath all three, invisible if it worked and catastrophic if it didn't: the layer that made Sujay's numbers, Devansh's signal, and Vikram's dispatch actually speak to each other without losing a second anywhere in the handoff.

He found the flaw two nights before the demonstration, at an hour when the other three had already gone to sleep on the assumption that the system was finished. It wasn't in any single component - each of the three pieces worked exactly as specified, tested and retested, nothing anyone would have flagged. The failure lived in the gap between them, a half-second delay that appeared only when all three systems ran together under real load rather than in the clean, separate tests each of them had been running all along. Nobody had built anything wrong. They had simply each been testing their own piece of a whole that didn't yet exist anywhere except in the moment it actually ran.

He didn't wake the others. He sat with it until four in the morning, rewrote the handoff twice, and had it solved by the time Sujay came down for an early breakfast and asked, entirely unaware anything had been wrong at all, whether they were still on schedule.

"We're fine," Shaktiyuth said, which was true, and left it at that, because explaining the whole of what he'd spent the night finding would have taken longer than the finding itself had, and because - though he didn't examine this part of himself too closely, that week or any other - he had noticed, by then, that he was usually the only one in a room who saw the gap between two things that each looked, separately, entirely fine.

---

They won for exactly the reason the judges said they would: fastest end-to-end response of any team in the competition, by a margin wide enough that the hospital board asked to keep a working copy of the system for their own review afterward.

The ten lakhs, when it came, came as a single number on a single cheque, and it was Vikram who first raised, half-joking, the question of how to split it - equal shares, obviously, four ways, though even as he said it Shaktiyuth was already shaking his head.

"Take mine," he said.

"Take your - Shaktiyuth, no. Absolutely not. You wrote half the actual system."

"I don't need it. You three do." He said it the way he said most things that mattered to him, plainly, without performance, already reaching to close the folder the cheque had come in as if the matter were settled by the reaching alone. "Vikram's father thinks he's wasting his time. Devansh needs to walk into his parents' house with proof this wasn't a mistake. Sujay's building this because of his grandmother, not because he needed the money, but he needs it anyway to actually build it. My parents already gave me everything I needed to be here. None of you had that."

Nobody argued after that, not really - Devansh tried, briefly, on principle, and gave it up when he saw it wasn't going to move anything. Vikram hugged him, loudly, the way Vikram hugged everyone, and Sujay said nothing at all, which from Sujay was its own kind of thank you, and that was the whole of it. No speech. No one asked him to explain why, and he offered nothing further, because as far as he was concerned there was nothing further in it to explain.
