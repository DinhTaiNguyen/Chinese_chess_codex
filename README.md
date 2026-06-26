# Cát Tiên ♡ Đình Tài Xiangqi

A static two-player Chinese chess web app for GitHub Pages.

## Deploy

1. Upload this folder to a GitHub repository.
2. In the repository, open `Settings > Pages`.
3. Set the source to your main branch and root folder.
4. Open the published Pages URL.

## Play Together

1. Đình Tài opens the site and clicks `Host`.
2. Click the copy button beside the room code.
3. Send that invite link to Cát Tiên.
4. Cát Tiên opens the link. Her browser joins as Black automatically.
5. Red moves first. Each legal move syncs to the other browser.

The default room code is:

```text
cattiendinhtai
```

If auto-join does not start, Cát Tiên can paste the room code and click `Join`.

## Private Coach

The coach is hidden until unlocked on the local browser. The default password is:

```text
123
```

After unlocking, the coach offers only two levels, plus selectable styles: balanced, attack, protect, and creative. The coach lock resets whenever the page is refreshed or reopened.

This is a friendly client-side lock, not cryptographic security. Anyone who inspects the static source can find or change the password.

## Rewards

Winner and loser rewards save in the browser forever. Each reward tracks separate counts for Đình Tài and Cát Tiên, with plus/minus controls for correcting mistakes. Use each panel's `Summary` button to see the full 🐶 Đình Tài and 🐼 Cát Tiên totals.

When both players are online, reward changes sync live between browsers. Each panel still has a `Sync` button as a manual online resend, but normal reward edits broadcast automatically.

Offline reward edits auto-save on the current browser too, so reopening the same deployed site keeps the added rewards and counts.

When a game finishes, a board popup cheers the winner, encourages the loser, shows a random love quote, plays a short love sound effect when sound is enabled, and gives direct buttons to the winner and loser reward panels. It can be minimized or closed.

`Redo` becomes active after `Undo`, so a mistaken undo can be restored.
