![This is an imagine](https://github.com/LeiamNashRebirth/Izumi/blob/main/LeiamNash/New%20Project%20%5B834E1C4%5D.png)
[Izumi Kun ver. 1.0.1](https://www.facebook.com/LeiamNashRebrth) <br> <br>
<a href="https://www.npmjs.com/package/fca-unofficial"><img alt="npm version" src="https://img.shields.io/npm/v/fca-unofficial.svg?style=flat-square"></a>
<img alt="version" src="https://img.shields.io/github/package-json/v/fca-unofficial/fca-unofficial?label=github&style=flat-square">
<a href="https://www.npmjs.com/package/fca-unofficial"><img src="https://img.shields.io/npm/dm/fca-unofficial.svg?style=flat-square" alt="npm downloads"></a>
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
<Br> `Created by Leiam Nash`
<br> <br> This API is the only way to automate chat functionalities on a user account
 this API won't work with an auth token but requires the credentials of a Facebook account.

<br> Disclaimer <br> <br> I am not responsible if your account gets banned for spammy activities such as sending lots of messages to people you don't know, sending messages very quickly, sending spammy looking URLs, logging in and out very quickly. Be responsible Facebook citizens

<br> Warning <br> <br> This bot is not program for low knowledge about networking, peronal messenger bot is not existing on messenger
witch mean this program is highly illegal so you need knowledge about scripting feature to understand how it is works

<br> Description
- [ ] [Akiara](https://github.com/LeiamNashRebirth/Akiara) 
> Bot Akiara is my first project about networking however this bot doesn't support encrypted C3C, also the file is running on `appstate.json` witch mean this script feature
is not advance vs what you think but the commanding file is have a fastest [Server](https://github.com/LeiamNashRebirth/Server)
that support `MP3` `MP4` `PNG` and `MANY` `MORE` advance commanding <br> [Instruction for installation]
- [ ] [Akihiko](https://github.com/LeiamNashRebirth/Akihiko)
> Bot Akihiko is have an advantage on system, this program is the version 5 of my [Server](https://github.com/LeiamNashRebirth/Server) but the file C3C remain unsupported for encrypted version
akihiko, the system updated to version 3 have an security program with protected by avoiding spam on group chats also the server ping is now improve on this program there's no 
time delay even this bots join multiple group chats on messenger [Instructions for installation]
- [ ] [Kyoko](https://github.com/LeiamNashRebirth/Kyoko)
> Bot Kyoko have a hundreds commanding feature without eating your own memory storage
this bot have an new feature for cloud storage support multiple languages on one commanding area, this built in program have an delay ui on messenger witch mean 
there's animetion on it every bot chat however this bot have na strongest ip hunter cost by package program on it also for
C3C this bot have an originally `fbstate.json` on C3C however encrypted C3C still unsupported on this program [Instructions for installation]
- [ ] [Kimiko](https://github.com/LeiamNashRebirth/Kimiko)
> Bot kimiko is my latest bot program and a lite version of kyoko, this program have an less commanding feature and support C3C encrypted to have high security however this bot
still on testing some of bugs are not fix also the security of this bot is not higher than other bots, this bots don't have protecting feature witch mean 
this bot support all group and all accounts on facebook [Instructions for installation]

<Br> Bots Program
- [ ] [Akiara](https://github.com/LeiamNashRebirth/Akiara)
- [ ] [Akihiko](https://github.com/LeiamNashRebirth/Akihiko)
- [ ] [Kyoko](https://github.com/LeiamNashRebirth/Kyoko)
- [ ] [Kimiko](https://github.com/LeiamNashRebirth/Kimiko)

<Br>
<Br> About Me

- [ ] [Why im creating BOT](https://github.com/LeiamNashRebirth/BOT_Messenger/blob/main/leiam.md)
- [ ] [When did I start](https://github.com/LeiamNashRebirth/BOT_Messenger/blob/main/when%20did%20i%20start.md)
- [ ] [Who am i](https://github.com/LeiamNashRebirth/BOT_Messenger/blob/main/who%20am%20i.md)

<Br> Modules
- [ ] [C3C](https://github.com/LeiamNashRebirth/C3C)
- [ ] [Server](https://github.com/LeiamNashRebirth/Server)
- [ ] [DataBase](https://github.com/LeiamNashRebirth/DataBase)
- [ ] [API](https://github.com/LeiamNashRebirth/API)
- [ ] [Language](https://github.com/LeiamNashRebirth/Language)
- [ ] [BootLoader](https://github.com/LeiamNashRebirth/BootLoader)
- [ ] [BotStart](https://github.com/LeiamNashRebirth/BotStart)
- [ ] [Plugins](https://github.com/LeiamNashRebirth/Plugins)
- [ ] [HeroLevel](https://github.com/LeiamNashRebirth/HeroLevel)


<Br> Question and Answer 
- [ ] What is the purpose of this BOT?
> You can access YouTube Spotify Anime and Google without a load by commanding on this BOT on messenger
- [ ] This is a public?
> No this BOT is a private to avoid spamming groups BOT
- [ ] This is safe?
> No, normally personal BOT account on facebook is still illegal that's why you need a high knowledge about network program before to use this on your account
- [ ] How it is works?
> JavaScript giving you a powerful scripting feature on internet, BOT is running under JavaScript program
- [ ] Why doesn't `sendMessage` always work when I'm logged in as a page?
> Pages can't start conversations with users directly; this is to prevent pages from spamming users.

- [ ] What do I do when `login` doesn't work?
> First check that you can login to Facebook using the website. If login approvals are enabled, you might be logging in incorrectly. For how to handle login approvals, read our docs on [`login`](DOCS.md#login).

- [ ] How can I avoid logging in every time?  Can I log into a previous session?
> We support caching everything relevant for you to bypass login. `api.getAppState()` returns an object that you can save and pass into login as `{appState: mySavedAppState}` instead of the credentials object.  If this fails, your session has expired.

- [ ]  Do you support sending messages as a page?
> Yes, set the pageID option on login (this doesn't work if you set it using api.setOptions, it affects the login process).
> ```js
> login(credentials, {pageID: "000000000000000"}, (err, api) => { … }
> ```

- [ ] I'm getting some crazy weird syntax error like `SyntaxError: Unexpected token [`!!!
> Please try to update your version of node.js before submitting an issue of this nature.  We like to use new language features.

- [ ] I don't want all of these logging messages!
> You can use `api.setOptions` to silence the logging. You get the `api` object from `login` (see example above). Do
> ```js
> api.setOptions({
>     logLevel: "silent"
> });
> ```

<a name="projects-using-this-api"></a>



<Br>

Developer: Leiam Nash <br> Program code by: Leiam Nash <br> Language: JavaScript & Node JS

<br> <br> Leiam Nash and Izumi Kun is the same person also my original name is  `Leiam Nash` i change my Facebook name to `Izumi Kun` cause that name means <br> `Spring or Fountain` cause i started doing this on <br> `spring season`

<br> <br>
- [ ] Leiam Nash
