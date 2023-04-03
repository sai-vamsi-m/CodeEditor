
# Web Code Editor

This is a web application that enables code editing in HTML, CSS, and JavaScript. The left-hand side of the webpage is used for editing code while the right-hand side displays the output.
## 🛠 Tools Used
- HTML
- CSS
- JavaScript


## ❇️ Getting Started

To run the project, please follow the below steps:

- Clone the project repository to your local machine.
- Open the project folder and locate the `index.html` file.
- Open the `index.html` file in your preferred web browser. 
- Write your codes of your project in the 3 textareas.
- After writing your codes you can see the output on the right hand side of the webpage.

That's it! You can now write and test your web development codes using this web code editor.


## ⚙️ How it Works

Here's how the project works:

- The HTML code consists of two main sections: the left section for editing code and the right section for displaying the output.
- The left section has three text areas for HTML, CSS, and JavaScript code, respectively. Each text area has an ID attribute.
- The right section contains an `iframe` element with an ID attribute for displaying the output.
- The `run()` function is called every time the user types something into one of the text areas.
- Inside the `run()` function, the HTML, CSS, and JavaScript code is extracted from the respective text areas.
- The HTML and CSS code are combined into a single string and injected into the output `iframe` as an HTML document.
- The JavaScript code is evaluated using the `contentWindow.eval()` method, which allows the code to be executed in the context of the `iframe` document.
- The output of the code is displayed in the output `iframe`


## 📸 Screenshots

![Code Editior by Sai Vamsi](https://user-images.githubusercontent.com/117112672/229502505-a307ce2b-0660-4764-a150-ad277c1d427f.png)

![Code Editior by Sai Vamsi](https://user-images.githubusercontent.com/117112672/229502533-a97f2055-2c2b-465c-94cf-dbe0d4594e30.png)


## 🚀 About Me
Hi there! I am Sai Vamsi, a final year computer science undergraduate with specialization in Artificial Intelligence at Vel Tech University, Chennai. I have a strong passion for software development, and Artificial Intelligence.

I'm proficient in C, C++, Java, and Python programming languages. I also have expertise in Data Structures and Algorithms. Besides, I am a Full-stack Web Developer who is familiar with front-end development technologies like HTML, CSS, JavaScript, and React, and also back-end development with Node.js, Express.js, and MongoDB.

On my GitHub profile, you can find a collection of projects that demonstrate my programming and development skills.

Thank you for taking the time to learn about me, and feel free to check out my projects on GitHub!

