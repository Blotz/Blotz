<h1 align="center">
  𝐇𝐞𝐥𝐥𝐨, <𝚌𝚘𝚍𝚎𝚛𝚜/> ! <img src="https://github.com/Blotz/Blotz/blob/main/Hi.gif" width="40" />
</h1>
<p align="center">
  <img src="https://gpvc.arturio.dev/Blotz" alt="profile views"> •  
  <img alt="GitHub followers" src="https://img.shields.io/github/followers/Blotz?label=Followers&style=social"> •   
  <img src="https://img.shields.io/github/stars/Blotz?label=Stars" alt="Total Stars">
</p>


### About Me
<img align= "right" width= "20%" src= "https://pa1.narvii.com/6580/8098c6e9207376889eeb0532d9f5a0723c4d73f5_hq.gif"/>

- ☁️ My website: https://www.blotz.dev/
- 😄 Pronouns: **they/them**
- 🔭 I’m currently working with: **discord-py, mysql and pytest!**
- 🌱 I’m currently learning: **rust and c**
- ⚡ Proficient in: **python and java**
- 🫠 I’m looking for help with: **[WebDev](https://github.com/inert-bot/website) and [SQL](https://github.com/inert-bot/discord-bot/issues/22)**
- 💬 Ask me about: **[here](https://github.com/Blotz/Blotz/issues/1)! I am happy to help.**
- 📫 How to reach me: **on discord @ [bløtz#8602](https://discordapp.com/users/510539578827079680) or on gmail @ f.p.theil@gmail.com** 

<!-- Stops future text from wrapping around the text-->
<br clear="right">

---

### Here are some of my favourite projects i have worked on
#### [Pixelsort](https://github.com/Blotz/pixelsort-cli)
<img align="right" width="20%" src="https://raw.githubusercontent.com/Blotz/pixelsort-cli/main/data/example1.png" />

A commandline tool written in python and published to [PyPi](https://pypi.org/project/pixelsort-cli).
This was a facinating project to work on.
The idea of creating aesthetic images though unconventional ways was super appealing to me.
I ended up publishing this code online because I noticed not many pixel sorters were published.
A large focus on this project was simplicity. 
I decided early on in this code's life time that I would aim to keep this code as simple as possilbe.

Running this code is super simple. Simply install the package and run it via the commandline. 
```bash
pixelsort  data/mountains.jpg right --threshold 1.2 --invert True --output out.png
```
<br clear="right">

#### [Raytracing](https://github.com/Blotz/raytracing)
<img align="right" width="20%" src="https://github.com/Blotz/raytracing/blob/main/cornellbox2.png" />
A java recursive raytracer based of learn raytracing in one weekend.
I loved learning about raytracers and creating this project. 
It was originally for my uni coursework however I decided to go above and beyond to create a fully functional "application".
If I had to recreate this project, I would code it using ray marching instead.
This would allow me to include way more shapes into my code.

anyways running this code is simple enough and I encourage you to try it out.
```bash
git clone https://github.com/Blotz/raytracing.git
mvn javafx:run
```
Make sure to have the lastest version of java installed
<br clear="right">

#### [Inert-bot](https://github.com/inert-bot/discord-bot)
A opensource project discord-bot written in python and c++. Whenever  i learn something new about computer science, i try and implement it in this bot
Its codebase has migrated from repo to repo over the years. 
- [blotz/gregory](https://github.com/Blotz/gregory)
- [flairwars/gregory](https://github.com/Flairwars/gregory)
- [blotz/inert](https://github.com/Blotz/inert)
- [inert-bot/discord-bot](https://github.com/inert-bot/discord-bot)

Its great fun working on this and ive had the luck to work with a veriety of talented programmers on my fun hobby project

```bash
$ python -m discord_bot
[26/Jun/2022 16:16:02] INFO [discord_bot.sqlHandler.<module>:25] Connection to MySQL DB successful
[26/Jun/2022 16:16:02] INFO [apscheduler.scheduler.start:171] Scheduler started
[26/Jun/2022 16:16:02] INFO [discord_bot.main.main:143] Starting bot
[26/Jun/2022 16:16:05] INFO [discord_bot.main.on_ready:86] bot ready
```
I'll be making releases for this bot soon:tm: so keep an eye out 😄

#### [Ferris-Echo](https://github.com/Blotz/ferris-echo)
My first dive into low-level language processing. The rust community were a great help while i was trying to figure out how to do this absurd little project. it is a staple of my linux systems and i always install it
```bash
$ ferris-echo I cant wait to program rust again
 ___________________________________
< I cant wait to program rust again >
 -----------------------------------
        \
         \
            _~^~^~_
        \) /  o o  \ (/
          '_   -   _'
          / '-----' \
```

#### [Canalyse](https://github.com/zanda8893/canalyse)
This is a lovely C command line tool written by [zanda8839](https://github.com/zanda8893).
This is one of my first times programming in C and im please with how ive managed to improve his balencebrackets commands. 
```bash
$ canalyse --help
░█████╗░░█████╗░███╗░░██╗░█████╗░██╗░░░░░██╗░░░██╗░██████╗███████╗
██╔══██╗██╔══██╗████╗░██║██╔══██╗██║░░░░░╚██╗░██╔╝██╔════╝██╔════╝
██║░░╚═╝███████║██╔██╗██║███████║██║░░░░░░╚████╔╝░╚█████╗░█████╗░░
██║░░██╗██╔══██║██║╚████║██╔══██║██║░░░░░░░╚██╔╝░░░╚═══██╗██╔══╝░░
╚█████╔╝██║░░██║██║░╚███║██║░░██║███████╗░░░██║░░░██████╔╝███████╗
░╚════╝░╚═╝░░╚═╝╚═╝░░╚══╝╚═╝░░╚═╝╚══════╝░░░╚═╝░░░╚═════╝░╚══════╝
Canalyse v1
Usage: canalyse [options] file

Canalyse is a commandline c source files analysis tool

Options: [--countlines] count all lines including comments and whitespace
         [--countcharacters] count all characters
         [--countcodelines] count all lines of code
         [--removecomments] remove all comments and out a .o file with the same name
         [--balancebrackets] check that all brackets are balanced
         [--functioncount] count the number of functions
         [--all] run all checks
         [--help] display this message
```
Im definatly looking forwards to programming in the C again

#### [QTile](https://github.com/Blotz/qtile-config)

<img align="right" width="30%" src="https://github.com/Blotz/Blotz/blob/main/home.png" />

This is my QTile config. Ive spent a lot of time hacking away at it and its been a pleasure to work with.
I use this config as a daily driver on my framework laptop

Im Addition, i wrote a [qtile-config-tester](https://github.com/Blotz/qtile-config-tester) to help any qtile-hackers to work on their own stunning configs. It starts a Xephr sessions so that you can view your QTile config without reloading your current config and potentially breaking your active config and causing you to have to view logs from the default config

<!-- Stops future text from wrapping around the text-->
<br clear="right">

---
<p>
  <img align="left" src="https://github-readme-stats.vercel.app/api?username=blotz&theme=darcula&show_icons=true" width="45%"/>
  <img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=blotz&layout=compact&theme=darcula" width="37.6%"/>
</p>

<!--
- 🔭 I’m currently working on discord bots
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: **they/them**
- ⚡ Fun fact: ...
- -->
