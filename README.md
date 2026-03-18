# Volleyballreceivev1
# Volleyball Receiving Check

## Overview
Volleyball Receiving Check is a lightweight student-facing web app prototype for PE.

Its purpose is to help students:
- observe receiving outcomes
- connect the outcome to movement and contact
- choose one adjustment to test
- reflect and try again

This is not a motion analysis tool.  
It is a guided observation and experimentation tool.

---

## Learning Goal
The app supports this learning cycle:

**What → So what → Now what**

Students learn to notice:
- whether they got into position to receive
- whether the pass had useful height
- whether the ball stayed playable

This helps them think about movement, readiness, contact, and adjustment.

---

## Current Features
- Enter Player Name
- Enter Email
- Enter Buddy / Coach
- Record 3 quick observations:
  - Position to receive
  - Pass height
  - Playability
- Choose 1 improvement focus:
  - Better position
  - Better pass height
  - More playable ball
- Instant feedback card with:
  - simple visual
  - What
  - So what
  - Now what
  - reflection prompt
  - next goal
- Email draft using `mailto:`
- Reset button for the next student

---

## Why It Is Lightweight
This prototype is intentionally simple.

It does not use:
- video analysis
- photo capture
- motion tracking
- backend email service
- database storage

The focus is student observation, movement awareness, and experimentation.

---

## Receiving Model Used
The app uses 3 key observation areas:

### 1. Position to receive
This looks at whether the player moved early enough and got into a workable position before contact.

### 2. Pass height
This looks at whether the ball travelled at a useful height after contact.

### 3. Playability
This looks at whether the ball stayed playable for the next touch.

These 3 areas were chosen because receiving is reactive, so students need to notice both:
- movement before contact
- outcome after contact

---

## How To Use
1. Student A receives the ball.
2. Student B observes the action.
3. Student B records:
   - position to receive
   - pass height
   - playability
4. Student chooses one thing to improve next.
5. The app generates feedback.
6. Student tries again.
7. Feedback can be sent by email for later reflection.

---

## Tech Notes
- Built as a static HTML/CSS/JavaScript page
- Designed for lightweight deployment on GitHub Pages / Cloudflare Pages
- Email uses `mailto:` for now
- No backend yet
- No database yet

---

## Suggested Next Steps
### Version 1.1
- refine wording for students
- shorten some feedback lines
- improve visual polish
- add class / group field if needed

### Version 1.2
- save results to a database
- support real email sending
- add teacher dashboard or export

### Version 2
- combine Serving Check and Receiving Check into one shared PE observation workflow

---

## Summary
This app is a guided observation tool for volleyball receiving.

It helps students:
- notice what happened
- think about what it suggests
- choose one adjustment
- improve through experimentation

The goal is to build observation, movement awareness, and decision-making in PE learning.
