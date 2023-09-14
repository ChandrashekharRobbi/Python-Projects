## 📌 LeetFunction: Enhance Your LeetCode Experience in Jupyter Notebooks! 🚀

Developed by Chandrashekhar Robbi 😎, the `LeetFunction` class is an advanced Jupyter Notebook tool designed to simplify and enhance the experience of solving problems on LeetCode directly within your notebooks.

### 🌟 Features:

1. **Dynamic Markdown Generation**: Instantly get a markdown version of the problem's content. This includes the problem description, images, and test cases.

2. **Link Navigation**: Just input the problem name, and the function can redirect you to the exact problem page on LeetCode.

3. **Comment Manager**: Easily create, remove, or print comments within the notebook.

4. **Clipboard Support**: Directly copy the markdown content or comments to your clipboard using `pyperclip`.

5. **Integrated Web Automation**: Uses Selenium to fetch problem details from LeetCode.

6. **IPython Notebook Cell Management**: Functions to delete Jupyter notebook cells, either the current or the previous one, allowing for seamless notebook operations.

### Quick Demo Video

https://github.com/ChandrashekharRobbi/helper-functions/assets/91750738/8c11b5ef-16fd-4f0a-8575-16af1e38c505
### 🛠 Core Functionalities:

- `new(s, link=None)`: Accepts the problem name as a string. It generates a markdown format of the problem description, automatically opens the problem in a browser tab, and creates a comment for the problem.

- `printArr()`: Prints and copies the array of comments to the clipboard. After execution, it automatically deletes the cell that contained the command, keeping your notebook tidy!

- `removeLastelement()`: Removes the last element from the comments array and then deletes the current cell.

- `removeByUsingIndex(x)`: Removes a comment from the list using its index and deletes the current cell.

- `makeNullArr()`: Clears the list of comments.

- `magic_markdown_create(link)`: Fetches and transforms the problem content from LeetCode into a markdown format.

### 🎩 IPython Magic:

- **Cell Deletion**: After executing methods like `.printArr()`, the cell that contained the method call is automatically deleted, ensuring a clean and organized notebook. This magic is achieved using IPython's JavaScript commands.

- **Cell Conversion**: The method `to_markdown()` converts a cell into markdown format, useful for displaying the fetched LeetCode content appropriately.

- **Cell Navigation**: There are methods integrated to programmatically jump between cells or edit them, offering more fluid notebook navigation.

### 🧐 How It Works:

1. **Fetching Problem Content**: Using Selenium, the script opens a browser, navigates to the problem page on LeetCode, and fetches the problem details, including description, images, and test cases.

2. **Transforming Content**: The fetched content is transformed into markdown format, ready to be used in Jupyter notebooks or any markdown-supported platform.

3. **Managing Comments**: A list of comments is maintained, which can be added to, printed, or cleared.

4. **Browser and Cell Automation**: The script employs various browser manipulations like opening links and minimizing windows, combined with IPython commands to manipulate notebook cells, creating a streamlined user experience.

### 💼 Use Case:

Ideal for those who solve LeetCode problems and document their solutions in Jupyter notebooks. With this script, users can seamlessly get problem descriptions, manage comments, and more, all within their notebook environment.

### 🔐 Note:

Ensure that the required libraries, such as `pyperclip`, `selenium`, and `tqdm`, are installed and that you have the correct path to the `chromedriver` for Selenium.


