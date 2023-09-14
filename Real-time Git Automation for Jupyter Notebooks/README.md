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
