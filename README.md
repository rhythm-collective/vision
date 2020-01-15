#Services:
- Support content restriction based on authentication of a user. If authenticated, direct to the private beta.

Can we do this more cheaply and quickly if we don’t use a traditional database? Whitelist an n-digit code that must be entered by the user on landing. Store it in a cookie to prevent multiple sign ins. We give out one of these codes to each of the beta participants.

- (?) Do we want a built in feedback mechanism or an invite to a private beta user section of this discord server?

We can provide a link to a google form for them to give feedback - this requires the least commitment from a user. A discord server would work great in addition to the form since we can give these beta users updates and we already think a lot of FFR people use discord.

- (?) Do we want registration?

Until we have a specific feature that requires registration, I would fight this. In fact I would fight us having a database at all until it’s absolutely necessary. It’s just another thing to have to maintain and pay for, and another step of setup for a user.

- (?) Do we want score retention, caching, saving?

#On storage:
How feasible is it to store replays server-side? I did some math...
How feasible is it to access/query replays? I’m not so familiar with this part
Leaderboards scale with the number of songs and the number of users, which has its own problems depending on how we allow more songs to be added

I’m going to fight us incurring costs because (1) this game we’re developing is unproven, (2) constraints encourage creativity, and (3) we don’t really know what users want, or rather, whether users are willing to pay for what they want. The fact that we’re not incurring costs actually gives us incredible freedom. We can go in whatever direction our users drive us.

#Game MVP:
- Upload your own .sm and .mp3 file
- Accuracy settings
- Synchronization settings
- Holds
- Upscroll and downscroll

TODO:
- A note skin that isn’t just some black boxes
- A more in-depth results screen - similar to FFR’s
- A UI that integrates all the html elements into the canvas
- That’s it. No replays, no rates, no health meter, no scoring.

#Web:
- A simple page with the game embedded in i for people authenticated and authorized to see the content.
- A simple page saying "coming soon" for people unauthenticated, or people authenticated without authorization.
- (?) Do we want the website to have a leaderboard or stats or anything? (Answered above)
