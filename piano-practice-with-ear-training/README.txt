# Piano Practice Timer

## Features
- A daily practice plan with exercise durations and no fixed start times.
- A countdown and a repeating alarm until you tap "OK, next exercise".
- Restarting or restoring the plan also stops the alarm.
- Edit exercise names and durations directly in the app.
- Add and delete exercises.
- Tap any exercise to skip ahead or go back, then press Start. Switching exercises stops the current timer and alarm and loads the selected exercise at its full duration.
- Skipped exercises are not marked as completed.
- Save your custom plan in this browser.
- Restore the original plan.
- App installation and offline caching when hosted over HTTPS.

## Try it
Open `index.html` in a browser. To install it as an app and use it offline, publish the files on an HTTPS host such as GitHub Pages.

## Update an existing GitHub deployment
1. Extract this ZIP.
2. Open your GitHub repository.
3. Choose Add file > Upload files.
4. Upload the new files, replacing the old ones.
5. Select Commit changes.
6. Refresh the published page. If the old version still appears, close and reopen the app or clear the site's cache.

## Files
- `index.html`: app, timer and plan editor
- `manifest.json`: app installation settings
- `sw.js`: offline support
- `icon.svg`: icon
- `README.txt`: instructions


CHORD DICE UPDATE
- Select the "Chord flashcards" exercise in the practice plan.
- Open "Chord dice · 36 chords".
- Draws all 36 chords in shuffled order without repeats.
- Chord symbol is shown first (for example F#m7); reveal shows quality, notes and formula.
- Use "Shuffle and restart round" to start a fresh random round.

EAR TRAINING ADDITION
- Select Ear training in the practice plan and click Open ear training · Piano.
- Click the exercise card to hear the reference note and see a random ascending or descending interval.
- Sing the answer first, then click the card again to reveal and hear the target note.
- Click the card once more for the next interval. The on-screen piano (C3 to B5) is playable.
- Acoustic piano samples are loaded online; a simple fallback sound is used if unavailable.
- Chord Dice is unchanged from the uploaded original.
