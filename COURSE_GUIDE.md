# Learn Python by Building Projects

**An 8-week practical roadmap for a complete beginner**  
**Commitment:** 2 hours daily · 7 days/week · **112 hours total**

> **Goal:** Learn enough Python and problem-solving skills to build, debug, and explain small applications independently—not merely finish a course.

## The approach

Learn a concept, practice it, then apply it to a real project **the same day**. Use one main course rather than switching between tutorials. Over time, aim to spend **60–70% of learning time writing and debugging code**.

### Daily 2-hour routine

| Time | Activity | What to do |
|---|---|---|
| 25 min | **Learn** | Study one concept. Type the examples and modify them. |
| 35 min | **Practice** | Solve exercises before looking at hints or solutions. |
| 50 min | **Build** | Implement or improve a project using what you learned. |
| 10 min | **Review** | Write down what you understood, note blockers, and commit your work to Git. |

**Tip:** If a topic is difficult, spend another day on it rather than rushing to match the schedule.

---

## Eight-week roadmap

### Week 1 — Python fundamentals

**Learn:** Variables, basic types, strings, numbers, input and output, `if` statements, `for` and `while` loops.

**Build:**
- A command-line calculator.
- A number-guessing game with hints and a replay option.

**Checkpoint:** Write a basic interactive program without copying from a tutorial.

### Week 2 — Functions and data structures

**Learn:** Functions, parameters, return values, lists, dictionaries, sets, tuples, and common string operations.

**Build:** A command-line to-do list that can add, view, complete, and remove tasks (initially stored in memory).

**Checkpoint:** Break a small application into clearly named, reusable functions.

### Week 3 — Files and debugging

**Learn:** Reading/writing files, JSON, handling exceptions, Python modules, debugger basics, introductory Git and GitHub.

**Build:** A personal expense tracker that records purchases and saves them between runs.

**Checkpoint:** Persist data reliably and diagnose common errors instead of randomly changing code.

### Week 4 — Real data and APIs

**Learn:** Installing packages with `pip`, virtual environments, HTTP requests, JSON responses, basic tests, and error handling.

**Build:** A weather lookup app or a Pokémon information lookup using a public API.

**Checkpoint:** Fetch, parse, display, and optionally save external data, including handling failed requests.

### Week 5 — Writing maintainable programs

**Learn:** Splitting code into modules, introductory classes and objects, separation of concerns, and testing with `pytest`.

**Build:** Refactor the expense tracker: separate business logic from user interaction and storage; add automated tests.

**Checkpoint:** Explain what each module does and run tests after making a change.

### Week 6 — Plan an original project

**Learn:** Turning an idea into requirements, writing small tasks, reading package documentation, making effective Git commits.

**Build:** Start **one** useful personal project. Write a README describing the problem, features, installation instructions, and initial task list.

**Checkpoint:** Implement a feature from a written requirement instead of following a step-by-step tutorial.

### Week 7 — Implement independently

**Learn:** Input validation, edge cases, debugging unfamiliar code, and reading technical documentation.

**Build:** Finish the project's core features and add tests for important behavior.

**Checkpoint:** Troubleshoot a bug and explain the root cause.

### Week 8 — Finish, document, and demonstrate

**Learn:** Refactoring, project cleanup, basic packaging or run instructions, and communicating technical decisions.

**Build:** Publish the finished project on GitHub with a clear README, example usage, and tests where appropriate.

**Checkpoint:** Demonstrate the project, explain how it works, and make a small improvement without step-by-step help.

> **The schedule is adjustable.** Eight weeks should produce a solid beginner foundation, not mastery or job readiness. Progress matters more than finishing on an exact date.

---

## Recommended free learning resources

Choose **one primary course**:

