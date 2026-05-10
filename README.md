# Patch34: Bionic Subtitles

**[→ Try it live](https://bionic-subtitles.patch34.workers.dev/)**

---

Converts SRT subtitle files to ASS format with bionic reading style — the first letters of each word are bolded to anchor the eye and speed up reading.

Single HTML file, runs entirely in the browser. No server, no upload, no dependencies.

## How to use

1. Open [the converter](https://bionic-subtitles.patch34.workers.dev/) in your browser
2. Drop an `.srt` file
3. Download the resulting `.bionic.ass` file
4. Place it next to your video — most players pick it up automatically

## Notes

- VLC: to resize subtitles, go to **Tools → Preferences → Subtitles** and uncheck **Override font size**
- The output file uses ASS bold tags (`{\b1}...{\b0}`) for bionic highlighting

## License

MIT
