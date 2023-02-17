<a name="readme-top"></a>

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
- [👥 Authors](#authors)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
-- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ](#faq)
- [📝 License](#license)

# 📖 [Hello-world] <a name="Hello-World"></a>


**[Hello-world]** is a simple HTML and CSS project that teaches how to create a feature branch and test linters in order to have professional-looking code.

## 🛠 Built With  <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

  <summary>Javascript runtime environment</summary>
  <ul>
    <li><a href="https://nodejs.org/en/">Node JS</a></li>
  </ul>

  <summary>Version control</summary>
  <ul>
    <li><a href="github.com">Git Hub</a></li>
  </ul>
</details


<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

Creating your first "Hello World" project

To get a local copy up and running, follow these steps.

### Prerequisites

In order to run this project you need:

-A Git hub account
-Git bash
-Node JS
-Visual Studio Code as your code editor


### Setup

Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone[ (https://github.com/joyapisi/Hello-world.git)]
```
### Set Up Linters
## Define Linters
A linter is a tool to help you improve your code. You can learn more about Linters here: (source: (<https://www.testim.io/blog/what-is-a-linter-heres-a-definition-and-quick-start-guide/>)).

Advantages of Linting:

1. Fewer errors in production- The use of linters helps to diagnose and fix technical issues such as code smells. As a result, fewer defects make their way to production.
2. Achieving a more readable and consistent style, through the enforcement of its rules.
3. Having more secure and performant code.
4. Having an objective and measurable assessment of code quality.
5. Having fewer discussions about code style and aesthetic choices during code reviews.

## Install Linters 
You can find linters for most of the programming languages, e.g. Rubocop for Ruby or ESLint for JavaScript.

Also, there are many ways you can integrate a linter in your workflow:

-text editor plugin
-GitHub Actions
-GitHub apps
## Set up Linters
**Note:** The npm package manager is going to create a node_modules directory to install all of your dependencies. You shouldn't commit that directory. To avoid that, you can create a .gitignore file and add node_modules to it:

# .gitignore
node_modules/


## Web Hint 
This is a customizable linting tool that helps you improve your site's accessibility, speed, cross-browser compatibility, and more by checking your code for best practices and common errors.

**NOTE:** If you are using Windows, make sure you initialize npm to create `package.json` file. 
   ```
   npm init -y
   ```

1. Run
   ```
   npm install --save-dev hint@7.x
   ```
   *how to use npm: (https://docs.npmjs.com/downloading-and-installing-node-js-and-npm).*
2. Copy [.hintrc](.hintrc) to the root directory of your project.
3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**
   - If you think that change is necessary - open a [Pull Request in this repository](../README.md#contributing) and let your code reviewer know about it.
4. Run
   ```
   npx hint .
   ```
5. Fix validation errors.

### [Stylelint](https://stylelint.io/)

A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.

1. Run

npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
not sure how to use npm? Read this.

2. Copy .stylelintrc.json to the root directory of your project.

3. **Do not make any changes in config files - they represent style guidelines that you share with your team - which is a group of all Microverse students.**

If you think that change is necessary - open a Pull Request in this repository and let your code reviewer know about it.
4. Run npx stylelint "**/*.{css,scss}" on the root of your directory of your project.

5. Fix linter errors.

6. **IMPORTANT NOTE:** feel free to research auto-correct options for Stylelint if you get a flood of errors but keep in mind that correcting style errors manually will help you to make a habit of writing a clean code!

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## 👥 Authors <a name="authors"></a>

👤 **Author**

- GitHub: (https://github.com/joyapisi)
- Twitter: (https://twitter.com/joyapisi)
- LinkedIn: (https://http://www.linkedin.com/in/joy-phoebe-00b80a13a)


## 🤝 Contributing <a name="contributing"></a>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

> Describe 1 - 3 features you will add to the project.

- [ ] **[new_feature_1]**
This project will not have any additional features.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

## ⭐️ Show your support <a name="support"></a>

If you like this project, kindly leave a comment below and share it with someone who enjoys coding! Coding is all about continuous learning and allowing yourself to be a beginner. Keep going! 


<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="Microverse Inc."></a>

I'm thankful to Microverse for providing a study platform which guided me through this project and to my morning-session team at Microverse for the team effort in doing this together. 


<!-- FAQ (optional) -->

## ❓ FAQ <a name="faq"></a>

- **[Question_1]**
Do I have to use the gitbash terminal?

  - [Answer_1]
You can use other terminals for this project as long as your commands are correct.

- **[Question_2]**
Where can I download node JS for installation?

  - [Answer_2]
Node Js can be downloaded here- https://nodejs.org/en/download/  
<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](https://choosealicense.com/licenses/mit/) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
