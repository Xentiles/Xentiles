<h1 align="center">Dominik Nagy</h1>

<p align="center">
  <strong>Applied AI Developer · Software & Data Systems</strong><br>
  Sweden · <a href="https://www.linkedin.com/in/dominik-nagy-841002144/">LinkedIn</a> · <a href="mailto:domisweden@gmail.com">Email</a>
</p>

I turn open-ended problems into working software, combining applied AI, system design, and hands-on implementation. I learn new tools by building with them, testing assumptions, and understanding how the pieces fit together.

## Featured Project: [Feedback Intelligence](https://github.com/Xentiles/feedback-intelligence)

**From raw feedback to results you can inspect and explain.**

Feedback Intelligence is an interactive local Workbench for importing reviews and comments, configuring keyword rules or connected AI, exploring results, comparing compatible runs, and exporting supporting evidence. The **v0.2.0** release moves beyond the recorded showcase into a usable workflow with saved datasets, editable classification templates, and recoverable runs.

[![Feedback Intelligence Workbench showing synthetic feedback distributions, monthly volume, and an open evidence inspection panel](https://raw.githubusercontent.com/Xentiles/feedback-intelligence/v0.2.0/docs/assets/workbench-results.jpg)](https://github.com/Xentiles/feedback-intelligence/blob/v0.2.0/docs/workbench.md)

*Synthetic Workbench results with inspectable records and provenance.*

- **Usable workflows:** connect data mapping, validation, classification, filtering, and export in a responsive React interface, with clear coverage and missing-data states.
- **Reliable processing:** preserve dataset and template revisions, decision provenance, and partial results; handle duplicate requests, retries, and worker restarts through durable jobs and an outbox.
- **Verification and boundaries:** test components and database failure paths, require consent before external AI processing, and keep credentials and feedback bodies out of operational telemetry.

The release verification includes a **10,000-record synthetic rules run** completed after a worker restart, with the full export count verified. This demonstrates workflow recovery, not AI accuracy or customer impact. The tool is local; human-calibrated model quality and hosted deployment remain separate work.

[Repository](https://github.com/Xentiles/feedback-intelligence) · [Walkthrough](https://github.com/Xentiles/feedback-intelligence/blob/v0.2.0/docs/demo-walkthrough.md) · [Verification](https://github.com/Xentiles/feedback-intelligence/blob/v0.2.0/docs/quality/v0.2.0-release-review.md)

<details>
<summary>Workflow preview</summary>

![Feedback Intelligence classification screen with dataset, template, model, reasoning effort, and external-processing consent controls](https://raw.githubusercontent.com/Xentiles/feedback-intelligence/v0.2.0/docs/assets/workbench-settings.jpg)

*Synthetic configuration preview with a demonstration account and model catalog.*

</details>

## [NotchQ](https://github.com/Xentiles/NotchQ) · Native macOS Utility

A native Swift/AppKit utility that displays remaining AI allowance beside the Mac's camera notch, with a menu-bar fallback. It combines Codex usage readings and an optional Claude Code connection with native settings and explicit handling of stale or unavailable data.

Demonstrates native interface development, provider integration, lifecycle handling, fixture-based testing, and universal macOS app packaging.

[Repository](https://github.com/Xentiles/NotchQ) · [v1.0.0 Beta release](https://github.com/Xentiles/NotchQ/releases/tag/v1.0.0)

*Ad-hoc signed, not Apple-notarized; Claude integration is fixture-tested, with live Pro/Max readings not yet verified.*

## How I Build With AI

**Scope → plan and wireframe → establish interfaces and tests → implement → review and verify.**

I start by understanding the problem, breaking it into workable steps, and defining what a correct result should look like. I use Codex, Claude, and local models to explore designs, establish structure, and accelerate implementation once the foundations have been checked.

My role stays hands-on: directing tasks, inspecting changes, debugging failures, and checking functionality and security boundaries. I use tests and review checkpoints to challenge generated code, then iterate on the evidence. I own the architectural decisions and validation rather than treating generated output as a finished result.

## Technical Foundation

- **Application engineering:** C# / ASP.NET Core, React, TypeScript, Swift / AppKit, API design, responsive interfaces.
- **AI and data workflows:** Python, SQL, PostgreSQL, ClickHouse, model integration, evaluation, computer vision.
- **Delivery and verification:** Git, Docker Compose, GitHub Actions, automated tests, versioned contracts, failure-path testing.

## Other Engineering Work

- **[OSFR](https://github.com/Xentiles/OSFR):** experimental Unity/URP rendering research using C#, shaders, deterministic scenes, and spatial/temporal measurements to test rendering ideas.
- **[CC:Tweaked Cylinder Mining Turtle](https://github.com/Xentiles/CC-Tweaked---Cylinder-Mining-Turtle-V3):** Lua automation combining path planning, position tracking, inventory handling, and remote status reporting.

I also develop applied-AI and computer-vision projects privately where confidentiality requires it.

## Let's Talk

I'm interested in opportunities combining practical AI, software development, and thoughtful problem-solving, with people who value curiosity, clear communication, and work that can be inspected and improved.

[LinkedIn](https://www.linkedin.com/in/dominik-nagy-841002144/) · [Email](mailto:domisweden@gmail.com)
