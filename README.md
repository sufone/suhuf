# suhuf.app
Aggregate news from different feeds related to Muslims.

*Work on this app is still under planning, I am sharing ideas publicly so all can coopoerate.*

Gathering news about the Muslims, so that we can easly apply the guidance of the Prophet peace and blessings upon him: one who does not give importance to Muslims' affairs is not from them. 

Aims:
- Instill love and care for Muslims all around the world
- Make sure no one region is favored; have 3 pieces of news from each region no more (or some other number)
- Leave a warning to think critically even for news aggregated on this site
- I18n of this site is difficult for this directly… but English is good to start, Arabic if we find a source for news. Other languages are too regional I think.
- Show an image from unsplash, without people, taken in a muslim country

We can later expand the feature of this site to include small intros for each country, matching the mission of erasing ignorance about fellow Muslims

Plan
1. Find API
  2.  The NYT supports location, but linking to them is a dead end because paywall
  3.  Most other services are expensive and targeting a different kind of customer (though we could use their free plans, and just cache what they respond with once a day… but that needs a backend! Or maybe a microservice writing to a NoSQL database… but that's beyond me right now)
  4.  **Just fetch RSS**: https://css-tricks.com/how-to-fetch-and-parse-rss-feeds-in-javascript/. Can easily filter by location as well! For an MVP, this is the way
3. MVP for personal use
  3. Make list of Muslim countries, or countries with significant amount of Muslims, to filter with
  1. Just get the API working: Filtering for yesterday/today, muslim places (by country name, or tag), by section (to exclude movies/tv and other undesirable things)
  3. Try SvelteKit
4. Design like a newspaper, a brown background and headlines
5. Share
