# Discord Server Assets

 This folder contains all the material needed to upkeep and mantain BTE Italy Discord server. All material is openly available for any other team to use

---

I'll add a guide to use this here, as well as a table of contents

# How to Deploy WebHooks

### Windows
Idk I don't use Windows

### MacOs
Same as windows I guess

### Linux

After configuring the DiscordHook to post in the desired channel, open a terminal window and execute the following command

```bash
curl -X POST <webhook_url>?with_components=true -H "Content-Type: application\json" -d @<yourfile.json>```

