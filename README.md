# Overview
A repository dedicated to study about developing stages to deliver a product of software. In general, it is practicing Software Engineering <br>

# Stages of developing a product of software
1. Think of an idea, deliverables, finish the diagrams for the system (Non-technical aspect)
2. Set up Version Control (e.g. Git, Github)
3. Determine the tech stack, utilize build tools
4. Continuous Integration / Continuous Development
5. Deploy
<br><br>
## Version Control
Version Control is a crucial component in software engineering. It is a system helps capture the details of input and changes made to the product, which will then be delivered. <br>

The two most common tools of Version Control is Git and Github. While Git is more on local version control, Github is a centralized website to commit our code into online repositories.<br>

This section would also include some Git and Github setups and commands that are useful for future implementation.<br>

### Setup
### Install Git<br>

Regardless of using Github or not, you would need to install Git into your local system first. <br>

You can either download it through web by Git website, or type the corresponding command using CLI:
- Linux: `sudo apt-get install git-core`
- Windows: (To be confirmed)

After installing, check if git is properly installed using the command:
- Linux: `git --version`
- Windows: `git --version`
<br>

### SSH Setup

SSH (Secure Shell) protocol ensures a secure connection between two machines.<br>

In terms of using SSH in Github, we set up a safe connection between our machine and Github.com server to retrieve/upload data without the need of providing username and password every time. Key notes about setting up is as below:
- Set a private SSH and add to SSH Agent
- Add public SSH key to account on Github before using the key to authenticate and commit
<br>
The guide for two tasks are below:
- Set up private key: (to be confirmed)
- Public key: (to be confirmed)

## Tech Stack and Building Tools
Determining a tech stack refers to the process of cherry picking technology that is going to be used to develop the full project delivered. For a fully integrated project, almost all the time the project will consists of these components, as well as the common layer of tech used:
- Front-end: Usually GUI (Tkinter: Python, Qt: C++, etc., HTML/CSS/GUI frameworks: Web) or CLI tools. In charge of interfacing and collect data from users/outer sources <br><br>
  |Language|Framework       |
  |--------|----------------|
  |Python  | Tkinter        |
  |C++     | Qt             |
  |CSS     | Bootstrap, etc.|
- Logic: Depends on which logic we want to resolve. A large portion of code in the market is Website. However, there is a strong growth in ML/AI logic in general. Embedded systems/Cybersecurity tools claim a smaller proportion in the market right now.
- Back-end: Focus on managing the database, serve queries and return data to front-end/use of logic<br>
  List of frequently used database frameworks: SQL variants (MySQL, PostgreSQL, SQLite, etc.) <br>
- External tools: Connection Protocols (HTTPS, SSH, IoT Protocols, etc.)/ System Security (Firewalls, IDS, IPS)

















