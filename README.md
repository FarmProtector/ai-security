

# AI Security Scanner for Python


---

## Project Description

In this project, I'm going to build a CLI tool that will scan python files and identify security vulnerabilities using Gemini AI. This will help me learn about connecting to Gemini. I'm interested in this because I want to expand my learning of how AI is used in Cybersecurity. 

### Key tools and concepts

The key tools I used include Python, Gemini API, and Colorama library. Key concepts I learnt include prompt structuring, python code basics, and terminal commands. 

### Challenges and wins

I did this project today to learn how to use Gemini API to scan files for security flaws and learn automation.

---

## Generating the Gemini API Key

In this step, I'm setting up Google AI API key. I need to do this so I can access Gemini. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_h3ymx6kd)

---

## Setting Up the Python Environment

In this step, I'm creating a new project folder, setting up Python and creating a virtual Python environment to build in This is important for this project because to keep our project Python dependencies isolated from other projects that I am working on my computer. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_rb4kj7mz)

### Installing the required packages

Now that I have my virtual environment set up I need to install two packages. Python-dotenv for securely storing our Gemini API key and Google-GenAI for recognizing Gemini calls written in Python. This is important for my project because we don't want our API keys to be exposed. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_pw6dq3ck)

---

## Connecting to the Gemini API

In this step, I'm connecting to connect to the Gemini and write my first bit of code for my scanner.py script. This is important because I need to be able to communicate to Gemini API key. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_yw8dt2jh)

### Securing the API key with a .env file

I got an error! My error was not having an API key configured. Having an .env file is important because hardcoding API keys directly in code is dangerous. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_kn3jm8tb)

### Verifying the connection

I verified the connection by running the command python3 scanner.py. Gemini responded with and answer to my prompt in the code which confirms that my API key works. 

---

## Engineering the Security Prompt

In this step, I'm writing a security prompt that tells Gemini to. analyze code for vulnerabilities and test that it works. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_rk9mb7ys)

---

## Building the File Scanner

In this step, I'm adding file scanning so my scanner can scan other files for security flaws.

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_jt7px3na)

---

## Running the Security Audit

In this step, I'm testing my scanner by adding test code files with security flaws. I'll start with one vulnerability first because I want test it to confirm that it's working and then I will add more files to test. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_ub6ry1wf)

### Analyzing the vulnerability report

My scanner detected 4 vulnerabilities. This shows that  that AI can help with security by identifying flaws quickly or security issues someone might miss. 

---

## Adding Color-Coded Severity Ratings

In this project extension, I'm adding colorama to color code the security vulnerabilities. This lets the scanner identify what is most important so I can identify the important security flaws quickly. 

![Image](http://nextwork.ai/loving_green_agile_basil/uploads/ai-security-audit-copy_mj7rc2vy)

### How the color system works

I added color to my responses by installing the Colorama library and updating prompt + my call to the Gemini API asked it to include the colors. 

---

## Wrapping Up

This project took me approximately 40 minutes to complete. 

---

---
