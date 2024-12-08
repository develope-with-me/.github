<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
# Welcome to DevelopeWithMe (DWM)! 👋

![Logo](link-to-your-logo) <!-- Optional: Add your organization logo -->

## Guide
- [About Us](#about-us)
- [Our Mission](#our-mission)
- [Projects](#projects)
- [Contribution Guidelines](#contribution-guidelines)
    - [General Guide](#general-guide)
    - [Issue Code](#issue-code)
    - [Contribution Practices](#contribution-practices)
        - [Setting up](#setting-up)
        - [Committing your changes](#committing-your-changes)
        - [When you have completed a task](#when-you-have-completed-a-task)
- [Code of Conduct](#code-of-conduct)
    - [Our Pledge](#general-guide)
    - [Our Standards](#issue-code)
    - [Our Responsibilities](#contribution-practices)
    - [Scope](#scope)
    - [Enforcement](#enforment)
    - [Attribute](#attribut)
- [Community](#community)
- [License](#community)
- [Contact Us](#contact-us)

## About Us 🙋‍♀️

We are a community of developers, designers, and tech enthusiasts committed to fostering innovation and making life easy for business and product owners. 
Our goal is to create impact through tech by developing and/or enhancing tools needed by business owners to make the day-to-day running of their businesses smooth, and empowering and supporting developers.

## Our Mission

At DWM, we believe in the power of communication, collaboration and teamwork. Our mission is to:

- **Empower Developers**: We provide resources, tools, and support to help developers grow and succeed.
- **Foster Innovation**: We encourage creativity and experimentation, supporting projects that push the boundaries of technology.

## Projects 👩‍💻

Here are some of the key projects we are working on:

- **Ecomie**: The ecomie application. It has two repositories
  - ecomie-api
  - ecomie-web 


## Contribution Guidelines 🌈

### **General Guide**

We welcome contributions from everyone! Here’s how you can get involved:

1. **Fork the repository**: Create your own copy of our project.
2. **Make your changes**: Improve the project by adding new features, fixing bugs, or updating documentation.
3. **Submit a pull request**: Share your changes with us for review.

### **Issue Code**
Each issue has an ID and status  
For development purposes, we attribute a code to the issue called **Issue Code**. The code combines the project code and the issue ID separated by the letter (t/T) and hyphens (-).

Issue codes are used when creating branches and also when committing our changes. In branches, they are in small letters while in commits they are capitalized.  

For example consider the ecomie project, it has **ec** as project code. Assuming we have an issue with id **36** then in a branch about that issue the Issue Code would look like this
**ec-t-36** while in a commit message it would look like **EC-T-36**.
Check repository README to get Project Code.
   
### **Contribution Practices**

#### Setting up
1. If you have not yet cloned the repository, clone it
   ```
   git clone <url-of-repo>
   ```
2. If have cloned it already checkout the main branch and pull the latest changes.
   ```bash
   git checkout main
   git pull origin main
   ```
3. Create a new branch following the format _[project-code]-t-[issue-id]-[3-to-5-words-describing-the-task]_ eg _ec-t-36-create-all-atoms_
   ```
   git checkout -b ec-t-36-create-all-atoms
   ```
   In the above example **ec** is the project-code, **36** is the issue-id and **create-all-atoms** is the issue's brief description. 
   

#### Committing your changes
1. Add your changes to the staging area to track your changes by running the **git add** command eg to add all modified files run
   ```
   git add .
   ``` 
2. Commit your changes by running the **git commit** command. Your commit message must follow the format EC-T-[issue-number] | Actual message e.g. _git commit -m "EC-T-36 | Created all buttons"_
   ```
   git commit -m "EC-T-36 | Created all buttons"
   ```

#### When you have completed a task
1. Push your changes to remote by running the git push command
   ```
   git push origin <branch-name>
   ```
2. Go to GitHub and make a Pull Request (PR) to main. 
3. Request review

## Code of Conduct

### Our Pledge

We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender
identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to a positive environment include:

- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

Examples of unacceptable behavior by participants include:

- The use of sexualized language or imagery and unwelcome sexual attention or advances
- Trolling, insulting, or derogatory comments
- Personal attacks
- Public or private harassment
- Publishing others' private information, such as a physical or electronic address, without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting

### Our Responsibilities

Project maintainers are responsible for clarifying the standards of acceptable behavior and are expected to take appropriate and fair corrective action in response to any instances of unacceptable behavior.

### Scope

This Code of Conduct applies both within project spaces and in public spaces when an individual is representing the project or its community. Examples of representing a project or community include
using an official project email address, posting via an official social media account, or acting as an appointed representative at an online or offline event.

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team at [domoubrice@gmail.com]. All complaints will be reviewed and investigated
and will result in a response that is deemed necessary and appropriate to the circumstances. 

### Attribution

This Code of Conduct is adapted from the [Contributor Covenant](https://www.contributor-covenant.org), version 1.4, available at https://www.contributor-covenant.org/version/1/4/.

For answers to common questions about this code of conduct, see the [FAQ](https://www.contributor-covenant.org/faq).

## Community 🍿

Join our community discussions:

- **Slack**: [Join our Slack](link-to-your-slack)
- **Discord**: [Join our Discord](link-to-your-discord)
- **Twitter**: [Follow us on Twitter](link-to-your-twitter)

## License

This project is licensed under the [License Name](link-to-license).

## Contact Us 🧙

For inquiries, please reach out to us at domoubrice@gmail.com.

---

Thank you for visiting DevelopeWithMe! We look forward to collaborating with you.



