# Project 0 - Reference Material and Submitting Projects[^1]

## Introduction

The projects for this class assume you can do the following:
- Use a *CLI* (command line interface) to perform system level functions
- Use a *CLI* or *IDE* to manage and update files
- Use fundamental programming knowledge from prior courses to pickup languages used in this course
- Create a user account 
- Work on a team

Project 0 will require you to:

- Download template files
- Make a simple text file update
- Create or use an existing GitHub account
- Upload files to a GitHub repository
- Submit a GitHub URL to an LMS (Learning Mangement System)
- Create or use an existing JetBrains account

## Files to Edit and Submit

You will fill in portions of ```p0.html```. Please do not change the other files in this repository or add new files to your repository. Submit GitHub URL to an LMS. The due dates for projects are listed on the syllabus. No late project will be accepted without an official excuse.

## Evaluation

Most of the requirements for each project are based on the design and functionality of your project. There are also style requirements which are awarded based on how you solve the problem. These reflect the importance of things such as proper HTML validation, clean code structure, and nice-looking interfaces. These requirements are described in each project.

## Browsers

Web browsers are still not 100% identical in their behavior, and it is possible for web pages to behave differently on different browsers. For this course, the reference browser is Chrome.  Your project solutions must work on Chrome.  You may use a different browser to develop your solutions if you wish.  Chrome, Firefox, and Safari all have very similar behavior. Please test on Chrome before submitting. We do not recommend that you use Internet Explorer for development. Historically, its behavior has been quite different from the other browsers.

## Academic Dishonesty and Getting Help

Please follow the [50 foot Policy](https://www.dna.caltech.edu/courses/cs191/50ft_policy.pdf) when collaborating on projects.  This applies at the team level for group projects.

## References

There are no required textbooks for this class. To complete programming projects, you will need additional reference material that is available on the Web.

## MERN Stack

The web applications built in the course's projects will use what is known as the MERN stack. The MERN stack uses the JavaScript language in both the browser and the server-side.

- [MERN stack](https://en.wikipedia.org/wiki/MEAN_(solution_stack)#Angular_and_alternatives)(*see MERN discription in the text of the link*)
- [MongoDB](https://www.mongodb.com)
- [mongoose](https://mongoosejs.com)
- [React](https://reactjs.org)
- [Express](https://expressjs.com)
- [Node](https://nodejs.org/en/)

## MERN Installation

If you don't already have MERN packages installed on your laptop, follow the instructions below to install them.

### Installing Node.js

Install the latest "Long Term Support (LTS)" version of Node.js (currently version 18.12.1). It can be downloaded from [this](https://nodejs.org/en/download) URL. To verify you have Node.js and its package manager (npm), try running the commands:

```node -v```

and:

```npm -v```

which should run and print out the version numbers of your node and npm programs.

### Installing MongoDB

Install the MongoDB Community Edition from [this](https://docs.mongodb.com/manual/administration/install-community/) website.

Once you start the MongoDB server using the command

```mongod``` (the exact arguments depend on where you placed the database)

you should be able to directly interact with the MongoDB database by running the command:

```mongosh```

Type help at the command prompt to see the available commands.

For Windows users, you may need to add the location of where MongoDB was installed to your environment path variable in order to run the commands. This is usually located at

```C:\Program Files\MongoDB\Server\<version_number>\bin```

## Reference Documentation for HTML, CSS, and the DOM

- [Mozilla Developer Network](https://developer.mozilla.org/en-US/)(*see the Guides menu*)
- [W3Scools](https://www.w3schools.com)(*see tutorials and references menu*)
- [Dynamic HTML: The Definitive Reference](https://www.oreilly.com/library/view/dynamic-html-the/0596527403/)

## Reference Documentation for JavaScript
- [Mozilla Developer Network](https://developer.mozilla.org/en-US/)(*see the Guides menu*)
- [W3Scools](https://www.w3schools.com)(*see tutorials and references menu*)
- [Eloquent JavaScript](https://eloquentjavascript.net)
- [ECMA Script](https://tc39.es/ecma262/)
- [JavaScript](https://www.oreilly.com/library/view/javascript-the-definitive/9781491952016/)
- [JavaScript: The Good Parts](https://www.oreilly.com/library/view/javascript-the-good/9780596517748/)
- [Learning JavaScript Design Patterns](https://www.oreilly.com/library/view/learning-javascript-design/9781098139865/)

## IDE (Interactive Development Environment)(*optional*)

[WebStorm](https://www.jetbrains.com/webstorm/) and [DataGrip](https://www.jetbrains.com/datagrip/) are recommended for this course.  You will need to signup for a JetBrains account to use these products.  Request free product downloads with your university email.
    
## Q1: Your Name

- Download the files for [p0](https://github.com/btdobbs/WA/tree/main/Project/00/p0)
- Update the word *My* in p0.html to the possessive form of your name.  There are two changes to make.
  - **Example:** If my name is Bob, I would change *My test page* to *Bob's test page* 

## Submission Guidelines

### Cleaning up before submitting

Please don't add any unnecessary files to your project repository. The web tools used with projects can generate hundreds of megabytes worth of files in your project directory that are not needed. The contents of the following directories contain generated files that can safely be deleted since we can regenerate them while grading:

- node_modules - Contains the modules fetched by npm based the specification in ```package.json``` file.
- compiled - Contains the bundled JavaScript product by the React.js tool chain.

### GitHub URL

Please create a repository for each project.  Provide the github link to your project repository and not a folder in the repository.

[^1]: [Stanford Computer Science](https://cs.stanford.edu)
