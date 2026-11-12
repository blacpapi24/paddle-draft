# Paddle Draft

An auction draft game for two to six players. Pick a genre, then take turns bidding from a £20 budget on its top 10. Each player fills five slots, and the biggest combined stat (box office, streams, goals and so on) wins.

## Playing phone to phone

1. Open the site on both phones while you're on the same Wi-Fi.
2. One person taps **Start a room**, picks the genre and rules, then taps **Pair a phone**.
3. The other person types their name, taps **Scan the host's code** and points their camera at the host's QR code.
4. The host scans the code that then appears on the second phone.

The phones talk directly to each other over your Wi-Fi (WebRTC). Game data never goes to a server. This site only serves the page.

If a phone disconnects (for example, the screen locks), tap **Reconnect** on that phone and **Pair a phone** on the host, then scan the codes again. The game picks up where it left off.

## Files

- `index.html` – the whole game.
- `vendor/qrcode.js` – QR code generator by Kazuhiko Arase (MIT).
- `vendor/jsQR.js` – QR code reader by Cosmo Wolfe (Apache 2.0, see `vendor/LICENSE-jsQR`).
