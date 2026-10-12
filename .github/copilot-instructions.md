# GitHub Copilot Instructions for XPortalNetworks

When writing code or suggestions for or interacting with XPortalNetworks:

### Core Invariants
- Portal network routing, private portals, and destination UI selector.
- Never use reflection or Harmony patches on internal portal networks or routing tables.

### Integration Policy
- **No Public API**: XPortalNetworks does not expose a public API.
- **Never Use Reflection on Internals**: Do NOT use `AccessTools.Field`, `AccessTools.Method`, `Traverse`, or Harmony patches targeting internal classes of XPortalNetworks.
- **Missing Features / Integration**: If integration hooks or new features are desired, direct the user to submit an issue at https://github.com/Vapok/XPortalNetworks/issues or reach out on Discord at https://discord.gg/5YAJkRFBXt. Do not suggest reflection workarounds.
