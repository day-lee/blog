---
title: "How Agentic Coding Transformed My Junior Dev Workflow in Just 2 Days"
date: 2026-05-08
lastmod: 2026-05-08
summary: "Building linkedin custom filter app with copilot agent in 2 days"
description: "desc"
tags: ["projects", "ai"] #http://localhost:1313tags/hugo/  ← "세부분류 hugo" 태그가 붙은 글 모음
categories: ["projects"] #http://localhost:1313/categories/  ← 큰 분류. 전체 카테고리 목록
keywords: ["linkedin automation", "job search automation"] # SEO용. 구글 검색엔진이 참고하는 용도. 방문자는 못 봄
author: "Daylee"
draft: false
toc: true
---
# How Agentic Coding Transformed My Junior Dev Workflow in Just 2 Days
<p style="font-size:14px; color:#696969;"> Daylee &nbsp; &nbsp;| &nbsp;&nbsp; 2026-05-08 </p>

---

## Changing Perspective
Recently, I built a LinkedIn job filtering app that saves me two hours a day. It took six iterations to build this bespoke software with the help of an AI agent.

Previously, I had held myself back from using coding assistants like Claude and GitHub Copilot. As a junior developer, I wanted to build my “coding muscle.” I believed that a solid foundation and true craftsmanship could only be developed through manual trial and error. However, I soon realised I was being a bit of a "caveman."

### "It’s just another tool."
My perspective shifted after attending the  [Monki Gras](https://monkigras.com/) conference in London. I had the chance to talk to engineers with over 25 years of experience, people whose careers evolved alongside Docker and AWS. When I shared my hesitation toward agentic coding, they all said the same thing: <i>“It’s worth building something with an agent; it’s just another tool.” </i>The landscape is shifting rapidly. A few months ago, companies were worried about the security risks of AI. Now, many are mandating the use of AI agents for efficiency.

### The Concept of the "Single-user App"
The idea of the “Single-user App” further motivated me to build personal software. As [Betty Junod](https://www.bettyjunod.com/blog/when-the-icp-equals-one) from Monki Gras put it: <i><b>"The AI app dev movement will see an explosion of highly custom apps designed by and for a single user."</i></b>

I was always told to build apps to hone my skills, but spending significant time on a side project that only catered to me never felt time-efficient. I have many forgotten "passion projects" because I felt discouraged that they weren't “scalable.” The concept of a custom, single-user app, built to solve my specific problems via "vibe coding" finally justified building something just for myself.

## How a Junior Developer Approached AI-assisted Coding
 #### *A LinkedIn job filtering app* 
Initially, I planned to build my own scraper. However, I learned that LinkedIn is strict about scraping, and the risk of being banned was too high. Instead, I used Apify, a professional scraping service. It was cost-effective and, most importantly, safe. With an AI agent, I built an automated system to filter and save that data into Google Sheets.
<br><br>
<img src="https://github.com/day-lee/blog/blob/main/static/linkedin-filter-app.png?raw=true" alt="linkedin custom filter app" width="400px" margin-top="14px">
<p style="text-align:center; font-size:14px; color:#696969;">Linkedin Custom Filtering App</p>


### The Agentic Coding Journey with GitHub Copilot:

   1. Context Setting: I explained the project goals, design, and requirements clearly.
   2. Prompt Engineering: I asked how to write better prompts for the Agent to minimise bugs from the start.
   3. Iterative Refinement: We refined the requirements until every detail made sense to both me and the AI.
   4. Modular Code Generation: I broke the work into five small phases. I reviewed the code after each phase rather than doing it all at once.
   5. Data Verification:  I added tests and cross-checking code to verify the raw data.
   6. User Testing: I tested the app myself to find bugs and edge cases

<i>Note: I later learned the importance of setting a  <code>copilot-instructions.md</code> file for context. Previously, I was manually pasting context for every phase.</i>

<img src="https://github.com/day-lee/blog/blob/main/static/copilot.png?raw=true" alt="linkedin custom filter app" width="720px">
<p style="text-align:center; font-size:14px; color:#696969;">Agentic coding</p>

I didn’t just perform “vibe coding” (building purely with natural language). Instead, I practiced AI-assisted coding, treating the AI as a true pair programmer. I actively reviewed code, made manual tweaks, and maintained a spec document. The project was built in gradual phases under my careful monitoring. 

Agentic coding is an unprecedented and inevitable trend. <b style="color:#263691">As a junior developer navigating a tough job market, the only way forward is to adapt to this ever-changing industry. We must pivot our skills just as veteran engineers have evolved their toolsets throughout their careers. <b>
<br>
<br>
<br>