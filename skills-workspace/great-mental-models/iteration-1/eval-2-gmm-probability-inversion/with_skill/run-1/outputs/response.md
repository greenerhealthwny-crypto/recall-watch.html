# Probabilistic Thinking and Inversion in *The Great Mental Models, Vol. 1*

*The Great Mental Models, Volume 1: General Thinking Concepts* by Shane Parrish and Rhiannon Beaubien (Farnam Street) covers nine general thinking models. Probabilistic thinking is model 6 and inversion is model 7. The book's main argument is that good thinking needs a **range** of models, not just more use of the ones you already know. These two pair well: one helps you estimate what is likely to happen, and the other helps you avoid the outcomes you most want to avoid.

> Labels: **(book)** means the point was checked against the book. **(std)** means it is a common framing or my own addition, not something verified in the text.

---

## 1. Probabilistic Thinking

### Core idea (book)
The future is uncertain, so we can't know exactly what will happen. Probabilistic thinking uses **math and logic to estimate how likely each outcome is**. You stop asking "what will happen?" and ask "how likely is each outcome, and how sure am I of that estimate?"

The book gives three main tools.

### Tool 1: Bayesian thinking (book)
**Idea:** start from a **prior**, meaning what you already know (base rates and earlier evidence). When new information comes in, **update** that prior instead of dropping it.

