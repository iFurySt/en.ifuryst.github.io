---
layout: post
title: "MCP and Its Role in the AI Era—Like HTTP for the Web"
date: 2025-05-08T13:30:00+08:00
tags: products
categories: products
giscus_comments: true
tabs: true
pretty_table: true
---

Over the past month, the industry has been buzzing:

- Two weeks ago, both OpenAI and Amazon announced their adoption of the MCP standard.
- Last month, Google’s CEO also mentioned on X that they are considering adopting the MCP standard.

Could MCP become the HTTP of the AI era?

I think it’s still too early to draw that conclusion. Much of the hype seems to come from social media and industry insiders. However, we can’t ignore the growing trend of MCP adoption. Thanks to media coverage over the past two months, MCP has entered the radar of both technical and non-technical communities.

In light of this trend, I’ve started my own exploration—something I’ve always been doing. I’ve noticed that many people have already begun building businesses around MCP application ecosystems. Some MCP Clients, such as Cline, are developing their own App Store-like platforms to make it easier to search for and install MCP Servers. At this stage, most attention is still on MCP Clients. For example, the stdio standard initiated by Anthropic and the use of SSE both lean heavily toward the client side.

This makes perfect sense. End-user applications represent a huge opportunity. With the rise of agentic AI, where AIs act as your proxy on the terminal, it’s natural to integrate them directly with your existing environments. This trend is logical and expected.

But in areas still underexplored—like remote/cloud/server-side use cases—we will likely see an explosion of applications as well. It’s easy to imagine that the client-heavy approach won’t fit enterprises or more professional users. MCP is not just for terminals. It will be widely used on the server side, in internal enterprise environments, and for external services.

I believe traditional FunctionCalling will gradually shift to MCP. Moreover, many existing APIs will need to be adapted to MCP, which will inevitably lead to the emergence of tools and services to support this transition.

That’s why I created MCP Gateway—an open-source project I launched in the middle of last month, with the following goals and vision:

1. Convert existing APIs into MCP Servers through configuration, with zero code changes.
2. Proxy MCP Servers and handle protocol transformations between stdio, SSE, and Streamable HTTP.
3. Act as a unified gateway for distribution—a bold comparison would be the “Nginx of MCP.”
4. Extend into MCP service governance. The imagination space is huge—how do you manage dozens or hundreds of MCP integrations?
5. Deliver enterprise-grade performance, stability, high availability, and scalability.

In just under a week, the project will hit its one-month mark. I’ve made 160 commits, released 13 versions, and gained over 600 🌟 on GitHub. The feedback has been incredibly encouraging, showing me the potential and future applications of this project. I’m continuing to iterate and improve it. You’re more than welcome to try it out, share feedback, or join me in building it together ❤️
