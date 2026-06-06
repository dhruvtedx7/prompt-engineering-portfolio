# prompt-engineering-portfolio
Dhruv_Shukla_PromptEngineering.md
# Prompt Engineering Portfolio

Name: Dhruv Shukla  
Date: 6 June 2026  
LLM Used: ChatGPT (GPT 5.5)

---

## Part 1: Prompt Design & Iteration

### 1.1 Scenario A: Technical Explanation

#### Goal
Explain a complex technical concept to a 10-year-old.

#### Concept Chosen
Neural Networks

---

### Version 1 — Initial Prompt

**Prompt:**
Explain neural networks to a 10-year-old.

**LLM Output:**
Imagine you're teaching a robot to recognize cats and dogs.

A neural network is like a giant team of tiny decision-makers working together.

🧠 Think of it as a brain made of LEGO pieces

Each LEGO piece (called a neuron) does one simple job:

It looks at some information.
It makes a tiny decision.
It passes the result to the next pieces.

One neuron isn't very smart, but thousands or millions together can do amazing things.

How it learns

Suppose you show it lots of pictures:

🐱 Cat
🐶 Dog
🐱 Cat
🐶 Dog

At first, it mostly guesses randomly.

When it gets an answer wrong, someone tells it:

"Nope, that's a cat!"

The network then adjusts its tiny decision-makers a little bit.

After seeing many examples, it starts noticing patterns:

Pointy ears
Whiskers
Shape of the face
Fur patterns

Eventually it gets really good at telling cats from dogs.

A simple example

Imagine three layers:

📷 Input layer → sees the picture

🔍 Hidden layers → look for patterns like eyes, ears, and tails

✅ Output layer → says "Cat" or "Dog"

Like this:

Picture
   ↓
Find edges
   ↓
Find ears & eyes
   ↓
Recognize animal
   ↓
Cat!
Why are they called "neural" networks?

Scientists got the idea from the human brain, which is made of billions of real neurons connected together.

Neural networks aren't actual brains, but they are inspired by how brains pass information around.

What can they do?

Neural networks help computers:

Understand speech 🎤
Recognize faces 📸
Translate languages 🌎
Drive cars 🚗
Create art 🎨
Power AI chatbots like ChatGPT 🤖

So, in one sentence:

A neural network is a computer system that learns from lots of examples, a bit like how a kid learns by practicing and getting feedback. 😊

**Reflection:**
The explanation was understandable but still contained technical language and lacked examples that a child could relate to.

---

### Version 2 — Refined Prompt

**Prompt:**
You are an elementary school teacher. Explain neural networks to a curious 10-year-old using simple words, one everyday example, and no difficult technical terms. Keep it under 200 words and end with one fun question.

**LLM Output:**
magine you’re teaching a robot how to recognize a dog.

At first, the robot is not very good. You show it lots of pictures and tell it, “This is a dog” or “This is not a dog.”

Inside the robot is a huge team of tiny helpers. Each helper looks for one small clue:

“Do I see floppy ears?”
“Do I see fur?”
“Do I see four legs?”
“Do I see a tail?”

Each helper gives a little opinion. Then another group combines those opinions and decides: “Hmm… I think this is a dog!”

If the robot guesses wrong, it adjusts how much it listens to each helper and tries again next time.

After seeing many examples, the robot gets much better at spotting dogs—even ones it has never seen before.

A neural network is basically a big team of tiny decision-makers that learns from lots of examples, kind of like how people practice and improve.

Fun question: If you were training a robot, what would you teach it to recognize first—animals, snacks, or superheroes?
**Reflection:**
I improved the prompt by adding a role, clearer instructions, and asking for an example to make the explanation easier to understand.

---
### Version 3 — Final Prompt

**Prompt:**
You are an experienced elementary school teacher introducing technology to a class of 10-year-olds who have never heard of neural networks before. Explain neural networks using simple language and one everyday example a child would know. Avoid difficult words, keep the explanation under 150 words, break it into short paragraphs, and end with one fun question plus one sentence summarising the idea.

**LLM Output:**
magine you are teaching a robot how to recognise a dog.

At first, the robot looks at lots of pictures and gets confused. Sometimes it says a cat is a dog!

So we help it learn. We show many examples and tell it when it is right or wrong.

Inside the robot are lots of tiny “decision helpers” working together. One helper notices ears. Another notices fur. Another notices the shape of the face. Together, they make a guess.

This teamwork of little helpers is called a neural network.

It’s a bit like how you learn too: the more examples you see, the better you get at spotting patterns.

Fun question: If you trained a robot with pictures of your favourite snacks, what snacks would it learn to recognise?

Summary: A neural network is a team of tiny decision-makers that learns from examples to recognise patterns.

**Reflection:**
This version added more context and structure. Shorter sections, a relatable example, and a summary made the explanation easier to understand and more suited to the audience.

---



### Iteration Documentation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|--------|--------------|------------------------------|
| V1 | Explain neural networks to a 10-year-old. | N/A | Baseline prompt used to see the initial quality. |
| V2 | Added role, audience instructions, example requirement, and simpler language constraints. | Introduced role assignment and clearer expectations. | The output became easier to understand and more engaging for a child. |
| V3 | Added classroom context, word limit, paragraph structure, summary, and interaction. | Added stronger context and output structure. | The response became more focused, age-appropriate, and easier to follow. |

---

### 1.3 Role and Context Analysis

Adding a role helped the model adjust its tone and style for the intended audience. Instead of giving a generic explanation, the responses became more suitable for how an elementary school teacher would explain concepts.

Providing context made the output more targeted and reduced unnecessary technical detail. Adding constraints such as examples, word limits, and structure also improved clarity.

This exercise showed that better prompts usually lead to better outputs and that context can strongly influence response quality.

---



### 1.1 Scenario B: Professional Email

#### Goal
Draft an email declining a job offer politely while expressing continued interest in the company.

---
### Version 1 — Initial Prompt

**Prompt:**
Write an email declining a job offer politely while expressing continued interest in the company.

**LLM Output:**
Dear [Hiring Manager’s Name],

Thank you very much for extending the offer for the [Role Title] position. I sincerely appreciate the time, effort, and consideration that you and the team invested throughout the interview process.

After careful consideration, I’ve decided to decline the offer at this time, as I’ve chosen to move in a different direction that I believe aligns more closely with my current priorities and goals.

This was not an easy decision, as I was genuinely impressed by the team, the conversations we had, and the work being done at [Company Name]. I continue to hold the company in high regard and would welcome the opportunity to stay connected and explore potential opportunities to work together in the future.

Thank you again for your time and support throughout the process. I truly appreciate the experience and wish the team continued success.

Warm regards,
[Your Name]


**Reflection:**
The email was professional but slightly generic and did not include enough context or personal tone.

---


