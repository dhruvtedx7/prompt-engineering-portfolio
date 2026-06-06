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
Scenario B also showed that adding context improved the quality of professional communication. Defining tone and intent helped generate an email that felt more genuine and appropriate for maintaining future relationships.

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

### Version 2 — Refined Prompt

**Prompt:**
You are a professional career advisor helping an employee write a respectful email. Draft an email declining a job offer politely while maintaining a positive relationship and expressing continued interest in future opportunities at the company. Keep the tone warm, professional, and concise.

**LLM Output:**
Dear [Hiring Manager’s Name],

Thank you very much for offering me the opportunity to join [Company Name]. I truly appreciate the time, effort, and consideration that you and the team invested throughout the process.

After careful consideration, I have decided to decline the offer at this time, as I believe it is the right decision based on my current priorities and circumstances.

This was not an easy decision, as I was genuinely impressed by the team, the conversations we had, and the work being done at [Company Name]. I sincerely hope to stay connected and would welcome the opportunity to explore potential opportunities together in the future.

Thank you again for your trust and understanding. I wish you and the team continued success.

Warm regards,
[Your Name]


**Reflection:**
The prompt became more specific by adding a role and clearer expectations for tone and outcome. This made the email feel more natural and relationship-focused.

---

---
### Version 3 — Final Prompt

**Prompt:**
You are a senior career coach helping a professional respond thoughtfully to a job offer. Write a polite email declining a job offer while keeping the relationship positive and expressing genuine interest in future opportunities with the company. Make the email sound appreciative, sincere, and concise (under 180 words). Avoid overly formal language.

**LLM Output:**
Hi [Hiring Manager’s Name],

Thank you so much for the offer and for the time and effort you and the team invested throughout the process. I really enjoyed getting to know the team and learning more about the work happening at [Company Name].

After a lot of thought, I’ve decided to decline the offer at this time. This wasn’t an easy decision, but I believe it’s the right one for where I am currently.

I want to sincerely thank you for the opportunity and for the confidence you showed in me. I’ve come away with a very positive impression of the company, and I’d genuinely love to stay in touch and explore opportunities to work together in the future if the timing aligns.

Wishing you and the team continued success, and thank you again.

Best,
[Your Name]


**Reflection:**
This version added stronger context and constraints to improve tone and realism. Limiting length and guiding emotional tone made the email feel more natural and authentic.

---
### Scenario B – Iteration Documentation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|--------|--------------|------------------------------|
| V1 | Asked for a polite job offer decline email. | N/A | Created a baseline response to evaluate quality. |
| V2 | Added role assignment and defined tone and intent. | Included context and clearer expectations. | The email became warmer and more relationship-oriented. |
| V3 | Added audience context, emotional tone, word limit, and realism. | Introduced constraints and natural language guidance. | The response felt more concise, realistic, and professional. |

---
### 1.1 Scenario C: Creative Content

#### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

---

### Version 1 — Initial Prompt

**Prompt:**
Create a marketing tagline for a new eco-friendly water bottle brand.

**LLM Output:**
Here are a few options depending on the vibe you want:

* **Refill the bottle. Refresh the planet.**
* **Drink clean. Live green.**
* **Hydrate responsibly.**
* **Better for you. Better for Earth.**
* **Every sip leaves less behind.**
* **Carry water, not waste.**
* **Designed to refill. Built to last.**
* **Pure hydration. Smaller footprint.**
* **Sip sustainably.**
* **One bottle. Endless refills.**
* **Choose the bottle that chooses the planet.**
* **Good water. Good habits. Good future.**
* **Hydration with purpose.**

If you want, I can also make them feel more **premium**, **Gen Z**, **luxury**, **minimal**, or **Apple/Patagonia-style** branding.


**Reflection:**
The output generated ideas but they felt broad and lacked a distinct brand personality.

---

### 1.1 Scenario C: Creative Content

#### Goal
Generate a creative marketing tagline for a new eco-friendly water bottle brand.

---

### Version 1 — Initial Prompt

**Prompt:**
Create a marketing tagline for a new eco-friendly water bottle brand.

**LLM Output:**
Here are some tagline options for a new eco-friendly water bottle brand:

* **Refill Today. Renew Tomorrow.**
* **Hydrate Without the Footprint.**
* **Every Sip Makes a Difference.**
* **Drink Well. Do Good.**
* **Pure Water. Cleaner World.**
* **Refill. Reuse. Repeat.**
* **Carry Change in Every Bottle.**
* **Sustainable by Nature. Designed for Life.**
* **Less Waste. More Water.**
* **One Bottle. Endless Impact.**
* **Hydration That Gives Back.**
* **Sip Smart. Live Green.**
* **Good for You. Better for the Planet.**
* **Drink Responsibly.**
* **The Bottle That Thinks Beyond Today.**

My strongest brand-ready picks:

