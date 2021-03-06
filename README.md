# Software Ideas People Would Actually Use

## Index

1. [All Software](#all-software)

Inspired by https://github.com/joereynolds/what-to-code.

These ideas, as far as I know, don't exist yet (or have done a poor job with SEO on Google). These are also ideas I desperately wish I could have tried at least once, meaning many others probably have as well. It's difficult to stay motivated coding or on a side project when you don't know if people will use it, or if your end goal is solving a solved problem. This list aims to fix that.

If you make any of these, let me know and I can credit you in contributors!
If you make them and they're open source, I can help brainstorm relevant communities or users.
Stay tuned -- this list will reach at least 100 ideas, as I have several hundred in my list (the majority of them patently riduculous and not a good use of anyone's time to read).
Feel free to use these for a hackathon, side project, or hacklodge project -- I'd love to see them get built! They include apps, webapps, and chrome extensions. Would appreciate idea credit to Divide-By-0/linking back to this repo!

## Contribution & pull requests

Want to be added to the list of people that have completed a project? Just add
the project's heading and your repo's url to
[CONTRIBUTORS.md](./CONTRIBUTORS.md) as a PR!

<a name="all-software"></a>

## All Software

- A collection of all large scale health studies for foods, ranked on a single number line of toxicity with error bars. Can scrape correlation/p values and error bars directly from papers.
   - Resulting graphic should look like: https://cdn.vox-cdn.com/uploads/chorus_asset/file/3523382/Medical_studies-05.0.png
- Remotely control your grandparents computer/phone with one link click that you can send them.
- Automatic haircut chooser -- input a picture, and based on aligning you to a celebrity with similar facial features, overlay celebrity hair on top of yours to find a new style or to show your barber.
- A creative startup name finder powered by baby names. Find meanings for baby babes, and make a site where you can input keywords your startup is about, and it will print resulting baby names with meanings with the highest keyword overlap (or min distance in the word embedding space).
   - Inpsired by https://www.joinleelo.com/blog/how-we-came-up-with-the-name-leelo
- Another startup name generator - input 2+ keywords, then try all reasonable pairwise ship names till you reach an untaken name .com/.ai/.io/other top TLD
- A lightweight create-react-app for ML apps. This starter app would compile on first clone and run React, Tornado, and SQLAlchemy (easiest to do with Parcel). Would be nice to have a 'yarn deploy' or something that does a one click deploy to GCP/AWS as well. Would be cool if starter apps were just email collectors, commonly the first stage of hype in a startup anyways.
- A program that takes your spotify playlist and converts it to another one of remixes of the same songs, to get some variety.
- A program that takes your spotify playlist and converts it to a clean version with the same songs, and removes it if it can't find any. Used to be able to listen to my playlists in the car with my parents.
- A tinder for songs -- plays the most commented 10 seconds of a song on soundcloud, and adds it to a playlist if you like it. Inspired by Soundsieve (https://github.com/wilzh40/SoundSieve) which is unfortunately dead.
- An actually good online red eye fixer.
- Search portal where you put in a dish and it says what percent of online recipes of that dish have nuts, maybe by country too. Done by scraping recipes with country of origin to determine what to avoid when allergic people eat that cuisine, and create an intuition about what allergens and dishes to avoid for a certain culture of restraunt.
- Rate your own affinity towards topics and get a ranked list of candidates that most aligned based on the wiki grid, like a buzzfeed quiz for local candidates.
  - Prefer to make this automated by building a scraping service for all candidates on ballotpedia comparing state senators etc. and scraping their beliefs from their speeches on youtube transcripts or personal links or twitter etc. Can also train on the wikipedia grid of candidate beliefs/policy votes. Perhaps this is not enough info on local leaders -- might require an embedding/LDA type approach to analyzing their public profile.
  - Existing solutions are lacking: isidewith (only for presidential race), voteredge (ugly), ballotpedia (no side by side or issues grid).
- Connect your spotify and visualize spotify data insights as plots. Existing apps show tables or list, but it's a small jump to display eyecandy plots instead, and will help with virality.
- Automatically make photos look good by aligning edge detection with rule of thirds. Perhaps as a Chrome extension that runs when you hit crop on a google photos image link?
- An extension where you could double click a citation # in a paper and it would automatically open the pdf from jstor or other 👀 sources.
- Convert chat in messenger to lowercase automatically (for speech to text or bad autocorrect).
- Keyboard shortcut for automatically fixing spelling in Google Docs+.
- Make app that embeds paperswithcode.com implementations directly to test (not generally, but a select cool few ones).
- Wiki game with subreddits and sidebars.
- Take a pic of a wine stand and recommend wines by rating to price ratio.
- A chrome extension that goes through an Instacart/Amazon Fresh cart and finds them on an ingredient website and scraps the ingredients, and flags foods with bad ingredients like hydrogenated oils (preferably, I would see all foods flagged in Deep Nutrition by Cate Shanahan, and I'm sure she would blast your app to her 13K+ twitter followers).
- Nerve (like the movie) but to avoid the horror scenarios, all submitted new dares must be moderated for safety. Alternatively mix and match a reasonable list of locations and actions.
- An automatic music video creator from mp3. Upload any collection of videos, pictures, or a topic, that you want to autoalign. The app detects drumbeats or other features, and staggers the videos to transition at those times.
- Could potentially also upload a 3d scene somehow, and randomly move around and show the field of view, but at a speed proportional to music energy and rotating only when beats hit. Perhaps to import the 3d scene, could be autogenerated from an image/set of images, or just a spot on google earth or something?
- An app that generates a trippy video from a regular video. For instance, upresolutioning every frame, or recoloring each frame (or any other transformation) independently with an imperfect generative adversarial network to have disconnected images but a connected idea.
- An actually good Chrome extension to keep you off Facebook etc. Tracks how long you spend on degenerate sites, then when you go to Facebook etc, it says "On average, you think you'll spend 16 minutes, but you end up spending 31 minutes on this tab. How many minutes do you think you'll spend this time?" And at the end of that # of minutes, it makes the page black and white so you can continue to browse but it'll be slightly uncomfortable.
  - Can also do for apps on phone.
- Make app/Chrome extension/background integration to autotag google photos images with ongoing calendar events, so I can search for the event and see the photos from that. Useful for class notes (if all your classes are on your calendar) and generally increasing searchability of photos.
- Windows automatic unzipper. When something is downlaoded, unzip it to its own folder then delete the original zip file (Macs do this already, but not Windows).
- An audio recorder where you can tap to add a flag at any time -- you can attach a note if you want, but the purpose is that later you can quickly skip to that time and know something important is there.
  - Can do this for a timer app/song player also, not just an audio recorder.
- A spoon/other device that emits sweet odors without having sugar in the food, to inspire kids to eat more of their food without being unhealthy. 
  - [This paper](http://scholar.google.com/scholar_lookup?&title=The%20handbook%20of%20multisensory%20processing&pages=69-83&publication_year=2004&author=Stevenson%2CRJ&author=Boakes%2CRA)  says "certain olfactory stimuli, such as vanilla, caramel, or strawberry aromas for those in the west, can also modulate, or perhaps even give rise to, the perception of sweetness in an otherwise tasteless solution puts pressure on the definition of taste. ([source](https://flavourjournal.biomedcentral.com/articles/10.1186/s13411-015-0040-2)) "
- Animation Generator: AI labels each frame in a video with the contents in text (representation learning), then based on given labels, generate missing labels/coherent story, then generate an animation based on all those labels. as inspired by eden bensaid, can deepfake style transfer all images to be the same style.
- Trippy Video Generator: A superresolution/style transfer model runs on each frame of a video independently, leading to a very raw flipbook-style animation
- Auto Analyze Game Footage: A drone above a sports game keeps track of all the footage and then you infer the plays the opponent is making based on similarity of movement, so you can get the strategies of an arbitrary team. Can also do with phone cameras possibly.
- AI for deep sea mining: Recently there's been a lot of new deep sea mapping data, and there's a wealth of minerals/new species to be found but I don't think anyones done the ML to do it
