## Hi, I'm Umair

I'm a software engineer in Lahore. I build products with Ruby on Rails, and my favourite part of the job is the stretch where a rough idea turns into something people actually use.

### How I got here

It started at FAST, where I studied Computer Science. The project I still think about is a blocks game I wrote in x86 assembly for our COAL course ([Coal-work](https://github.com/Umair0092/Coal-work)). When every pixel has to pass through a register, you stop taking anything a computer does for granted.

After university I joined QbitxSystems, and that's where I started writing Rails every day.

The first product I helped build there was **Startup-Pal**, an HR and payroll app for startups and small companies. I wrote much of its core (employees, payroll, attendance, leave) and put serious time into the RSpec suite. That paid off: bugs dropped by up to 80%, and I learned that good tests are what let you change code without being nervous about it.

Then came **Lawzo**, a legal marketplace. A client describes their problem, AI helps them find the right lawyer, and they book a consultation in person or over video. I built the AI research agents, the video calls on Daily.co, and the live updates and push notifications that hold the whole flow together.

These days I'm on **TireTag**, a traffic rules enforcement platform we build for a client. I own the technical side of the project: how it's structured, what goes into each release, and what gets merged.

Along the way I tried other stacks to see how they compare: MERN, Flutter for mobile ([Bookify](https://github.com/Umair0092/Bookify)), FastAPI. I keep coming back to Rails, but each detour taught me something I brought back with me.

That work is client code, so it stays private. What's below is what I build for myself.

### What I'm working on now

**[Nexora](https://github.com/Umair0092/Nexora)** is an interview practice app. You answer out loud to an AI interviewer that has read your CV, and afterwards you get a report on what you said and how you came across on camera. The camera analysis runs in the browser, so the video never leaves your device. Companies can use the same interviewer to screen candidates, with a pipeline board, team scorecards and side-by-side comparison. It's a Rails 8 API with a React front end, Postgres, and Groq for the LLM and Whisper calls.

<p align="center">
  <img src="./assets/nexora/demo.gif" width="100%" alt="Nexora walkthrough: landing page, hiring pipeline, candidate review and comparison" />
</p>

<table>
  <tr>
    <td width="50%"><img src="./assets/nexora/report-section.jpg" alt="Interview feedback" /><p align="center"><sub>Feedback on each answer</sub></p></td>
    <td width="50%"><img src="./assets/nexora/job.jpg" alt="Hiring pipeline" /><p align="center"><sub>The hiring pipeline</sub></p></td>
  </tr>
  <tr>
    <td width="50%"><img src="./assets/nexora/candidate.jpg" alt="Candidate review" /><p align="center"><sub>Reviewing a candidate</sub></p></td>
    <td width="50%"><img src="./assets/nexora/compare.jpg" alt="Comparing candidates" /><p align="center"><sub>Comparing candidates</sub></p></td>
  </tr>
</table>

**[embed_sync](https://github.com/Umair0092/embed_sync)** is a Ruby gem that keeps vector embeddings in sync with your ActiveRecord models. [neighbor](https://github.com/ankane/neighbor) searches vectors and [ruby_llm](https://github.com/crmne/ruby_llm) generates them, but keeping them up to date as records change was still left to you. It's early, and I'm building it in the open through the roadmap issues.

### What I use

Ruby and Rails, Hotwire (Turbo and Stimulus), PostgreSQL, RSpec, ActionCable and Solid Queue. When a page needs more than Hotwire, I reach for React with Tailwind.

### Recent activity

<p align="center">
  <img src="https://raw.githubusercontent.com/Umair0092/Umair0092/output/streak.svg" alt="GitHub streak" />
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Umair0092/Umair0092/output/github-contribution-grid-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/Umair0092/Umair0092/output/github-contribution-grid-snake.svg" alt="Contribution graph animation" width="100%" />
</picture>

If you want to talk about Rails, a role, or anything above, you can reach me on [LinkedIn](https://www.linkedin.com/in/umair-hassan-1a11b12b8) or at umairhassan0092@gmail.com.
