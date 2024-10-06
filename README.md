# mellow
mellow is a Discord bot created by [HAKUMI](https://github.com/hakusoda) that allows Discord server owners to sync member profiles with external services, such as Roblox.<br/>

> [!WARNING]
> As of October 2nd, the mellow Project has been **deprecated**, and updates have ceased effective **immediately**.
> 
> Following an internal plan, mellow will stay online, and be taken **offline** when it is deemed safe to do so.
> 
> Thank you for your support! 💌

# Contributing
To set-up a local development environment, you first need to set the required environment variables.<br/>
We recommend specifying these in [`.cargo/config.toml`](https://doc.rust-lang.org/cargo/reference/config.html).
* API_KEY — A random, unique string used to secure the Rest API.
* DISCORD_TOKEN — Discord bot token, learn more [here](https://discord.com/developers/docs/getting-started).
* DISCORD_APP_ID — The unique identifier of your Discord application.
* SUPABASE_API_KEY — The [service role key](https://supabase.com/docs/guides/api#api-url-and-keys) of your Supabase project.
* DISCORD_PUBLIC_KEY — The public key of your Discord application, this is currently only used for verifying interaction requests from Discord.
* ROBLOX_OPEN_CLOUD_KEY — The client secret of your [Roblox OAuth 2.0 Application](https://create.roblox.com/docs/cloud/open-cloud/oauth2-overview), this is currently unused.

Further instructions to come.
