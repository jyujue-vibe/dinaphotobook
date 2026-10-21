# Dina Prompt Library

Prompt library for generating images of **Dina**, an AI influencer character, with Google Flow / Nano Banana (character sheet used as the image ingredient) and a planned Krea 2 LoRA on RunPod.

234 prompts (v3), each built from a real Instagram reference photo's outfit, pose, camera, lighting and setting — rewritten in the "working prompts" formula:

- Extreme pear-shaped hourglass figure spec asserted at the opening and re-asserted from the camera's actual angle
- Pose written as body mechanics (weight placement, hip/shoulder angles, hand positions) inside a candid in-between moment
- Outfit described garment by garment, including how the fabric behaves on the figure
- Anti-normalization clause (proportions are never flattened, compressed or minimized)
- Fixed footer on every prompt: face preservation from the reference sheet, micro-detail block, cinematic lighting, 8K, Ratio 3:4
- The subject is never named in a prompt — only "a woman" / "she"

## Files

| File | Contents |
|---|---|
| `prompts_v3.md` | All 234 v3 prompts, readable |
| `prompts_v3.json` | Same prompts as JSON (id, account, file, spicy, tags, prompt) |
| `all_entries.json` | Full analysis data per entry, including v1 and v2 prompt versions |
| `V3_SPEC.md` | The v3 writing spec the prompts were produced from |

## Stats

- 234 entries from 6 reference accounts: realjennycoox (10), sueainsi_ (13), lex_jariya (56), aommwarang (42), vjessna (65), nangaomyingkham (48 kept of 60 — face-visible posing shots only, per selection rule)
- Spicy levels: none 134 / mild 84 / spicy 16 (kept as-is; spicy entries are for paid platforms, the rest are Instagram-safe)
- v3 word counts: 420–597 per prompt (avg 483)

The character reference sheet and the reference photos themselves are not stored in this repo — only the prompt texts and analysis data.
