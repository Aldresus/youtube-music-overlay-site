# YouTube Music Overlay Companion - Privacy Policy

Last updated: October 8, 2026

Developed by Aldresus. Version 0.1.2 and later connect YouTube Music web playback to a separate desktop overlay on the same computer.

## Information handled

The extension stores your pairing code locally. On music.youtube.com it reads the current song's title, artist, artwork URL, video ID, song URL, playing state, position and duration. It does not read Google authentication cookies, fetch playlists, or make playlist changes.

It does not inspect other websites, collect general browsing history, record keystrokes, or include analytics or advertising trackers.

## Use and sharing

Playback information and playback command results are sent only to the paired desktop app at 127.0.0.1:43822, a local address on your computer. The app displays the song and controls previous/next and seeking in the Music tab.

The developer does not receive playback information or pairing codes. Data is not sold, used for advertising, used for creditworthiness decisions, or transferred for unrelated purposes. YouTube Music and the Chrome Web Store operate under Google's own privacy policies.

## Storage, retention and removal

The pairing code remains in local extension storage until replaced or the extension is removed. The desktop app stores its pairing secret with Electron's operating-system encryption and retains the window position. Playback state is held temporarily in memory; the app does not store listening history.

Close the Music tab or desktop app to stop sharing playback. In desktop Settings, use Change connection > Reset pairing to invalidate the code. Removing the extension clears its local storage. Desktop data can be removed through your operating system.

Earlier previews (0.1.0-0.1.1) also read playlist names, IDs and membership and used Google authentication cookies inside the Music page for user-requested playlist edits. Those features and cookie reads were removed in 0.1.2. Upgrade both app and companion. Upgrading does not undo earlier playlist edits.

## Contact

Use the developer contact option on the Chrome Web Store listing for questions about this extension or policy.
