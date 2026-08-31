# Playback Behavior

Nova Music playback should remain predictable across track changes.

## Track changes
When a new track is selected, the player should update the current-track state before starting playback. Failed media loads should leave the previous state recoverable rather than leaving controls in a loading state indefinitely.

## Progress
Progress controls should clamp values to the media duration and avoid writing invalid values when duration is unavailable.

## Accessibility
Playback controls should expose their current state through accessible labels and should remain usable with keyboard input.
