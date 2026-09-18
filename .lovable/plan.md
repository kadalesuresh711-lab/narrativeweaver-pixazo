# Faster, authentic comic-book generation

## Changes
- Replace the vivid anime-leaning colour direction with a restrained 1990s American print-comic palette: limited muted inks, off-white paper, heavy black shadows, flat colour separations, coarse halftone, and minimal highlights.
- Keep medium and wide framing only, while removing visual cues that encourage glossy anime rendering.
- Generate scene descriptions in consecutive batches of exactly 15 timestamps, with missing descriptions retried in groups of up to 15.
- Increase the drawing queue to ten simultaneous lanes so all ten configured Pixazo keys receive work in parallel; keep one active render per key to avoid throttling.
- Update saved-run versioning so new generations cannot reuse earlier anime-coloured prompts or images.
- Verify the prompt batching, key distribution, and generation flow with focused checks.

## Technical details
- Update the fixed renderer style and colour wording in `src/lib/manga.server.ts`.
- Set `PROMPT_RANGE` to 15 and `IMAGE_CONCURRENCY` to 10 in the generation page.
- Set the server-side Pixazo lease limit to one render per key and correct its documentation.
- Update the roadmap to reflect the requested generation configuration.
