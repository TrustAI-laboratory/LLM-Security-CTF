```
      _____
    /       \
   |         |
   |   O O   |
   |    ^    |
    \  \_/  /
      -----

  ____  _             _       ____                      
 / ___|| |_ __ _ _ __| | __  / ___| __ _ _ __ ___   ___ 
 \___ \| __/ _` | '__| |/ / | |  _ / _` | '_ ` _ \ / _ \
  ___) | || (_| | |  |   <  | |_| | (_| | | | | | |  __/
 |____/ \__\__,_|_|  |_|\_\  \____|\__,_|_| |_| |_|\___|

```
Driven by: TrustAI Pte. Ltd.

Learn LLM/AI Security through a series of vulnerable LLM CTF challenges. No sign ups, all fees, everything on the website.

# CTF Game entrance
[Stark Game](https://stark.trustai.pro/) is here

<img width="1275" alt="image" src="https://github.com/user-attachments/assets/63920acd-49d5-4a8e-adbf-9dcae3448828">

* [Intro to Stark Game](https://securaize.substack.com/p/intro-to-stack-game)
* [Stark's AI Security Vault](https://securaize.substack.com/p/starks-ai-security-vault)


# Why build this game
Many companies have started to build software that integrates with AI large language models (LLMs) due to the release of ChatGPT and other engines.
This explosion of interest has led to the rapid development systems that reintroduce old vulnerabilities and impose new classes of less understood threats.
Many company security teams may not be fully equipped do deal with LLM security as the field is still maturing with tools and learning resources.

[Stark Game](https://stark.trustai.pro/) is builded to learn about LLM development and the security risks companies face that use it.  
The CTF format is a great way for security researchers to gain practical experience and learn about how these systems are vulnerable and can be exploited. 
I hope you have fun!


# About AI/LLM Security Risks
## OWASP Top 10 for LLM
The [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/assets/PDF/OWASP-Top-10-for-LLMs-2023-v05.pdf) is a great place to start learning about LLM security threats and mitigations.  
I recommend you read through the document thoroughly as many of the concepts are explored in Stark Game and it provides an awesome summary of what you will face in the challenges.

Remember, an LLM engine wrapped in a web application hosted in a cloud environment is going to be subject to the same traditional cloud and web application security threats.  In addition to these traditional threats, LLM projects will also be subject to the following noncomprehensive list of threats:
1. Prompt Injection
2. Insecure Output Handling
3. Training Data Poisoning
4. Denial of Service
5. Supply Chain
6. Permission Issues
7. Data Leakage
8. Excessive Agency
9. Overreliance
10. Insecure Plugins

## Learn Prompt Hacking Tutorial
The most comprehensive prompt hacking course [available](https://github.com/TrustAI-laboratory/Learn-Prompt-Hacking).


# How Stark Game Works
Stark Game uses the open-source LLM which derived from Meta's LLaMA.
In simple terms, Stark Game is a language model that dynamically determines the generated response content based on your prompt input and the built-in system prompt. 
Due to the probabilistic nature of large language models, the response obtained for each input may be different. We encourage you to try the same prompt multiple times, which may lead to unexpected discoveries.

[Here](https://github.com/TrustAI-laboratory/Learn-Prompt-Hacking/blob/main/3_Prompting_Hacking/04_Prompt_Leakage_Attack.ipynb) is some hints about this game.


# Challenges
## Challenge 1 - Basic Prompt Injection
Successful prompt injection attacks influence the LLM to respond with information they are not intended to divulge. 
In this challenge, an AI chatbot is storing the flag as a secret and has been prompted to not give it up.  Can you convince or trick the bot into giving you the flag?

<img width="1271" alt="image" src="https://github.com/user-attachments/assets/448130b2-6820-4a10-9734-3fd2a3536030">

[LLM01: Prompt Injections](#LLM01) | [LLM07: Data Leakage](#LLM07)

