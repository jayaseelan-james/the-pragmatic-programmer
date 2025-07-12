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
  - [Chapter 4: Pragmatic Paranoia](#chapter-4-pragmatic-paranoia)
    - [23. Design by Contract](#23-design-by-contract)
    - [24. Dead Programs Tell No Lies](#24-dead-programs-tell-no-lies)
    - [25. Assertive Programming](#25-assertive-programming)
    - [26. How to Balance Resources](#26-how-to-balance-resources)
    - [27. Don't Outrun Your Headlights](#27-dont-outrun-your-headlights)
  - [Chapter 5: Bend, Or Break](#chapter-5-bend-or-break)
    - [28. Decoupling](#28-decoupling)
    - [29. Juggling the Real World](#29-juggling-the-real-world)
    - [30. Transform Programming](#30-transform-programming)
    - [31. Inheritance Tax](#31-inheritance-tax)
    - [32. Configuration](#32-configuration)
  - [Chapter 6: Concurrency](#chapter-6-concurrency)
    - [33. Breaking Temporal Coupling](#33-breaking-temporal-coupling)
    - [34. Shared State Is Incorrect State](#34-shared-state-is-incorrect-state)
    - [35. Actors And Processes](#35-actors-and-processes)
    - [36. Blackboards](#36-blackboards)
  - [Chapter 7: While You Are Coding](#chapter-7-while-you-are-coding)
    - [37. Listen to Your Lizard Brain](#37-listen-to-your-lizard-brain)
    - [38. Programming by Coincidence](#38-programming-by-coincidence)
    - [39. Algorithm Speed](#39-algorithm-speed)
    - [40. Refactoring](#40-refactoring)
    - [41. Test to Code](#41-test-to-code)
    - [42. Property-Based Testing](#42-property-based-testing)
    - [43. Stay Safe Out There](#43-stay-safe-out-there)
    - [44. Naming Things](#44-naming-things)
  - [Chapter 8: Before the Project](#chapter-8-before-the-project)
    - [45. The Requirements Pit](#45-the-requirements-pit)
    - [46. Solving Impossible Puzzles](#46-solving-impossible-puzzles)
    - [47. Working Together](#47-working-together)
    - [48. The Essence of Agility](#48-the-essence-of-agility)

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

``` md
Tip 16: Make It Easy to Reuse
```

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

## Chapter 4: Pragmatic Paranoia

``` md
Tip 36: You Can't Write Perfect Software
```

- No one in the brief history of computing has ever written a piece of perfect software. It’s
  unlikely that you’ll be the first.
- Good drivers anticipate trouble; good coders do the same, defending against others' and their own
  potential mistakes.

### 23. Design by Contract

- Contracts define mutual rights, responsibilities, and repercussions—an idea that applies equally
  to software module interactions.
- DBC
  - Design by Contract (DBC) ensures program correctness by documenting software modules' rights,
    responsibilities, and expected outcomes. The expectations and claims as follows:
    - Preconditions: Callers must ensure valid data to meet those requirements before invoking them.
    - Postconditions: Ensuring guaranteed outcomes and proper termination without infinite loops.
    - Invariants: They may break internally but must be restored before the routine exits.
  - If preconditions are met, the routine guarantees all postconditions and invariants will be true
    upon completion.

``` md
Tip 37: Design with Contracts
```

- Orthogonality recommended writing “shy” code. Here, the emphasis is on “lazy” code: : be strict in
  what you will accept before you begin, and promise as little as possible in return.
- Implementing DBC
  - Defining input range, boundaries, and promises to deliver (and what it doesn't) improves
    software design.
  - Assertions
    - Documenting assumptions helps, but compiler-enforced contracts provide greater reliability.
      Assertions aid but lack inheritance support and automation.
- DBC and Crashing Early: Use DBC to validate conditions, crash early, and get detailed errors,
  avoiding hidden bugs.
- Semantic Invariants
  - You can use semantic invariants to express inviolate requirements, a kind of "philosophical
    contract."
  - Distinguish semantic invariants from changeable policies; document invariants clearly for
    consistent understanding and adherence.

### 24. Dead Programs Tell No Lies

- Defensive coding catches unexpected errors early, ensuring data integrity and handling the
  "impossible" with proper error checks and defaults.
- Pragmatic Programmers tell themselves that if there is an error, something very, very bad has
  happened.
- Catch and Release Is For Fish
  - Avoid catching all exceptions and re-throwing it; it reduces verbosity, uncouples code, and
  ensures new exceptions propagate automatically without updates.

``` md
Tip 38: Crash Early
```

- Crash, Don't Trash
  - Early crashing avoids further damage.
  - Terminate programs when the impossible occurs; continuing risks unreliable actions. Handle
    cleanups and exit immediately.
  - A dead program normally does a lot less damage than a crippled one.

### 25. Assertive Programming

- Avoid self-deception in coding; assumptions like "this can never happen" lead to unpreparedness
  and potential errors.

``` md
Tip 39: Use Assertions to Prevent the Impossible
```

- Use assertions to check "impossible" conditions, ensuring parameters and results meet expectations
  for robust, error-free code.
- Don't use assertions in place of real error handling. Assertions check for things that should
  never happen.
- Assertions with side effects can result in Heisenbug, where debugging code unintentionally causes
  new errors or alters system behavior.
- Leave Assertions Turned On
  - Assertions should remain active in production to catch errors missed during testing, as bugs and
    unexpected issues can arise in real environments.
  - Disabling assertions in production is risky. If performance issues arise, only disable specific
    critical assertions, leaving others active for safety.

### 26. How to Balance Resources

- Coding involves managing resources like memory, threads, and files by allocating, using, and then
  deallocating them predictably.

``` md
Tip 40: Finish What You Start
```

- In many modern languages, you can scope the lifetime of a resource to an enclosed block of some
  sort.

``` md
Tip 41: Act Locally
```

- Nest Allocations
  - Deallocate resources in reverse order of allocation to avoid orphaning resources with references
    to each other.
  - Always allocate resources in the same order across your code to minimize the risk of deadlock.
- Objects and Exceptions: Encapsulate resources in classes for auto-allocation and deallocation via
  constructors/destructors, aiding exception-safe cleanup.
- Balancing and Exceptions
  - To ensure resource cleanup during exceptions, use variable scope or a try-finally block for
    controlled deallocation.
  - An Exception Antipattern: If resource allocation fails, deallocation in finally will act on an
    unallocated resource. Therefore, consider allocating resources outside try-finally.
- When You Can't Balance Resources
  - For dynamic structures, set a clear ownership rule to define who manages memory allocation and
    deallocation responsibilities. You can do this in three ways:
    - The top-level structure must free its substructures, which recursively delete their own
      contained data.
    - Deallocating the top-level structure orphans any unreferenced substructures it pointed to.
    - The top-level structure refuses to deallocate itself if it contains any substructures.
- Checking the Balance: Pragmatic Programmers recommend using wrappers to track resource allocations
  and deallocations, ensuring no memory leaks occur.

### 27. Don't Outrun Your Headlights

- Headlights have a limited range, like foresight in software development—beyond a point, visibility
  diminishes, making planning harder.

``` md
Tip 42: Take Small steps—Always
```

- Take small steps, adjust based on feedback, and never exceed your feedback rate, it's your speed
  limit in decision-making.
- A task is too big if it requires guessing the future. Design for maintainability, but focus on
  replaceability over speculation.
- Black Swans
  - Rare, unpredictable events shape history. Predicting the future is tricky—like past tech debates
    that missed the rise of the web.

``` md
Tip 43: Avoid Fortune-Telling
```

---

## Chapter 5: Bend, Or Break

- Code must be flexible to keep up with rapid change; rigid code risks becoming obsolete or
  unfixable.

### 28. Decoupling

- Coupling makes code harder to change. For flexibility, minimize dependencies. Unlike bridges,
  software should adapt, not stay rigid.

``` md
Tip 44: Decoupled Code is Easier to Change
```

- Watch for signs of coupling: unexpected dependencies, cascading changes, fear of edits, and
  meetings where no one knows the impact.

``` md
Tip 45: Tell, Don't Ask
```

- Avoid decisions based on an object's internal state before updating it. This breaks encapsulation
  and spreads implementation details.
- Tell-don't-ask is a guideline, not a rule. In some cases, exposing key objects makes sense because
  they have their own identity.
- Law of Demeter
  - The Law of Demeter (LoD) reduces coupling and keeps functions clean. A method in class C should
    only call:
    - Its own instance methods
    - Its parameters
    - Methods of objects that it creates
    - Global variables

``` md
Tip 46: Don't Chain Method Calls
```

- The one-dot rule can be ignored for stable libraries, but app code and third-party APIs are likely
  to change and should be handled carefully.
- Evils of Globalization
  - Global data increases coupling, making changes risky and code harder to reuse or test. Clean
    interfaces help decouple and simplify maintenance.
  - Wrapping global data in a singleton does not remove coupling. Adding methods helps, but it is
  still a single shared data source.

``` md
Tip 47: Avoid Global Data
```

- Any mutable external resource is global data. To avoid issues, always wrap databases, APIs, and
  file systems in controlled code.

``` md
Tip 48: If It's Important Enough to be Global, Wrap It in an API
```

### 29. Juggling the Real World

- Event-driven apps improve interactivity and efficiency but need a clear strategy to avoid messy,
  tightly coupled code.
- There are four strategies that can help:
  - Finite State Machines: A state machine defines states, events per state, and transitions based
    on those events.
  - Observer Pattern: This lets observers register for events; the observable notifies them by
    calling their functions.
  - Publish/Subscribe: It improves observer pattern by using named channels to decouple and
    asynchronously connect publishers and subscribers.
  - Reactive Programming and Streams: Streams simplify handling events by treating them as data
    collections, making it easier to trigger reactions in code.

### 30. Transform Programming

- Programs transform input to output, and focusing on this simplifies design, reduces errors, and
  lowers coupling.

``` md
Tip 49: Programming Is About Code, But Programs are About Data
```

- Start with requirements, define inputs and outputs, then map steps. This top-down method reveals
  transformations.

``` md
Tip 50: Don't Hoard State; Pass it Around
```

- The transformational model treats data as a flow, enabling reusable functions and reducing system
  coupling.
- Transformations avoid raw values; instead, they use data structures that indicate value validity.

### 31. Inheritance Tax

- Two styles of inheritance: Type combination (C++, Java); Organize behaviors (Ruby, JavaScript).
- Inheritance is coupling. Inheritance couples child classes to parents and their ancestors, as well
  as to code that uses the child.

``` md
Tip 51: Don't Pay Inheritance Tax
```

- Better Alternatives
  - Interfaces and Protocols
    - OO languages allow classes to implement multiple behaviors, like a Car class implementing
      Drivable and Locatable.
    - Declarations define required methods (e.g., getSpeed, stop) for classes implementing behaviors
      like Drivable or Locatable, but add no code.
    - Interfaces and protocols give us polymorphism without inheritance.

  ``` md
  Tip 52: Prefer Interfaces to Express Polymorphism
  ```

  - Delegation
    - Inheritance leads to large classes with unused methods, losing control over the interface.

  ``` md
  Tip 53: Delegate to Services: Has-A Trumps Is-A
  ```

  - Mixins, Traits, Categories, Protocol Extensions, ...
    - A mixin adds new functionality to classes without inheritance, combining original capabilities
      with additional functions, even without source code access.
    - The key idea is merging functionality between existing and new things through these
      implementations.

  ``` md
  Tip 54: Use Mixins to Share Functionality
  ```

- Use the technique that best expresses your intent, and avoid unnecessary complexity or excess
  baggage.

### 32. Configuration

- Externalize changing values to adapt code for different environments or customers, enabling
  flexible, parameterized apps.

``` md
Tip 55: Parameterize Your App Using External Configuration
```

- Example configuration data include:
  - Credentials for external services
  - Logging levels and location
  - IP address, port, and license keys
- Static Configuration
  - Store configuration in flat files (like YAML/JSON) or databases, depending on structure and
    change frequency. Load as a global data structure at startup.
  - Preferably, wrap configuration data in a thin API to decouple code from representation details,
    avoiding direct global access.
- Configuration as a Service
  - Use a service API to store configuration data externally, rather than relying on flat files or
    databases.
  - Storing configuration behind a service API allows sharing, global updates, controlled access, a
    UI for maintenance, and dynamic data.
- Without external configuration, code lacks flexibility. In nature, lack of adaptation leads to
  extinction.

---

## Chapter 6: Concurrency

- Concurrency is essential in real-world systems; without it, apps feel slow and underuse the hardware’s potential.
- Temporal coupling limits flexibility by enforcing unnecessary code order, making systems harder to change and slower to respond.

### 33. Breaking Temporal Coupling

- Temporal coupling is about time in design—specifically concurrency and ordering—not just deadlines
  or ship dates.
- Linear thinking in code causes temporal coupling; decoupling time/order boosts flexibility, speed,
  and system reliability.
- Looking for Concurrency: Activity diagrams help analyze workflows, showing order and parallelism
  to reduce unnecessary sequential steps.

``` md
Tip 56: Analyze Workflow to Improve Concurrency
```

- Opportunities for concurrency: Activity diagrams reveal concurrency, but design determines if it's
  worth exploiting—like offloading time-consuming tasks.
- Opportunities for parallelism: Concurrency is software-driven; parallelism uses hardware to run
  independent tasks simultaneously and speed up work.

### 34. Shared State Is Incorrect State

``` md
Tip 57: Shared State Is Incorrect State
```

- The issue isn't shared memory, but inconsistent views—non-atomic actions can lead to outdated or
  incorrect decisions.
- A semaphore controls access by allowing only one holder at a time-ensuring safe updates to shared
  resources.
- Concurrency issues can occur with any shared mutable resource, like files, databases, or services,
  not just shared memory.

``` md
Tip 58: Random Failures Are Often Concurrency Issues
```

### 35. Actors And Processes

- An actor is an independent unit with private state and a mailbox, processing messages one at a
  time and updating state or creating new actors.
- A process is a general-purpose virtual processor that can act like an actor when constrained by
  design or convention.

``` md
Tip 59: Use Actors For Concurrency Without Shared State
```

- The actor model avoids shared state and explicit flow control, enabling concurrency across single,
  multicore, or networked systems.

### 36. Blackboards

- Like detectives using a shared blackboard to coordinate clues, systems can use shared spaces to
  manage tasks and communication.
- Linda was an early blackboard system using typed tuples. Programs added and retrieved data via
  pattern matching on the shared space.
- A blackboard with a rules engine handles unordered data elegantly, triggering rules and feedback
  loops as new facts are posted.

``` md
Tip 60: Use Blackboards to Coordinate Workflow
```

- Actor, blackboard, and microservice architectures reduce concurrency issues but add complexity;
  central message tracking and strong tooling are essential.

---

## Chapter 7: While You Are Coding

- Coding isn't just mechanical; thoughtful decisions at every step are crucial to building correct,
  efficient, and maintainable software or the project may fail.

### 37. Listen to Your Lizard Brain

- Instincts are nonverbal responses shaped by experience. As you program, tacit knowledge builds,
  guiding actions without conscious thought through subtle feelings.
- The trick is first to notice it is happening, and then to work out why.
- Fear Of The Blank Page:
  - Nagging doubts often signal hidden issues your experience has sensed. Trust those feelings, as
    they can guide you before problems become clear and improve your performance.
  - Fear of making mistakes is natural. Developers often tie their self-worth to their code, leading
    to doubt or imposter syndrome when a task feels overwhelming.
- Fighting Yourself: If coding feels unusually hard, your instincts may be warning you of deeper
  issues like bad design or the wrong problem. Listen to that feedback instead of pushing through.
- How To Talk Lizard:
  - Step away from the code and do something mindless to let your brain reset. With time, ideas may
  surface on their own and lead to a clear *aha* moment.
  - If stuck, externalize the problem by doodling or explaining it. If that fails, start prototyping
  to tell your brain the task is low stakes and reduce pressure.

``` md
Tip 61: Listen to Your Inner Lizard
```

- It's Playtime!: Call it a prototype to lower pressure and explore freely. Resolve doubts, take
  breaks if needed, then start fresh and write clean, final code once clarity returns.
- Not Just Your Code: When reading others' code, note odd patterns and try to see their reasoning.
  Understanding their instincts makes the code easier to follow and may teach you something new.
- Not Just Code: Trusting your instincts applies to design too. If something feels wrong, pause and
  explore it. Speaking up early can help you spot and avoid deeper issues.

### 38. Programming by Coincidence

- Developers face daily traps. Avoid drawing false conclusions or relying on luck. Focus on
  deliberate, thoughtful coding instead of programming by coincidence.
- Code that seems to work by chance can lead to confusion and failure later. Without understanding
  why it works, fixing issues becomes nearly impossible. Avoid false confidence.
- Examples:
  - Accidents of Implementation: Don't rely on accidental behavior or undocumented details. Use
    clear, documented interfaces and note any assumptions to avoid bugs, failures, and performance
    issues later.
  - Close Enough Isn't: Fixing values based on small, consistent errors can hide deeper flaws.
    Relying on coincidences leads to unreliable code and masks real design issues.
  - Phantom Patterns: Intermittent bugs or inconsistent test results may hint at real issues like
    race conditions or environment differences, not just coincidence. Don't assume it, prove it.
  - Accidents of Context: Avoid assuming context that may not always apply. Code should not depend
    on specific environments, user types, or copied solutions that only appear to work.
  - Implicit Assumptions: Coincidences can mislead at any stage, especially testing. Assumptions
    without proof or clear documentation often conflict and are a major cause of project failure.

``` md
Tip 62: Don't Program by Coincidence
```

- How To Program Deliberately:
  - Stay aware of your actions.
  - If you can't clearly explain the code to a junior, you may be depending on coincidences.
  - Avoid coding blindly. If you don't understand why something works, you won't know why it fails.
  - Work from a clear plan, whether it's in your head or on a whiteboard.
  - Depend only on what is proven. If reliability is unclear, assume it will fail.
  - Document assumptions clearly. [Design by Contract](#23-design-by-contract) helps clarify.
  - Test your assumptions, not just your code. Do not guess, verify them by [Assertive
    programming](#25-assertive-programming).
  - Focus on the important parts first. Without a solid base, extras won't matter.
  - Do not let old code limit new work. Replace or [refactor](#40-refactoring) when needed to stay
    effective.

### 39. Algorithm Speed

- Pragmatic Programmers estimate algorithm resources like time and memory using analysis, Big-O
  notation, and common sense to make better performance decisions.
- Big-O Notation:
  - Big-O notation expresses algorithm complexity by showing how runtime grows with input size. For
    example, O(n²) means time increases roughly fourfold if input size doubles.
  - It gives an upper bound on growth. It drops low-order terms and constants, focusing on the
    highest-order term since it dominates as input size increases.
  - Big-O shows how performance changes with input size, not actual speed.
- Common Sense Estimation:
  - Simple Loops:
    - A loop running from 1 to n is typically **O(n)**, meaning time grows linearly with input.
      Examples include searches, finding a max value, and creating checksums.
  - Nested Loops:
    - Nested loops usually lead to **O(n²)** complexity, as time depends on both loop limits. This
      is common in basic sorts like bubble sort, where each element is compared repeatedly.
  - Binary Chop:
    - If an algorithm halves the input each loop, it's likely **O(log n)**. Examples include binary
      search, binary tree traversal, and finding the first set bit in a word.
  - Divide and Conquer:
    - Divide-and-conquer algorithms like quicksort are typically **O(n log n)**, as they split
      input, process halves, and combine results. Quicksort averages O(n log n) despite worse cases.
  - Combinatoric:
    - Algorithms exploring permutations can have **O(Cⁿ)** time, growing explosively with input.

``` md
Tip 63: Estimate the Order of Your Alogorithms
```

- Theory matters, but real-world use reveals the truth. Test with large inputs and varied cases,
  because only production performance with real data truly counts.

``` md
Tip 64: Test Your Estimates
```

- Best Isn't Always Best:
  - Choose algorithms pragmatically. The fastest one is not always the best for the job. Complex
    algorithms can have setup costs that may outweigh their benefits for small inputs.
  - Avoid premature optimization. Focus on improving code only after confirming the algorithm is a
    true bottleneck worth your time and effort.

### 40. Refactoring

- As programs grow, revisiting and reworking earlier code is natural. Code evolves over time and
  should not be treated as static or unchangeable.
- Restructuring includes rewriting and re-architecting code. A specific subset of this process,
  focused on improving structure without changing behavior, is called *refactoring*.
- When Should You Refactor?
  - Duplication: You've discovered a violation of the [DRY](#9-drythe-evils-of-duplication)
    principle.
  - Non-orthogonal design: You've discovered something that could be made more
    [orthogonal](#10-orthogonality).
  - Outdated knowledge: Requirements change and understanding grows, so code must evolve to stay
    effective.
  - Usage: Real use reveals true priorities, shifting focus from once vital features to what matters
    now.
  - Performance: Shifting functionality within the system can help boost performance where it's most
    needed.
  - The Tests Pass: Refactoring works best in small steps with tests. Once new code passes, it's the
    perfect time to clean it up.

``` md
Tip 65: Refactor Early, Refactor Often
```

- How Do You Refactor?
  - Refactoring is thoughtful redesign. It should be done slowly and carefully, not with reckless
    changes. Martin Fowler's simple tips to refactor safely and avoid causing more harm than good:
    - Don't try to refactor and add functionality at the same time.
    - Have solid tests before refactoring and run them often to catch any breakage early.
    - Refactor in small, careful steps like moving fields or renaming variables. Test each change to
      prevent long debugging sessions.

### 41. Test to Code

``` md
Tip 66: Testing Is Not About Finding Bugs
```

- By thinking about testing first, you can shape better code. Without writing any logic, test
  planning may lead to interesting discoveries.

``` md
Tip 67: A Test Is the First User of Your Code
```

- Tests Drive Coding:
  - Testing guides coding, reduces code coupling by making functions easier to test, and forces
    deeper understanding before implementation.
  - Thinking about tests early reveals clearer logic, simplifies code, and helps you handle
    boundaries and errors better before writing a single line.
- Test-Driven Development: The basic cycle of TDD is:
  - Decide on a small piece of functionality you want to add.
  - Write a test that will pass once that functionality is implemented.
  - Run all tests. Verify that the only failure is the one you just wrote.
  - Write minimal code to pass the test, then check that all tests run without errors.
  - Refactor your code to improve it, and ensure all tests still pass after the changes.
- Bottom-Up vs. Top-Down vs. The Way You Should Do It:
  - Top-down design breaks problems into smaller parts from the top level. Bottom-up builds layers
    of abstraction from the ground up until the problem is solved.
  - Top-down and bottom-up fail because we rarely know everything at the start. The best way to
    build software is incrementally, learning and involving the customer as you go.

``` md
Tip 68: Build End-to-End, Not Top-Down or Bottom Up
```

- Take small, test-driven steps when the problem is unclear, but stay focused, or you risk
  over-polishing easy parts and losing sight of your goal.
- Unit Tests: Unit testing in software is like chip-level hardware testing: test modules in
  isolation using controlled setups, checking results against known or past values.
- Testing Against Contract: Unit testing should check if code honors its contract, ensuring it works
  as expected and prevents hidden issues that could cause major problems later in the project.

``` md
Tip 69: Design to Test
```

- Ad-hoc testing is manual, like using console logs or a REPL. If it reveals a bug, turn it into a
  formal test to prevent future issues.
- Build A Test Window: Some bugs only show in production. Use structured logs, hotkeys, URLs, or
  feature switches to expose diagnostics and support debugging without affecting users.
- Culture of Testing:
  - All software is tested eventually, either by you or by the user. Testing it thoroughly now
    prevents future issues and support effort.
  - Like production code, test code must be clean, decoupled, and reliable to ensure long-term
    stability.

``` md
Tip 70: Test Your Software, or Your Users Will
```

### 42. Property-Based Testing

- Property-based testing uses contracts and invariants to automate checks, ensuring code behaves
  correctly across varied inputs and consistent internal rules.

``` md
Tip 71: Use Property-Based Tests to Validate Your Assumptions
```

- Property-based testing is powerful but unpredictable. It can reveal hidden bugs, though diagnosing
  failures can be challenging due to the randomness of generated inputs.
- So, when a property-based test fails, extract the input and create a unit test. This isolates the
  issue and ensures it won't reappear, since property-based inputs are random.
- Property-based tests, like unit tests, shape how you think about code. They focus on invariants
  and contracts, revealing edge cases and inconsistent states. Use both for stronger testing.

### 43. Stay Safe Out There

- When your code "works," you're only halfway done. You still need to test for failures, bad inputs,
  resource issues, and even malicious external actions to ensure it's truly robust.
- Pragmatic Programmers stay cautious, aware of their own limits and the risks of attacks. Each
  environment has unique security needs that must be carefully addressed.
- A few basic principles that you should always bear in mind:
  - The attack surface includes all points where data enters, exits, or triggers actions. Reduce it
    by limiting access, simplifying code, and securing all exposed components.
  - Use the least privilege for the shortest time needed. Limit access scope and apply fine-grained
    permissions to reduce risk, just like minimizing attack surface. Less is indeed more.
  - Default settings should favor security, even if less convenient. Let users choose to lower
    security if needed, like showing passwords for accessibility in low-risk situations.
  - Never store sensitive data like credentials or personal info in plain text or version control.
    Use encryption and manage secrets separately through config files or environment variables.
  - Always apply security updates promptly. Delaying patches leaves systems open to known exploits
    and has caused major breaches. This applies to every connected device you use.

``` md
Tip 72: Keep It Simple and Minimize Attack Surfaces
```

``` md
Tip 73: Apply Security Patches Quickly
```

- Avoid writing your own encryption or authentication. Even tiny errors can compromise security.
  Rely on trusted libraries and providers who follow best practices.

### 44. Naming Things

- Names matter. Every name in code should reflect the role it plays, clearly showing intent and
  meaning to others and to your future self.
- Before creating anything, ask why it exists. Thinking about its purpose helps clarify its role,
  often revealing flaws in your approach when you can't name it meaningfully.
- Naming clarifies meaning and improves code understanding, though not every name must be perfect.
- Honor the Culture: Single-letter variables like i, j, or k are fine when they follow language
  norms, but using them outside their expected context can be confusing and should be avoided.
- Consistency: Every project has unique jargon, so teams must use terms consistently. Frequent
  communication and pair programming help share and align this vocabulary naturally.
- Renaming Is Even Harder: As code changes, update misleading names immediately. If a name no longer
  reflects its intent, fix it now. Regression tests will help catch anything you miss.

``` md
Tip 74: Name Well; Rename When Needed
```

---

## Chapter 8: Before the Project

### 45. The Requirements Pit

- Requirements are not simply gathered; they are often hidden under assumptions or may not exist
  clearly at all, making discovery a complex and uncertain process.

``` md
Tip 75: No One Knows Exactly What They Want
```

- In a messy, unclear world, exact specs are rare. A key role of programmers is helping people
  discover and define what they truly need.

``` md
Tip 76: Programmers Help People Understand What They Want
```

- Client needs are often just starting points, not final requirements. Instead of jumping to
  solutions, treat them as invitations to explore and understand the real problem.

``` md
Tip 77: Requirements Are Learned in a Feedback Loop
```

- Pragmatic Programmers help clients understand the impact of their needs through feedback. Use
  mockups or prototypes to clarify intent, enabling quick adjustments and shared understanding.
- Gain real insight and build trust by experiencing the client's work firsthand. Observing their
  tasks helps you understand needs and improves communication.

``` md
Tip 78: Work with a User to Think Like a User
```

- Designing around flexible policies allows easy updates through metadata, leading to systems that
  adapt well to change and are structured for maintainability.

``` md
Tip 79: Policy Is Metadata
```

- Tools must match user needs and habits. Features alone are not enough. Early feedback helps reveal
  when something works in theory but fails in practice or usability.
- Documenting Requirements:
  - Detailed requirements documents often fail because clients don't fully know what they want and
    rarely read them. Such documents serve developers, not clients, and hinder true collaboration.
  - Requirements should be lightweight and clear, like user stories. Short formats promote clarity,
    planning, and ongoing feedback between developers and clients.
- Requirements should be simple, abstract statements of need, not detailed designs or interfaces.
  Capture core business needs clearly without over-specifying solutions.
- Scope creep leads to project failure. Prevent it with constant client feedback during iterations,
  helping them see the real impact of added features and make informed trade-offs.
- Maintain a shared project glossary to ensure everyone uses consistent terms. Clear, accessible
  definitions prevent confusion and improve collaboration across the team.

``` md
Tip 80: Use a Project Glossary
```

### 46. Solving Impossible Puzzles

- Solving problems requires identifying true constraints and recognizing your freedom within them.
  It is not about thinking inside or outside the box, but understanding where the box really is.

``` md
Tip 81: Don't Think Outside the Box—Find the Box
```

- When stuck on a tough problem, take a break. Shifting focus gives your subconscious mind space to
  work, often leading to surprising and effective solutions.
- People often solve complex problems better when distracted. If you can't step away, try explaining
  it to someone. Their questions or your own words may reveal the answer.
- *Eureka* moments come from a well-fed brain. Learn from daily feedback, build experience, stay
  calm and reflect often.

### 47. Working Together

- Work directly with users as part of the team. Collaborate while coding, not just in meetings, to
  solve problems and build useful software together.
- Pair Programming:
  - Pair programming combines two minds on one task, blending different skills, experiences, and
    focus levels to improve problem-solving and code quality.
  - In pair programming, one focuses on code syntax while the other considers higher-level issues.
    This division boosts problem-solving by using more collective brainpower.
  - Having a peer present encourages better coding habits and discourages sloppy shortcuts, leading
    to cleaner, higher-quality software.
- Mob Programming:
  - Mob programming extends pair programming to a whole group. With one typist and many minds, it
    boosts collaboration and brings diverse insights to the same problem.
  - Mob programming is live, collaborative coding that can involve users, sponsors, and testers, not
    just developers, to improve communication and build better solutions together.
- Explore different coding styles like solo, pair, or mob programming. Each has its own practices
  and benefits, so research first and start small before using them on critical code.

``` md
Tip 82: Don't Go into the Code Alone
```

### 48. The Essence of Agility

- Agile is how you work, not who you are. It's about adapting to change with flexibility and using
  responsive practices as a team or individual.

``` md
Tip 83: Agile Is Not a Noun; Agile Is How You Do Things
```

- We are uncovering better ways of developing software by doing it and helping others do it. Through
  this work we have come to value:
  - Individuals and interactions over processes and tools
  - Working software over comprehensive documentation
  - Customer collaboration over contract negotiation
  - Responding to change over following a plan
- Agile values the left side of the manifesto more than the right. Prioritizing the right-side means
  straying from the core principles the manifesto was built on.
- Agility means adapting to change, not following a fixed plan. Decisions must be based on context
  and feedback, not rigid rules or one-size-fits-all methods.
- No one can tell you exactly what to do, but the key is handling uncertainty by gathering feedback
  and using it to guide your actions and decisions. The recipe for working in an agile way:
  - Work out where you are.
  - Make the smallest meaningful step towards where you want to be.
  - Evaluate where you end up, and fix anything you broke.
- Using feedback at all levels improves both code and process. It helps refine design, rethink
  requirements, and evolve team practices. Without it, a team isn't truly agile.
- Good design makes change easy, which supports agility. If changes are painless, feedback loops
  stay effective and teams can adapt freely without fear or hesitation.

---
