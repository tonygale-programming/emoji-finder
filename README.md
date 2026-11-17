# Emoji Finder

Find any emoji by name or keyword and copy it with one click. No more googling "fire emoji" and copying from a random site.

**Open it:** https://tonygale-programming.github.io/emoji-finder/

## How it works

1. Start typing: `fire`, `thumbs up`, `party`, `:tada:`. You don't need to click the search box first.
2. Press **Enter** to copy the top result, or click any emoji.
3. Paste it anywhere with `⌘V`.

## Features

- Search all 1,906 emoji (up to Emoji 16) by name, keyword or GitHub-style shortcode
- **Enter** copies the selected emoji; arrow keys move through the results; **Esc** clears the search
- **Collect several**: Shift+click or Shift+Enter adds emoji to a tray, then **Copy all**
- Skin tone picker that applies to every emoji that has skin tones, and is remembered
- **Recently copied** row, so the emoji you use most are always at the top
- Browse by category: Smileys, People, Animals & nature, Food & drink, Travel, Activities, Objects, Symbols, Flags
- Shows each emoji's name, shortcode and Unicode code points
- Light and dark themes follow your system setting
- Works on phones too

## Privacy

Everything runs in your browser. There is no server, no analytics and no account. Your skin tone and recently copied emoji are stored only in your browser's local storage.

## Tip

On a Mac, **Control + Command + Space** opens the system emoji picker in any text field. Emoji Finder is better when you want to search by keyword, collect several emoji at once, or keep your favourites one click away.

## Development

It's a single static file, `index.html`, with no build step. Open it in a browser to run it locally.

The emoji names and keywords come from [Emojibase](https://emojibase.dev/) (`emojibase-data` 16.0.3, MIT), which is built on Unicode CLDR data.

## License

[MIT](LICENSE)
