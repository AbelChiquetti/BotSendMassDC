<p align="center">
  <img src="https://i.imgur.com/z8ig6eN.png">
  <img src="https://img.shields.io/github/license/V4NSH4J/discord-mass-DM-GO?style=for-the-badge&logo=appveyor">
  <img src="https://img.shields.io/github/downloads/V4NSH4J/discord-mass-DM-GO/total?style=for-the-badge&logo=appveyor">
  <img src="https://goreportcard.com/badge/github.com/V4NSH4J/discord-mass-dm-GO?style=for-the-badge&logo=appveyor">
  <img src="https://img.shields.io/github/stars/V4NSH4J/discord-mass-DM-GO?style=for-the-badge&logo=appveyor">
  <img src="https://img.shields.io/github/forks/V4NSH4J/discord-mass-DM-GO?style=for-the-badge&logo=appveyor">
  </p>

# Discord Mass DM GO
**DMDGO** is a Multi-threaded Discord Self-Bot primarily used for mass messaging users on Discord. It has numerous other quality features to enhance the user experience and allowing the user to target the most users. 

## Community 

[Telegram Server for Support](https://t.me/tosviolators)

[Discord Community Server](https://discord.gg/T9FBNBQb4d)


## **Features** :
### Token Utilities
- Avatar Changer
- Username Changer
- Hypesquad Changer
- Bio Changer
- Token Changer
- Invite joiner (Single/Multi modes)
- Guild Leaver
- Token Onliner 
- Token Format Changer
- Token Checker
- Reaction Adder
- Server Checker
### Mass Messaging
- Mass DM Advertisement 
- Single DM Spam
- DM on React
### Scraping Utilities
- Opcode 14 Scraper (Memberlist scraper)
- Opcode 8 Scraper (Bruteforce Scraper)
- Reaction Scraper
### Other Features
- Multiple Captcha APIs supported
- Supports token & email:pass:token formats
- Compatible with all major OS and Architectures
- Proxyless 
- Supports HTTP(s), SOCKS5 and SOCKS4 proxies
- Free & Open source
- Emulates Discord's requests to a very high accuracy to prevent detection
- Highly Documented
- Multi-threaded using Light-weight Goroutines supporting thousands of concurrent accounts
- Can Receieve messages during mass DM
- Can ping user
- Can send embeds using 3rd Party APIs
- Supports multiple messages
### Preview
<p align="center">
  <img src="https://i.imgur.com/rpa7CnG.png">
</p>

## Disclaimer 
 The automation of User Discord accounts also known as self-bots is a violation of Discord Terms of Service & Community guidelines and will result in your account(s) being terminated. Discretion is adviced. I will not be responsible for your actions. Read about Discord [Terms Of service](https://discord.com/terms) and [Community Guidelines](https://discord.com/guidelines)
 
Discord Mass DM GO (DMDGO) was written as a proof of concept that Discord accounts can be automated and can perform actions beyond the scope of regular Discord Users like sending Embeds so that Discord can make changes. The DMDGO authors are released of any liabilities which your usage may entail. 

## Tutorial / Showcase Video
### DMDGO v1.7.0
[![Youtube - Click to play](https://i.imgur.com/Jx4gk54.png)](https://youtu.be/9HX64DHJYWI)
Click to play

### DMDGO v1.5.0
[![Youtube - Click to play](https://img.youtube.com/vi/3m56RTbThbg/maxresdefault.jpg)](https://www.youtube.com/watch?v=3m56RTbThbg&t=174s)
Click to play

 
## Basic Usage
1) [Build from source](https://github.com/V4NSH4J/discord-mass-DM-GO#building-from-source-) or download a pre-built version for your OS & Arch from [releases](https://github.com/V4NSH4J/discord-mass-DM-GO/releases)
2) Run the program via the binary. 
3) Set your [Config](https://github.com/V4NSH4J/discord-mass-DM-GO#configuration) by modifying the `config.yml` file. 
4) If you already have memberids to DM, put them in `\input\memberids.txt` or obtain them from [Scraping]()
5) Put HTTP(s) Proxies in `\input\proxies.txt` if you enabled proxies in config. The format is IP:Port or User:pass@IP:Port if your proxies have a user-pass authentication. 
6) Enter your message(s) in `message.json` file. You can use [this](https://glitchii.github.io/embedbuilder/?editor=json) website to easily make JSON objects. However, if you do not want to/ are unable to format the file properly, you will have an option to input a simple message before mass DM-ing. Writing "\<user\>" without quotes anywhere in message content will ping the user to whom you're sending a message. Please make sure to use \n to change lines. You may pick an [example]() message.json and build from it.

## Building from source
1) Download and install [Golang](https://go.dev/) and verify your installation
2) Open a terminal window/ command prompt in the directory of the source code and type `go build`
3) A binary compatible with your OS/Arch should be made. If there are some problems on MacOS/Linux with executing the binary as a program. You can run this command `chmod +x ./discord-mass-dm-GO` or go to properties -> permissions -> Allow executing file as program. 


## How to get help? 
Read this documentation, try using `Ctrl + F` to find what you're looking for. Watch the tutorial video on YouTube. Other than that, feel free to make an [issue](https://github.com/V4NSH4J/discord-mass-DM-GO/issues) or try asking on our [Telegram Server](https://t.me/tosviolators)
