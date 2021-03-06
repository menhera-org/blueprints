# Platforms

## Ideas
- Abstract and integrate the main features of: Slack+Discord+Twitter+LINE+Twitter+wiki+blog+Git.
- Frontend: notification-triggered alarms.
- Can turn on notifications on every feed.
- Deny the idea of "followers".
- Location sharing.
- Manage channel messages (versions) on a distributed manner. cf. Git
- File storage. cf. IPFS
- Various layers of protocol: messaging protocol, distribuetd storage (content-addressable storage), channels and domains.

## Requirements
- Division of backend and frontend.
- Tor Browser compatibility (`privacy.resistFingerprinting`, first-party isolation, no WASM). [Really needed?]
- ServiceWorkers may not be available (private tabs on Firefox or iOS WebView).
- Fully JavaScript-based (altJS such as PureScript?)
- Frontend clients/UAs are Web-based.
  - Webextension version.
  - PWA version.
  - Electron desktop version.
  - iOS version?
- Resistance against bad Internet connections.
- End-to-end encryption whenever feasible.
- NAT compatibility.
- WebRTC.
- Every text can be language-tagged.
