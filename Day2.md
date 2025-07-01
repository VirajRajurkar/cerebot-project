## Day 2: Tuesday the 2nd of July 2025.
Welcome back! 🎉

Yesterday you got set up with Python, VS Code, GitHub, and Git. You even created your first project repo. 
That’s already more than many university students ever do. Well done.
Today, we’re finally going to write code. Not just any code — we’re going to start building your Cerebot’s brain. 

Think of this like making your bot come to life for the very first time!

---

### Objectives for Today

* Practice Python basics: `print()`, `input()`, variables, and string concatenation
* Write your first chatbot-style program that talks to the user
* Understand how Python code “flows”
* Get used to writing and saving Python files in VS Code
* Push your code to GitHub

---

### Agenda

| Time        | What to do                                        |
| ----------- | ------------------------------------------------- |
| 15 min      | Review Day 1: Tools check, Python version test    |
| 20 min      | Warm-up: What would your ideal chatbot say first? |
| 30 min      | Python Basics: `print()`, `input()`, variables    |
| 45 min      | Play around with "barebones" chatbot logic        |
| 15 min      | Customize your chatbot’s responses                |
| 15 min      | GitHub push + reflection                          |
| Homework | Add more responses and questions to your bot      |

## Python Warm-Up: Say Hello!

Let’s open VS Code and create your first `.py` file:

```python
# chatbot_hello.py
print("Hi! What’s your name?")
name = input()
print("Nice to meet you, " + name + "!")
```

Try running it from Terminal (the funny little box below your coding setup) by typing this:

```bash
python chatbot_hello.py
```
Just like you saw the output on the left side in programmiz, it should run here too!

### ✅ Key Python Concepts Today ✅

| Concept       | What It Means            | Example                       |
| ------------- | ------------------------ | ----------------------------- |
| `print()`     | Display a message        | `print("Hello!")`             |
| `input()`     | Ask the user something   | `name = input("Your name: ")` |
| Variable      | A label for storing info | `color = "blue"`              |
| String        | Text (inside quotes)     | `"hello"`                     |
| Concatenation | Stick strings together   | `"Hi " + name`                |

### ✅ Build Your First Chatbot ✅

Try this more complete version:

```python
# chatbot_greetings.py
print("Hello, human! What’s your name?")
name = input()

print("Cool name, " + name + "! What’s your favorite color?")
color = input()

print("Nice! I bet " + color + " suits you well.")
```

Once it works, this is what you do:

* Save it as `chatbot_greetings.py`
* Run it
* Change  emojis or questions to match your own personality

If you remember the talk about the Agile method from yesterday, this might feel pleasing to you.
This super super basic script is your first example of a "working prototype"! NICE WORK!

### ✅ File Structure So Far ✅

The diagram below is meant to illustrate the arrangement of files in your project.
Here’s how your project folder might look at this point. Keeping track of our files is really useful in projects!

```
cerebot/
├── chatbot_hello.py
├── chatbot_greetings.py
└── README.md
```

### 🚀 Push to GitHub 🚀

Let’s save your progress online.

If using **GitHub Desktop**:

1. Open your repo folder
2. Click **"Commit to main"** – message: `Add greeting chatbot`
3. Click **Push origin**

If using **Terminal**:

```bash
git add chatbot_greetings.py
git commit -m "Add greeting chatbot"
git push origin main
```
And just like that, you've also taken a first step to documenting your work!


### 🏠 Homework for Day 2 🏠

* Add two more fun questions to your chatbot
* Example: Ask for favorite animal or what they had for lunch
* Honestly go crazy with the print statements. Tailor it to what different scenarios. Get creative. 
* Push your updated chatbot to GitHub!

---

### 🔁 Tomorrow: Decision-Making Bots! 🔁

We’ll teach your chatbot how to make decisions using `if`, `elif`, and `else`. 
These statements are only executed based on certain conditions.

It’s going to get smarter!

