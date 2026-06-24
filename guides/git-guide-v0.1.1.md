# Git -- A Plain Language Guide

Version: 0.1.1
Status: Draft
Style Guide: style-guide--plain-language-for-general-audiences-v0.2.0

## Abstract

This document explains what Git is, why it is useful, and what kinds of things you can use it for. It is written for anyone who has not used Git before, regardless of technical background. It also addresses the learning curve honestly — Git is a powerful tool that was designed by and for software developers, and that shows. But it is becoming more accessible every year, and many tools you already use are quietly built on top of it.

Here's the summary section as unrendered markdown, ready to drop in after the abstract:

## Summary

Git solves a problem everyone has — keeping track of what changed, when, and why. It does this for files of any kind: code, writing, designs, data, or documents. At its most direct, you use Git yourself to track your own work and collaborate with others. At its most invisible, it runs quietly inside tools you already use, keeping versions in order without you ever needing to know it is there. Either way, the same idea is at work: nothing is ever truly lost, every change is recorded, and going back is always an option.

## Sources and acknowledgements

All technical information in this document refers to the <a name="apa-git-citation"></a>[Git Project (2024)](#apa-git-reference) official documentation. Information about open source licensing follows the <a name="apa-fsf-citation"></a>[Free Software Foundation (2024)](#apa-fsf-reference) description of the GNU General Public License. Examples of Git integration in third-party products are drawn from the <a name="apa-vscode-citation"></a>[Visual Studio Code documentation (Microsoft, 2024)](#apa-vscode-reference), the <a name="apa-figma-citation"></a>[Figma branching documentation (Figma, 2024)](#apa-figma-reference), and the <a name="apa-wikipedia-citation"></a>[Wikimedia Foundation (2024)](#apa-wikipedia-reference) infrastructure documentation.

## 1. What is Git?

Git is a tool for tracking changes to files over time. When you use Git, it keeps a full history of every change you have made. You can look back at any earlier version of your work, see exactly what changed, and restore anything you need. Nothing is lost.

Git was created by Linus Torvalds in 2005 to manage the source code of the Linux operating system. It is now the most widely used version tracking tool in the world. It is free to use and open source, meaning anyone can inspect, modify, and share it.

Git was built by software developers, for software developers. Its interface is a command line — a text-based window where you type instructions. That is not the most welcoming introduction for everyone, and it is fine to acknowledge that. You do not need to use the command line to benefit from what Git makes possible. Many tools now give you Git's features through a familiar visual interface, and some of the apps and services you already use are quietly running on Git behind the scenes without ever asking you to type a single command.

## 2. Who is Git for?

Git is most often used by software developers, but it is useful for anyone who works with files that change over time. Writers, designers, researchers, and teams of all kinds use Git to manage their work.

If you have ever saved a file as `final.docx`, then `final_v2.docx`, then `final_ACTUAL_FINAL.docx`, you have been solving the same problem that Git solves — just manually. Git does this automatically, cleanly, and without cluttering your folders.

## 3. Git in tools you already use

Git is not always visible. It often works behind the scenes inside products that present its features in a much friendlier way. You may already be using Git without knowing it.

**Visual Studio Code** is one of the most popular code editors in the world. It has Git support built directly into its interface. You can track changes, review your history, and collaborate with others using buttons and menus — no command line needed <a name="apa-vscode-citation-2"></a>([Microsoft, 2024](#apa-vscode-reference)).

**Figma**, the design tool used by product and interface designers worldwide, uses a branching model directly inspired by Git. Designers can create a branch of their work, make changes safely, and merge those changes back in when they are ready — the same concepts Git introduced, presented in a visual interface built for designers <a name="apa-figma-citation-2"></a>([Figma, 2024](#apa-figma-reference)).

**Wikipedia** stores the source of every article, and the complete history of every edit ever made, in a version control system that shares Git's core ideas. Every change is tracked, attributed, and reversible. That is why you can view the full edit history of any Wikipedia article and restore any earlier version <a name="apa-wikipedia-citation-2"></a>([Wikimedia Foundation, 2024](#apa-wikipedia-reference)).

These are not coincidences. The problems Git solves — tracking change, enabling collaboration, protecting against loss — are universal. The tools built on top of Git are making those solutions available to everyone, not just developers.

## 4. What can you use Git for?

Git is useful any time you want to track, share, or collaborate on files. Common uses include:

- **Tracking your own work** — keep a full history of every change you make to a document, a project, or a codebase. Go back to any earlier version at any time.
- **Collaborating with others** — multiple people can work on the same files at the same time. Git tracks who changed what and when. It helps merge everyone's work together without overwriting anyone else's changes.
- **Backing up your work** — Git works with remote services like GitHub, GitLab, and Codeberg. Pushing your work to one of these services means you always have a copy stored safely offsite.
- **Experimenting safely** — Git lets you create a **branch**, which is a separate copy of your work you can change freely. If the experiment works, you merge it back in. If it doesn't, you discard it. Your original work is never at risk.
- **Releasing and publishing** — teams use Git to manage versions of software, documentation, and other published work. It makes it easy to mark a specific point in time as a release.
- **Auditing changes** — Git keeps a complete, timestamped log of every change ever made, along with a note about why the change was made. This is useful for understanding the history of a project and for meeting accountability requirements.

## 5. How does Git work?

Git tracks changes through a series of **commits**. A commit is a snapshot of your files at a specific point in time. Each commit has a message that describes what changed and why. Together, your commits form a timeline of your project from its very beginning to right now.

You do not need to commit every small change. Most people commit when they have finished a meaningful piece of work — a section of writing, a fix to a problem, a new feature. The commit message is your note to your future self, and to anyone else who works on the project later.

Git stores all of this history in a **repository**. A repository is simply a folder that Git is tracking. Everything inside it — files, subfolders, history — is part of the repository.

## 6. Is Git free?

Yes. Git is free to download, free to use, and open source. It is licensed under the GNU General Public License <a name="apa-fsf-citation-2"></a>([Free Software Foundation, 2024](#apa-fsf-reference)), which means you are free to use it for any purpose, inspect how it works, and share it with others. There is no paid version and no feature locked behind a subscription.

Services that host Git repositories — such as GitHub, GitLab, and Codeberg — are separate from Git itself. Some of these services have paid tiers, but Git the tool is always free.

## 7. How do you get Git?

Git runs on Windows, macOS, and Linux. You can download it from the official Git website at [git-scm.com](https://git-scm.com). Installation is straightforward on all three platforms. The official site includes guides for each operating system.

If the command line is not for you right now, that is a reasonable place to start. Tools like GitHub Desktop and the Git integration built into Visual Studio Code give you Git's core features through a visual interface. You can always learn the command line later, if and when you want to.

## Resources

### Git

- [Git documentation](#apa-git-reference)

### Licensing

- [GNU General Public License](#apa-fsf-reference)

### Git in third-party tools

- [Visual Studio Code — Git integration](#apa-vscode-reference)
- [Figma — branching documentation](#apa-figma-reference)
- [Wikimedia Foundation — infrastructure documentation](#apa-wikipedia-reference)

## References

<a name="apa-fsf-reference"></a>Free Software Foundation. (2024). *GNU General Public License, version 2*. Free Software Foundation. https://www.gnu.org/licenses/old-licenses/gpl-2.0.html
[Return to citation](#apa-fsf-citation)

<a name="apa-figma-reference"></a>Figma. (2024). *Branching and merging in Figma*. Figma Inc. https://help.figma.com/hc/en-us/articles/360063144053
[Return to citation](#apa-figma-citation)

<a name="apa-git-reference"></a>Git Project. (2024). *Git documentation*. Software Freedom Conservancy. https://git-scm.com/doc
[Return to citation](#apa-git-citation)

<a name="apa-vscode-reference"></a>Microsoft. (2024). *Using Git source control in VS Code*. Microsoft Corporation. https://code.visualstudio.com/docs/sourcecontrol/overview
[Return to citation](#apa-vscode-citation)

<a name="apa-wikipedia-reference"></a>Wikimedia Foundation. (2024). *Wikimedia infrastructure*. Wikimedia Foundation. https://www.mediawiki.org/wiki/Wikimedia_infrastructure
[Return to citation](#apa-wikipedia-citation)

## Changelog

| Version | Status | Notes |
|---------|--------|-------|
| 0.1.0 | Draft | Initial draft |
| 0.1.1 | Draft | Added Summary Section |
