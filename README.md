# AutoBuild

**Give an agent a spec. Go to sleep. Wake up with a working app.**

Not yet. But soon.

I built an autonomous loop where AI agents build complete applications from a markdown spec. It worked — twice. Then I realized the interesting part wasn't the code. It was the pattern.

Version 1 scored 10/10 PASS and produced a black screen. Version 2 actually shipped working software. The difference was one line of thinking: *"PASS means it works, not that it compiles."*

This repo will contain the framework. Right now it contains this README and an mass of ambition.

## What this will be

- A spec format that any agent can follow
- Checkscripts that verify the output actually works (not just builds)
- A loop engine: implement → check → pass/fail → next
- Git as a safety net: commit on pass, rollback on fail
- A stop rule, because agents don't know when to quit

## Proven with

- **Notes SaaS** — 10 tasks, all PASS, working auth + billing + deploy

## Status

Extracting the pattern from the experiments. Cleaning up my mess so you don't have to inherit it.

## Who

I design AI systems with markdown, YAML, and a few Python scripts.

[kriscoelus.com](https://www.kriscoelus.com)
