# NodeJS First Steps

I watched @glitch's YouTube vid "Website Starter Kit. Part 4: Intro to Node" & I've become obsessed w/ making multi-player web apps. My web design students have been beta testing them w/ my Seniors even trying to hack them!
https://m.youtube.com/watch?v=c5Xd8xPBuOA

## Trivia
My 1st Node app was a trivia game based on @Glitch's Website Starter Kit. glitch.com/edit/#!/intro-… My thinking was just... how can I handle question/answer storage server-side? I was excited when I realized the server was storing game progress & it was already co-op multiplayer.

The trivia game has gone through three iterations. v1: triviagame.glitch.me
v2: trivia2.glitch.me
v3: trivia3.glitch.me
Here is video of version 3. I learned @SocketIO by remixing @_gw & @jennschiffer's glitch.com/edit/#!/socket… project.

## Platformer
My high school game design students made @p5xjs platformer games after watching some @shiffman #codingtrain videos. Here's one student project (hosted by @glitch) cats2thepizzawars.glitch.me After I learned @SocketIO I decided to try coding a multiplayer #p5js platformer next...

Still a work in progress but I'm happy w/ socks.glitch.me In the course of making that I learned about how linear interpolation is used to smooth out movement between server updates. At some point I can re-implement my coin class & enemy class, now that I know NodeJS

## Paint
Finally, I wanna share p5share.glitch.me which is a shared @p5xjs canvas based on this starter #p5js sketch p5js.org/get-started/#s… In this I used AJAX polling rather than Socket.IO but I'll probably switch it someday. Still a few bugs but fun, interactive art.