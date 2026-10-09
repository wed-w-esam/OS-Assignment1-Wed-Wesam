# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [we wesam AL-aghbar] |
| **Student ID** | [446052681] |
| **University Email** | [446052681]@std.psau.edu.sa |
| **GitHub Username** | [wed-w-esam] |
| **Repository Link** | [https://github.com/wed-w-esam/OS-Assignment1-Wed-Wesam] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [0ct 7, 2026, 11:30 AM]
**What I did**:Completed Part 1 and implemented Feature 1 (Priority).

**Details**:I set up my assignment repository and added a priority field to the Process class. I also assigned a random priority to each process and displayed its priority .when adding it to the ready queue.

**Challenges**:I needed to understand where to add the priority field and how to display it without changing the FIFO scheduling behavior.

**Solution**:I followed the existing code structure, added the priority-related changes, and checked that the program still ran.

**Time spent**:1 hour.

---

### Entry 2 - [0ct 8, 2026, 1:00 AM]
**What I did**:Implemented Feature 2 (Context Switch Counter).

**Details**: I added a counter to track context switches and incremented it whenever the scheduler started a process thread. I also added a message at the end of the program to display the total count.

**Challenges**: I did not encounter any major challenges while implementing this feature.

**Solution**: I followed the existing scheduler code and ran the program to check that the counter was displayed.

**Time spent**:1 hour.

---

### Entry 3 - [[0ct 8, 2026, 3:00 pM ]
**What I did**:Implemented Feature 3 (Waiting Time Tracking).

**Details**:I added arrival time and waiting time variables to the Process class. I implemented methods to set the arrival time, calculate waiting time, and retrieve the waiting time. I also added a results table displaying each process’s burst time, waiting time, and turnaround time.

**Challenges**:The first output showed unusually large waiting times and duplicate process entries in the results table.

**Solution**:I corrected the arrival time handling and used a HashSet to display each process only once. I ran the program again and checked the results.

**Time spent**:2 hours.

---

### Entry 4 - [[0ct 7, 2026, 10:00 pM]
**What I did**:Completed Part 1 of the assignment.

**Details**:I set up my GitHub repository, updated the repository name, and completed the required student information and initial setup.

**Challenges**:I needed to make sure the repository was configured correctly and followed the assignment requirements.


**Solution**:I followed the assignment instructions and checked the repository settings.

**Time spent**:30 minutes.

---

### Entry 5 - [[0ct 9, 2026, 2:00 pM]
**What I did**:Tested the completed features and reviewed the program output.

**Details**: I ran the program to verify the priority display, context switch counter, and waiting time results table. I also checked that each process appeared only once .in the results table.

**Challenges**: I needed to make sure the output was clear and that the calculated results were displayed correctly.

**Solution**: I reviewed the output after running the program and checked the results against the implemented code.

**Time spent**:1 hour.

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [X hours]

**Most challenging part**:

**Most interesting learning**:

**What I would do differently next time**:

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[Through this assignment, I learned how multithreading concepts are applied in a Java program. I already knew that Thread.start() starts a thread, Thread.sleep() pauses a thread for a specified time, and Thread.join() makes one thread wait for another thread to finish. However, implementing the assignment helped me understand how these methods are used within a complete program. I also gained practical experience working with the scheduler and the ready queue. In addition, I learned how to track waiting time and display process results in a table. Overall, this assignment helped me practice concepts I had learned and understand how they work in code]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was working on the code using my iPad. I was able to edit the code, but I could not run the program to test it. This made it difficult to check whether my changes worked correctly. I had to continue writing the code without seeing the program’s output. As a result, I could not verify the implementation until I had access to a computer.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame this challenge by opening my project on my computer after finishing the code on my iPad. I ran the program to check whether the implemented features worked correctly. When I noticed problems in the output, I reviewed the relevant parts of the code and made corrections. I ran the program again to verify the changes. This helped me make sure that the program worked as expected.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is useful in many real-world applications. For example, web servers can use multiple threads to handle requests from different users at the same time. This helps the server respond to users more efficiently. Another example is download managers, which can perform multiple download tasks concurrently. The concepts of thread scheduling and time allocation help manage tasks and share system resources. Understanding multithreading can help me develop applications that are more responsive and efficient.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is a program in execution, while a thread is a unit of execution within a process. A process usually has its own memory space and resources, whereas threads within the same process share memory and resources. In this assignment, the Process class represents a simulated process, not a real operating system process. In the addProcessToQueue() method, new Thread(process) creates a Java thread that uses the Process object to perform its task. The thread begins executing when start() is called. This shows how the assignment uses Java threads to simulate process scheduling.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process does not finish within its time quantum, it is added to the end of the ready queue if other processes are waiting. In my program, P8 had a burst time of 4616 ms and a time quantum of 2000 ms. It was re-queued twice before finishing, because it still had remaining execution time after its first two turns. Re-queueing allows other processes to use the CPU while P8 waits for its next turn. This makes scheduling fairer by giving waiting processes a chance to execute.]

