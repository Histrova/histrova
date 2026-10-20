# Privacy

Histrova runs on your computer. It works with Git on your repositories there, and **never uploads your code, file names, commit messages, branch names or anything you type.**

## What Histrova itself sends

**By default, nothing.**

- **Anonymous usage counts (off unless you turn them on).** In VS Code: the `histrova.telemetry.enabled` setting, which also stays off while VS Code's own telemetry is off. When on, Histrova records only which features are used and whether they worked (an error _code_, never a message): never file names, paths, commit messages, branch names, remote URLs or anything you type. Every event is shown in the **Histrova Telemetry** output channel exactly as recorded. (In the current beta, no destination is set up, so nothing is sent even when it's on.)
- **Git itself** talks to your remotes (GitHub, GitLab…) when you fetch, pull or push, exactly as Git does on the command line.

## The website and downloads

- **histrova.pages.dev** (hosted by Cloudflare) counts page visits with Cloudflare Web Analytics, without cookies.
- **Downloads** are counted: which file, which version, and the country and operating system of the download, as reported by Cloudflare. No IP address or anything that identifies you is stored.
- **The feedback form** is a Google Form. Everything in it is optional; leave your email only if you'd like a reply.

## Questions

Open a [discussion](https://github.com/Histrova/histrova/discussions) or use the [feedback form](https://histrova.pages.dev/#feedback).
