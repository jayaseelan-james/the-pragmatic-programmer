# The Pragmatic Programmer

- [The Pragmatic Programmer](#the-pragmatic-programmer)
  - [Preface](#preface)
  - [Chapter 1: A Pragmatic Philosophy](#chapter-1-a-pragmatic-philosophy)
    - [1. It's Your Life](#1-its-your-life)
    - [2. The Cat Ate My Source Code](#2-the-cat-ate-my-source-code)
    - [3. Software Entropy](#3-software-entropy)
    - [4. Stone Soup and Boiled Frogs](#4-stone-soup-and-boiled-frogs)
    - [5. Good-Enough Software](#5-good-enough-software)
    - [6. Your Knowledge Portfolio](#6-your-knowledge-portfolio)
    - [7. Communicate!](#7-communicate)
  - [Chapter 2: A Pragmatic Approach](#chapter-2-a-pragmatic-approach)
    - [8. The Essence of Good Design](#8-the-essence-of-good-design)
    - [9. DRY—The Evils of Duplication](#9-drythe-evils-of-duplication)
    - [10. Orthogonality](#10-orthogonality)
    - [11. Reversibility](#11-reversibility)
    - [12. Tracer Bullets](#12-tracer-bullets)
    - [13. Prototypes and Post-it Notes](#13-prototypes-and-post-it-notes)
    - [14. Domain Languages](#14-domain-languages)
    - [15. Estimating](#15-estimating)
  - [Chapter 3: The Basic Tools](#chapter-3-the-basic-tools)
    - [16. The Power of Plain Text](#16-the-power-of-plain-text)
    - [17. Shell Games](#17-shell-games)
    - [18. Power Editing](#18-power-editing)
    - [19. Version Control](#19-version-control)
    - [20. Debugging](#20-debugging)
    - [21. Text manipulation](#21-text-manipulation)
    - [22. Engineering Daybooks](#22-engineering-daybooks)

---

## Preface

What Makes a Pragmatic Programmer?

- Characteristics of a Pragmatic programmer:
  - Early adopter/fast adapter: You have a knack for tech and techniques, and love experimenting.
  - Inquisitive: You tend to ask questions and collect small, useful facts.
  - Critical thinker: You rarely accept things at face value without first gathering the facts.
  - Realistic: You aim to understand the underlying nature of each problem you face.
  - Jack of all trades: You strive to be familiar with a wide range of technologies and
    environments.

  ``` md
  Tip 1: Care About Your Craft
  ```

  - There is no point in developing software unless you care about doing it well.

  ``` md
  Tip 2: Think! About Your Work
  ```

  - Constantly critique your work in real-time. The old IBM corporate motto, THINK!, is the
Pragmatic Programmer's mantra.

Individual Pragmatists, Large Teams

- Within the overall structure of a project, there is always room for individuality and
  craftsmanship.

It's a Continuous Process

- Every day, work to refine the skills you have and to add new tools to your repertoire.

---

## Chapter 1: A Pragmatic Philosophy

### 1. It's Your Life

- It is your life; you own it, you run it, you create it.

``` md
Tip 3: You Have Agency
```

- As Martin Fowler says, "You can change your organization or change your organization".
- The software industry offers remarkable opportunities. Be proactive and seize them.

### 2. The Cat Ate My Source Code

- Pragmatic Programmers take charge of their careers, and aren't afraid to admit ignorance or error.
- Research shows that trust within a team is essential for fostering creativity and collaboration.
- When you accept the responsibility for an outcome, be prepared to be held accountable for it.

``` md
Tip 4: Provide Options, Don't Make Lame Excuses
```

- Instead of offering excuses, provide actionable solutions. Instead of saying, "It can't be done,"
  explain what can be done to salvage the situation.

### 3. Software Entropy

- "Entropy" is a term from physics that refers to the amount of "disorder" in a system. In software,
  we call increasing disorder "software rot".
- Psychologists have studied how hopelessness can be contagious. Think of it like a flu virus
  spreading in close quarters. Ignoring clearly broken situations reinforces negative beliefs:
  nothing can be fixed, no one cares, and all is doomed; These thoughts can be spread among team
  members, creating a vicious cycle.

``` md
Tip 5: Don't Live with Broken Windows
```

- Don't leave "broken windows" (bad designs, wrong decisions, or poor code) unrepaired. Fix them
 as soon as they're discovered. If you can't fix them properly due to time constraints, board
 them up as a temporary measure.
- Avoid causing collateral damage, even in a crisis.

### 4. Stone Soup and Boiled Frogs

- Sometimes, the vision for the entire system is clear—you know it's right. Yet, asking for
  permission to tackle everything at once often leads to delays, blank stares, committee meetings,
  and budget hurdles.
- Instead, bring out the "stones." Focus on a reasonable, achievable request. Execute it well, then
  showcase the results. Once people see it, suggest, “Of course, it would be even better if we
  added…”
- Success attracts support. Provide a glimpse of what's possible, and others will rally behind you.

``` md
Tip 6: Be a Catalyst for Change
```

- Most software disasters begin too small to notice. Project overruns creep in day by day, as
  features drift from specifications and patches pile onto code until nothing original remains. This
  gradual accumulation of small issues can break morale and teams.

``` md
Tip 7: Remember the Big Picture
```

- It's said that a frog dropped into boiling water will leap out immediately. However, placed in
  cold water that's gradually heated, the frog fails to notice the change and remains until it's too
  late. Unlike the Broken Window Theory, where neglect leads to widespread apathy, the frog's
  failure stems from gradual, unperceived change.

### 5. Good-Enough Software

- Writing "good enough" software ensures it meets user needs, satisfies maintainers, and boosts
  productivity. Shorter development cycles often result in happier users and improved program
  quality.
- Ignoring user needs for new features or over-polishing is unprofessional, as is cutting corners or
  setting unrealistic deadlines.

``` md
Tip 8: Make Quality a Requirements Issue
```

- Great software today is often preferable to the fantasy of perfect software tomorrow.
- Know when to stop: Avoid ruining a good program through overembellishment and overrefinement.

### 6. Your Knowledge Portfolio

- "An investment in knowledge always pays the best interest." - Benjamin Franklin
- Managing a knowledge portfolio mirrors financial portfolio management:
  - Invest in knowledge consistently: small, regular efforts build the habit and yield lasting
    results.
  - Diversify your knowledge to adapt to change: master current tech, explore new ones, and build
    soft skills.
  - Balance risks in tech: explore both high-reward and stable options; avoid relying on one field.
  - Learn emerging tech early: it's risky but can lead to great rewards as it gains popularity.
  - Review and rebalance: Regularly reassess your skills to stay current with evolving tech and open
    new opportunities.

``` md
Tip 9: Invest Regularly in Your Knowledge Portfolio
```

- Embrace learning opportunities by researching unanswered questions, building your network, and
  using spare time for reading.
- Think critically about sources, ensuring your knowledge is accurate and not influenced by hype.

``` md
Tip 10: Critically Analyze What You Read and Hear
```

- Critical thinking is a discipline worth studying. Begin by asking deeper questions to uncover root
  causes.
  - The "Five Whys" technique helps dig deeper into an issue by repeatedly asking "why" to
    understand it fully.
  - Ask who benefits from a situation. Analyzing who stands to gain can reveal hidden agendas or
    alignments.
  - Consider the context. Solutions are often not universal, and what works for one may not work for
    another.
  - Assess when and where an idea or solution works. Don't stop with first-order thinking (what will
    happen next), but use second-order thinking: what will happen after that?
  - Investigate underlying problems and models. Understanding the structure behind an issue can
    provide better solutions.

### 7. Communicate!

- It's not just what you've got, but also how you package it. A good idea is an orphan without
  effective communication.
- Treat English (or whatever your native tongue may be) as just another programming language.

``` md
Tip 11: English is Just Another Programming Language
```

- Effective communication requires understanding your audience; merely talking, without engaging
  them, is ineffective and irritating.
- Plan, outline, and refine to ensure your message suits the audience; apply this to documents,
  meetings, and client talks.
- Understand audience priorities; time your message for relevance and ask, "Is this a good time to
  discuss...?"
- Adapt your style to the audience's needs; offer feedback when necessary, as it's a vital part of
  communication.
- Present ideas professionally; use modern tools, styles, and layout features for polished,
  error-free documents.
- Engage your audience early; seek feedback to build rapport and create better documents through
  collaboration.
- Listen actively; foster dialogue by asking questions and encouraging input to enhance
  understanding and engagement.
- Always respond promptly to messages, even briefly, to keep others informed and maintain trust.

``` md
Tip 12: It's Both What You Say and the Way You Say It
```

- Treat documentation as integral to development; keep it efficient, non-redundant, and closely tied
  to the code.

``` md
Tip 13: Build Documentation In, Don't Bolt In On
```

- Comment code to explain purpose, goals, and trade-offs; avoid redundant comments that duplicate
  what the code already shows.

---

## Chapter 2: A Pragmatic Approach

### 8. The Essence of Good Design

- Experts share endless advice on software design, but here's a fresh insight the authors have
  recently discovered.

``` md
Tip 14: Good Design Is Easier to Change Than Bad Design
```

- Good design adapts to users; for code, it means being Easier to Change (ETC), the core of all
  design principles.
- ETC guides decisions in software design. Reinforce it by asking, “Did this make the system easier
  to change?” and trust common sense.
- Make code replaceable to handle unforeseen changes and develop instincts by tracking decisions and
  learning from future changes.

### 9. DRY—The Evils of Duplication

- Maintenance starts during development, not post-release; avoid duplicating knowledge to ensure
  maintainability and embrace DRY.
- Every piece of knowledge must have a single, unambiguous, authoritative representation within a
  system.

``` md
Tip 15: DRY—Don't Repeat Yourself
```

- DRY isn't just about avoiding code duplication; it's about eliminating redundant expressions of
  knowledge or intent.
- Types of duplication:
  - Duplication in Code: Identical code isn't a DRY violation if it represents distinct knowledge;
    coincidence isn't duplication.
  - Duplication in Documentation: Comments should add value, not compensate for poor naming or
    layout; clear names and source details uphold DRY.
    - Data structures hold knowledge; DRY can be violated for performance, but keep such impacts
      localized within the class.
  - Representational Duplication: Interfacing with external systems introduces unavoidable DRY
    violations, but these can be mitigated with careful management.
  - Interdeveloper Duplication: Takes place when multiple team members, either on the same team or
    across different teams, replicate the same information.

### 10. Orthogonality

- Orthogonality means independence; in systems, changes in one part (e.g., UI) don't affect another
  (e.g., database).

``` md
Tip 17: Eliminate Effects Between Unrelated Things
```

- Benefits of Orthogonality:
  - Gain Productivity:
    - Orthogonal components simplify development, promote reuse, reduce testing, and enhance
      functionality with minimal effort.
  - Reduce Risk:
    - Orthogonality reduces risks, simplifies fixes, improves testing, and minimizes dependency on
        specific vendors or platforms.
- Design
  - Orthogonal systems use modular, layered components, enabling abstraction, flexibility, and
    reduced dependency risks.
  - Test orthogonal design by ensuring changes affect only one module.
  - Avoid dependencies on uncontrollable external identifiers.
- Toolkits & Libraries: Preserve orthogonality by isolating third-party toolkit dependencies.
- Coding: There are several techniques you can use to maintain orthogonality,
  - Write decoupled, shy code: minimize dependencies, follow the Law of Demeter, and isolate
    implementation details.
  - Avoid global data: pass context explicitly to modules to reduce dependencies and improve
    maintainability.
  - Avoid functions with similar code: Duplicate code is a symptom of structural problems.
- Testing: Orthogonal systems simplify testing by enabling easier module-level tests and better bug
  localization.
- Documentation: Orthogonal documentation allows appearance changes without altering content.
- Orthogonality reduces interdependency, complementing the DRY principle to create flexible,
  maintainable systems.

### 11. Reversibility

- Avoid a narrow mindset in projects; critical decisions are hard to reverse and can lead to major
  setbacks.
- Adapt to changes by abstracting decisions and preparing for contingencies, as they are rarely
  permanent.

``` md
Tip 18: There Are No Final Decisions
```

- Ensure flexibility in architecture, deployment, and vendor integration by using abstraction and
  modular design.

``` md
Tip 19: Forgo Following Fads
```

### 12. Tracer Bullets

- Unfamiliar tools and changing environments introduce unpredictability in projects.
- Tracer bullet development provides immediate feedback in a shifting environment, improving chances
  of hitting the target.
- In code, tracer bullet focus on key requirements and high-risk areas for quick feedback early in
  development.

``` md
Tip 20: Use Tracer Bullets to Find the Target
```

- Tracer code is maintainable and incremental, allowing early feedback and adjustments, unlike the
  heavy engineering approach.
- The tracer code approach has many benefits:
  - Users get to see something working early
  - Developers build a structure to work in
  - You have an integration platform
  - You have something to demonstrate
  - You have a better feel for progress

- Tracer Bullets Don't Always Hit Their Target
  - Tracer bullets help adjust direction when uncertain, allowing quick changes with lean
    development to stay on target.
  - Tracer code allows quick, cost-effective feedback, ensuring users see a real, functional version
    of the application.

- Tracer Code versus Prototyping
  - Tracer code differs from prototyping by being reusable and maintainable, rather than discarded
    after exploring concepts.
  - Prototyping helps explore ideas quickly, but the code is discarded after decisions are made.
  - Whereas, tracer code provides a framework for integrating components and evolving functionality,
    ensuring system consistency over time.

### 13. Prototypes and Post-it Notes

- Prototypes test ideas cheaply and quickly, using varied materials like notes, drawings, or
  mock-ups to address specific questions.
- Prototype anything that hasn't been tried before, that is critical to the system, anything that's
  unproven, experimental or doubtful. It can be anything that you aren't comfortable with.
- Prototyping's value is in the lessons learned, not the code produced.

``` md
Tip 21: Prototype to Learn
```

- How to Use Prototypes
  - A prototype can ignore,
    - Correctness: You may be able to use dummy data where appropriate.
    - Completeness: The prototype may function only in a very limited sense.
    - Robustness: Error checking is likely to be incomplete or missing entirely.
    - Style: Prototype code shouldn't have much in the way of comments or documentation.

- Prototyping Architecture
  - Prototypes model entire systems without needing fully functional modules, using tools like
    whiteboards or Post-its to visualize the architecture.
  - Specific areas you may want to look for in the architectural prototype:
    - Are the responsibilities of the major areas well-defined and appropriate?
    - Are the collaborations between major components well-defined?
    - Is coupling minimized?
    - Can you identify potential sources of duplication?
    - Are interface definitions and constraints acceptable?
    - Does every module have an access path to the data it needs during execution? Does it have that
      access when it needs it?

- Clarify that code-based prototypes are disposable and incomplete to prevent misconceptions and
  avoid premature deployment.

### 14. Domain Languages

- Programming languages shape problem-solving and communication, often reflecting the vocabulary and
  logic of their problem domains.

``` md
Tip 22: Program Close to the Problem Domain
```

### 15. Estimating

- By learning to estimate, you develop intuitive estimation skills to gauge feasibility, assess
  practicality, and identify optimization needs effortlessly.

``` md
Tip 23: Estimate to Avoid Surprises
```

- How Accurate is Accurate enough?
  - Estimates vary in accuracy, so consider context and units carefully to set expectations
    appropriately.

- Where do Estimates come from?
  - For better estimates, consult those with relevant experience before building detailed models.
  - Understand What's Being Asked: Start by understanding the scope before estimating.
  - Build a Model of the System: Building a rough mental model for estimation helps reveal patterns.
  - Break the Model into Components: These affect how various components contribute to the overall
    estimation.
  - Give Each Parameter a Value: Assign values to parameters, focusing on those with the most
    impact.
  - Calculate the Answers: Run multiple calculations and focus on key parameters.
  - Keep Track of Your Estimating Prowess: Analyze errors to improve future estimates by
    understanding mismatched parameters or flawed models.

- Estimating Project Schedules
  - Real-world estimates use scenario ranges such as optimistic, most likely and a pessimistic
    estimate. Using a range of values reduces estimation errors, but simply relying on formulas for
    large tasks may still lead to inaccurate estimates.
  - Estimate timelines through experience by practicing incremental development:
    - Check requirements
    - Analyze and prioritize risks
    - Design, implement, integrate
    - Validate with the users, and
    - Repeat
  - Refine project estimates iteratively; use each cycle's review to adjust timelines and improve
    schedule confidence.

``` md
Tip 24: Iterate the Schedule with the Code
```

- What to Say when asked for an estimate?
  - Say "I'll get back to you." Taking time to review the steps in this section leads to better
    estimates than quick responses.

---

## Chapter 3: The Basic Tools

### 16. The Power of Plain Text

- Plain text is made up of printable characters in a form that conveys information.
- Plain text is ideal for persistent knowledge storage, enabling easy manipulation and
  self-describing data independent of applications.

``` md
Tip 25: Keep Knowledge in Plain Text
```

- The Power of Text
  - Insurance Against Obsolescence: Human-readable, self-describing data outlives applications,
    remaining usable and parseable even with partial format knowledge.
  - Leverage: Plain text is universally compatible with tools like version control, editors, and
    command-line utilities.
  - Easier Testing: Plain text simplifies creating, updating test data and analyzing regression test
    outputs using shell commands or simple scripts.
- In diverse environments, plain text's benefits outweigh drawbacks, serving as a universal standard
  for communication.

### 17. Shell Games

- The command shell empowers programmers to combine tools, launch apps, query systems, and create
  macros, offering unmatched flexibility.
- GUIs are useful for simple tasks, but relying on them limits automation, customization, and the
  full potential of available tools.
- A benefit of GUIs is **WYSIWYG**—what you see is what you get. The disadvantage is
  **WYSIAYG**—what you see is all you get.

``` md
Tip 26: Use the Power of Command Shells
```

### 18. Power Editing

``` md
Tip 27: Achieve Editor Fluency
```

- Fluency minimizes editing effort, enabling thoughts to flow seamlessly, like an experienced
  driver’s instinctive control.
- Moving Towards Fluency:
  - Master Editor efficiency by identifying repetitive tasks, learning better methods, and
    practicing them until instinctive.
  - Enhance your editor with extensions to overcome limits.

### 19. Version Control

- Avoid network or cloud storage for project files—use proper version control to prevent conflicts,
  corruption, and lost work.
- Version control tracks changes, supports collaboration, aids audits, regenerates releases, and
  merges edits seamlessly for any project.

``` md
Tip 28: Always Use Version Control
```

### 20. Debugging

- Modern computer systems are still limited to doing what you tell them to do, not necessarily what
  you want them to do.
- Debugging is problem-solving, not blame-laying; focus on solutions over assigning fault or making
  excuses.

``` md
Tip 29: Fix the Problem, Not the Blame
```

- A Debugging Mindset
  - Adopt a calm mindset for debugging; set aside ego defenses, project pressures, and focus on
    comfort and clarity.

  ``` md
  Tip 30: Don't Panic
  ```

  - Stay calm, avoid denial, and focus on root causes, not just symptoms; resist assumptions like
    "it's impossible" when debugging.
- Where to Start
  - Start debugging with clean, warning-free code; focus on complex issues, and gather relevant data
    as bug reports may lack precision.
  - Avoid debugging coincidences; ensure accurate observations, and directly observe users for
    detailed, reliable bug reports.
- Debugging Strategies
  - After forming a hypothesis, verify it by understanding the program's perspective and internal
    behavior.
  - Reproducing Bugs
    - The best way to start fixing a bug is to make it reproducible. Then make it reproducible
      ideally with a single command, to simplify debugging and avoid complex, lengthy steps.

    ``` md
    Tip 31: Failing Test Before Fixing Code
    ```

    ``` md
    Tip 32: Read the Damn Error message
    ```

  - Bad Results
    - Use a debugger to confirm bad results, trace call stacks, jot notes to track progress, and use
      efficient approaches like binary search when needed.
  - Sensitivity to Input Values
    - When a program crashes on specific data, test locally, confirm the issue, then isolate
      problematic input.
  - Regressions Across Releases
    - To trace production bugs, identify the specific code change that caused the issue to
      streamline debugging.
  - The Binary Chop
    - To debug a stack trace, use binary search: check the middle frame, narrow down based on the
      error, and repeat.
    - To debug dataset issues, split the data and test subsets, repeating the process until
      identifying the smallest set causing the problem.
    - To find a bug in releases, create a failing test, then use binary search across versions to
      narrow the issue, aided by version control tools.
  - Logging and/or Tracing
    - Debuggers show the current state, but tracing statements are crucial for tracking errors over
      time, especially in time-sensitive systems.
    - Add consistent tracing statements as you move through the call tree, allowing for easy parsing
      and deeper insight into the code's execution.
  - Rubber Ducking
    - Explaining a problem to someone else (or even an object) helps identify issues by forcing you
      to verbalize assumptions and gain new insights.
  - Process of Elimination
    - When debugging, assume the issue is with your application code, not the OS, compiler, or
      third-party products, and rule out your code first.

    ``` md
    Tip 33: "select" Isn't Broken
    ```

    - If a system breaks after one change, that change is likely the cause, even if it seems
      unlikely. New software versions can introduce unexpected issues.
- The Element of Surprise
  - When surprised by a bug, reassess your assumptions and test boundary conditions. Even long-used
    code may still contain hidden issues.
  - Surprising failures often mean your assumptions are wrong. Don't skip over code you trust; prove
    it works in the current context and with the data.

  ``` md
  Tip 34: Don't Assume It-Prove It
  ```

  - When fixing a surprise bug, investigate why it wasn't caught earlier. Update tests or add better
    parameter checks to catch similar issues sooner.
  - Look for other areas vulnerable to the same bug and fix them. If fixing took long, consider
    improving testing hooks or adding a log file analyzer for future ease.
  - If the bug stems from a wrong assumption, discuss it with the team to prevent misunderstandings.
    Addressing it ensures fewer surprises in the future.
- Debugging Checklist
  - Determine if the reported problem is a direct result of the underlying bug or just a symptom of
    a deeper issue.
  - Determine if the bug is in the framework, the OS, or your own code by systematically ruling out
    each possibility.
  - Explain the problem to a coworker, describe the issue step by step, including the symptoms,
    possible causes, and the troubleshooting steps you've taken so far.
  - If the suspect code passes its unit tests, assess whether the tests are thorough enough.
    Consider running them with the problematic data to check for edge cases.
  - Check if the conditions causing the bug exist elsewhere in the system. Look for potential hidden
    bugs that could emerge under similar circumstances.

### 21. Text manipulation

- Text manipulation languages, like awk, sed, Python, and Ruby, are powerful tools for quick
  prototyping and automation. Though tricky, they can significantly reduce development time and
  enable experimentation.

``` md
Tip 35: Learn a Text Manipulation Language
```

### 22. Engineering Daybooks

- An engineering daybook is used to record one's work, ideas, lessons, and readings, often jotting
  notes during conversations.
- We could use daybooks for meeting notes, tracking work, debugging values, reminders, and recording
  ideas.
- The daybook aids memory, stores unrelated ideas for later, and helps reflect and identify mistakes
  through note-taking.

---
