---
aliases:
  - 
date_created: 
date_modified: 
tags:
  - project
title: Project Name
---

# Project Name

This design template helps you maximize success on your projects. The value of this template comes through going through the process, gathering feedback, exploring solutions, and adjusting as you learn.

A word of caution—Be careful about confusing a filled-out document as going through the process effectively.

Project lead tips:
- Be flexible and adjust the template as needed. This template is a starting point and guide. It is not a prescriptive destination.
- Not all feedback is valuable. You can learn a lot from some discussions. And sometimes, you gain nothing. However, you can never learn _less_ by gathering input.
- Work as a team on the design. While it’s your job as the project lead to own the overall structure and voice, it’s not your job to write everything yourself. Get your team involved by assigning ownership to sections.
- This document needs to stand on its own. A nice benefit is this helps with onboarding, meeting new stakeholders, and project reviews.

Leadership tips:
- Ask your team to walk you through the document once you’ve read through it deeply. And don’t use slides.
- Avoid setting OKRs and goals that focus on filling out this document. There is a fine line between incentivizing your team to gather feedback and think through solutions vs. your team filling it out to check a box.
- Give your team as much context upfront as you can. It’s incredibly demotivating for a group to jam on a design for weeks only to hear they went in a wildly different direction than you expected. It’s your fault when this happens, so when it does, own up to it and provide better expectations.
- Incentivize your team to keep this document updated throughout the project. Also, if your organizational culture allows, encourage your team to make projects discoverable so that others can build on their work.

## Problem Statement

This section answers the question, “Why are we doing this work?” Think expansively rather than reductively at first. For example, ask questions like, “In a perfect world where this data exists and you have a great prediction, what would you do?” Very rarely is a specific ask from a stakeholder the right problem to solve. Tips:
- If you don’t understand why you are doing this work, don’t do it.
- “Far better an approximate answer to the right question, which is often vague, than an exact answer to the wrong question, which can always be made precise.” - John Tukey

### Business Case and Current State

Why is this project important? How is this problem solved today? Thought starters:
- What business metric(s) improve by doing this work? How does this project align with larger company goals?
- What happens if we don’t do this work? More often than not, a current “good enough” solution is still “good enough,” even if it is an annoyance for a team. Remember that a “yes” on your time is also a “no” to other opportunities.

### Success Metrics

How do you know the project is successful? Get specific. Thought starters:
- Will it be a “2% increase of conversion rate” or some meaningful change to a business metric?
- Is it a production model with a minimum percentage uptime?
- Can you run an experiment such as an AB test? What other metrics are important?

### Lessons Learned

What did you learn from the last phase of the same project? Or what did you learn from a previous, similar project?

### Requirements

What are the high-level requirements? Work with the stakeholders and come up with ~3-5 bullet points such as:
- Make a model that predicts XYZ.
- Model results should be available in the data warehouse and updated periodically.
- Business owners should understand how to query and use these results.

### Deliverables

What are the final deliverables? Work with the stakeholders to come up with deliverables, using the above requirements as examples, such as:
- A presentation explaining the model outputs, feature importance, exploratory visuals, and recommended next steps.
- A specific database location for model results with documentation on data refresh frequency.
- Training for business owners on how to query the results and a data dictionary.

Tips:
- If you don’t understand what the high-level goals are, then keep iterating. Often the high-level goals are too high-level, and it’s up to us as data professionals to refine and articulate them, which is great because we get to own and guide the project.
- Do not start a project without at least one explicitly defined and agreed-upon deliverable with a target due date.

### Prioritization

Work with your broader organization to evaluate the priority of this project against other projects.

Your organization may say that this project is not worth doing right now or even not worth doing at all. Document this decision here and review it with stakeholders. Priorities can shift, and it’s OK to redesign or reprioritize a project at a later date. What is not relevant to this prioritization decision is the timing of the request. Be careful about pressure from stakeholders because someone requested something x months ago.

## Stakeholders

Who are the project stakeholders? List names and roles. Tips:
- No development should start until the scope is finalized-ish. And be careful about scope creep during a project. It’s OK if the goal changes and we adjust. What’s not OK is if a significant scope change isn’t discussed and agreed on.
- Too many stakeholders are a mess. Too few stakeholders are ineffective. Find what works best for your company culture, and don’t be afraid to prune over time.
- Be flexible. You’ll know when you are ready to start; feedback helps refine the design and approach and allows folks to invest in the results.

## Ethics

Does your project cause harm? Thought starters:
- Can the data product harm users or the organization? If so, how can you reduce these risks?
- How are you capturing, storing, and retaining user data? Does your system comply with data-related laws such as GDPR and CCPA?
- Are your model results and analyses biased against specific demographics?
- How transparent is the decision-making logic in the system?

## System Architecture

What’s this going to look like at the end? Be specific—diagrams, a picture or handwritten design, dashboard mocks, etc. Ideally, you’re able to link to pre-existing resources as well.

### Inputs and Outputs

What are all the data inputs and outputs? Exactly where. Directories, formats, schema.tablename, etc.

### Product Usage

How will this data product be used? What systems and teams will this data product interact with at a detailed level? Be specific. For example:
- Data flows from this system to X and Y and influences decision Z.
- Data flows into G and is used for H, K, and J.

### Algorithm/Mocks/Report

Rename this header as appropriate for the project. This part is a bit of a grab bag and depends on the problem. Thought starters:
- ML models
	- It’s tempting to spend way too much time on this one, so this documentation is vital to put in some guardrails.
	- The suggested approach would be an iterative approach like “build X and Y review with the team and evaluate based on target metric Z, if target metric is > T% launch, otherwise, decide next steps. “
- Dashboard or report
	- Mocks are essential to decide if this solution fulfills the requirements. You need to review them with stakeholders.
	- In place of a specific mock, an iterative approach is to build X and Y, review with the team, then decide the next steps.
	- What calculations/aggregations are necessary? Sometimes this is obvious in a mock.
- Corner cases
	- Document any weird or essential corner cases.
	- Team review is essential as everyone has their pet corner case.

## Milestones

What are you delivering and when? Having a project split into bite-sized pieces is helpful in many ways:
- Detailed tickets with clear items to be done help maintain focus.
- Communicate progress to wider stakeholders.
- Provide guardrails to stay on track.
- Are nicely incremental and allow for an iterative approach to a project.
- Be flexible. Too much detail in a ticket entails too much time spent writing tickets; too little leaves the ticket vague and makes completion unclear.

## Close-Out

How does this project end? Document the end to ensure that your team can account for maintenance in project planning. Thought starters:
- Some projects need maintenance to keep running.
- Some projects can spur on another project.
- Some projects are done with a deliverable.
- Some projects are handed off to other teams.