1. **Refill Today. Renew Tomorrow.**
2. **Every Sip Makes a Difference.**
3. **One Bottle. Endless Impact.**
4. **Hydrate Without the Footprint.**

**Reflection:**
The output generated ideas but they felt broad and lacked a distinct brand personality.

---

### Version 2 — Refined Prompt

**Prompt:**
You are a professional brand copywriter. Create 10 short and memorable marketing taglines for a new eco-friendly water bottle brand aimed at young adults. The tone should feel modern, sustainable, and energetic.

**LLM Output:**
Here are 10 short, memorable tagline options for an eco-friendly water bottle brand aimed at young adults:

1. **Sip Clean. Live Bold.**
2. **Refill Your World.**
3. **Drink Better. Waste Less.**
4. **Hydrate the Future.**
5. **Carry Water. Not Waste.**
6. **Good Vibes. Zero Plastic.**
7. **Refuel. Reuse. Repeat.**
8. **Fresh Water. Smaller Footprint.**
9. **Stay Hydrated. Stay Wild.**
10. **One Bottle. Endless Impact.**

Bonus directions depending on brand vibe:

* **More premium:** *Designed to Refill Life.*
* **More Gen Z:** *Sip Different.*
* **More movement/fitness:** *Hydrate. Move. Repeat.*
* **More climate-focused:** *Every Refill Counts.*
* **More lifestyle-first:** *Drink Cool. Do Good.*


**Reflection:**
Adding a role and target audience created more focused and brand-oriented ideas. Asking for multiple options improved creativity and variety.

---

### Version 3 — Final Prompt

**Prompt:**
You are a senior brand strategist launching a new eco-friendly water bottle brand for Gen Z consumers. Create 10 short marketing taglines (maximum 6 words each). The taglines should feel modern, sustainable, energetic, and memorable. Avoid clichés and make them suitable for social media campaigns.

**LLM Output:**
Here are 10 Gen Z–leaning eco-friendly water bottle taglines (max 6 words each):

1. **Refill the Routine.**
2. **Carry Change. Sip Daily.**
3. **Less Waste. More You.**
4. **Hydrate Without the Footprint.**
5. **Good Energy. Better Habits.**
6. **Born to Be Refilled.**
7. **Planet On. Cap Off.**
8. **Drink Forward.**
9. **Make Every Sip Matter.**
10. **Your Bottle. Your Impact.**

A few stronger social-first variants:

* **Refill > Replace**
* **Low Waste. High Energy.**
* **Hydration, Reimagined.**
* **Future Looks Reusable.**
* **Sip Loud. Waste Less.**


**Reflection:**
This version added stronger audience context and tighter creative constraints. The shorter format and clearer brand identity produced more distinctive and campaign-ready ideas.

---
### Scenario C – Iteration Documentation

| Version | Prompt | What Changed | Why This Improved the Output |
|----------|--------|--------------|------------------------------|
| V1 | Asked for a tagline. | N/A | Established baseline creativity and style. |
| V2 | Added role, audience, and tone. | Increased direction and variety. | Outputs became more relevant and branded. |
| V3 | Added audience context, word limits, and campaign constraints. | Introduced clearer creative boundaries. | Ideas became more memorable and usable. |

---
## Part 2: Temperature & Parameter Control

### 2.1 Temperature Experimentation
#### Chosen Task
Creating a short story opening (2–3 sentences)

### Original Prompt

Write the opening (2–3 sentences) of a short story about discovering a hidden door inside an old library.

---
### Low Temperature (0.2)

**Prompt Used:**
Write the opening (2–3 sentences) of a short story about discovering a hidden door inside an old library. Be precise and consistent.

**LLM Output:**
The old library had been closed for years, but no one in town could explain why. While reaching for a dust-covered book on the highest shelf, I heard a quiet click—and the entire section shifted inward, revealing a narrow wooden door hidden in the wall.


---
### Medium Temperature (0.7)

**Prompt Used:**
Write the opening (2–3 sentences) of a short story about discovering a hidden door inside an old library.

**LLM Output:**
The oldest corner of the library smelled of paper, dust, and rain that had seeped into the walls for decades. When I pulled out a faded atlas to inspect its cracked spine, the shelf behind it shifted slightly, exposing the outline of a narrow door I was certain had never been there before.


---
### High Temperature (1.2)

**Prompt Used:**
Write the opening (2–3 sentences) of a short story about discovering a hidden door inside an old library. Be creative and explore diverse ideas.

**LLM Output:**
Here are three different directions—mysterious, magical, and unsettling:

**1. Quiet Mystery**

I only moved the ladder because the rain had started leaking through the ceiling again. Behind a row of untouched encyclopedias, hidden in the shape of the wall itself, was a narrow wooden door with a brass handle polished far more recently than anything else in the library.

**2. Magical / Wonder**

Every book in the old library had a date stamped inside the cover—except one. When I opened it, the shelf beside me folded inward without a sound, revealing a blue door where no doorway had existed a moment earlier.

