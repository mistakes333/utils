# YT-PARSER
A lightweight JavaScript function designed to parse YouTube video URLs and effortlessly extract the video ID.

## Installation 

```bash
npm install yt-parser
```
## There is no need to install with a command to run immediately.
```js
import { youtube_parser } from "https://esm.sh/gh/mistakes333/yt-parser@c1ce76d465";
```
## Usage

```js
const { youtube_parser } = require('@mistakes333/yt-parser);

const url = 'https://youtu.be/Z9GALbeNd88?si=oiav5Y3Tx1yd7Jz9'; // ex. https://music.youtube.com/watcv=Z9GALbeNd88&si=VqD4hbprat0AgsdO
const videoId = youtube_parser(url);

if (videoId) {
  console.log(`YouTube Video ID: ${videoId}`);
} else {
  console.error('Invalid YouTube URL');
}
```

## Function: `youtube_parser`

### Description
* Efficiently parses a YouTube video URL and retrieves the video ID.
### Parameters
* url (string): The YouTube video URL.
### Returns
* If a valid video ID is found, returns the video ID (string).
* If no valid video ID is found, returns false.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
