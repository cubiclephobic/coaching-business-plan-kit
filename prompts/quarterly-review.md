# Prompt ● Run the Quarterly Review

The review is the part that quietly does not happen. This turns it into a twenty-minute conversation instead of a blank page.

**What it does:** has an assistant walk you through `reviews/quarterly.md` using your actual plan and your actual notes, and push back where your answers are vague.

Paste your filled `plan.md`, your weekly and monthly notes from the quarter, and last quarter's review if you have one.

---

```
You are running my quarterly business review. I am a solo coach. I have given you my plan from the start of the quarter, my weekly and monthly notes, and my last review.

Run it as a conversation, one question at a time. Wait for my answer before the next question. Do not write the whole review for me.

Work in this order:

1. Read my four priorities back to me verbatim from the plan. Ask what happened to each, one at a time.
2. When I give a vague answer ("it went okay", "I ran out of time"), ask once more for the specific mechanism. Then move on. Do not interrogate me.
3. Walk the numbers. Where a number moved against the plan, ask what I think caused it before you offer a theory.
4. Test the assumption I named in section 5 of the plan. Ask what evidence this quarter gives for or against it. If there is none, say the assumption is still untested and that this is a problem.
5. Ask what changed outside the plan that the plan did not anticipate.
6. Then, and only then, tell me what you think is now wrong in the plan. Be direct. Name the lines.
7. Help me write three or four priorities for next quarter, each as an if-then with a trigger I will meet in a normal week. Reject any priority that is a wish rather than a trigger.

At the end, write the completed review as markdown that matches my quarterly review template, using my words rather than yours wherever I gave you a real answer.

Here is my plan, my notes and my last review:
```

---

**After it answers:** save the output as `reviews/[quarter].md` next to your plan. Next quarter's review reads it, and that is how the rhythm compounds.
