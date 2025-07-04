## Day 4: Friday the 4th of July 2025.

Welcome back, (and happy 4th of July lol)! 🎉

As per instructions so far, Cerebot can greet users, ask questions, and react based on simple inputs. I'm a big fan of the task manager that you made. Brilliant work!! 
That’s an awesome start. Today's objective is to call and make efficient use of functions. 😵 

Code without functions is generally not recommended by software engineers because it leads to less maintainable, less reusable, and harder-to-understand code, especially for larger programs. 
While calling functions can introduce a tiny overhead, the benefits of modularity, readability, and organization significantly outweigh this minor performance cost for most applications. 

You can think of functions as a sort of machine. This machine accepts certain defined inputs, and returns to you predictable outputs. How and why is this output predictable? It's because the function contains the code that YOU wrote! Nice!

The most important function that I would love to see in your code is the *main()* function! Please bear in mind, functions should never be duplicated (their name or the code they contain)!

Today, I also encourage you to keep thinking about the direction your project is headed in. What features do we want in your task manager? Do you want to stick to it, or try something else out, etc. 🤩

---

### Objectives for Today

* Understand how functions work and why we use them
* Break chatbot logic into reusable functions
* Think about what kind of chatbot Cerebot should become
* Start sketching out feature ideas and conversation paths
* Keep the project folder tidy and modular

---

### Agenda

| Time       | What to do                                                  |
| ---------- | ----------------------------------------------------------- |
| 15 min     | Quick review of if/else logic and yesterday’s chatbot       |
| 30 min     | Learn how to define and call functions in Python            |
| 30 min     | Refactor chatbot into functions like `greet_user()`         |
| 30 min     | Brainstorm what Cerebot should be able to do                |
| 15 min     | Save code, push to GitHub, note feature ideas for next week |
| 30 min     | Have a chat to align on outcomes this week, and feedback    |

---

## 🧠 Python Stuff: Breaking the Code Into Brains 🧠 

Right now, your bot is like a brain with no structure — it just does everything in one big chunk. Functions let us break that brain into **sections**, each with a job.

Think of it like this:

* You wouldn’t write a novel with no paragraphs, right?
* You wouldn’t cook a full meal in one giant pot, right?

Therefore, we mustn't write code that way either.

### ✅ Key Python Concepts Today ✅

| Concept            | What It Means                           | Example                   |
| ------------------ | --------------------------------------- | ------------------------- |
| `def`              | Defines a function (gives it a name)    | `def greet_user():`       |
| Calling a function | Runs the code inside that function      | `greet_user()`            |
| Parameters         | Input that you can give to the function | `def greet(name):`        |
| Return values      | What the function sends back            | `return "Hello, " + name` |
| main function      | The starting point of a python script   | `def main()`              | 


Here’s what a function looks like:

```python
def greet_user():
    name = input("What’s your name? ")
    print("Hi, " + name + "!")
```

You can now just call `greet_user()` anytime you want that greeting flow to happen. Neat and tidy.

### ✅ Today’s Mission ✅

If you're out of ideas (I don't think you are), you’ll write a chatbot script that:

1. Has **at least 3 functions**, such as:

   * `greet_user()`
   * `ask_favorite_color()`
   * `give_compliment()`
2. Calls those functions in order
3. Uses some conditional logic inside the functions
4. Feels more organized and easier to read than yesterday’s bot

Otherwise, I encourage you to pack the logic for your task manager into little functions that do the same

The tutorial from Programming with Mosh is more than enough!

### ✅ File Structure So Far ✅

Here’s a possible snapshot of your project folder now:

```
cerebot/
├── chatbot_hello.py              # Day 2: print/input
├── chatbot_greetings.py         # Day 3: if/else logic
├── chatbot_functions.py         # Day 4: modular version
└── README.md
```


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

### 🏠 Homework for Day 4 🏠

No homework! Instead, I encourage you to keep writing features (in simple English - no need to code yet) that you would like Cerebot to do. The reason I encourage doing it this way is because we will later undergo a "code freeze". 

This is where you stop writing logic later in the internship and focus on launching the Cerebot. For that to happen, your logic must be bulletproof, and for your logic to be bulletproof, your features must be crystal clear in plain and simple English. 

---

### 🔁 Next week 🔁

We continue working on the logic, but this time, we code the core logic!


