# Denote — Beta

AI design tools are good at turning a prompt into a screen. The trouble comes after. Once the app is built, changing anything structural (how the objects fit together, what the navigation looks like, how data flows between screens) is painful. Code turns to spaghetti. Nav becomes a frankenstein. You either live with what you got or start over.

Denote is where you make those decisions before any code is generated. You name the objects, define how they relate, lay out the pages, decide the navigation. When you're ready, Claude Code reads your decisions and builds. Changing structure later means editing those decisions, not untangling generated code.

This is a beta build. Things will break. If you're testing — your feedback is the entire point.

## Before you install

Denote requires **Claude Code** to be installed on your Mac. Denote is the thinking tool; Claude Code is the building tool. Without it, Denote's embedded terminal can't run any skills and the app won't be useful.

Install Claude Code first: https://docs.claude.com/en/docs/claude-code/overview

After installing, open Terminal and type `claude` — if the command runs, you're ready.

## Download

Grab the latest DMG from the [Releases page](https://github.com/yarcom/denote-releases/releases/latest):

- **Apple Silicon (M1, M2, M3, M4 Macs)** → the `arm64.dmg` file
- **Intel Macs** → the `.dmg` file (without `arm64`)

Not sure which Mac you have? Apple menu → About This Mac. If it says "Apple M1/M2/M3/M4", get the Apple Silicon version. If it says "Intel", get the other one.

## Install

1. Open the `.dmg` you downloaded.
2. Drag the **Denote** icon into the **Applications** folder shortcut in the same window.
3. Open the **Applications** folder in Finder.

## First launch — important

Denote isn't signed by Apple yet (that costs $99/yr — not worth it for a small beta). On first launch, macOS will block it with a warning that says *"Denote can't be opened because Apple cannot check it for malicious software."*

To get past this, **don't double-click** Denote the first time. Instead:

1. **Right-click** (or Control-click) on the Denote app in Applications.
2. Choose **Open** from the menu.
3. A new dialog appears with an **Open** button — click it.

After this one-time step, Denote opens normally on every launch.

## Updates

Denote checks for updates automatically when you launch it. When a new version is available, you'll see a dialog asking if you want to download it. The dialog reappears on every restart until you update. You don't need to re-do the right-click step for updates.

## Privacy

Denote sends anonymous usage data (which skills you run, which layers you switch to, app version) and crash reports back to me so I can see what's working and fix bugs without asking you to repro them. **No design content ever leaves your machine** — none of your vision, entities, governance rules, terminal input or file paths.

If you'd rather not send anything, email yarcom@gmail.com and I'll exclude your data.

## Reporting bugs

If something breaks, please tell me:

- What you were trying to do
- What you expected to happen
- What actually happened (screenshots are gold)
- What version you're on (Denote → About, or check the title bar)

Send to: yarcom@gmail.com — or wherever we're already chatting.

## Known limitations in this beta

- App is not signed (the right-click-to-open thing above)
- Inline editing is still early — expect rough edges in fields you can edit directly
- First-time experience isn't fully robust yet — empty states and onboarding flow are works in progress
- Beta builds may have rough edges; expect surprises

Thanks for trying.
