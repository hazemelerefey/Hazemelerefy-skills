# Hazemelerefy-skills

## Reference Website to Native Next.js

[`reference-to-next-native`](.opencode/skills/reference-to-next-native/SKILL.md) is an OpenCode skill for converting an authorized URL, static HTML export, or Framer reference into an editable Next.js/React site. It covers reference capture, asset and font inventory, responsive structure, animation and interaction reconstruction, visual comparison, and release verification. [Worked examples](.opencode/skills/reference-to-next-native/EXAMPLES.md) include observed patterns from the VO Technology project and reusable templates; the two are explicitly distinguished.

To use it in another OpenCode project, copy `.opencode/skills/reference-to-next-native/` into that project's `.opencode/skills/` directory. To make it available across projects, place the folder under `~/.config/opencode/skills/` instead. Restart OpenCode after installing a skill.

This workflow cannot guarantee a pixel-perfect match from a URL alone. Verify the permitted reference, assets, viewport and interaction states, then compare the running app against them. Do not ship copied HTML or the original Framer browser runtime as a substitute for native React components.
