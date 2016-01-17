# Soundboard

Given a DropBox user ID and a publicly-served directory, this tool will read a
JSON file listing MP3 sound clips, and arrange them with keyboard shortcuts, so
you can click them with your mouse or mash your hand on the keyboard.

Here's an example JavaScript file:

```javascript
initBoard(
    {
        "title": "The Bohemian Rhapsody Soundboard",
        "sounds": [
            {
                "title": "I see a little silhouetto of a man",
                "url": "01.mp3"
            },
            {
                "title": "Scaramouche, Scaramouche, will you do the Fandango?",
                "url": "02.mp3"
            },
            {
                "title": "Thunderbolt and lightning, very, very frightening me",
                "url": "03.mp3"
            },
            {
                "title": "Galileo",
                "url": "04.mp3"
            },
            {
                "title": "Galileo",
                "url": "05.mp3"
            },
            {
                "title": "Galileo Figaro",
                "url": "06.mp3"
            },
            {
                "title": "Magnifico!",
                "url": "07.mp3"
            },
            {
                "title": "I'm just a poor boy, nobody loves me",
                "url": "08.mp3"
            },
            {
                "title": "He's just a poor boy from a poor family, spare him his life from this monstrosity",
                "url": "09.mp3"
            },
            {
                "title": "Easy come, easy go, will you let me go?",
                "url": "10.mp3"
            },
            {
                "title": "Bismillah!",
                "url": "11.mp3"
            },
            {
                "title": "No, we will not let you go",
                "url": "12.mp3"
            },
            {
                "title": "Let him go!",
                "url": "13.mp3"
            },
            {
                "title": "We will not let you go",
                "url": "14.mp3"
            },
            {
                "title": "Will not let you go",
                "url": "15.mp3"
            },
            {
                "title": "Let me go...",
                "url": "16.mp3"
            },
            {
                "title": "No no no no no no no!",
                "url": "17.mp3"
            },
            {
                "title": "Oh mama mia, mama mia",
                "url": "18.mp3"
            },
            {
                "title": "Mama mia let me go",
                "url": "19.mp3"
            },
            {
                "title": "Beelzebub has a devil put aside for me",
                "url": "20.mp3"
            },
            {
                "title": "For me",
                "url": "21.mp3"
            },
            {
                "title": "For me!",
                "url": "22.mp3"
            }
        ]
    }
);
```

The MP3s should be placed in the same web-servable directory as that file (
which should be called `board.js`). Feed the URL of the file - minus the
`board.js` bit - into the `index.html`'s `DROPBOX_URL` setting, and you should
be good to go.

I recently adapted this [for use in a BBC project](http://bloomsbury.digital/development/odd-taste/).
