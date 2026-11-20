# AURIX

**English** | [繁體中文](README.zh-Hant.md)

AURIX is a desktop app for working with AI coding agents. It puts your agents, your tools and your tasks in one window.

This page is for people who use AURIX. Downloads and release notes are on the [Releases page](../../releases).

## What AURIX does

- **Work with several agents at once.** Open terminals for Claude Code, Codex and other agents side by side. A label on each terminal shows if the agent is working, waiting for you or idle.
- **Answer agents in one place.** When an agent asks a question or needs your OK, a card appears over any app. Pick an answer, or press Approve or Deny.
- **Assistant.** Talk to Assistant by text or voice. It can start and watch agents for you, run scheduled jobs and remember facts about you. A Dispatch Board lists what needs your decision, what is running and what just finished.
- **Tasks and review.** Give a task to an agent in its own work folder. Check its work against your list of checks before you merge it. A task board and a flow strip show where each task is.
- **MCP plugins.** Install and manage MCP plugins from one page, and choose which tools each agent or Assistant may use. Keys are kept in a secret store.
- **Built-in Browser.** Browse inside AURIX with tabs, bookmarks, saved passwords and phone or tablet screen sizes. Agents can use it, and you can review their prototypes there.
- **Memory.** Agents save decisions and lessons, and look them up before they start new work.
- **Skills.** Import your own skills and run them from the right-click menu of any terminal.
- **Remote access.** Control AURIX on one computer from another, over your own Tailscale network or over SSH. Each connection is checked with a six-digit code and Touch ID or Windows Hello.
- **Usage view.** See how much of your plan or API budget you have used.

## System requirements

- **macOS:** macOS 14 Sonoma or later, on Apple Silicon (M1 or newer).
- **Windows:** 64-bit (x64).

## Install

**macOS**

1. Download the `.dmg` file from the [Releases page](../../releases).
2. Open it and drag AURIX into your Applications folder.
3. Open AURIX from Applications.

**Windows**

1. Download the `.exe` installer from the [Releases page](../../releases).
2. Run it and follow the steps.

The Windows installer is not signed yet. Windows SmartScreen may show "Windows protected your PC". If you downloaded it from this page, choose **More info**, then **Run anyway**.

## Update

AURIX checks for new versions. When one is ready, the app shows **Restart to Update**. Click it and AURIX restarts on the new version.

You can also download the latest version from the [Releases page](../../releases) and install it over the old one.

## Report a problem

Open an issue on this repo: [New issue](../../issues/new).

Please include:

- What you did and what you expected.
- What happened instead.
- Your AURIX version (shown in Settings › App) and your system (macOS or Windows).
- A screenshot, if it helps. Remove any private information first.
