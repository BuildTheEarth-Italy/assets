# Discord Server Assets

 This folder contains all the material needed to upkeep and mantain BTE Italy Discord server. All material is openly available for any other team to use

---

I'll add a guide to use this here, as well as a table of contents

# How to Deploy WebHooks

### Windows

To post a new WebHook Message, you will need to use the `curl` command. Modern Windows CMD offers curl by default, so first of all let's check if this is your case.

Run:
```bash
curl --verion
```
If the CMD returns your curl version you are in the good

```bash
curl -X POST ^
-H "Content-Type: application/json" ^
-d @your_file.json ^
<webhook_url>?with_components=true
```

### MacOs
Same as Linux I guess

### Linux

After configuring the DiscordHook to post in the desired channel, open a terminal window and execute the following command

```bash
curl -X POST <webhook_url>?with_components=true -H "Content-Type: application/json" -d @your_file.json
```

