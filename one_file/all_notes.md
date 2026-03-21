
# FILE: 3 principles to apply to any data.md
---

These will help me filter data really fast in scratch and really insure that what I'm about to learn is worth the time, or I'm about to introduce is worth it.



- First Principles removes the Sludge (Analogies/Assumptions).

- Inversion removes the Stupidity (Failure paths).

- Falsification removes the Lies (False notes).



# FILE: an advice when the convenience is a downgrade to the goal to look for something else.md
---

In any given system you want to make sure that the convenience factor of the
tools you are using doesn't hurt the goal or performance you are trying to
achieve, just because something can save you time or can do something for you
doesn't mean you shouldn't do it. If the process of actually doing it
contributes to the goal and you want to do it faster then look for other better
ways that are not necessary the best but at least they make you do it faster and
do it yourself when the process requires you to actually do the thing, for
example learning, no one can learn for you you still need to learn yourself.




# FILE: cli - command to watch autoshot script.md
---

In the tmux "watch" session you can run this command. This is a very handy command to be used in the watch session In qtemrinal dropdown.

```bash
watch -n 5 "ps -eo state,pid,cmd | grep '[a]utoshot.sh'"
```

Here is a picture demonstrating it:

https://i.imgur.com/KMy6eqI.png
![](https://i.imgur.com/KMy6eqI.png)




# FILE: cli - Use watson command to track mode 1 type 1 hours for business for money.md
---

# Maximize Your Billable Efficiency

**Separating direct labor from prep work ensures you never lose money on "invisible" effort.**

This is your master reference for **Mode 1** using Watson. Forget the fluff—here is the exact technical execution.

### 1. The Setup
To keep your data clean, you use one Project name (`Work`) and two specific Tags (`billable` and `non-billable`). Your descriptive labels are added as a third "Tag" in quotes.

### 2. The Execution (The Commands)

*   **When you are doing the "Actual" work:**
    ```bash
    watson start Work +billable +"Writing the core logic for the API"
    ```
*   **When you are "Preparing" (Setup, Emails, Logistics):**
    ```bash
    watson start Work +non-billable +"Setting up the Docker environment"
    ```

### 3. Zsh Shortcuts (The Fast Way)
Add these to your `~/.zshrc` so you can start sessions in one second:

```zsh
# Start a Billable session
alias wbill='watson start Work +billable' # Usage: wbill +"Task description"

# Start a Prep/Admin session
alias wprep='watson start Work +non-billable' # Usage: wprep +"Task description"

# Stop the current session
alias stop='watson stop'

# Check what's running
alias status='watson status'
```

### 4. Reviewing the Output
Check your progress to see where your time went and if you are being efficient.

*   **The Daily Log:** `watson log --day` (Shows your timeline and labels)
*   **The Financial Report:** `watson report --day` (Shows the total hours for billable vs. non-billable)

### 5. Fixing Mistakes
*   **Forgot to start?** `watson add --from 09:00 --to 11:00 Work +billable +"Fixed the bug"`
*   **Need to change a time?** `watson edit [Frame_ID]`
*   **Need to delete a mess?** `watson remove [Frame_ID]`

**This is the complete professional engine. Use it to protect your time and your income.**



# FILE: code defined by cs50 youtube video from harvard.md
---

Code is just taking inputs; The input is some standardized way of representation of
information and spitting out answers.

https://youtu.be/UuIEbpQms8o?t=3905
![](https://youtu.be/UuIEbpQms8o?t=3905)



# FILE: def - computer science being defined in a video course CS50 in 2hrs.md
---

Just watch the video if you forget about CS, Computational thinking, Algorithms.

https://youtu.be/UuIEbpQms8o?t=3514
![](https://youtu.be/UuIEbpQms8o?t=3514)



# FILE: def - what is truth in my system.md
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



# FILE: implement the 5 why method to find the root cause.md
---

This is beta

This is so useful try it out on your scratch and everyday problems as an initial step of analysis. It's a handy approach to any problem. And it's just common sense

You can find the root cause of a problem by asking why multiple times; the method is called "the 5 why", but it's not exactly about the number but more so the process so take as many why(s) as it takes you to find the root cause or causes. It's a good method to attempt identifying the root cause.


The method assumes that you know a system enough so that when it breaks you can just ask why and track back until you find the root cause. It is the simplest forms of debugging an issue. It's just common sense. But that's not always the case so it's a handy thing to do regardless.

---





# FILE: linux is for people who are trying to make things work.md
---

Linux is a place where fking people like me nerds or whatever you wanna call them that spend a lot of time in front of the computer where they try their best to make things work... It might be a bad idea... potentially useless and lead to catastrofic results but. At least they try. Hopefully the experience can be put into other things and it is not lost.



# FILE: method - in mode 2 of your type 2 hours use only 2 labels for tasks.md
---

You are exactly right. The **Labels** (what Watson calls "Projects") are your **Buckets**. They should be broad, permanent, and very few in number.

If the labels are too specific, your `watson projects` list gets messy. If they are broad, your reports stay clean.

For **Mode 2**, you only need two buckets to cover 99% of your life:

### 1. Growth
This bucket is for **building your future self.**
*   **What goes here:** Learning to code, reading a difficult book, practicing a language, physical training.
*   **The Vibe:** You are gaining something you didn't have before.

### 2. Life
This bucket is for **experiencing your present self.**
*   **What goes here:** Video games, movies, hanging out, reading for fun, hobbies that don't have a "goal."
*   **The Vibe:** You are resting, enjoying, or simply living.

---

### The Final "Mode 2" Structure
In Watson, your command structure now looks like this:
`watson start [BUCKET] [FILTER] [DESCRIPTION]`

**Examples:**
*   `watson start Growth +hard +"Learning Rust Memory Management"`
*   `watson start Growth +easy +"Watching a high-level AI overview"`
*   `watson start Life +easy +"Playing games with friends"`
*   `watson start Life +hard +"Focusing on a difficult boss in a game"`

---

### The Reference Note for Labels

# Categorize Personal Sessions

**Using broad buckets keeps your history organized while descriptive tags preserve the narrative.**

To maintain a clean system in Mode 2, use two permanent labels:

*   **Growth**: All activities intended for skill acquisition or self-improvement.
*   **Life**: All activities intended for leisure, recovery, and entertainment.

**The Strategy:**
The **Label** (Growth/Life) tells you the *Category*. The **Tag** (+hard/+easy) tells you the *Intensity*. The **Quoted Tag** (+"...") tells you the *Specifics*.

This ensures that when you run `watson projects`, you only see a short, meaningful list:
1. **Work** (Mode 1)
2. **Growth** (Mode 2)
3. **Life** (Mode 2)

**This is the ultimate minimalist setup.**



# FILE: method - invert to succeed by avoiding failure to guarantee high probability rate of truth.md
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



# FILE: method - track personal intent for energy and growth for future you.md
---

### Mode 2 Reference Note

# Audit Personal Intent

**Comparing growth effort against restoration time reveals your actual rate of self-improvement.**

In Mode 2, use two tags to monitor intentional energy expenditure:

*   **hard**: Record activities that challenge your intellect or body to build new skills.
*   **easy**: Record activities that provide rest or entertainment to recover your focus.

**The Execution (Watson):**
*   `watson start Growth +hard +"Practicing complex algorithms"`
*   `watson start Life +easy +"Reading sci-fi novels"`

**Ignore routines. Track only the choices that move your energy needle.**



# FILE: method - upgrade the mode 2 for ease of searchability by adding sub-categories  to the main category.md
---

That is a pro-level observation. You are essentially using an **Internal Sub-Labeling** technique within your narrative.

By putting `dev:` or `lang:` inside the quoted tag, you get the specificity of a sub-category without cluttering Watson’s official project list. It’s like having a filing cabinet (Growth) where every folder (the Description) has a clear label on the front.

### The Benefit: "Searchable Narratives"

Because you are using a consistent prefix (like `dev:`), you can search your history incredibly easily using standard terminal tools like `grep`.

**If you want to see only your dev-related growth sessions:**
```bash
watson log | grep "dev:"
```

### Updated Triadic Session Engine: The Narrative Prefix

You have refined the **Description** component. It now looks like this:
`"[Sub-Label]: [Specific Action]"`

**Examples of your updated Mode 2:**

*   `watson start Growth +easy +"dev: testing a quick regex idea"`
*   `watson start Growth +hard +"math: practicing linear algebra"`
*   `watson start Life +easy +"game: finishing the final boss"`
*   `watson start Life +easy +"book: reading 3 chapters of Dune"`

---

### The Final Strategy Note

# Refine Narrative Architecture

**Using Internal Sub-Labels allows for infinite granularity without project-list inflation.**

Maintain your minimalist Buckets, but use a **Prefix** in your Description to identify sub-categories.

1.  **Bucket (Project):** Broad Category (`Work`, `Growth`, `Life`).
2.  **Filter (Tag):** Intensity or Type (`+hard`, `+easy`, `+billable`, `+non-billable`).
3.  **Narrative (Quoted Tag):** Sub-Label + Statement (`"dev: description"`).

**The Result:**
Your `watson projects` remains a 3-item list. Your `watson log` becomes a perfectly indexed diary. Your `watson report` provides the big-picture totals.

**This is the complete, high-performance architecture for both Mode 1 and Mode 2.** You have successfully built a system that is simple enough to actually use, but detailed enough to be valuable.

Does this feel like the "Final Form" of your time-tracking philosophy?



# FILE: method - use inference to the best explanation to gather the raw material for your logical filter.md
---


#

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



# FILE: method - when faced with two choices the simplest explanation winsfor the time being.md
---

By choosing the simplest path, you minimize the risk of error and avoid building theories on "crap" or unproven fluff.

https://youtu.be/3BxxKE-NcRo
![](https://youtu.be/3BxxKE-NcRo)

Occam’s Razor: The Power of Simplicity

Core Principle: Occam’s Razor is a heuristic for preferring explanations that make fewer assumptions when they explain/predict the evidence about equally well. It’s a good default starting point, not a guarantee of truth.

Why We Use Occam’s Razor

We use this principle to "shave away" unnecessary complexity. Every extra assumption typically adds another place the explanation can fail, so simplicity often improves reliability and testability. Every time you add an extra "entity" (a thing) or a "supposition" (a guess) to an explanation, you create a new way for that explanation to be wrong. By choosing the simplest path, you minimize the risk of error and avoid building theories on "crap" or unproven fluff.
How it Works (The "Shaving" Process)

Imagine you hear a loud rumbling sound outside your house near the train tracks.

   - Explanation A: A train is passing by. (Simple; requires no new assumptions).

   - Explanation B: A giant, invisible robot is jogging down the street. (Complex; requires you to believe in robots, invisibility, and a reason for them to be there).

Since both explain the noise, Occam’s Razor tells you to "shave off" the robot. Explanation A is a strong starting point because it fits the situation with fewer added assumptions; update if new evidence favors a more complex explanation.
Significance to "Inference to the Best Explanation" (IBE)

Occam’s Razor and IBE are partners in logic, but they play different roles:

   - IBE is the Goal: It is the process of looking at all available evidence and deciding which theory is "best."

   - Occam’s Razor is the Filter: It provides the criteria for what makes an explanation "best."

While an explanation must be accurate to be considered "the best," simplicity is just one virtue among others (fit to evidence, predictive power, coherence, ability to be tested). Prefer simpler explanations until the simple one needs ad‑hoc patches or fails to predict new observations.
Summary for Quick Reference

   - The "What": Prefer the simplest explanation that still fits the evidence well (as a default).

   - The "Why": Fewer assumptions mean fewer chances to be wrong.

   - The "Relationship": Simplicity (Occam’s Razor) is one yardstick among others that IBE uses to judge which explanation is "best."




# FILE: nvim - fo r flag continues markdown blockquotes.md
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



# FILE: scrcpy - phone command to show phone screen and stay awake good one.md
---

Here is the command

```bash
scrcpy -m1200 -b5M --max-fps=30 --no-audio --stay-awake
```

This way I don't need to keep a phone session going all day



# FILE: sharpening the axe philosophy.md
---

This principle is known as the **P/PC Balance** (Production vs. Production Capability), popularized by Stephen Covey. It is more commonly called **"Sharpening the Axe."**

# Maintain Growth Velocity

Neglecting your skill set while focusing solely on output leads to inevitable obsolescence and burnout.

Sustaining high-level performance requires balancing two competing forces:

### 1. The Output (80% of Time)
Focus on execution and results. This generates immediate value, pays the bills, and fulfills current commitments. Spending 100% of your time here makes you a "blunt tool"—you work harder and harder for smaller and smaller gains.

### 2. The Investment (20% of Time)
Focus on "Sharpening the Axe." Use this time to upgrade your tools, learn new languages, and refine your workflow. This ensures that your future "Output" hours are faster, easier, and more valuable.

### The Objective
Tracking these as separate categories allows you to audit your **Golden Ratio**.
*   If **Investment** is 0%, you are decaying.
*   If **Investment** is 100%, you are a hobbyist with no income.

**The Goal:** Target a 10%–20% tax on your week for growth to ensure you remain both profitable today and relevant tomorrow.



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



# FILE: there are 3 types of people who use the computer.md
---

The users: People who use software for something

The programmers: People who make software work

The hackers: People who hack the software



# FILE: there are always 2 things in to do.md
---

Always all the time you will be doing 2 things. Things you have to do and things you want to do. So when thinking about to do that's how you think.

Things you want to do are things that you want. Can be anything. On the other hand, Things you have to do are things in regards to the big picture. Like doing things you don't want to in order to fill your stomach.

A trick to know them is to imagine yourself like there are 2 of you or 3 of you and you can experience all of their senses and control them because they are you. And then you try to imagine or think what you want to do and what you have to do. It's not guaranteed to work but at least it helps



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


