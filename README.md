# suhuf.app
Under planning

After this project is released, [Nasheed](https://github.com/sufone/nasheed) is the next focus. Can use all we learn from the audio work on this project.

## Idea

Like the room in Topkapi Palace, where there is someone always reciting Quran so anyone can come for some time and listen to Quran. 

The user will not have to worry about choosing a reciter or surah, and can instantly listen anytime. 

Would like to have an MVP released by end of 2021, *God willing*.

## To-do
Very broadly:
- [ ] Design a logo
- [ ] Make wireframes of the front end
- [ ] Plan and prototype the backend 

## Technical Implementation

Based on the above, how can we implement such an app? There's a lot of research, investigation and discussion to be done before writing any code!

There are some quick ideas from me, but I've never worked with Audio on the web beyond simple media elements, so help is highly appreciated!

### Audio Stream
- This will require a small backend running on a VPS somewhere. If we architecture smartly, even a $5 plan should be enough to serve 10,000+ or more. (ie. instead of streaming the current recitation, it can serve an API which tells clients the current reciter, surah and minute to join into.) 
- Would like to avoid a YouTube based stream… because that's a website of distractions and possibly bad content. But at the same time, having a 24/7 Quran stream as a source of goodness on YouTube could also be great – and that stream (or YouTube video) could easily be embedded into the Suhuf website to offer a focused experience. Can see how freecodecamp and all those lo-fi streams do it and make an automated video stream.
- Can hook into the Quran.com v4 API to load reciter audio

### Suhuf App / Website
- The audio stream will require internet, so a PWA is no problem even without offline capability.
- Can take inspiration from focusmusic.fm
