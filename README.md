# Metal & Triv(ia) Game (Twitch Extension)

## Game Architecture

### Roles
1. Viewer
2. Broadcaster

_Default UI will be viewer. Log in will be required for broadcaster UI._

### Workflow
On first extension load, viewer role sees splash screen and broadcaster role sees splash screen and option to start new game.

When new game is started (by the broadcaster role), page automatically refreshes and viewer sees option to enter username to play upcoming round (opt-in).

When new game is started (by broadcaster), viewer sees list of 3-5 questions to answer within a limited amount of time.

*Once timer is up*
Viewer sees "Pending results" screen.
Broadcaster see the results immediately. They can use a button to reveal the results to the viewers when ready

Create leaderboard

Have validation for offensive words (used as username), look into running incoming username against Twitch API auto-mod.

If username is flagged, broadcaster will get notification (or will appear in notification panel) and can choose to accept or reject username.

### Real-time Awareness and Updates

Real-time databases are reactive and enable you to attach listeners.

### State Management

### Target Dates

July 25th - August 6th: Planning, documentation, flowcharts
September 8th: Functionality of app to be complete.
September 21st: App responsive design complete. Submit to Twitch for review.
October 21st: Extension tested, launched and live.