# Platform Zero

Transit board games for phones: Hide & Seek, Chase, Race and Territory on Greater London, Central London, New York, Delhi or a fictional city. Each player plays on their own phone; no accounts needed.

Open the site, host a game, and send the invite link to friends.

Games sync through a free public MQTT relay (broker.emqx.io, with test.mosquitto.org and broker.hivemq.com as fallbacks). Hidden information (the hider's station and cards, runners' positions) stays on the player's own phone.

## Credits

- Greater London network: Oliver O'Brien (tubecreature), derived from OpenStreetMap, CC BY-NC.
- River Thames: OS Open Data, Open Government Licence.
- MQTT client: mqtt.js (MIT), loaded from unpkg.