Example from my output:
```
[P8 executing quantum [2000ms]
P8 completed quantum 2000ms
Remaining time: 2616ms
P8 yields CPU for context switch
P8 added to ready queue — Burst time: 4616ms — Priority: 6

P8 executing quantum [2000ms]
P8 completed quantum 2000ms
Remaining time: 616ms
P8 yields CPU for context switch
P8 added to ready queue — Burst time: 4616ms — Priority: 6

P8 executing quantum [616ms]
P8 completed quantum 616ms
Remaining time: 0ms
P8 finished execution!]
```

**Explanation of example:**
[P8 needed 4616 ms of CPU time, but its time quantum was 2000 ms. After the first turn, 2616 ms remained, and after the second turn, 616 ms remained. Therefore, P8 was added back to the ready queue twice before completing its final turn. During this time, other processes were allowed to execute, which helps ensure fairness in Round-Robin scheduling.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1’s thread is created in addProcessToQueue() using new Thread(process). At this point, the thread has not started executing.]

2. **Runnable**: [When the scheduler calls currentThread.start(), P1’s thread becomes eligible to run and waits for CPU time if necessary.]

3. **Running**: [ When P1 gets CPU time, it executes the run() method, which simulates running for one time quantum or its remaining time, whichever is smaller.]

4. **Waiting**: [Inside run(), P1 calls Thread.sleep(stepTime) in the progress loop, temporarily entering the Timed Waiting state.Meanwhile, currentThread.join() makes the main thread wait until P1’s thread finishes its current turn. ]

5. **Terminated**: [When P1’s run() method finishes, its thread terminates. If P1 still has remaining time and other processes are waiting, the program creates a new thread for the same Process object and adds it to the ready queue for another turn.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling in a Time-Sharing Operating System]

**Description**:
[A time-sharing operating system shares CPU time among multiple processes. In Round-Robin scheduling, each process gets the CPU for a fixed time quantum before the scheduler moves to the next process if the current one is not finished. This is similar to my simulation, where each Process represents a program waiting for CPU time.]

**Why Round-Robin works well here**:
[Round-Robin promotes fairness by giving each ready process a chance to use the CPU. The time quantum limits each turn, while a context switch allows another process to run.
]

### Example 2: [A Multithreaded Web Server]

**Description**:
[A multithreaded web server handles requests from multiple clients at the same time. Each thread can handle work related to a client request, similar to how processes are represented in my simulation. Round-Robin can share CPU time among ready threads by giving each one a fixed time quantum.]

**Why Round-Robin works well here**:
[This approach promotes fairness and helps prevent one CPU-intensive thread from monopolizing the processor. A context switch allows another ready thread to execute, which can improve responsiveness when many requests need CPU time.]

## Summary

**Key concepts I understood through these questions:**
1. How Round-Robin scheduling shares CPU time among processes using a fixed time quantum
2. How threads move through their lifecycle, from New to Terminated.
3. How context switches and re-queuing help give other processes a chance to execute

**Concepts I need to study more:**

1. The differences between process states and Java thread states.
2.. How time quantum size affects scheduling performance and responsiveness.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
