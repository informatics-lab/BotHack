# BotHack
Instructions for the Graphical Web hack session on Twitter bots

# Pick a name
First, you'll need a name for your bot. If you get stuck, here are some suggestions:

- @SurrealFashionBot
- @SpookyStoryBot
- @Bot_js
- @OverhypedTechBot
- @FortunatelyUnfortunatelyBot
- @StrangeWeatherBot
- @SongLyricBot
- @StudentFoodBot
- @CreativeBaristaBot
- @RejectedPatentBot
- @BadDirectionsBot
- @MarsRoverBot
- @RomComBot
- @BadCodeBot
- @LocalLegendBot
- @ExtremeBoardGameBot
- @DaytimeTVBot
- @ModernArtBot
- @MedievalTravellerBot
- @PacManBot

# Create a Twitter account
Sign out of Twitter and create a new account for your bot with its name and handle. 

You'll need to provide an email address, which might be tricky if you already have a Twitter account. You can either use a different address, or use one of the workarounds listed [here](http://thesocialmediaguide.com.au/how-to-setup-multiple-twitter-accounts-with-one-email-address/).

Once you've signed up, make sure you follow @GraphicalBot! #shamelessplug

# Set up your bot
For this tutorial, we'll be using a site called [Cheap Bots Done Quick](http://cheapbotsdonequick.com/). Go to their homepage and sign in with the Twitter account you just made.

# Make it say stuff!
When you first set up your bot, you'll be given some sample code. Try changing some of the elements and scrolling to the bottom of the page to see what it says. 

For another example, here's part of the code from @GraphicalBot:

```json
{
	"language": ["Python", "JavaScript", "CSS"],
	"activity": ["hacking", "coding with"],
	"silly imperative": ["bring plenty of snacks"],
	"sane imperative": ["use source control"],
	"imperative": ["#silly imperative#", "#sane imperative#"],
	"suggestion": ["writing some documentation", "narrowing your focus"],
	"action": ["#activity# #language#"],
	"tip": ["When I'm #action#, I always #imperative#", "If you're #action#, make sure you #imperative#", "If you're #action#, try #suggestion#"],
	"origin": ["#tip#."]
}
```
Try copying it in, and see the kind of statements it comes up with. Can you change the JSON to let it say:

- When I'm coding with Python, I always practice mindfulness
- When you're messing around with JavaScript, be sure to take a deep breath

Finally, there are more examples available at [tracery](http://www.crystalcodepalace.com/traceryTut.html). Go ahead and experiment!