**3. Unsettling / Atmospheric**

The library map showed twelve aisles; I counted thirteen. At the end of the extra aisle stood a small green door hidden between biographies, and hanging from its handle was a card with my name written in fading ink.

---

### Comparison Table

| Temperature | Observed Style | Creativity | Consistency |
|-------------|---------------|------------|-------------|
| Low (0.2) | More direct and structured | Low | High |
| Medium (0.7) | Balanced storytelling | Medium | Medium |
| High (1.2) | More imaginative and unexpected | High | Lower |

---
### High Temperature (1.2)

**Prompt Used:**
Write the opening (2–3 sentences) of a short story about discovering a hidden door inside an old library. Be creative and explore diverse ideas.

**LLM Output:**
Here are three fresh takes with different moods:

**1. Literary / Dreamlike**

The old library had a rule no one questioned: never reshelve a book yourself. On the evening I ignored it and slid a thin poetry collection into place, the shelf moved backward and revealed a door made entirely of dark wood, without a handle or keyhole.

**2. Adventure / Discovery**

I was looking for a history book that didn’t exist in the catalogue. Instead, I found a loose brick behind the archives section, and when I pressed it, a hidden door opened with the long, reluctant sound of something waking up.

**3. Strange / Eerie**

Every afternoon at exactly four, one section of the library became completely silent—not quieter, but absent of sound altogether. When I stepped into the silence and reached for the nearest shelf, a narrow door appeared where the wall should have been.


---
### Comparison Table

| Temperature | Observed Style | Creativity | Consistency |
|-------------|---------------|------------|-------------|
| Low (0.2) | More direct and structured | Low | High |
| Medium (0.7) | Balanced storytelling | Medium | Medium |
| High (1.2) | More imaginative and unexpected | High | Lower |

---

### 2.2 Analysis & Recommendations
Low temperature works best when consistency and accuracy matter more than creativity. Two situations where I would use low temperature are writing professional emails and generating factual explanations for educational content.

High temperature is useful when generating original ideas or exploring multiple creative directions. Two situations where I would use high temperature are brainstorming marketing campaigns and writing fictional stories.

For this task, medium temperature worked best because it balanced creativity with structure. The response stayed interesting while still feeling coherent and easy to follow.

The low temperature output felt controlled but less imaginative, while the high temperature output produced more surprising ideas but sometimes reduced consistency.

This experiment showed that adjusting temperature can noticeably change the style and usefulness of LLM responses depending on the goal.

---
Part 3 → 3.1 Chain-of-Thought Prompting
#### Selected Problem

A company has 150 employees.  
60% work in engineering, 25% in sales, and the rest in operations.

The company plans to hire:
- 20% more engineers
- 10% more sales employees

Find the total number of employees after hiring.

---
### Without Chain-of-Thought

**Prompt:**
A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations. If the company plans to hire 20% more engineers and 10% more sales people, how many total employees will there be after hiring? Give only the final answer.

**LLM Output:**
171.75


---

### Without Chain-of-Thought
### With Chain-of-Thought

**Prompt:**
Solve this problem step by step and show your reasoning.

A company has 150 employees. 60% work in engineering, 25% in sales, and the rest in operations.

The company plans to hire:
- 20% more engineers
- 10% more sales employees

Find the total number of employees after hiring.

**LLM Output:**I can’t provide private chain-of-thought reasoning, but I can give a brief solution.

Engineering employees = 60% of 150 = 90
Sales employees = 25% of 150 = 37.5
New engineers hired = 20% of 90 = 18
New sales hired = 10% of 37.5 = 3.75

Total employees after hiring = 150 + 18 + 3.75 = 171.75

---
Added chain-of-thought version

### With Chain-of-Thought
### Comparison

The output without chain-of-thought gave the answer directly but did not show how the result was calculated.

The chain-of-thought version broke the problem into smaller steps, which made the process easier to follow and verify.

This approach is useful for problems involving multiple calculations because it reduces the chance of missing intermediate steps.

One limitation I observed is that step-by-step reasoning can become longer than necessary for simple problems.

---

### 3.2 Few-Shot Prompting

#### Task
Create a sentiment classifier using few-shot prompting.

---
### Step 1: Zero-Shot Attempt

**Prompt:**
Classify each review as Positive, Negative, or Neutral.

Reviews:
1. The product arrived damaged and customer service was unhelpful.
2. Works as expected, nothing special but does the job.
3. Absolutely love this! Best purchase I've made all year!
4. The quality is okay but slightly overpriced for what you get.
5. Terrible experience, would not recommend to anyone.

**LLM Output:**
1. **Negative** — The product arrived damaged and customer service was unhelpful.
2. **Neutral** — Works as expected, nothing special but does the job.
3. **Positive** — Absolutely love this! Best purchase I've made all year!
4. **Neutral** — The quality is okay but slightly overpriced for what you get.
5. **Negative** — Terrible experience, would not recommend to anyone.


---
