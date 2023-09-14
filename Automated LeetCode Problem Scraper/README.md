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

### Quick Demo Video




https://github.com/ChandrashekharRobbi/helper-functions/assets/91750738/8c11b5ef-16fd-4f0a-8575-16af1e38c505
