# Features
1. Automatically close tickets if the ticket is left empty 1 hour after creation.
2. Automatically close tickets if the ticket creator leaves the Discord.
3. HTML transcripts will be sent to your logs channel and to the ticket owner in pms.
4. A reaction panel is used to open tickets.
5. Custom bot prefix.
6. Add and remove people from tickets.

# Setup:
1. Invite the bot to your server https://discord.com/api/oauth2/authorize?client_id=809975422640717845&permissions=126032&scope=bot.
3. Create a new `tickets` channel category.
4. Remove `@everyone`'s viewing permissions from `tickets`.
5. Give your support team permission to the category.
6. Set the category with `-setcategory`.
7. (Optional) Use the `-panel` command wherever you want the panel to be.
8. (Optional) Create a transcript channel with `-setlog`.

# Support
If you run into any issues or bugs, you can ask for help in the Birdflop Hosting Discord: https://discord.gg/ZrRvTMu.

# TODO
1. Setticketowner command
2. Close tickets with lock reaction
3. Close inactive tickets