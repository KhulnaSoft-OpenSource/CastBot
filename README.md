# How can I implement this in my chat?

Before I jump into the code, I need to share some of the streaming basics.

## OBS Studio

[OBS Studio](https://obsproject.com/) is a free and open-source software for live-streaming and screen recording. This walk-through will show OBS Studio and consult your platform's documentation or community on how to add browser source plugins.

**Browser Source plugins**
When you set up an out of the box alert or chat system, like [Streamlabs](https://streamlabs.com/), they require you to add something called a Browser Source plugin. To do this, you add the URL pointing to the plugin, provided in the Streamlabs dashboard. This is the backbone of most streaming interactions on Twitch. Browser source plugins are HTML, CSS, and some JavaScript—so basically webpages. 

If you are looking to code live on stream, you probably have these skills to make chat alerts.  

## The happy path with ComfyJS

ComfyJS is maintained by [Instafluff](https://www.twitch.tv/instafluff), which you should give a follow for comfiest live code stream on Twitch. 

Everything you need to make a bot run lives in my open-sauced/beybot repo, linked below. This chatbot template contains no JavaScript framework code in the hopes that anyone live coding stream could apply their own desired flavor to it. If you are interested, I would love to see a post where someones take this bot to the next level with Vue, React, or even Svelte.

If you would like to see this chat command working live on the air here is a clip of me interacting with the basic `!yo` command.
