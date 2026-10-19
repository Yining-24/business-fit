# Business Fit

A self-contained Codex skill for discovering, brainstorming, researching and testing businesses suited to your abilities, resources, constraints and goals. Supports starting from scratch and evaluating existing ideas.

## Install

Copy the complete `business-fit/` directory into `~/.agents/skills/`. Restart Codex if it does not appear. No source skills or special connectors are required.

## Personal profile

Keep your profile outside this repository. Supply its path in the conversation, or create `~/.codex/business-fit/profile-config.md` pointing to a private background document and optional constraints/goals note. A generic template is included at `business-fit/references/profile-template.md`. Missing profile access is disclosed rather than assumed.

## Usage

- `$business-fit Read my profile and brainstorm realistic businesses. Ask only for missing facts that change the shortlist.`
- `$business-fit Evaluate [idea]. Research alternatives and compare my ability to build, sell and operate it.`
- `$business-fit Design a willingness-to-pay test for [offer] within [time] and [budget], with thresholds and next decisions.`

## Validation

Skill-creator structural validation passed; all 11 relative references resolve. Independent synthetic tests covered brainstorming from scratch and an existing AI app idea. Neither test is evidence of real customer demand. No personal background, private configuration or credentials are included.

## Attribution and licenses

See [sources](business-fit/references/sources.md) for verified upstream paths, pinned revisions and adaptations. Anthropic product-management Apache 2.0 terms are included. Founder Skills declares MIT but lacked full license text in the inspected checkout; its prose, code and templates were not copied.
