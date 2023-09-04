## 🛠️ Coding Companion: Your Suite of Python Functions 🚀

Welcome to the ultimate toolset crafted by Me i.e `Chandrashekhar Robbi`, designed to elevate your coding journey. From automating Git commits to crafting eloquent markdowns for LeetCode problems, it's all here. Dive in!

### 🌠 **At a Glance**:
<details>
  <summary>👀 Watcher Function: Keep tabs on your code directory and auto-commit to Git without breaking a sweat.</summary>
  

  ## 🚀 Git Commit Handler
  
  A script that tracks changes in a directory and auto-commits them to Git with descriptive messages.
  
  ### 🌟 Features:
  1. **🔍 Watches Files**: Uses the `watchdog` library to check for changes.
  2. **🤖 Git Automation**: Automatically pulls, commits, and pushes code.
  3. **💡 Smart Commit Messages**: Creates messages based on what's changed.
  
  ### 🛠 How it Works:
  1. Starts by pulling the latest from Git.
  2. Watches your chosen directory for changes.
  3. Sees a new file? Logs it.
  4. Sees changes? Commits them:
      - Finds a new function? Says so in the commit.
      - Other changes? Uses a general commit message.
  5. Pushes the changes to Git.
  
  ### 📌 Before You Start:
  - You'll need the `watchdog` library.
  - Make sure `git` is installed.
  
  ### 🚀 How to Use:
  1. Set the directory you want to watch in the `DIRECTORY_TO_WATCH` variable.
  2. Run the script.
  
  ### ⚠️ Heads Up:
  - Be careful using this on important projects. It commits automatically.
  - It currently uses basic rules for commit messages. Adjust if you need something specific.
  - It ignores 'Untitled.ipynb' files.

Screenshot of the logs:
![image](https://github.com/ChandrashekharRobbi/GFG-DSA/assets/91750738/0ad5d7bc-252f-47a2-ba34-69f03059da19)
---
</details>



<details>
  <summary>🙌🏻 Auto-Markdown Comment Generator : Make documentation a breeze. Turn comments into markdown and clip them right to your clipboard.</summary>
  

## 📝 Auto-Markdown Comment Generator

Easily turn your IPython comments into navigable markdown! Crafted by Chandrashekhar Robbi, this tool not only creates markdown cells but also populates your clipboard, making documentation a breeze!

### 🌠 Features:
1. **✍️ Easy Markdown**: Convert a comment to markdown with `new(string)`.
2. **📋 Clipboard Magic**: Automatically copies the generated markdown to your clipboard.
3. **🔍 Quick Navigation**: Hyperlink comments for swift notebook navigation.
4. **🗑️ Manage Comments**: Clean up and manage your list with a range of utility functions.

### 🚀 How to Use:
1. **Initialize**: Simply create an instance of `MyFunction`.
2. **Generate**: Use `new(string)` to turn a comment into markdown. It even warns you if a comment already exists!
3. **Manage**: View your comment list with `printArr()`, or remove items with `removeLastelement()` or `removeByUsingIndex(x)`.

### ⚙️ Behind-the-Scenes:
- The code integrates with IPython to manage and modify notebook cells.
- It cleverly uses `pyperclip` to populate your clipboard with markdown content instantly.
  
### ⚠️ Heads Up:
- The script works its charm in IPython notebooks.
- Make sure `pyperclip` and `IPython` are installed and ready to roll!

---
</details>




<details>
  <summary>🖊️ LeetCode Markdown Generator Documenting your LeetCode journey has never been this easy! Fetch, format, and fortify your problem-solving sessions.</summary>


## 📘 LeetCode Markdown Generator

Transform your LeetCode problem-solving journey into a well-documented notebook. Created by Chandrashekhar Robbi, this Python tool seamlessly fetches problem descriptions from LeetCode and formats them into markdown. And the magic doesn't stop there; it also auto-copies the content to your clipboard! ✨

### 🌠 Features:
1. **🔗 Hyperlink Creation**: Automatically creates a clickable link to the original LeetCode problem.
2. **📝 Markdown Magic**: Converts the problem description, including images, into a neatly formatted markdown.
3. **📋 Clipboard Ready**: Once your markdown is ready, it's copied to your clipboard for easy pasting.
4. **🔍 Problem Search**: Just provide the problem name, and let the tool do the rest.
5. **🗂 Comment Management**: Maintain, view, or remove comments as you like.

### 🚀 How to Use:
1. **Initialize**: Kick things off by creating an instance of `LeetFunction`.
2. **Fetch & Format**: Call `new(string)` with the problem name to generate markdown.
3. **Manage Comments**: Use functions like `printArr()`, `removeLastelement()`, and more to manage your comment list.

### ⚙️ Behind-the-Scenes:
- Uses `selenium` to automate the browser and fetch data from LeetCode.
- Leverages `pyperclip` for clipboard operations, making copying seamless.
  
### ⚠️ Before You Begin:
- Ensure you've got `selenium` and `pyperclip` installed.
- Also, don't forget to set the path for your browser's driver, like ChromeDriver for Chrome.


---
</details>


<details>

  <summary>🔓 Leetcode Markdown Assistant (smaller version of above function) : The lightweight champ. Quickly transform problem names into detailed markdowns.</summary>

  

## 📘 LeetCode Markdown Assistant


### 🌠 Features:
1. **🔗 Quick Links**: Generate direct links to the specified LeetCode problem with a simple command.
2. **📝 Markdown Mastery**: Instantly convert a LeetCode problem name into markdown, complete with placeholders for your approach and complexities.
3. **📋 Clipboard Convenience**: With `pyperclip` integration, your markdown is immediately ready for pasting.
4. **🗃 Comment Management**: Effortlessly maintain a list of your comments with utility functions.

### 🚀 Usage:
1. **Start-Up**: Fire up by creating an instance of `LeetFunction`.
2. **Markdown Magic**: Invoke `new(string)` with the problem name and watch it convert into a markdown link and template.
3. **Comment Control**: Functions like `printArr()`, `removeLastelement()`, and more are there to help you manage your comment inventory.

### ⚙️ Behind-the-Scenes:
- Designed especially for IPython notebooks.
- Uses the magic of `pyperclip` to make your clipboard markdown-ready in an instant.

### ⚠️ Quick Note:
- Ensure `pyperclip` is installed.
- Ready to ease your LeetCode documentation? Let's get started!


---
</details>

> Toggle to know more about each function 😊


### 🎯 **Why Use It?**:
If you're coding frequently in IPython notebooks and navigating the challenges of LeetCode, this toolset is a game-changer. It streamlines processes, making your coding sessions more efficient and well-documented. Spend less time on chores and more on crafting solutions!

### 🚀 **Get Started**:
Dive into each function, and you'll find detailed instructions on how to wield its power. Each is loaded with features, waiting to make your life easier. So why wait? Supercharge your coding sessions today!


