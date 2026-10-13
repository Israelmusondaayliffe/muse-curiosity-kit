# Muse Curiosity Kit

26 independent skills for research, writing, decisions, software, creative work and projects. Each skill carries its own complete methods and supporting resources. Start with **Chief of Staff** when you want help choosing an approach, or select a specialist directly.

Original contributions use the [MIT License](LICENSE). Third-party components retain their own terms; see [licensing](LICENSING.md) and [readiness](READINESS.md).

## Download for Muse

The easiest route is to give Muse the [public repository link](https://github.com/Israelmusondaayliffe/muse-curiosity-kit) and ask it to download the kit. You do not need to use a terminal or download a ZIP yourself. Copy this into Muse:

```text
Download Muse Curiosity Kit from https://github.com/Israelmusondaayliffe/muse-curiosity-kit into a separate folder. Read its Muse setup instructions and explain how installation would work in my account. Do not change my existing skills or settings yet.
```

**ZIP option:** [Download the ZIP](https://github.com/Israelmusondaayliffe/muse-curiosity-kit/archive/refs/heads/main.zip). You can also open this page's **Code** menu and choose **Download ZIP**. If Muse cannot download files in your current session, download the ZIP yourself and attach it to Muse if your session supports file attachments. Ask Muse to unpack it in a separate folder and read the setup instructions.

### Downloading versus installing

**Downloading** saves a copy of the skill files. **Installing** puts those files where your Muse account loads skills, then checks that Muse can read each skill and its supporting files.

Downloading, unpacking a ZIP or attaching it to a chat does not install the kit. When you are ready, ask Muse to install the downloaded kit while preserving your existing skills and settings. It should identify your account's actual skill folder, check for existing files before changing them, and verify that the new skills can load. The kit does not include an automatic Muse installer; see the [Muse setup guide](adapters/muse/README.md).

## Use in Muse

Use Muse's actual installed skill catalog. Select a skill by its technical name, such as `chief-of-staff`, `writing-like-me` or `coding-studio`, then describe the result you want and the material it may use. Read the selected entry and supporting files from that skill's real directory.

> Use Chief of Staff to turn these project notes into a one-page team update. Keep decisions separate from open questions, preserve the dates and save a draft here.

> Use Writing Like Me to turn these notes into an article. Use the two supplied pieces as voice references, keep the argument mine and flag unsupported claims.

A name appearing in a catalog does not establish that every support file or tool is accessible. Confirm the account's actual skill root and refresh behavior when installing or updating. This candidate supplies skill files; it does not provide a Muse plugin installer or change your host instructions, memory or existing work. Read the [Muse guide](adapters/muse/README.md).

Selecting a method does not authorize sending, publishing, installing, scheduling or changing an account. AI Film, Gauntlet, the Matt library, Operating Graph and ProofLoop require affirmative selection. Chief of Staff asks before choosing protected methods unless you already selected them. Quoted or incidental mentions do not activate work.

## The skills

| Work | Skills |
|---|---|
| Choose and investigate | [Chief of Staff](skills/chief-of-staff/SKILL.md), [Strategy Room](skills/strategy-room/SKILL.md), [Knowledge Work Superpowers](skills/knowledge-work-superpowers/SKILL.md), [Last30Days](skills/last30days/SKILL.md), [Founder Revenue Engine](skills/founder-revenue-engine/SKILL.md), [Matt library](skills/matt-pocock-knowledge-work/SKILL.md) |
| Write and create | [Writing Like Me](skills/writing-like-me/SKILL.md), [Explanation Studio](skills/explanation-studio/SKILL.md), [Guide Production Studio](skills/guide-production-studio/SKILL.md), [Data Storytelling Studio](skills/data-storytelling-studio/SKILL.md), [Visual Production Studio](skills/visual-production-studio/SKILL.md), [AI Film](skills/ai-film-studio/SKILL.md) |
| Build tools | [Coding Studio](skills/coding-studio/SKILL.md), [Web Product Studio](skills/web-product-studio/SKILL.md), [Harness Engineering](skills/harness-engineering/SKILL.md), [Model Prompt Lab](skills/model-prompt-lab/SKILL.md), [Agent Ops](skills/agent-ops/SKILL.md) |
| Carry work through | [Outcome Engine](skills/outcome-engine/SKILL.md), [LoopKit](skills/loopkit/SKILL.md), [Operating Graph](skills/operating-graph/SKILL.md), [Gauntlet](skills/gauntlet/SKILL.md), [ProofLoop](skills/proofloop/SKILL.md), [Loop Observatory](skills/loop-observatory/SKILL.md) |
| Preserve and learn | [Continuity Vault](skills/continuity-vault/SKILL.md), [Memory](skills/memory/SKILL.md), [Practice Compiler](skills/practice-compiler/SKILL.md) |

## LoopKit and Memory

LoopKit supports truthful `host: muse` contracts and manual selection, status, checkpoint and resume. On a new conversation, read the exact selected run, current snapshot and artifacts before continuing. Resume uses the current generation; stale state or an uncertain pending effect stops work until reconciled. Read the [manual route](skills/loopkit/references/binding.md#personal-muse-manual-route).

Automatic Muse startup/compaction hooks are unsupported. The hook command refuses Muse before reading input or touching state. A timer or cron is not a lifecycle hook.

Memory requires the external Claude Mem engine and a supported public-tool integration. That engine is not included, and Memory remains inactive when it is absent. Muse's own memory is not automatically substituted. The complete recall, continuity and health methods remain for a genuinely supported integration.

## Requirements and data handling

Your host supplies models, permissions, file access, workers and connected services. Most local helpers require Python 3.9 or later; Memory's health helper requires Python 3.11. Browser checks, media rendering and generation require the actual tools named by the selected method. Prompt preparation does not generate media. A required independent reviewer must be a real separate reviewer.

Some visual methods need supplied licensed textures, sound clips or fonts. Uncleared source assets are excluded; texture, audio timing and typography methods remain. Missing required inputs are reported honestly.

Selected workflows can read authorized task files and create drafts, research records, logs, checkpoints or reviewed learning records. These can contain sensitive information and persist until you or the environment removes them. The kit supplies no universal deletion deadline. Keep private task data out of reusable skill directories.

Your host and selected external services process content through their own tools and policies. Requested visual workflows may transmit selected prompts or references to a provider. Some HTML templates request GSAP from jsDelivr when opened. Review the destination before sending sensitive material; selecting a skill does not authorize transmission.

## Other target hosts and building

Useful Codex and Claude Code methods and distributions remain for explicitly selected targets. They do not establish Muse loading or automatic hook support. From this checkout, use the selected host's native commands when installation is separately requested:

```sh
codex plugin marketplace add .
codex plugin add muse-curiosity-kit@muse-curiosity-kit

claude plugin marketplace add .
claude plugin install muse-curiosity-kit@muse-curiosity-kit
```

Check installation, enabled state and fresh skill loading separately. Hook registration, trust and observed execution are different states. No public repository URL is assumed.

Build combined and standalone target packages with the existing builder:

```sh
python3 -B build/package.py --out /absolute/owned/output
```

Source methods live in `skills/`; `adapters/` holds target metadata. Keep generated packages aligned with the same source. See [contributor notes](AGENTS.md).

## Credits

Credited methods and components include Pstack/Poteto Mode, Matt Pocock, GStack, Ponytail, REA, Claude Mem and the creators identified in skill-local notices. Preserve their licenses and attribution. Public creator names identify authors, not personal defaults for the user. Font, vendor and other asset terms remain scoped; see [licensing](LICENSING.md).
