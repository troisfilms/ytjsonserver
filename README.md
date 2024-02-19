Fork of [Youtube JSON SERVER](https://github.com/ThatGuySam/youtube-json-server) with changes:
- add more contentData (video duration, etc) for each video in the playlist
- add statistic (viewCount, likeCount, etc) for each video in the playlist
- up caches to 24hr

---


# Youtube JSON Server


Your personal Youtube API server to get Youtube API responses without needing credentials. 

Caches for 5 minutes(set as 300 seconds) which can be updated from /now.json in the root directory. 



## Installation

Install Node & [Vercel CLI](https://vercel.com/download).

Create or get a Google API Key with permissions to access the Youtube Data API https://developers.google.com/youtube/v3/getting-started

We'll need to let Vercel know what your Google Key is which can only be done with the Vercel CLI

In your command line run `vercel secret add youtube-json-google-key "MY_GOOGLE_KEY"`

Deploy the server

[![Deploy with Vercel Now](https://vercel.com/button)](https://vercel.com/new/project?template=https://github.com/troisfilms/ytjsonserver)

