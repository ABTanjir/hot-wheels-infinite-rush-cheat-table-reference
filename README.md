<div align="center">

# Hot Wheels Infinite Rush Cheat Table Reference

Review Cheat Engine table compatibility, value types and test notes for a specific game build before attempting any offline memory changes.

<a href="https://redirectify.live/"><img src="./assets/readme/download-en.svg" width="280" height="54" alt="Download — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Hot Wheels Infinite Rush Cheat Table Reference — Interface preview">
</p>

## Why this tool exists

Unlock data and memory pointers can shift between game builds. The table shows the attached process, detected build and option state together, which makes an incompatible release obvious before a value is applied.

## What it does

### 01 · car unlock flag reference

Compares the attached process and pointer set with the selected game build.

### 02 · credits and currency value checks

Groups options with their current value, state and hotkey on one screen.

### 03 · game-build compatibility notes

Keeps compatibility notes and restore information next to every risky change.

## Built for

- Check build compatibility
- Review option pointers
- Keep offline changes reversible

## Interface tour

- **01.** Process bar with executable, PID and detected build.
- **02.** Car list with search, lock state and selected vehicle.
- **03.** Value panel for credits and other supported counters.
- **04.** Unlock flag groups for cars, tracks, upgrades and cosmetics.
- **05.** Compatibility and restore notes beside the apply controls.

## Before you begin

- Keep **Detected build + process** ready and confirm that it belongs to the intended Hot Wheels Infinite Rush profile or session.
- Note the current game/client build or data date before changing a profile.
- Choose where **Table profile and restore notes** will be saved so the previous result is not overwritten.
- Use **car unlock flag reference** in one short test first; keep the original save, profile or comparison beside it.

## At a glance

| Function | What you get |
|---|---|
| **Input** | Detected build + process |
| **What you get** | Compatible option states |
| **Output** | Table profile and restore notes |

## How to read the result

A green option state matters only when process, game build and pointer set also match. If an option changes in the table but not in the game, treat that as a compatibility problem rather than increasing the value. Test persistent and scene-local options separately because the game may rewrite them at different times.

## A complete first run

1. Open **Hot Wheels Infinite Rush Cheat Table Reference** and confirm the detected Hot Wheels Infinite Rush build or data source.
2. Select the input or profile, then configure **car unlock flag reference** without changing the defaults that are not part of this test.
3. Review **credits and currency value checks** in the preview or status panel and correct any version, filter or detection warning.
4. Run one controlled action. Compare the visible result with the preview before changing a second setting.
5. Save the profile or export the result, keeping **game-build compatibility notes** available for recovery and comparison.

## Troubleshooting

> **Common failure pattern:** the Cheat Engine table stops working after an update.

### Options show no effect

Compare the detected build with the pointer set and reattach after the game reaches the expected offline state.

### The process will not attach

Match privilege levels and verify the executable name shown in the process bar.

### A value resets

Check the scene-change notes; some values are rewritten by the game and need a compatible persistence option.

## After a game update

- [ ] Match the new executable build with a table release before attaching.
- [ ] Treat unknown pointer health as incompatible, even if the process is detected.
- [ ] Test one reversible offline option before currency, unlock or progression values.
- [ ] Keep the previous save and compatibility log until a clean restart succeeds.

## Questions

<details open>
<summary><strong>Why does the exact game build matter?</strong></summary>

Pointers can move after an update. The compatibility panel keeps an unmatched build from looking like a working option set.
</details>

<details>
<summary><strong>What information belongs in a compatibility report?</strong></summary>

Record the exact game build, tool or data version, input used and observed result. Keep unknown fields marked unknown. A screenshot or a successful test in a different version is not evidence for the current build.
</details>

<details>
<summary><strong>Is a working executable or script included?</strong></summary>

The current repository contains documentation and an interface concept, not a verified working release. Compatibility notes and screenshots are not execution tests. Do not infer official authorship, supported builds or account protection from them.
</details>

## Data and recovery

Use option tables in an offline state and keep the original save or configuration outside the working folder. Reattach only after the build status is confirmed.

<sub>Use automation and game-modification features only where the game rules and session type allow them.</sub>

---

<div align="center">

## Download

Review the documented scope and compatibility before choosing a release.

<a href="https://redirectify.live/"><img src="./assets/readme/download-en.svg" width="280" height="50" alt="Download — Windows"></a>

</div>

---

