# Dark P2P Chat

A secure, peer-to-peer chat application that works directly between browsers without any server or database.

## Features

- 🔒 **No Database Required** - Messages are sent directly between browsers
- 🌐 **Peer-to-Peer** - Uses WebRTC for direct communication
- 🎨 **Dark Theme** - Modern WhatsApp-inspired design
- ⚡ **Real-time** - Instant messaging with typing indicators
- 📱 **Responsive** - Works on desktop and mobile devices

## How to Use

1. Open the application in your browser
2. Share your unique ID with a friend
3. Enter your friend's ID and click "Connect"
4. Start chatting securely!

## Live Demo

Deploy to GitHub Pages:

1. Fork or upload this repository to GitHub
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" → main branch
4. Your chat will be available at: `https://yourusername.github.io/repository-name`

## Local Development

To run locally:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Then open http://localhost:8000
```

## Security

- All communication is peer-to-peer via WebRTC
- No messages are stored on any server
- Uses PeerJS for signaling (only for initial connection)
- Consider self-hosting PeerJS for enhanced security

## Browser Support

- Chrome/Edge 80+
- Firefox 75+
- Safari 13+
- Mobile browsers with WebRTC support

## Technical Details

- **Frontend**: Vanilla HTML, CSS, JavaScript
- **P2P Library**: PeerJS v1.5.2
- **Communication**: WebRTC DataChannels
- **No Backend Required**

## License

MIT License - Feel free to use and modify!