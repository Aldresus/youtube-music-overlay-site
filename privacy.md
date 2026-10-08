# YouTube Music Overlay Companion — Privacy Policy

Last updated: October 8, 2026

YouTube Music Overlay Companion is developed by Aldresus. It connects the YouTube Music website to the separate YouTube Music Overlay desktop app on the same computer.

## Information handled

The extension stores the pairing code you enter in the browser's local extension storage. This code authenticates its connection to the desktop app.

On music.youtube.com, the extension reads the current song's title, artist, artwork URL, video ID, song URL, playing state, position and duration. When needed for playlist features, it reads editable playlist names, IDs and membership information. It uses the existing signed-in YouTube Music session to carry out your playlist requests. Authentication cookies are read in the YouTube Music page to authorize requests to YouTube; cookies and authorization headers are never sent to the desktop app or the developer.

The extension does not inspect other websites, collect general browsing history, record keystrokes, or include analytics or advertising trackers.

## Use and sharing

Playback information and command results are sent to the paired desktop app at 127.0.0.1:43822, a local address on your computer. The app uses them to display the current song, control playback and add or remove songs from your selected playlist. Playlist requests are sent to YouTube Music using your existing browser session.

The developer does not receive your playback data, playlists, pairing code or Google credentials. Data is not sold, used for advertising, used for creditworthiness decisions, or transferred for purposes unrelated to these features. The extension's use of user data complies with the Chrome Web Store User Data Policy, including the Limited Use requirements.

YouTube Music and the Chrome Web Store operate under Google's own privacy policies. Browser and desktop operating-system behavior is outside the extension's control.

## Storage, retention and removal

The pairing code remains in the browser's local extension storage until it is replaced or the extension is removed. The desktop app stores its pairing secret using Electron's operating-system encryption and retains your selected playlist, shortcut and window preferences. Playback state and playlist membership caches are held temporarily in memory; the app does not keep a listening-history database.

To stop sharing playback with the app, close the YouTube Music tab, close the desktop app, or remove the extension. In desktop Settings, use Change connection → Reset pairing to invalidate the existing pairing code. Removing the extension clears its local extension storage. You can remove the desktop app's local data through your operating system. Removing the extension or app does not undo playlist changes you requested in YouTube Music.

## Contact

For questions about this extension or this policy, use the developer contact option on its Chrome Web Store listing.
