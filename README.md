# Kbot : devops practise with go

# How to use:

## Installation

To get started with KBot, clone the repository:

```bash
git clone https://github.com/AnnaKlueva/kbot.git
cd kbot
```

To install all necessary dependencies and compile the project, use:

```bash
go get
go build -ldflags "-X="github.com/AnnaKlueva/kbot/cmd.appVersion=v1.0.0
```

To test the compiled project, do the following:

```bash
./kbot version
```

as a result, you should get the app's version `v1.0.0`.

## Configuration

Enter your Telegram bot token in silent mode:

```bash
read -s TELE_TOKEN
```

Export the value of the TELE TOKEN variable to the current shell environment.

```bash
export TELE_TOKEN
```

## Running

Run KBot using the following command:

```bash
./kbot start
```

## Link to Telegram bot

[@annakliuieva_bot](https://t.me/annakliuieva_bot)