1. **[University of Helsinki — Python Programming MOOC](https://programming-26.mooc.fi/)** — Best default for structured, exercise-heavy learning. Ideal for someone who learns by reading and writing code.
2. **[Harvard CS50P — Introduction to Programming with Python](https://cs50.harvard.edu/python/)** — Great alternative for learners who prefer video lectures and guided problem sets.

Keep this reference handy:

- **[Official Python documentation](https://docs.python.org/3/)** — Look up language features, modules, and the standard library as questions arise.

**Avoid:** Attempting both courses at once, endlessly searching for the “perfect” course, or spending weeks watching videos without writing programs.

---

## Project ladder

### 1. CLI to-do list — beginner

**First version:** Add, view, complete, and delete tasks.

**Stretch features:** Save tasks as JSON, due dates, filter completed tasks, sort by priority.

**Skills:** Lists, dictionaries, functions, loops, input validation, file storage.

### 2. Expense tracker — beginner to intermediate

**First version:** Record a transaction and display all transactions and total spending.

**Stretch features:** Categories, monthly totals, CSV export, JSON persistence, tests.

**Skills:** Data modeling, files, dates, modules, error handling, testing.

### 3. Weather or Pokémon lookup — intermediate

**First version:** Ask for a location or Pokémon name, call a public API, and display key information.

**Stretch features:** Multiple lookups, caching, saved favorites, better handling of network errors.

**Skills:** HTTP, JSON, third-party packages, virtual environments, external documentation.

### 4. Habit tracker — possible final project

**First version:** Create habits, record daily completions, and view progress.

**Stretch features:** Streaks, weekly statistics, SQLite persistence, automated tests, polished command-line interface.

**Skills:** Requirements, program structure, state, persistence, tests, documentation.

**Choose a final project that solves a real problem for the learner.** Personal interest is a major advantage when the work gets difficult.

---

## How to use AI without outsourcing learning

Use AI as a **tutor and reviewer**, not a solution generator.

1. **Try alone for 15–20 minutes.** Read the error message and attempt a few hypotheses.
2. **Ask for a hint**, not a complete solution. Request an explanation of the relevant concept if needed.
3. **Finish the implementation yourself.** Only compare with example code after your own attempt.
4. **Request code review.** Ask about bugs, readability, edge cases, and test coverage.
5. **Rebuild a small feature from memory the next day.** This checks whether the skill actually stuck.

### Copyable AI tutoring prompt

> I'm learning Python. Act as a programming tutor. Don't write the full solution for me. Ask guiding questions, provide small hints, and help me understand mistakes. Review my code after I've attempted the problem myself. Favor explanations and debugging strategies over generated implementations.

---

## Progress checkpoints

- [ ] **End of week 2:** Build a small command-line app using functions without following a tutorial.
- [ ] **End of week 4:** Read data from an API and save results locally.
- [ ] **End of week 6:** Split an original project idea into small tasks and implement features independently.
- [ ] **End of week 8:** Show a complete working project, explain the code, and diagnose a bug without AI writing the fix.

### Weekly self-review

At the end of each week, answer:

- What can I build now that I couldn't build last week?
- Which concept can I explain in my own words?
- Where did I get stuck, and how did I resolve it?
- What is the **one** most important feature or concept to tackle next?

---

## Optional: Support from an experienced developer

If a more experienced friend or mentor is available, schedule a **30-minute review once a week**:

- Have the learner demo their current project.
- Ask them to explain a design decision in their own words.
- Suggest **one** realistic new feature.
- Identify **one** bug or edge case to investigate.
- Suggest **one** targeted code-quality improvement.

The mentor should avoid taking over the keyboard. Helping the learner discover a solution is more valuable than supplying one.

---

## Suggested setup

Start simple:

- Install a recent supported [Python 3](https://www.python.org/downloads/) release.
- Use [VS Code](https://code.visualstudio.com/) with the Python extension, or another beginner-friendly editor.
- Create a GitHub account and use a repository for each meaningful project.
- Learn `python`, `pip`, and virtual environments as they become relevant. Don't front-load a complex toolchain.

**First action today:** Install Python, create `hello.py`, run it in a terminal, modify it to ask for the user's name, and commit the file to a Git repository.

**Guiding principle:** Build things, get stuck, investigate, fix them, and repeat.
