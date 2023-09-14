
## 📌 AutoGit: Automatic Git Committer and Pusher for Dynamic Development! 🚀

Developed by Chandrashekhar Robbi 😎, the `AutoGit` is designed to watch for file changes in your directory, automatically generating git commit messages based on the changes, and pushing them to the repository. It's particularly useful when working on iterative development where you'd like commits to be automatically generated and pushed based on the specific changes you make.

### 🌟 Features:

1. **File Monitoring**: Monitors a specific directory for any file modifications, creations, etc.

2. **Dynamic Commit Messages**: Automatically generates commit messages based on the changes, especially targeting function modifications.

3. **Counter Mechanism**: Ensures that random commit messages are only chosen after a set number of changes to avoid spammy commits.

4. **Color-coded Terminal Feedback**: Feedback messages in the terminal are color-coded for better clarity.

### 🛠 Core Functionalities:

- **Watcher Class**: Sets up an observer on a specified directory, monitors for any changes, and triggers appropriate handlers.

- **Handler Class**: Handles specific events like file creation or modification. When a file is modified, it evaluates the changes, generates a commit message, commits the changes, and pushes them.

### 🎩 Behind the Scenes:

1. **Git Pull**: As a safety measure, the script performs a `git pull` at the start.

2. **Function Detection**: Using regular expressions, the script checks if a function within the modified file has changed and crafts a commit message around that function's name.

3. **Random Commit Messages**: If no specific function change is detected, the script chooses from a pool of generic commit messages. However, this only happens every 20 changes to avoid clutter.

4. **File Exclusion**: The script avoids committing changes from generic filenames like "Untitled.ipynb".

5. **Feedback System**: After committing and pushing changes, you get a success message. If your commit was postponed due to the counter mechanism, you'd be informed about how many changes are left before the next commit.

### 📂 How to Set Up:

1. **Directory Monitoring**: Set the `DIRECTORY_TO_WATCH` variable in the `Watcher` class to the directory you want to monitor.

2. **Dependencies**: Ensure you have the required modules such as `watchdog` for directory monitoring and standard libraries for system operations.

3. **Run**: Simply execute the script, and it will continuously monitor the directory, making git operations as necessary.

### 💼 Use Case:

Ideal for developers working in Jupyter notebooks or other iterative development environments. Instead of manually crafting commit messages and pushing changes, `AutoGit` takes care of this, allowing you to focus solely on coding!

### 🔐 Note:

Ensure you're in the correct directory (where the repository is initialized) before running the script. Always review automatically generated commits occasionally to ensure they convey meaningful information about the changes.

---

This description provides a comprehensive overview of the script, its functionalities, and its use-case. Adjust as necessary for your audience on GitHub!

Screenshot of the logs:
![image](https://github.com/ChandrashekharRobbi/GFG-DSA/assets/91750738/0ad5d7bc-252f-47a2-ba34-69f03059da19)
