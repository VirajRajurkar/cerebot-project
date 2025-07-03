## Day 3: Tuesday the 3rd of July 2025.

Welcome back! 🎉

Yesterday, you wrote your first chatbot using `print()` and `input()`, and you learned how to store user input in variables. 
At this point, your "Cerebot" should at least be able to greet the user! Furthermore, depending on how creative you are, it should be able to ask about their favorite things. 

Today, we’re going to make the bot **smarter**.

We’ll teach it how to make decisions using something called **conditionals** in programming. 
This will let your bot react differently depending on what the user says. It’s kind of like giving it a personality — or at least a set of basic reflexes.

The idea is for the Cerebot to say something predefined based on a condition. 

---

### Objectives for Today

* Learn how to write decision-making code using `if`, `else`, and `elif`
* Get comfortable with indentation (Python is strict about it!)
* Make your chatbot respond to different answers with different outputs
* Write and save a new chatbot file with logic-based conversation
* Push your updated code to GitHub

---

### Agenda

| Time  | What to do                                                      |
|------ | --------------------------------------------------------------- |
|15 min | Quick recap of variables and input handling                     |
|30 min | Learn and explore conditionals in Python                        |
|30 min | Build a chatbot that responds differently based on answers      |
|30 min | Add some funny or custom reactions (a “secret password” maybe?) |
|30 min | Save your file, push to GitHub                                  |

---

## 🧠 Python Stuff: Giving Your Bot a Brain

So far, your chatbot could only say the same thing no matter what the user typed.

But that’s not how real conversations work. You want your bot to **respond** to the user, to think just a little before replying. This is where conditionals come in.

A **conditional** lets you tell the computer:

> "If this thing is true, do this. Otherwise, do something else."

You’ll use `if`, `elif` (which means “else if”), and `else` to set up these choices.  

Example:

```python
name = input("What's your name? ")

if name == "Batman":
    print("Welcome, Dark Knight.")
elif name == "Harry":
    print("You're a wizard!")
else:
    print("Nice to meet you, " + name + "!")
```

Even this tiny snippet - your bot already has an "attitude". 

---

### ✅ Key Python Concepts Today ✅

| Concept     | What It Means                                                       | Example                   |
| ----------- | ------------------------------------------------------------------- | ------------------------- |
| `if`        | Tests whether something is true                                     | `if name == "Alice":`     |
| `else`      | What to do if the `if` wasn’t true                                  | `else: print("Hi!")`      |
| `elif`      | A second test if the first `if` wasn’t true                         | `elif name == "Bob":`     |
| `==`        | Comparison operator — checks if two things are equal                | `if color == "blue":`     |
| Indentation | Tabs/spaces used to show what belongs inside the `if`, `else`, etc. | (Use 4 spaces or Tab key) |

Remember: in Python, **indentation is not optional**. It’s how the language knows which code belongs to which block. If something is not indented properly, Python will complain! I highly recommend looking at Python tutorials for further help with this, for example [this one that you are likely familiar with](https://youtu.be/_uQrJ0TkZlc?si=2hTmdu8-rD7Be9dc).


### ✅ What Are We Building Today? ✅

Today, I would love if we could build (at the very least) a chatbot that:

1. Asks for the user’s name
2. Responds differently depending on the name
3. Asks for the user’s favorite color
4. If the color is "blue", says “That’s the color of the sky!”
5. If the color is "red", says something else (you decide)
6. Otherwise, just says “Nice choice”

This might sound small — but it’s the **first step toward dynamic logic**. Real programs are full of `if`s and `else`s, and this is your first one.

Later, we’ll be using this to build whole conversation flows!

---

### ✅ File Structure So Far ✅

Here’s how your project folder might look now:

```
cerebot/
├── chatbot_hello.py          # Your very first script
├── chatbot_greetings.py      # Today’s file with conditionals
└── README.md                 # A file explaining your project
```

We’re separating each chatbot experiment into its own file. This keeps things clean and makes it easier to test ideas.

---

### 🚀 Push to GitHub 🚀

As long as you save your work on your own laptop, there is no need to worry about this part. It is optional but SUPER nice to have. 
If you've been successful setting up Git and a GitHub account, let’s save your progress online. 

You should be doing this at least at the end of your day! Please do let me know if you are finding it a bit too challenging with this bit!

**If using GitHub Desktop:**

1. Open your repo folder
2. Click **"Commit to main"**
3. Message: `Add greeting chatbot with if-else`
4. Click **Push origin**

**If using Terminal:**

```bash
git add chatbot_greetings.py
git commit -m "Add greeting chatbot with if-else"
git push origin main
```

And just like that, you’ve backed up your work and can show it to the world. I'll remind you that this is how software engineers document their work!

---

### 🏠 Homework for Day 3 🏠

1. Try adding one more question to your bot (e.g. "What's your mood today?") and use `if/else` to respond.
2. Try writing a version where a certain input gives a *special* reply ("You found the easter egg! 🥚")
3. Go crazy with the if-else statements! The sky's the limit. Invent complex scenarios and try solidifying the logic into if-else statements!
4. Watch this great beginner-friendly video on conditionals: [Python If Else Statements – Real Python](https://youtu.be/FvMPfrgGeKs?si=Y74m1PtQoySMAXjM).

---

### 🔁 Tomorrow: Modular Brains and Functions 🔁

Right now, all your chatbot logic is in one big pile. That’s fine for now — but soon, it will get messy.

Tomorrow, we’ll start learning how to **organize** your bot’s brain using **functions**. This lets you reuse logic, stay clean, and build more complex bots step by step.
You’re doing amazing. See you tomorrow!
