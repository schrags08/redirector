# JavaScript Redirect Example

## HOW TO USE

Determine the URL you'd like to redirect to, e.g. `https://farkusmusic.bandcamp.com`

Run `encodeURIComponent` on this URL to encode unsafe characters...

```js
encodeURIComponent('https://farkusmusic.bandcamp.com');
// result: "https%3A%2F%2Ffarkusmusic.bandcamp.com"
```

Visit [https://schrags08.github.io/redirector/index.html](https://schrags08.github.io/redirector/index.html) and open the console.

Add a `redirectUrl` query string parameter to the URL

Provide your encoded destination URL as the value for the parameter:

e.g. [https://schrags08.github.io/redirector/index.html?redirectUrl=https%3A%2F%2Ffarkusmusic.bandcamp.com](https://schrags08.github.io/redirector/index.html?redirectUrl=https%3A%2F%2Ffarkusmusic.bandcamp.com)

Explore the script in `index.html` to make changes and get a better understanding.
