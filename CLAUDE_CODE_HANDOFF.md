# Claude Code Handoff

## Runtime (honest)
`SCRIPT_LOCKED.md` has about 827 spoken words (840 words including the title). At 130–150 wpm, that is **5.5–6.4 min** of speech. With natural pauses on the beat transitions, expect **about 6–6.8 min**. That is below the 7–9 min target. Do not pad. Measure the real voice track.

## Build order
1. Build a design system for the 1920×1080 frame. Use large type (≥48 px body, ≥72 px keywords) so it reads on a phone, a neutral palette and one accent colour for "condition/warning". Add a fixed **ILLUSTRATIVE EXAMPLE** corner badge.
2. Build the reusable components:
   - Mock chat message (fictional names, no Slack logo)
   - Mock document
   - AI answer card
   - Prompt card
   - Four-step route bar (Prompting → Research → Automation → Agents; agents greyed "later")
   - Workflow node diagram (Form → Trigger → Sheet)
   - Spreadsheet grid
   - File list with a "couldn't open" state
   - DRAFT stamp
   - Checklist with ✓/⚠
3. Build the Friday/Tuesday motif. The two date chips (A01) plus the condition tag "only if testing is done" recur in beats 01, 04, 06, 15 and 16.
4. Assemble beats 01–22 in order from `shot_asset_map.csv`. Align them to the narration anchors.
5. Run QA: check the illustrative badge on every mock, check that no real logos, vendors or prices appear, and check credits (A09 only if used).

## Icons available (`assets/`, redistributable)
- A01 calendar
- A02 magnifier
- A03 spreadsheet
- A04 document
- A05 warning
- A06 new message
- A07 robot (CC0)
- A08 checkmark
- A09 robot (OpenMoji, CC BY-SA 4.0, credit required)

## Illustrative, not real tests
All of these scenes are illustrative. None of them shows a real test, product UI or integration run:
- Slack thread
- Google Doc
- ChatGPT/AI answers
- Manager update
- Pricing comparison (fictional Vendor A)
- Make/Zapier/n8n workflow and form test entries
- Spreadsheet rows
- App connection panel
- Agent search, the revised schedule file and the evidence trail

Show Make, Zapier and n8n as plain text names only.

## Missing visuals
No external photo or video was found that suits beats 01–22 better than original graphics. Every beat relies on GFX-xx original graphics, and the icons are only accents. No b-roll was selected, because the brief rules out a generic typing montage. If b-roll is wanted, take Pexels footage locally only (VIDEO_USE_ONLY) and record each clip URL.
