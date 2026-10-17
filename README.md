# PulseForge

**An open-source, community-driven drum platform built for electronic drummers.**

PulseForge aims to make expressive, realistic and accessible drum software for electronic drum kits. Its development is driven by real-world playing experience, community feedback and an iterative, AI-assisted development process.

The long-term vision is not just to build another drum plugin. It is to build a platform where users can help shape the product, report problems in a reproducible way, influence priorities and benefit from continuous improvements.

## Vision

Electronic drummers deserve drum software that responds naturally to how they play.

PulseForge puts electronic drums first. Dynamics, velocity response, hi-hat behaviour, articulation, MIDI interpretation and trigger compatibility are core product concerns rather than secondary features.

The project aims to combine:

- A drum plugin with a flexible sample playback engine.
- A standalone application for playing, configuring, testing and hosting the instrument.
- A feedback workflow that lets users report problems using MIDI performances, settings and descriptions of expected versus actual behaviour.
- A community-driven process for discussing, prioritising and evaluating improvements.
- An AI-assisted development workflow that turns approved priorities into implemented, tested and reviewable changes.

## Guiding principles

### Electronic drums first

The software should be designed around the needs of electronic drummers, including expressive playing, reliable triggering, predictable MIDI handling and realistic articulation changes.

### Realistic dynamics

Ghost notes, accents, velocity layers and round robins should contribute to a natural playing experience. The goal is not merely to trigger samples, but to preserve the drummer's intent.

### Reproducible feedback

Users should be able to describe what they expected, explain what happened and, where appropriate, submit a short MIDI performance and relevant configuration to help reproduce the issue.

Feedback collection must be transparent and privacy-conscious. Users should control what they submit.

### Community-driven priorities

Community feedback, discussion and voting should help determine which problems and improvements deserve attention.

Popularity alone should not determine every decision. Product coherence, accessibility, reliability, security and technical feasibility also matter.

### AI-assisted development

AI coding agents may analyse feedback, propose plans, implement changes, create tests and prepare release candidates.

Agents should operate within explicit project rules and approved scopes. Important product decisions, security controls and release approvals must remain subject to appropriate human oversight.

### Open development

The project aims to make its goals, decisions, issues and development process transparent, enabling users and contributors to participate meaningfully.

## Initial direction

The initial development phase will focus on establishing a working foundation:

- A sample-based drum instrument.
- MIDI triggering and velocity-layer selection.
- Support for a freely distributable acoustic drum sample library.
- An initial plugin for macOS, targeting Logic Pro.
- Automated tests and a repeatable build process.

The first reference instrument is expected to be a Roland TD-17KVX electronic drum kit. Broader compatibility with other electronic drum modules is an important long-term goal.

The exact architecture, technology choices and scope of the first release remain open to investigation and validation.

## Development approach

PulseForge is intended to evolve through small, testable iterations.

Early development will be actively guided by human feedback. As the project matures, parts of the workflow may become increasingly automated:

1. Collect and analyse user feedback.
2. Identify recurring problems and improvement opportunities.
3. Propose priorities and a development plan.
4. Obtain the required human approvals.
5. Implement changes and run automated tests.
6. Review security, compatibility and release readiness.
7. Publish beta builds for evaluation.
8. Promote verified changes to a stable release after the required approvals.

Automation must not bypass project governance, security requirements or mandatory release approvals.

## Release channels

The intended product will distinguish between:

- **Stable:** verified releases intended for regular use.
- **Beta:** prerelease builds intended for testing and feedback.

Users should be able to choose whether to participate in beta testing and return to a stable release when necessary.

## Licensing and third-party assets

PulseForge is intended to be an open-source project.

The software licence and the licences of samples, libraries, tools and other third-party assets must be documented separately. Every distributed asset must have a verified source and appropriate redistribution rights.

The project must preserve applicable attribution requirements and respect the original licences of third-party material.

The definitive software licence and contribution policy will be documented in the repository.

## Current status

PulseForge is in its early exploration and planning phase.

The initial priorities are to validate the sample library, establish the repository and development workflow, define the first release and implement a small but functional prototype.

Features described as long-term goals are intentions, not promises of existing functionality.

## Contributing

Community participation is central to the long-term vision.

As the project develops, contribution guidelines will explain how to report issues, suggest improvements, participate in discussions, submit code and help test beta releases.

Constructive feedback from electronic drummers, developers, audio engineers and other interested users is welcome.

## Project philosophy

**Build for drummers. Learn from real playing. Improve through community feedback. Automate carefully. Keep humans accountable.**

PulseForge aims to demonstrate how an open-source product can be developed through a combination of community participation, AI-assisted engineering, reproducible testing and transparent human governance.
