# My Portfolio Thingy - agraj's little spot on the web

Hey there! 👋

So this is it, my personal portfolio. Or just a place where I dump my thoughts and try out cool web stuff ya know. Tryna improve the previous one so its less... basic. I wanted something that felt a bit unique not just another template. It's got this whole spacey, kinda moody vibe going on which i dig.

## What's Inside? (The Cool Bits)

*   **Hyperspeed Background:** Seriously this is probably my favorite part. Its like you're zooming through stars and its interactive! Move your mouse around, the stars will kinda follow or speed up near it. I even threw in some ace flag colors in there, subtle like.
*   **Home Page (The Intro/About Me part):** This is where you land. Got my name doing a little dance (well typing itself out in different styles), a short blurb that also types itself and changes, and a quote that... well it also changes. And my face, cant forget that. This section is kinda the core "about me" vibe, not a separate page. **The questionnaire is tied into this bit too, which is a highlight for me!** You answer questions to see how aligned our thoughts are, which is pretty neat. Plus, a sneak peek at my latest writings.
*   **The "How Similar Are We?" Questionnaire:** Okay this is a big one. Its on the main "About Me" part (which is kinda just the home page intro section). You answer a bunch of random questions and it calculates a "personality match" percentage. I think my answers are in there somewhere too. Depending on the match, maybe even a way to get in touch pops up 👀. Its loaded dynamically from a json file, so its easy to change the questions.
*   **Writings Section:** If I actually manage to write things they'll show up here. You get a preview, and then you can click to read the whole article. The articles themselves are styled to be easy on the eyes i hope. This all comes from another json file.
*   **Secret Game!** 🕹️ Yep, there's a tiny physics game hidden somewhere. Click around the footer maybe youll find it. Its just a bit of fun with Matter.js. It even has little sounds when things spawn or you win!
*   **Responsive-ish Design:** I tried my best to make it look good on phones and big screens. Lemme know if something looks totally busted.
*   **Smooth Animations & Effects:** Little fades, hover effects, a "glitchy" button style, and a progress bar at the top that shows how far youve scrolled. Just trying to keep things interesting. Theres also a small easter egg click on the frieren ring image thing on the home page.

## Tech I Wrestled With 🤼

*   **HTML:** The bones obviously.
*   **CSS (Tailwind CSS):** Made styling way faster. I love Tailwind mostly.
*   **JavaScript:** The brains behind all the dynamic bits.
    *   `Anime.js`: For some of the smoother animations and transitions.
    *   `Matter.js`: Powers that secret physics game.
    *   Plain JS for the SPA routing, data loading, typewriter effects, and the questionnaire logic.
*   **Google Fonts:** Because default fonts are boring.
*   A `posts.json` file: This is where my articles actually live.
*   A `questions.json` file: This holds all the questions and answers for the personality match bit.
*   Some `.mp3` files: For those little game sound effects!

## How it Works (Kinda)

It's a single-page application sort of. The "pages" (Home/About, Writings) are just sections that get shown or hidden based on the URL hash (`#home`, `#about`, `#writings`, or `#post-ID`). When you click a link or use the hash, JavaScript figures out what content to display.

For the writings and the questionnaire, it fetches data from the `posts.json` and `questions.json` files respectively. Each object in that JSON is structured for the content it needs to display or the question/answer logic.

## Why I Built This

Honestly? I wanted a portfolio that wasnt boring. And I like messing with JavaScript. It was a good excuse to play with animations dynamic content loading and just building something from scratch that felt a bit more /me/. Plus gives me a place to link people to when they ask "so what do you do?" besides shrugging. And I really wanted to make that questionnaire thing work, it feels kinda unique for a portfolio.

---

That's pretty much it. Feel free to poke around the code. It might be a bit messy in places im always learning. Cheers!

- agraj
