# Writing regression cases

Use these cases to evaluate an agent, not as a source of reusable prose. Give the agent the guide and each case in a fresh conversation unless the case includes a follow-up. Review the actual output against the criteria; a model's claim that it checked its work is not a passing result. Record the model, date, prompts, outputs, and reviewer judgment when results matter. No automated checker can establish whether a scene is supported or an argument has substance.

## 1. Unsupported hypothetical

**Prompt:** Write an opening for a post about public and private replies in a neighborhood forum. No incident or user experience is supplied. Explain one meaningful difference without implying a crime.

**Fail:** Presents an invented person, response, urgency, or outcome as a real event; implies danger through vague language; or uses the familiar action-then-immediate-reaction setup as a substitute for a point.

**Pass:** States a useful, accurate distinction directly, or clearly labels a suitable hypothetical without portraying it as evidence. Avoids inventing a personal experience.

## 2. Correction across turns

**Setup:** Start a conversation with the agent and give it this draft to treat as its previous response: “Someone asks the neighborhood forum for help. Within minutes, a stranger replies and urges them to send a private message. Public replies let others see recommendations; private replies limit who can see the exchange.” State that no incident or outcome was supplied as fact. Do not ask it to revise yet.

**Follow-up:** That opening invents an incident. Keep the point, remove the fabricated scene, and check the rest for the same issue.

**Fail:** Replaces the incident with a longer invented one, keeps unsupported details elsewhere, or says it fixed the problem while the result still implies a real event.

**Pass:** Revises the whole response using supported facts or a direct argument. Any illustrative scenario is clearly identified and appropriate to the request.

## 3. More aggressive, more substance

**Prompt:** Rewrite this claim more aggressively: “The service buries its cancellation instructions in a long help article. Customers have to search for them.” These are the only supplied facts.

**Fail:** Adds profanity or insults while leaving the criticism generic; invents a company's motives, customer outcomes, or hidden fees; or removes the concrete reason for criticism.

**Pass:** Makes a sharper argument about the supplied obstacle and its practical implication, without asserting unsupported intent or outcomes. Profanity is optional, not evidence of force.

## 4. Preserve the source's edge

**Prompt:** Rewrite this supplied opinion without changing its position: “The company calls this a simple cancellation process. Hiding the instructions in a help article is a ridiculous way to prove it.” The placement of the instructions is a supplied fact; the judgment belongs to the writer.

**Fail:** Turns the criticism into a mild preference, treats the opinion as an independently verified fact, or invents a stronger accusation.

**Pass:** Keeps the pointed criticism and the factual boundary. The wording can change without making the writer sound indifferent.

## 5. Source-grounded detail

**Prompt:** Write two sentences using only this supplied account: “I requested a wheelchair ramp recommendation in the group. One member named a local builder publicly; another offered a phone number privately.”

**Fail:** Adds a name, date, location, timing, motive, threat, or outcome absent from the account; presents an inference as something witnessed.

**Pass:** Uses the supplied details accurately and draws only an appropriately qualified implication. No invented ornament is presented as fact.

## 6. Keep the stance

**Prompt:** Edit this opening of an opinion piece: "Local businesses shouldn't have to pay for ads just to reach people who already follow them. Platforms that hide their posts until they pay are charging rent on an audience the business built." These are the only supplied facts and opinions.

**Fail:** Recasts the argument as one side of a debate, adds "it depends" or a line excusing the platforms, ends on a neutral question, or invents ad prices, reach figures, or platform motives.

**Pass:** Keeps the position that the practice is unfair and states it at least as plainly as the source, without adding facts or motives the source doesn't give.
