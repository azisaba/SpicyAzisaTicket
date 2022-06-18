<p align="center">
 I'll make a cool cover photo for you, just leave me alone for now.
</p>

<p align="center">
 🪐 Discord Bot for general management of support contact 🪐
</p>

<p align="center">
 <a href="https://github.com/azisaba/SpicyAzisaTicket/actions/workflows/codeql.yml"><img src="https://github.com/azisaba/SpicyAzisaTicket/actions/workflows/codeql.yml/badge.svg" alt="CodeQL Analysis"></a>
</p>

----



## 🛠 - Setup

### 🐋 Build

```sh 
docker build ./ -t spicy-azisa-ticket
docker run --env-file ./.env spicy-azisa-ticket
```

### 📡 Command Registration

SpicyAzisaTicket is need Application Command

Introduce the bot with `application.commands`, an invitation link with the `bot` scope added.

After that, registration is completed by sending `data/application-command.json` as an HTTP request to the following endpoint

This is endpoint use register application command(guild command): 

``` 
https://discord.com/api/v10/applications/{YOUR APP ID}/guilds/{A GUILD ID}/commands
```

(* `{YOUR APP ID}` is the same as the Bot's user ID.)

## 🔔 Features

- Ticket make and backup, close
- Send mention to server admin (so called "urging", lol)

This is schedule. Subject to change without notice.
