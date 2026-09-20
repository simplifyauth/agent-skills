# Parked skills (SimplifyAuth fork)

These upstream skills are not loaded by the plugin (plugin.json points at `./skills` only).
They are parked, not deleted, so they can be restored with a single `git mv` when needed:

- frontend-ui-engineering, browser-testing-with-devtools, performance-optimization,
  shipping-and-launch: restore when the console UI phase starts.
- deprecation-and-migration, source-driven-development, doubt-driven-development:
  not needed for the NHI product; restore if a use appears.

Restore: `git mv skills-parked/<name> skills/<name>`
