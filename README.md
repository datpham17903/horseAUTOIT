# horseAUTOIT

An automation tool for **Independent Training** careers in *Umamusume: Pretty Derby*, written with a
**Rust core**.

> [!WARNING]
> Automating gameplay may violate the game's Terms of Service and can get an account flagged or
> restricted. This project is for personal and educational use, at your own risk.

## Status

**Early development.** The design phase is complete; implementation has not started. Nothing here is
usable yet, and there are no releases.

## What it is meant to do

- Run Independent Training careers unattended, repeating automatically when each career's
  server-side window elapses.
- Handle **multiple accounts** from one instance, each isolated from the others.
- Let you configure a run up front — trainee, inheritance parents (including borrowing one from a
  friend, with fallback), support deck, training focus, prioritized skills and race agenda — and
  save those configurations as **presets you can export and import**.
- Keep a separate, exportable preset for end-of-career skill purchases.
- Reroll inheritance sparks according to your own scoring rules.
- Optionally clean up produced trained characters that do not meet your criteria.
- Keep a **history of your last 20 runs**: stats, skills, parents, sparks, fans, race wins and rating.

## Platforms

Windows, Linux (including headless servers), macOS, and Android. Interfaces planned: a native
desktop app, a browser UI, a command-line daemon, and an Android app that can either run on the
device or drive a daemon elsewhere.

## Building

Nothing to build yet. Build and usage instructions will land with the first milestone.

## License

No license is granted at this time. All rights reserved.
