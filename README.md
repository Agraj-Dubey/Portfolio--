# My Portfolio Thingy - agraj's little spot on the web

Hey there! 👋

So this is it, my personal portfolio. Or just a place where I dump my thoughts and try out cool web stuff, ya know? I wanted something that felt a bit unique, not just another template. It's got this whole spacey, kinda moody vibe going on, which i dig.

## What's Inside? (The Cool Bits)

*   **Hyperspeed Background:** Seriously, this is probably my favorite part. It's like you're zooming through stars, and its interactive! Move your mouse around, the stars will kinda follow or speed up near it. I even threw in some ace flag colors in there, subtle like.
*   **Home Page:** This is where you land. Got my name doing a little dance (well, typing itself out in different styles), a short blurb that also types itself and changes, and a quote that... well it also changes. And my face, can't forget that. Plus, a sneak peek at my latest writings.
*   **Writings Section:** If I actually manage to write things, they'll show up here. You get a preview, and then you can click to read the whole article. The articles themselves are styled to be easy on the eyes, i hope.
*   **Secret Game!** 🕹️ Yep, there's a tiny physics game hidden somewhere. Click around the footer, maybe youll find it. It's just a bit of fun with Matter.js.
*   **Responsive-ish Design:** I tried my best to make it look good on phones and big screens. Lemme know if something looks totally busted.
*   **Smooth Animations & Effects:** Little fades, hover effects, a "glitchy" button style, and a progress bar at the top that shows how far youve scrolled. Just trying to keep things interesting.
*   **Dynamic Content:** My writings are loaded from a `posts.json` file, so its pretty easy for me to add new stuff without touching the main HTML too much.

## Tech I Wrestled With 🤼

*   **HTML:** The bones, obviously.
*   **CSS (Tailwind CSS):** Made styling way faster. I love Tailwind, mostly.
*   **JavaScript:** The brains behind all the dynamic bits.
    *   **Anime.js:** For some of the smoother animations.
    *   **Matter.js:** Powers that secret physics game.
*   **Google Fonts:** Because default fonts are boring.
*   **A `posts.json` file:** This is where my articles actually live. The JavaScript fetches them and builds the writing pages.

## How it Works (Kinda)

It's a single-page application, sort of. The "pages" (Home, Writings) are just sections that get shown or hidden. When you click a link or use the URL hash (#home, #writings, #post-ID), JavaScript figures out what to display.

For the writings, it fetches data from `posts.json`. Each object in that JSON is a post with a title, date, excerpt, and the full content (which can be simple markdown-ish text or actual HTML snippets, ive made it flexible for myself).

## Why I Built This

Honestly? I wanted a portfolio that wasnt boring. And I like messing with JavaScript. It was a good excuse to play with animations, dynamic content loading, and just building something from scratch that felt a bit more *me*. Plus, gives me a place to link people to when they ask "so what do you do?" besides shrugging.

---

That's pretty much it. Feel free to poke around the code. It might be a bit messy in places, im always learning.
Cheers!
- agraj
