---
title: "Building linkedin custom filter app with copilot agent in 2 days"
date: 2026-04-14
lastmod: 2026-04-14
summary: "summary"
description: "desc"
tags: ["projects", "ai"] #http://localhost:1313tags/hugo/  ← "세부분류 hugo" 태그가 붙은 글 모음
categories: ["projects"] #http://localhost:1313/categories/  ← 큰 분류. 전체 카테고리 목록
keywords: ["linkedin automation", "job search automation"] # SEO용. 구글 검색엔진이 참고하는 용도. 방문자는 못 봄
author: "Daylee"
draft: true
toc: true
---
I built a LinkedIn job filtering app that saves me two hours a day. \
It took just two days and six iterations to build this bespoke software. \

I was only able to build it because I attended a conference called [Monki Gras](https://monkigras.com/) in London, which completely changed my perspective.

Previously, I had held myself back from coding with agents like Claude, Codex, and Copilot. As a junior developer, I wanted to build my "coding muscle". I believed that a solid foundation and true craftsmanship could only be built through trial, error, and manual experience.

However, I realised I was being a caveman.

During Monki Gras, I had the chance to talk to many engineers with over 25 years of experience. When I told them about my hesitation toward agentic coding, they all said the same thing: **"It’s worth building something with an agent; it’s just another tool."**
The landscape is changing rapidly. A few months ago, companies were worried about the security risks of AI. Now, I hear that companies are encouraging or even mandating the use of AI agents for efficiency.

Furthermore, the concept of the "single-user app," which I learned about from Betty Junod at the conference, motivated me to build personal software.

> AI app dev movement will see an explosion of highly custom app designed by and for a single user.  - Betty Junod

I was always told to build apps to hone my coding skills. However, spending significant time on a side project that only catered to me never felt time-efficient. As a result, I have many forgotten passion projects; I felt discouraged knowing my apps weren't "scalable". Betty’s concept of the custom, single-user app finally justified building something just for myself.

## How a junior developer approached AI-assisted coding:
 #### *A LinkedIn job filtering app* 
Initially, I was going to build my own scraper. 
However, I learnt that LinkedIn strongly dislikes scraping, and there is a high risk of being banned. I did not want to lose my connections and posts. As an alternative, I used Apify, a scraper maintained by professionals. It was cost-effective, worked smoothly, and most importantly, removed the risk of a ban. With the help of an AI agent, I built an automated system to filter and save the data into a Google Sheet.

### The Agentic coding journey with GitHub Copilot:

   1. Context: I explained the project goals and requirements clearly.
   2. Prompt Engineering: I asked how to write better prompts for the AI to minimise bugs from the start.
   3. Iteration: We refined the requirements until every detail made sense to both me and the AI.
   4. Strategy: I asked for a strategy to work effectively with an agent. I broke the work down into small chunks and reviewed them after each phase. The task was divided into five phases based on specific features.
   5. Verification:  I added tests and cross-checking code to verify the raw data
   6. User Testing: I tested the app myself to find bugs and edge cases

*Note: One thing that was learnt later was the importance of setting up a `copilot-instructions.md` file for context. Previously, I entered the entire context document manually for each phase.*


I didn't perform "vibe coding" (building software using only natural language). Instead, I practiced AI-assisted, agentic coding, treating the AI as a true pair programmer. I actively reviewed the code after each phase, made manual changes, and wrote a spec document. The project was built in gradual phases under my careful monitoring.

Agentic coding is an unprecedented and inevitable trend. As a junior developer navigating a tough job market, the only way forward is to adapt to this ever-changing industry. We must pivot our skills just as those engineers with 25 years of experience have evolved their toolsets throughout their careers.
