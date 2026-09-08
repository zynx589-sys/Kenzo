# PairLink

Simple temporary 1-to-1 browser chat.

- No username
- No login
- No database
- No message history
- Messages are sent peer-to-peer using WebRTC through PeerJS.
- PeerJS Cloud is used only for connection/signaling; it does not store the chat messages.

## GitHub Pages

Upload `index.html` directly to the root of your GitHub repository.

Then enable:
Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.

Your site can look like:
https://YOUR-USERNAME.github.io/CHAT/

Open the base URL. It creates a unique link automatically, for example:
https://YOUR-USERNAME.github.io/CHAT/#abc123...

Use "Share Link" and send that link to the other person.

Important: the person who creates the link must keep that page open while chatting. If that page closes/disconnects, the other person cannot reconnect to that room.

PeerJS documentation:
https://peerjs.com/
