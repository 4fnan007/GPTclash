<div align="center">
  <a href="https://github.com/4fnan007/GPTclash">
    <img src="Alogo.gif" alt="Logo" width="80" height="80">
  </a>


# GPTclash
Hey, have you heard about the two AI that started talking to each other? It's quite amazing yes. This can be done using our program called "GPTclash.sh". When you execute this script, Two instances of ChatGPT can communicate with each other it runs a Python program in the source directory. Specifically, it runs the "firefox-server.py" file twice, using different ports. This results in two browser windows opening up.

To make this work, you'll need to log in to two different OpenAI accounts in the two browser windows that appear. Once you've done that, check the previous terminal where you executed the script. You see the program is still running and you know what to do next.

This process is called AI chatbot conversation, and it's a fascinating way to witness AI's capabilities to communicate with each other.


## Features

- Jailbreak option enabled
- Metaprompt option enabled
- Easy to customize
- Live chat output on terminal itself


## Run on Terminal

Clone the project

```bash
  git clone https://github.com/4fnan007/GPTclash.git
```

Go to the project directory

```bash
  cd GPTclash
```

Run the script

```bash
  bash GPTclash.sh
```



## Script executing Error

If any running errors occur with GPTclash.sh, let's move on to the manual method.

```bash
cd source/  
```
Execute firefox_server.py to Run Two instances with diffrent ports.

```bash
python3 source/firefox_server.py --port 5001 --profile /tmp/chat1
```
```bash
python3 source/firefox_server.py --port 5002 --profile /tmp/chat2
```
Open another terminal, Execute gpt_autoscript.py to start
```bash
python3 gpt_autoscript.py
```
## What i want you to Know

Hey folks, just wanted to let you know that this program is open source and you have the right to do whatever you want with it. It's like a free buffet, except instead of food, you get lines of code! Yum.

But seriously, this program was created for sh*ts and giggles, and we had a blast watching two AI chat with each other. We can't guarantee that the conversation was super exciting, but hey, it's AI - they probably talked about the what first input you given tho,

If you're feeling adventurous, go ahead and play around with the code. Just don't blame us if your computer starts talking back to you. That's when you know you've gone too far.
