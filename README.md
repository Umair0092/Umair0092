## Hi, I'm Umair

I'm a Rails developer in Lahore. Right now I lead a small team at QbitxSystems, which means a lot of architecture calls, code reviews and sprint planning, but I still write a good share of the code myself.

### How I got here

I studied Computer Science at FAST from 2019 to 2023. The university project I remember best is a blocks game I wrote in x86 assembly for our COAL course ([Coal-work](https://github.com/Umair0092/Coal-work)). Moving things around the screen one register at a time is a good way to stop taking computers for granted.

I joined QbitxSystems in August 2023, right after graduating, and I've been writing Rails there ever since.

My first big project was **Startup-Pal**, an HR and payroll app for startups and small companies. I built a lot of its core models (employees, payroll, attendance, leave) and spent real time on the RSpec suite. That project is where I learned that good tests are what let you change code without being nervous about it.

Next came **Lawzo**, a legal marketplace where clients find a lawyer and book a consultation, in person or over video. I worked on the AI agents for case and legal research, the video calls on Daily.co, and the live updates with ActionCable and native push notifications.

Today I'm Team Lead on **TireTag**, a traffic rules enforcement SaaS we build for a client. Leading has changed how I look at code. A lot of my job now is making sure everyone else on the team can move quickly without breaking things.

Along the way I tried other stacks to see how they compare: MERN, Flutter for mobile ([Bookify](https://github.com/Umair0092/Bookify)), FastAPI. I keep coming back to Rails, but each detour taught me something I brought back with me. At HackXVI, the LUMS web hackathon, my team finished in the top five out of 20.

The work projects above are private client code, so you won't find them here. What you will find is what I build on my own time.

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
