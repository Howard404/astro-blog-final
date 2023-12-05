---
layout: ../../layouts/MarkdownPostLayout.astro
title: Next JS
author: Grant Howard
description: "This article covers Next JS and its uses!"
image:
  url: "https://images.ctfassets.net/c63hsprlvlya/IacLLeOBR5WCvdCPqKuff/6860b5cc464c4f54703a2befa3f706b4/nextjs3.webp"
  alt: "Next JS logo"
pubDate: 2023-12-05
tags: ["astro", "learning in public", "setbacks", "community"]
---

Next JS has a lot of simiilarities when it comes with react. Let's go over what is Next JS and what can we do with Next?

# What is Next JS

Next JS is very similar to React JS, in fact they are actually the same library but with a twist. React JS as we know is a JS library for creating declarative clinet side UI components while managing state. The keyword being client side. See, Next JS is best known for flipping this paradigm in what is called server side rendering. As the name suggests, the pages HTML, CSS, and JS are all rendered on the server having clients recieving the fully loaded page when they HTTP reqest to the server.

# Why Next JS?

Why do this? Well it has a multiple benefits, but for now we will focus on one. Imagine you are creating a stock market app, when the markets are open lots of data changes are happening every second. Rendering can be done on the client side, but we risk slow performance and latency causing poor user experience. This is where Next JS can come in, rendering changing in stocks and displaying the items to the user in optimal speeds.