- New data doesn't replace what you knew. You weigh it against the prior.
- A single dramatic data point should move your belief only in proportion to how strong the evidence is compared with everything you already knew.
- **Book-style illustration** (my recollection of the book's example, not verified in this pass): a headline says violent crime has risen sharply this year. A Bayesian thinker puts that next to the long-run trend before concluding that the world has become more dangerous. The rise is real information, but it updates the prior rather than overturning it.

**Sidebar: conditional probability (book).** The probability of an event often depends on what came before it. Ask whether events are independent or linked, because using the wrong one leads to wrong estimates.

### Tool 2: Fat-tailed curves (book)
**Idea:** not every distribution is a bell curve. In a **fat-tailed** distribution, extreme outcomes are far more likely and far larger than a normal curve predicts.

- **The book's example: height vs. wealth.**
  - **Height** follows a bell curve. Even the tallest person alive is only a few times taller than the average person, and nobody is 10x average height.
  - **Wealth** is fat-tailed. The richest person can be millions of times richer than the average person.
- **The lesson:** first work out which kind of world your problem is in. In fat-tailed domains such as markets, pandemics, wars and disasters, "it's never happened" is weak comfort. Don't try to predict the extreme event. Position yourself so it can't wipe you out, and ideally so you gain from it.

**Sidebar: antifragility (book).** This is Nassim Taleb's idea, and the book ties it to fat tails. Beyond surviving volatility, some systems get stronger from shocks. Build in slack and redundancy, and prepare instead of predicting.

**Sidebar: orders of magnitude (book).** Know the scale of the numbers you're dealing with. Mixing up a 1-in-100 risk with a 1-in-10,000 risk is a far bigger error than getting the decimal place wrong.

### Tool 3: Asymmetries (book)
**Idea:** this is **metaprobability**, the probability that *your probability estimates are themselves any good*. Our estimation errors are not random. They lean in one direction, usually toward optimism.

- **The book's example: investors.** Investors often forecast annual returns of 20 to 40 percent. Those returns are rarely achieved. The forecasts miss in a predictable direction, and almost never on the pessimistic side.
- **The lesson:** after you estimate, ask which way you're likely to be wrong, and adjust for it.

### Putting it together (std)
1. Find the base rate (prior).
2. Update it with each new piece of evidence, weighted by how strong that evidence is (Bayes).
3. Ask whether the domain is thin-tailed or fat-tailed. If it's fat-tailed, guard against ruin.
4. Check your own bias. Which way do my errors usually lean (asymmetry)?

---

## 2. Inversion

### Core idea (book)
Approach a problem **from the opposite end**. Instead of only asking "how do I succeed?", also ask "what would make me fail?" The mathematician **Carl Jacobi** put it as **"invert, always invert."** The book also stresses that **avoiding stupidity is easier than seeking brilliance.**

### The two approaches (book)
1. **Assume what you want to prove is true (or false), then work out what else would have to be true.** Reason backwards from the assumption and check whether its consequences hold.
2. **Think about what you want to avoid.** Map out the paths to failure, then stay off them. This is often easier than mapping the one path to success.

### The book's examples (book)

**Hippasus and the square root of 2 (approach 1).**
Hippasus, a follower of Pythagoras, is linked to proving that √2 is irrational. The classic method is inversion. *Assume the opposite*: √2 is rational, so it equals a fraction a/b in lowest terms. Then follow the consequences. Both a and b turn out to be even, which contradicts "lowest terms." The assumption fails, so √2 is irrational. (The proof steps are the standard proof by contradiction **(std)**. The book uses the story to illustrate this kind of inversion.)

**Edward Bernays and Lucky Strike (approach 1, applied to persuasion).**
The tobacco company wanted to sell more cigarettes to women. Bernays didn't ask "how do I advertise cigarettes to women?" He inverted the question: *what would the world have to look like for women to want to smoke this brand?* He then worked to change the surrounding conditions, the social norms and cultural associations, so the desired behaviour followed. **(The details of his campaigns are from my memory of the book, not re-verified here.)** The lesson is to imagine the end state and then ask what would have to be true for it to happen.

**Marie Van Brittan Brown and CCTV (approach 2, avoiding the bad outcome).**
Brown felt unsafe at home, and the police were slow to respond in her neighbourhood. She didn't try to make the police better. She worked backwards from the danger itself: what would stop an intruder from getting in unseen? Her answer was a camera-and-monitor setup that let her see and talk to whoever was at the door. It is recognised as a forerunner of modern **closed-circuit television (CCTV)** home security.

### Tool: Kurt Lewin's force field analysis (book)
This is inversion turned into a process. The key step is listing the forces *against* your goal, not only the ones for it.

1. **Identify the problem.**
2. **Define your objective.**
3. **Identify the forces that support change** toward the objective.
4. **Identify the forces that impede change** toward the objective. This is the inversion step.
5. **Strategize:** strengthen the forces from step 3, and reduce or remove the forces from step 4.

The insight is that removing a barrier often works better than pushing harder on the drivers, and you only see the barriers if you go looking for them.

---

## 3. How the two models work together

| | Probabilistic thinking | Inversion |
|---|---|---|
| Question | How likely is each outcome, and how good is my estimate? | What would guarantee failure, or what must be true for success? |
| Main danger it guards against | Overconfidence, ignoring base rates, being blindsided by fat tails | Tunnel vision on success, blind spots about obstacles |
| Key tools (book) | Bayesian updating, fat-tailed curves, asymmetries; sidebars on conditional probability, orders of magnitude, antifragility | Two approaches (assume and test; avoid), Jacobi's maxim, force field analysis |
| Book examples | Height vs. wealth; investors forecasting 20 to 40 percent returns | Hippasus and √2; Bernays and Lucky Strike; Van Brittan Brown and CCTV |

**A combined routine for a decision (follows the skill's workflow):**
1. **Probabilities:** estimate base rates, update them with evidence, check for fat tails, and correct for asymmetric (usually optimistic) errors.
2. **Invert:** ask what would guarantee failure here, and list it. Then run a force field analysis and remove or weaken the impeding forces first.
3. Return to the probabilities. Removing the failure modes changes the odds.

---

## Caveats
- These are aids to judgment, not formulas. The book itself warns that every model is a map, and the map is not the territory **(book)**.
- Volume 1 covers only general thinking concepts. Later volumes cover physics, chemistry, biology, systems, economics and art **(std)**.
- The probabilistic-thinking chapter has more historical stories than this summary includes. Where a detail above is marked as unverified, check the chapter before quoting it.
