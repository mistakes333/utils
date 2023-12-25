# YT-PARSER
A lightweight JavaScript function designed to parse YouTube video URLs and effortlessly extract the video ID.

## Installation

```bash
npm install @mistakes/yt-parser
```
## Usage

```js
const { youtube_parser } = require('@mistakes/yt-parser);

const url = 'https://www.youtube.com/watch?v=aazJK_P2HCM';
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
