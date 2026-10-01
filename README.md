# Freshly88

> A fair feed for newly created GitHub repositories.

Every repo gets the same chance. No stars, no followers, no ranking. Just what was published in the last 24 hours, shuffled and shown to you.

---

## The problem

GitHub is built around stars. The more you have, the more visible you become — and the more visible you become, the more stars you collect. It's a loop that rewards people who are already known.

If you publish your first repository today, you are invisible. Not because it's bad, but because it hasn't had time to accumulate anything yet. By the time it does, it's already competing against projects with thousands of stars, and it loses.

The result is that most people never see what's actually being built right now. They see what was built two years ago and already won.

Freshly88 is an attempt to fix that, at least for a small window of time.

---

## What it does

It collects every public repository created within a recent time window — the last hour, 6 hours, 24 hours, or 3 days — and presents them in a plain, equal feed.

There is no popularity ranking. A repo with zero stars appears next to one with two hundred. The default order is a complete random shuffle, which means every repository in the pool has the same probability of being the first thing you see.

You will find good projects. You will also find rough drafts, empty repos, weekend experiments, half-finished ideas, and things that probably should not have been made public. That is not a bug. That is the entire point — the feed shows you what exists, not what has been curated.

---

## Why "fair"

Most discovery tools filter before they show you anything. They decide what is worth your attention based on signals like stars, forks, or account history — and those signals favor people who already have an audience.

Freshly88 does not make that decision for you. It shows you everything and lets you decide. The only thing it sorts by is time: how recently a repository was published.

This means the feed is noisier than GitHub's trending page. It also means you occasionally find something genuinely new — a project from a first-time contributor, a niche tool nobody has noticed, a prototype that is weeks away from being useful. You will not find those things on a ranked list, because they have not earned their ranking yet.

---

## Features

### Time windows

Choose how far back you want to look: the last hour, the last 6 hours, the last 24 hours, or the last 3 days. Shorter windows surface fewer, fresher repos. Longer windows give you more to browse, but a higher chance of running into abandoned experiments.

### Four ways to sort

- **Fair shuffle** — the default. Every repo has an equal chance of appearing first.
- **Newest first** — most recently created at the top.
- **Most starred** — when you want to see what's already gaining attention.
- **Rising fast** — repos that are picking up stars quickly relative to how long they've existed. A repo created four hours ago with thirty stars ranks higher than one created two days ago with fifty.

### Language filter

Enter any language GitHub recognizes and the feed narrows to just those repos. Useful if you're looking for something specific — Rust projects, Elixir projects, whatever you're curious about.

### No account required

You can browse without signing in, without connecting a GitHub account, and without giving up any personal information. The site has no tracking, no analytics, and no server. It runs entirely in your browser.

### Optional token

GitHub limits how often a visitor can request data. Without a token, you can browse a few pages before you have to wait for the limit to reset. If you add a personal access token — the key icon in the header — the limit goes up, and you can keep browsing longer. The token is stored only on your device and is never sent anywhere except GitHub itself.

---

## How to use it

1. Open the site.
2. Pick a time window and a language (or leave the language empty to see everything).
3. Scroll through the feed. Click on any repository that looks interesting — it opens on GitHub.
4. Click **Load more** at the bottom to fetch another batch.
5. Change the sort order whenever you want a different view of the same pool of repos.

That's it. No signup, no onboarding, no tutorial.

---

## What you will and won't find

**You will find:**

- First-time projects from new developers
- Weekend experiments and prototypes
- Documentation sites, configuration files, personal websites
- Tools and libraries that nobody has starred yet
- Occasional gems that would otherwise go unnoticed

**You won't find:**

- A ranked list of "the best" repositories
- Curated or hand-picked projects
- Recommendations based on your history
- Anything filtered by quality, effort, or usefulness

The feed is a raw slice of what's being published on GitHub right now. What you do with that is up to you.

---

## A note on expectations

This is not a tool for finding the best repositories. It is a tool for finding the newest ones.

If you're looking for a well-established library, you're better off on GitHub's search or on a curated list somewhere else. If you're curious what people are building today — including the failed experiments and the half-finished ideas — this is for you.

The value here is not in what's polished. It's in what's unfinished.

---

## Copyright

Copyright © [mohamed005cheikh@gmail.com](mailto:mohamed005cheikh@gmail.com) | by MC88
