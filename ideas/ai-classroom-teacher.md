# Idea: AI Classroom Teacher for Young Learners

**Status:** Parked — build after Week 2 (agent fundamentals) + Domain 3-5 skim week
**Captured:** [today's date]

## Summary
Persistent AI teacher avatar for primary school kids (CBSE Class 1-5) — visible on
screen during study time, listens continuously, speaks naturally, helps with
textbook reading, pronunciation, math, comprehension. Full spec pasted below.

## Why parked, not dropped
Needs all of: agents (Domain 2), computer vision (Domain 3), speech, and
information extraction (Domain 5) — none of which are built yet as of [today].
Natural fit as a capstone project once those modules are done.

## Scoped-down MVP (for Week 4 build, not full vision)
Child speaks a question about a textbook page (camera captures it) → agent
answers via voice, age-appropriate, remembers child's name/grade across session.
NO avatar, NO lip-sync, NO parent dashboard for v1.

## Full original spec
# Epic: AI Classroom Teacher for Young Learners

## Title

Build an AI-powered virtual classroom teacher for primary school children.

## Background

Current AI chatbots are excellent at answering questions but do not provide the experience of interacting with a real teacher. Young children are generally more engaged when they can see a friendly face rather than a chat interface.

The goal is to create a persistent AI teacher that sits on a laptop or tablet screen during study time. Instead of opening a chatbot, the child interacts naturally with the teacher as if speaking to a tutor sitting across the table.

The application should become a companion throughout the learning session rather than an assistant that appears only when prompted.

---

## User Story

**As a** primary school student (CBSE Class 1–5),

**I want** to study from my physical textbook while a friendly AI teacher is present on the screen,

**so that** I can ask questions naturally whenever I get stuck, receive explanations appropriate for my age, and feel like I have my own personal teacher.

---

## Vision

The AI teacher should:

* Remain visible throughout the study session.
* Have a warm, friendly appearance suitable for children.
* Listen continuously for questions.
* Speak naturally using expressive speech.
* Maintain eye contact and simple idle animations (smile, blink, nod, think).
* Encourage curiosity rather than simply answering questions.
* Adapt explanations based on the child's age and understanding.
* Be patient and never make the child feel embarrassed for asking questions.

The experience should resemble sitting beside a kind elementary school teacher rather than chatting with an AI assistant.

---

## Example Scenario

A child is reading a CBSE Class 3 English textbook.

Child:
"Teacher, what does this word mean?"

The AI teacher smiles, pronounces the word correctly, explains it using simple language, uses it in a sentence, and asks the child to repeat it.

Later:

Child:
"I don't understand this paragraph."

The teacher summarizes it in age-appropriate language, gives a relatable example, and checks whether the child has understood before continuing.

---

## Functional Requirements

### Teacher Presence

* Persistent on-screen teacher avatar.
* Natural idle animations.
* Lip-sync while speaking.
* Friendly facial expressions.

### Voice Interaction

* Always available for questions.
* Natural conversation.
* Interruptible speech.
* Handles follow-up questions with context.

### Learning Assistance

* Read from physical textbooks.
* Explain difficult words.
* Correct pronunciation.
* Explain concepts with examples.
* Solve mathematics step by step.
* Read stories aloud.
* Ask comprehension questions.
* Encourage independent thinking instead of immediately giving answers.

### Computer Vision

* Understand textbook pages from the camera.
* Identify which paragraph or illustration the child refers to.
* Read handwritten or printed text.
* Support pointing to a specific word or sentence.

### Personalization

* Remember the child's name.
* Know current grade level.
* Adapt vocabulary.
* Increase difficulty gradually.
* Celebrate progress.

---

## Non-Functional Goals

* Child-safe responses.
* Low latency conversation.
* Friendly and emotionally supportive.
* Simple interface with almost no buttons.
* Parent-configurable settings.

---

## Future Enhancements

* Multiple teacher personalities.
* Regional language support (Tamil, Hindi, etc.).
* Homework mode.
* Quiz mode.
* Storytelling mode.
* Reading assessment.
* Progress dashboard for parents.
* Integration with CBSE curriculum.

---

## Success Criteria

A child should naturally refer to the application as "my teacher" rather than "an AI" or "a chatbot."

The interaction should feel like learning with a patient human tutor who is always available and never gets tired of answering questions.
