# Intel

# Setup Intel:

[How to setup a mongoDB server on windows 10](https://youtu.be/ABAOvvBh99w)

```YAML
First, setup a mongoDB database

After you're in the mongoDB shell (followed the tutorials above)

Run these commands:
```
```javascript

use Bot
db.whitelist.insertOne({useless: "github.com/barleywarley"})
```

# Make sure your bot has this intent:
<img src="Intent.png">

#Self build?

You will need these dependencies:

```YAML
https://golang.org/dl/ - download this (>=1.15 (recommended: latest))
go get github.com/bwmarrin/discordgo@v0.22.0 - command line
go get go.mongodb.org/mongo-driver - command line
```

After you've installed the dependencies, you are good to run this command:

```YAML
cd (directory of the main.go file)

go build -ldflags "-s -w"

(you are also welcome to run it straight from the go file.)

go run main.go
```


# General help

```YAML
Q: What is a token?
A: A token is an authentication "ticket" that allows the bot to function.

Q: What is the fastest Anti-Nuke bot?
A: Summrs was the fastest bot but now its no more a thing so but this code is the fastest.

Q: How do I make a bot/How do I get it's token?
A: Go Here https://discord.com/developers/applications then create an application (if you don't know how use youtube.)

Q: What is this bot?
A: This is a bot that protects your server from being "nuked"/"wizzed"

Q: Why is the setup so complex?
A: Due to the database that is used, Complex setup | Easier to read code

Q: Why do I need to specify the amount of shards and what are they?
A: Simple answer, more servers your bot is in the more shards you need.

Q: What is the recommended amount of shards?
A: Unless you're using this for hundreds of guilds, It's safe to use 1.
```