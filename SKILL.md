---
name: cursor-in-fog-easy-ui-codex-build
description: "Build visually convincing websites, product prototypes, and mini-program interfaces with Codex by separating composition, image prompting, UI rules, small-zone implementation, nine-grid asset production, typography, and verification. Use when a generic AI-generated first draft works but does not yet look complete, when mobile screens must remain fully visible, or when turning supplied visual references into an editable interface."
---

# Cursor in Fog · Easy UI Codex Build

Use this skill to turn a product idea into a buildable visual system. Keep the developer in charge of judgment; treat image generation and coding as separate tools with separate jobs.

## 1. Diagnose the draft

Inspect the existing page or brief before changing code. Name the concrete gaps:

- missing or undecided requirements;
- weak visual hierarchy;
- insufficient icons, illustrations, logos, or other assets;
- underspecified states, motion, spacing, or typography;
- missing reference material or incomplete page content.

Do not claim that Codex is incapable. A default draft is normally a useful skeleton, not a finished visual direction.

## 2. Compose before prompting

Define each page in a compact build sheet:

1. Establish the target device and logical viewport before composing the page.
2. State who is looking at the page and what they need to notice first.
3. Sketch the information hierarchy and major visual zones.
4. Decide the UI rules: palette, type roles, spacing scale, surface treatment, density, and motion restraint.
5. Turn that sheet into image-generation prompts. Generate several directions under one visual system rather than unrelated styles.

When the product is mobile, keep the supplied viewport as an acceptance target. In comparison panels, recording posters, and case-study containers, show the entire mobile screen at its correct aspect ratio. Use contain behavior and reduce the surrounding layout before considering any crop of the product screen.

Use image output as visual reference, not as a single full-page screenshot to paste into production code.

## 3. Rebuild in small visual zones

Give the coding agent one page or one or two visual zones at a time. For every handoff, specify:

- exact zones in scope;
- hierarchy and spacing to preserve;
- CSS behavior, interaction states, and motion constraints;
- asset slots to reserve;
- what must remain untouched.

Review the composition after each zone. Avoid handing an entire system and a pile of images to the agent in one prompt.

## 4. Fill the missing visual information

After the skeleton works, inspect what still feels empty. List the missing visual roles, then generate each page's supporting material as a nine-grid asset sheet.

Request separable assets with empty space around them. Ask for multiple variants when selection matters. Keep each asset sheet tied to a specific page and visual role.

Direct the coding agent to crop, remove backgrounds or mask shapes, size, and place the chosen assets. Do not ask it to fake assets that were never supplied.

## 5. Finish the type and interaction system

Choose a deliberate type pairing with explicit roles for display text, body text, labels, numbers, and metadata. Set size, weight, line-height, and contrast rules in code.

Use motion to guide attention, not to conceal missing composition. Prefer transform and opacity animations. Respect reduced-motion preferences and verify that decorative effects do not slow the page.

## 6. Verify before calling it finished

Check the output at desktop and mobile widths, including real interaction states. Confirm that the full target screen fits its presentation container, text remains readable, visual assets are correctly clipped, the hierarchy is clear without narration, and motion does not overlap the interface.

When the work refers to a real product or client, use only supplied materials and verified facts. Mark placeholders plainly. Never invent a completed feature, user result, customer, or case study.
