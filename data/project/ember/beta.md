---
name: Ember
baseFileName: ember
filter:
  - /ember\./
  - /ember-template-compiler/
repo: emberjs/ember.js
initialVersion: 4.12.0 # Manually update, the prior version to the current beta. See https://libraries.io/npm/ember-source throughout
lastRelease: 5.0.0-beta.1 # Manually update
futureVersion: 5.0.0-beta.2 # Manually update
finalVersion: 5.0.0 # Manually update
channel: beta
cycleEstimatedFinishDate: 2023-04-03 12:00:00 # Manually update, the expected date of the finalVersion release
date: 2023-02-20 12:00:00 # Manually update, get date for `initialVersion`
nextDate: 2023-04-03 12:00:00 # Manually update, change next one to 6 weeks from this date...regardless of delays in the release
changelogPath: CHANGELOG.md
debugFileName: .debug.js
ignoreFiles:
  - ember.js
---

# Install Ember %s:

<br>
npm install --save-dev ember-source@~%s
