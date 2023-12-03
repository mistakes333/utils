# YT-PARSER

A simple JavaScript function to parse YouTube video URLs and extract the video ID.

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
### Description:
* Parses a YouTube video URL and extracts the video ID.
### Parameters:
* url (string): The YouTube video URL.
### Returns:
* If a valid video ID is found, returns the video ID (string).
* If no valid video ID is found, returns false.

## Example

```js
const { youtube_parser } = require('@mistakes/yt-parser');

const url = 'https://www.youtube.com/watch?v=aazJK_P2HCM';
const videoId = youtube_parser(url);

if (videoId) {
  console.log(`YouTube Video ID: ${videoId}`);
} else {
  console.error('Invalid YouTube URL');
}
```

## License
