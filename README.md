# Wukong Completion Tracker

A single-page, offline-friendly checklist for a full playthrough of Black Myth: Wukong. It tracks bosses, side quests, hidden tricks, missables, rewards, trophies, pills and gourd items, grouped by chapter.

This is an unofficial fan project. It is not affiliated with the game's developer or publisher.

## Use it

Open `index.html` in a browser. There is no build step and no server. It also works on GitHub Pages: enable Pages for this repository and serve the root of the main branch.

## Features

- Progress bar and per-tab and per-chapter counts
- Search, chapter filter, "Hide completed", "Missable only"
- Turn whole categories off, or skip single items, and they leave your progress count
- Collapsible chapters
- Guide and Video buttons on quests, hidden tricks, pills and gourd items (and on every item if you switch it on). These open a web search for that item.
- Back up and restore your progress as text
- Light and dark theme that follow your system setting

## Your data

Ticks, skipped items and view settings are saved only in your own browser (`localStorage`). Nothing is sent anywhere, and the page has no analytics. Use "Back up or restore progress" to move your progress to another browser or device.

## Fonts

The page loads two fonts (Barlow Condensed and Public Sans) from Google Fonts. If they cannot load, it falls back to system fonts.
