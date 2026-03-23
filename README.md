# Relinker

**Every link, right browser.**
[Relinker](https://relinker.dev) 

Relinker sends each URL to the browser where it belongs. Google Docs to Chrome, YouTube to Firefox, GitHub to Arc. You set the rules — Relinker does the rest, invisibly.

[Download for free](#) | [See how it works](#how-it-works)

---

## How it works

### Three steps. Under a minute.

Relinker registers as your default browser and routes each link to the right place based on your rules.

1. **Set Relinker as default** — The onboarding walks you through it. Relinker never shows a window when you click a link — it works invisibly.

2. **Create your rules** — Match by domain, wildcard, or regex. Pick the target browser. Drag to set priority. Or use a built-in template for Google Workspace, Microsoft 365, and more.

3. **Click links as usual** — Every link from any app — Mail, Slack, Notes, Finder — opens in the right browser automatically. No extra steps, no popups.

---

## Features

### Domain & wildcard matching
Route all links from drive.google.com to Chrome. Or use wildcards like `*slack.com/archives/*` for flexible patterns.

### Regex for power users
Write regular expressions for complex URL patterns. Live validation shows if your regex compiles as you type.

### URL cleaning
Automatically strips 30+ tracking parameters (utm_source, fbclid, gclid), removes AMP redirects, and forces HTTPS. A built-in tracker counter keeps score.

### Rule templates
One-click templates for Google Workspace, Microsoft 365, social media, and developer tools. Set up a full rule set in seconds.

### Menu bar app
Lives in your menu bar. See recently routed links, create rules with one click, pause routing, and check your daily stats — without opening the main window.

### Live rule tester
Paste any URL and instantly see which rule matches and which browser it would open in. Debug your rules without leaving the app.

### Import & export
Export your rules as human-readable JSON. Edit them in any text editor. Share them with your team. Import with one click.

### Free. No strings.
No subscriptions, no in-app purchases, no ads, no tracking. Relinker is free because browser choice shouldn't cost money.

---

## Why Relinker?

| Relinker | Typical alternatives |
|----------|---------------------|
| Free on the Mac App Store | Paid ($4–$14) or config-file only |
| Native SwiftUI — feels like a system app | Older UI frameworks or Electron |
| Domain, wildcard, regex, and source-app rules | Limited to domain matching |
| Built-in URL cleaning (trackers, AMP, HTTPS) | No URL cleaning |
| Human-readable rule export (JSON) | No export, or proprietary format |
| No data collection, fully offline | Some include analytics or telemetry |

---

## FAQ

**How does Relinker work?**
Relinker registers itself as your Mac's default browser. When any app opens a URL, macOS sends it to Relinker. Relinker checks the URL against your rules, cleans it (strips trackers, removes AMP redirects), and opens it in the matching browser. If no rule matches, it opens in your chosen fallback browser. The whole process takes milliseconds — you never see Relinker's window.

**Do I need to set Relinker as my default browser?**
Yes. This is how macOS lets Relinker intercept links from other apps. The onboarding guides you through it — it takes one click in System Settings > Desktop & Dock > Default web browser.

**Does Relinker slow down link opening?**
No. Rule matching happens in microseconds. URL cleaning adds no perceptible delay. The optional short-URL expansion feature makes a brief network request, but it's disabled by default.

**What is URL cleaning?**
Relinker can automatically strip tracking parameters like utm_source, fbclid, and gclid from URLs before opening them. It also removes Google AMP redirects and upgrades HTTP links to HTTPS. All configurable in Settings.

**Does Relinker collect any data?**
No. Relinker has no analytics, no telemetry, no crash reporting, and no user accounts. Your URLs are processed in memory and never leave your Mac. The app makes no network requests unless you enable the optional short-URL expansion feature.

**Which browsers are supported?**
Any browser installed on your Mac: Safari, Chrome, Firefox, Arc, Brave, Edge, Opera, Vivaldi, Orion, Zen, and more. Relinker automatically detects all installed browsers.

**What macOS version do I need?**
macOS 14 (Sonoma) or later.

**Can I share my rules with my team?**
Yes. Export your rules as a human-readable JSON file, share it however you like, and your teammates can import it with one click. The format is simple enough to edit by hand.

**Is it really free?**
Yes. No subscriptions, no in-app purchases, no ads. Free forever. The source code is on [GitHub](https://github.com/Montesinnos/relinker).

---

## Download

Stop opening links in the wrong browser. Download Relinker for free. Set your rules once. Every link goes where it belongs.

[Download for free](#)

---

[Privacy Policy](#privacy) | [Report an issue](https://github.com/Montesinnos/relinker/issues)

© 2026 Relinker
