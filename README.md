# soundness deployment script 

this script automates the whole process for getting a soundness private and public key.

it does the followng :
- installs dependencies 
- installs Soundness cli 
- reloads your profile 
- automatically exports both keys

Pre-requisites :

Linux based systems, MacOS, Github codespace or gitpod will work.

## how to use

### Step 1: Clone the repository, make it executable and execute it :

```bash
git clone https://github.com/bigray0x/soundness-script.git && cd soundness-script && chmod +x deploy-pk && ./deploy-pk
```

follow the script steps by choosing "y" when it asks and inputting your password when its asks.
NB : you won't see your inputted password so type carefully. 

save both keys somewhere safe.

### Step 2: Register your public key for testnet whitelist

join [discord](https://discord.gg/soundnesslabs)

head to #soundness-cockpit 

use the /acess (your public key) here to register for testnet WL access.  
🚀🐬 **Welcome to the Soundness Cockpit!** 🐬🚀

Your command center for managing everything Soundness Labs. Here’s what you can do:
🔗 Link or unlink your X (Twitter) account
📲 Connect your Telegram account
🗂️ View your account details
🚀 And more!

Use the commands below to get started — all commands are **ephemeral** (only visible to you) for your privacy. 🔒

Available Commands:

`/access` - Share your public key to join our exclusive whitelist
`/change_key`  - Update your whitelist public key
`/x_login` — Link your X (Twitter) account  
`/x_unlink` — Unlink your X (Twitter) account  
`/info` — View your linked X account, whitelist key, and Telegram account  
`/link_telegram` — Link your Telegram username  
`/unlink_telegram` — Unlink your Telegram account  


