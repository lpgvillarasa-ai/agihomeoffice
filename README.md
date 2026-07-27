# Daily Worship Roll 🕯️

A simple web app that rolls (randomly assigns) who does each part of the daily worship:

1. **Opening Prayer** 🙏
2. **Applying the Blood of Jesus** ✝️
3. **Worship Lead** 🎵 (rolled among the Worship Leaders, Mieko and Elijah by default, and a song they know is picked automatically)
4. **Word** 📖
5. **Closing Prayer** 🕊️

## How to use

Just open `index.html` in any browser. No install, no server needed.

- **Today's Roll tab**: press **🎲 Roll for Today**. Every role gets a different person (when there are enough names). The roll is saved for the day, so reopening the page shows the same assignments; press the button again to reshuffle.
- **People tab**: add names **once** and they're saved on the device (browser localStorage), so you don't re-add them every day. Toggle **★ Leader** on anyone who can lead worship; the Worship Lead role is only rolled among leaders.
- **Songs tab**: the team's song list comes preloaded, with each song marked as "Both know" or "Mieko only". The roll only ever gives a leader a song they know: Elijah draws from the shared songs, Mieko draws from the shared songs plus her own list. Press **Edit** on a song to paste in its lyrics, then **View Lyrics** on the Worship Lead card (or **Lyrics** in the song list) displays them full-screen with adjustable text size.

## Where is the data stored?

Everything (names, songs, daily rolls) is saved in the browser's localStorage on the device you use. Nothing is uploaded anywhere.
