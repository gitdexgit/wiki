
# FILE: 3 principles to apply to any data.md
---

These will help me filter data really fast in scratch and really insure that what I'm about to learn is worth the time, or I'm about to introduce is worth it.



- First Principles removes the Sludge (Analogies/Assumptions).

- Inversion removes the Stupidity (Failure paths).

- Falsification removes the Lies (False notes).



# FILE: code defined by cs50 youtube video from harvard.md
---

Code is just taking inputs; The input is some standardized way of representation of
information and spitting out answers.

https://youtu.be/UuIEbpQms8o?t=3905
![](https://youtu.be/UuIEbpQms8o?t=3905)



# FILE: command to watch autoshot script.md
---

In the tmux "watch" session you can run this command. This is a very handy command to be used in the watch session In qtemrinal dropdown.

```bash
watch -n 5 "ps -eo state,pid,cmd | grep '[a]utoshot.sh'"
```

Here is a picture demonstrating it:

https://i.imgur.com/KMy6eqI.png
![](https://i.imgur.com/KMy6eqI.png)




# FILE: computer science being defined in a video course CS50 in 2hrs.md
---

Just watch the video if you forget about CS, Computational thinking, Algorithms.

https://youtu.be/UuIEbpQms8o?t=3514
![](https://youtu.be/UuIEbpQms8o?t=3514)



# FILE: invert to succeed by avoiding failure to guarantee high probability rate of truth.md
---

Use this in the scratch by making a ## section at the bottom called The invert. This is really solid. Always and always invert.


# Invert to Succeed: Avoid Failure to Guarantee Progress

**Core Principle:** Inversion is the practice of thinking backward. Instead of asking how to achieve a goal, ask how to guarantee failure. By identifying and avoiding the "path to failure," you clear the most direct path to success.

### Claim 1: It is easier to avoid stupidity than to seek brilliance.
Most problems are too complex to solve with a single "brilliant" idea. It is much easier to identify the behaviors that cause certain failure and simply stop doing them.
*   **Evidence:** In competitive games like *League of Legends*, players often win not by making "big plays," but by avoiding "idiot" mistakes like overextending without vision or flaming teammates. Success comes from "winning by not losing."

### Claim 2: Anti-goals create a "Security Protocol" for your projects.
Defining an "Anti-goal" (the worst possible outcome) allows you to build a checklist of what to avoid. This transforms a vague hope for success into a concrete plan for safety.
*   **Evidence:** When building a circuit, an engineer can invert the goal: "How do I make this fail?" The answers—reversing polarity or omitting a heat sink—become a mandatory safety checklist.

### Claim 3: Inversion defines your "Operating Space."
Inversion works with First Principles to set boundaries for your thinking. While First Principles find the "floor" (what is true), Inversion finds the "ceiling" (what is a failure).
*   **Evidence:** In learning a new language like C, the "Anti-goal" is to remain confused forever by never drawing memory maps. The "Attack" is the opposite: always draw the map to stay within the successful operating space.

***

**Summary for Quick Use:**
*   **The Method:** Ask, "How could I guarantee this fails spectacularly?"
*   **The Action:** Do the exact opposite of that answer.
*   **The Result:** You bypass "fuzzy thinking" and go straight to a hardened, reliable strategy.



# FILE: nvim fo r flag continues markdown blockquotes.md
---

**Automating blockquote leaders maintains writing flow by removing manual formatting tasks.**

The `r` flag in `formatoptions` continues the current comment leader (`>`) after a carriage return. Since Neovim identifies Markdown blockquotes as comment leaders, this enables seamless multi-line quoting.

```vim
:set fo+=r
```

---

#wiki #nvim #automation-typing #action
> [Practice in scratch.md; tag \#internalized once mastered.]



# FILE: properties of a truth fundamental.md
---

to help me find truth fundamentals, they should have these bellow characteristics:

@ai:
A truth is fundamental if:

    It is Tool-Independent (Works in C, Python, and Assembly).

    It is Universal (Works on Linux, Windows, and a Toaster).

    It is a Constraint (You cannot "code your way around" it).

    It has no "It's like..." in the definition.

Don't worry about being "Right" on day one. Worry about being "Deep." Keep digging until you hit the hardware or the physics. That is where the "Gold" for an inventor is buried.



# FILE: Solve complex problems by composing a sequence of reliable modular components where each verified output functions as the next input.md
---

Building complex solutions requires nesting verified outputs as inputs because connecting reliable small components allows you to solve minor problems that together conquer bigger ones.

Complex software scales by treating each completed function as a building block where the "answer" from an inner step directly plugs into the next step to perform more advanced work.

https://youtu.be/UuIEbpQms8o?t=5237
![](https://youtu.be/UuIEbpQms8o?t=5237)



# FILE: the 6 socratic type questions used for critical thinking a scratch.md
---

So here are the types of questions you should ask when you are attacking in your scratch. The main idea is to ask questions so that you are not stuck in the why? why? why? why? loop, even though why? why? is good another approach or tools are just using good questions that target specific areas when you are in the scratch.

Good questions to start are the evaluation questions and then you move your way down. So you are working on bloom's taxonomy higher level. Studies show that, if you know the "So what?" and like work at the evaluation part it's more rewarding and easier to understand and remember and apply better. So work on the higher levels for and even analyse as well.


@ai:
How to use these in your scratch.md

When you are transcribing and you feel the "urge to attack," don't just write "This is wrong." Pick a skillshot:

    Clarify: "Define [X] better."

    Assume: "You're assuming [X], but what if [Y]?"

    Evidence: "Show me the logs for this."

    Perspective: "An expert in [X] would call this trash because..."

    Consequence: "This leads to [X] failure later."

    Meta: "This whole topic is a distraction from the real goal."

The "Triangle" Example using the 6 Types:

    Source: "A triangle is a shape."

    Clarification: "What kind of shape? 2D or 3D?"

    Assumption: "Are you assuming the lines must be straight?"

    Evidence: "Can you show me a triangle with 4 sides? No? Then '3 sides' is the requirement."

    Perspective: "A topologist might say a triangle and a circle are the same. Why are we focusing on the sides?"

    Consequence: "If I define it this way, does it exclude 'curved' triangles on a sphere?"

    Meta: "Does defining a triangle actually help me build this bridge?"



# FILE: use inference to the best explanation to gather the raw material for your logical filter.md
---

# IBE: The Discovery Phase of Reasoning

**Core Principle:** Inference to the Best Explanation (IBE) is the process of reasoning from a set of observations to the most plausible cause. It is the logical "detective work" that allows us to move from raw data to a working theory.

### Why We Use IBE
We use IBE to solve mysteries or explain phenomena where the cause isn't immediately obvious. It allows us to hypothesize *why* something happened by looking at the results.

### The Power of "More Options"
The most critical stage of IBE is the **generation of explanations.** At the start of an investigation, the goal is to cast a wide net.
*   **The Rule:** The more options you generate, the better.
*   **The Logic:** If you only consider one or two explanations, you are more likely to be blinded by your own biases. By listing every possible cause—even the unlikely ones—you ensure that the true explanation is actually on the table before you begin evaluating them.

### How it Works (The Exploration Phase)
Imagine you wake up and see the grass is wet.
*   **Option 1:** It rained overnight.
*   **Option 2:** The sprinklers turned on.
*   **Option 3:** A water truck leaked while driving by.
*   **Option 4:** A neighbor washed their car late at night.

By using IBE to find **as many options as possible**, you prevent yourself from jumping to a conclusion (like "it rained") before considering other valid possibilities.

### The Connection: IBE as the Funnel, Occam’s Razor as the Filter
IBE and Occam’s Razor work as a two-part system:

1.  **IBE provides the Options:** It acts like a wide funnel, gathering every potential explanation for a set of facts.
2.  **Occam’s Razor provides the Filter:** Once IBE has given you a list of choices, you apply **Occam’s Razor** to "shave away" the fluff. You look at your list and ask: *"Which of these requires the fewest unproven guesses?"*

**Summary:** IBE finds the candidates; Occam’s Razor picks the winner. Use IBE to be **creative and thorough**, then use Occam’s Razor to be **rational and simple.**



# FILE: use second-order thinking to ensure your short-term wins don't become long-term disasters.md
---

Basically think of the results of your actions, like ok you will do that, you will gain x, but at what cost, meaning what happens next? If the cost is so high then don't take it. If the benefits outweighs the cost or there is little to no cost, take it.

---

**Summary for Quick Use:**
*   **The Question:** Ask the "Duck," *"I'm doing [X] to get [Y]. And then what happens?"*
*   **The Rule:** Never make a first-order win that leads to a second-order loss.
*   **The Goal:** Prioritize long-term stability over "fast" fixes.



# Audit the Aftermath: Use Second-Order Thinking to Ensure Your Short-Term Wins Don't Become Long-Term Disasters

**Core Principle:** Second-order thinking is the study of the **consequences of consequences.** It is the practice of asking "And then what?" to ensure that an immediate "win" does not create a much larger problem in the future.

### Claim 1: First-order "wins" often hide second-order "losses."
Most people stop thinking at the immediate result of an action. However, every result creates a new environment with its own set of problems. A decision that solves a problem today may "throw the game" tomorrow.
*   **Evidence:** Using a complex code library might solve a problem in ten minutes (first-order win). However, it creates a massive dependency you do not understand. When that library has a bug or an update, your entire invention breaks, and you cannot fix it (second-order loss).

### Claim 2: Second-order thinking identifies "invisible" physical and logical stress.
In engineering and programming, actions have cascading effects on heat, power, and complexity. Thinking one step ahead allows you to build "hardened" systems that survive real-world use.
*   **Evidence:** Increasing voltage makes a motor spin faster (first-order). However, the higher current generates heat that can melt solder or blow a component (second-order). By thinking ahead, you know that increasing speed **must** include adding a heat sink.

### Claim 3: High-utility notes protect you from negative second-order effects.
A note has high utility if it prevents a future disaster rather than just stating a fact. If a decision only provides a short-term gain but has a high long-term cost, it should be filtered out.
*   **Evidence:** In *League of Legends*, diving a tower for a kill gives you 300 gold (first-order). But if you use your "flash" and "ultimate" to do it, you are now defenseless when the enemy jungler arrives to take the Dragon (second-order loss).

***




# FILE: valgrind is a popular too for managing memory and debugging c code so use it.md
---

I did `sudo pacman -S valgrind`

@ai:

Yes, Valgrind is extremely popular—it is considered the industry standard for memory debugging and profiling on Linux, particularly for C and C++ development.[1]

Since you are on Arch Linux and using both C and Python, here is how it fits into your workflow



some notes make what is bellow an alternative so valgrid? But only after I actually try it out lol I don't even know what this is:


Is there a modern alternative?

While Valgrind is very popular, many developers have moved toward AddressSanitizer (ASan) for C programming.[1]

    Valgrind: Works on the binary; very thorough; makes the program run 10x–30x slower.[1][4]

    ASan: Built into the compiler (-fsanitize=address); much faster (only 2x slower); but requires recompiling your code.[1][2]

Conclusion: For a Linux developer writing C, Valgrind is a "required skill" for your resume and a lifesaver for your code. For Python, it's a specialized "heavy-duty" tool you'll only need when things go seriously wrong at the system level.



# FILE: what is truth in my system.md
---

What is truth in my system. Moving notes from beta to active.

@ai:
5. The Spartan's Stance on "Truth"

In your system, Truth is what remains after you have tried everything to prove it's a lie.

    If the AI Assassin can't kill it.

    If the Vault Evaluation can't find a contradiction.

    If Fuzzing doesn't break it.

    If Reality doesn't punish you for it.

Then, and only then, does it move to ~/work/active or it has no ? at as a title of the note.



# FILE: when faced with two choices, the simplest explanation wins.md
---

By choosing the simplest path, you minimize the risk of error and avoid building theories on "crap" or unproven fluff.

https://youtu.be/3BxxKE-NcRo
![](https://youtu.be/3BxxKE-NcRo)

Occam’s Razor: The Power of Simplicity

Core Principle: Occam’s Razor is a logical tool used to find the truth by choosing the explanation that makes the fewest assumptions. When faced with two explanations that explain the same facts equally well, the simpler one is usually the correct one.
Why We Use Occam’s Razor

We use this principle to "shave away" unnecessary complexity. Every time you add an extra "entity" (a thing) or a "supposition" (a guess) to an explanation, you create a new way for that explanation to be wrong. By choosing the simplest path, you minimize the risk of error and avoid building theories on "crap" or unproven fluff.
How it Works (The "Shaving" Process)

Imagine you hear a loud rumbling sound outside your house near the train tracks.

   - Explanation A: A train is passing by. (Simple; requires no new assumptions).

   - Explanation B: A giant, invisible robot is jogging down the street. (Complex; requires you to believe in robots, invisibility, and a reason for them to be there).

Since both explain the noise, Occam’s Razor tells you to "shave off" the robot. Explanation A is the most rational starting point because it uses the fewest "extra parts."
Significance to "Inference to the Best Explanation" (IBE)

Occam’s Razor and IBE are partners in logic, but they play different roles:

   - IBE is the Goal: It is the process of looking at all available evidence and deciding which theory is "best."

   - Occam’s Razor is the Filter: It provides the criteria for what makes an explanation "best."

While an explanation must be accurate to be considered "the best," Occam’s Razor argues that simplicity is a primary indicator of quality. We infer that the simplest explanation is the best one because it is the most likely to be true without needing extra, unproven miracles to function.
Summary for Quick Reference

   - The "What": The simplest explanation is usually the right one.

   - The "Why": Fewer assumptions mean fewer chances to be wrong.

   - The "Relationship": Simplicity (Occam’s Razor) is the yardstick we use to measure which explanation is the "best" (IBE).



