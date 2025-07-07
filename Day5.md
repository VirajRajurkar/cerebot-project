## Day 5: Monday, July 8th, 2025

Welcome to **Gameplan + Practice Day**!

Today, we reflect a little, regroup, and make a plan for where the Cerebot project is headed. You’ve built a task manager already (awesome!), so we know you’re comfortable with Python inputs and basic structures. Now, let’s redirect those skills into making Cerebot smarter.

By the end of today:

* You’ll know what Cerebot is going to do this week (No pressure to know everything right now, just the basic features from a high level!)
* You’ll write code that loops through conversations
* You’ll get more confident using **lists**, **loops**, and **dictionaries**
* You’ll push your work to GitHub like a real developer 🚀

---

### Objectives for Today:

* Decide what Cerebot’s “conversation goal” is this week.
* Write `while` loop chatbot script that asks 2+ questions in a row. Get creative!
* Practice storing responses in a list and dictionary. Once again, get creative. 
* Push updated code to GitHub. 
* Complete your project brainstorm doc!

---

### Concepts: Lists, Loops, Dictionaries

This is me trying to get you started with the concepts today. Please also check YouTube and other online resources out too! 

#### 🔁 `while` loops:

Let you keep asking the user questions until they want to stop. 

```python
while True:
    answer = input("Are you having a stroke? ")
    if answer == "Yes":
        break
    else
        print("Lol rip!")
```

I would love for you to explore nested loops, and for loops too!

#### Lists:

Hold multiple things, like a list of symptoms or answers.

```python
symptoms = ["headache", "fatigue", "sadness", "sad"]
```

#### 🗂️ Dictionaries:

Let you label things (like mapping a symptom to its meaning).

```python
symptom_meaning = {
    "fatigue": "You might be stressed or low on sleep",
    "blurred vision": "This can be a warning sign of stroke"
}
```

---

### Tasks for Today

#### 1. **Brainstorm Cerebot Goals**

Open a shared Google Doc in [our shared folder](https://drive.google.com/drive/folders/1wxsy7kRp4OLEWfoEJRS3JF3PmM7GFz0e?usp=sharing) and write bullet points answering:

> “What should Cerebot do by the end of this week?”

Remember to answer in simple English. Try to answer from the POV of the user. So since I am really into the idea of using the Cerebot to asses symptoms, my bullet points could be:

- Have a sense of humour
- Recognise symptoms of stroke (specifically ... blah blah)
- Recognise symptoms of depression (specifically ... blah blah)

It can be serious, weird, fun, or personal. Want to help patients? Offer advice? Pretend to be a wizard? Get creative! It would be nice if you could remind me to check out your brainstorm doc on WhatsApp by the end of today!

#### 2. **Write a Simple “Conversational Loop” Bot**

Just an idea: create a new file called `cerebot_loop.py`. Start with:

* A `while` loop that keeps asking the user questions
* A way to store answers in a list
* A dictionary that connects certain answers to advice
* A way to exit the bot using a command like `"exit"`

Example structure:

```python
symptom_log = []

while True:
    symptom = input("Tell me a symptom (or type 'exit'): ").lower()
    
    if symptom == "exit":
        break
    
    symptom_log.append(symptom)
    
    if symptom in symptom_meaning:
        print(symptom_meaning[symptom])
    else:
        print("Thanks. I'll note that down.")
```

#### 3. **Organize Your Files**

Put your new file inside your project folder:

```
cerebot/
├── cerebot_loop.py
├── README.md
└── (any older files like chatbot_hello.py, etc.)
```

#### 4. 🚀 **Push to GitHub**

Use GitHub Desktop or Terminal to commit and push:

```bash
git add cerebot_loop.py
git commit -m "Add conversational loop and symptom logging"
git push origin main
```

---

### 🏠 Homework

* Finish your paragraph in the brainstorm doc
* List 3–5 symptoms or phrases you’d like Cerebot to recognize
* Bonus: Come up with one joke or surprise the bot could say!

---

### 🔁 Tomorrow: Sentiment Recognition 🔁

After developing a simple loop-based conversational structure, tomorrow we’ll continue working on this to teach Cerebot how to guess how someone is feeling based on the words they type. There's no pressure to finish up the conversation today, we'll get to it tomorrow!

