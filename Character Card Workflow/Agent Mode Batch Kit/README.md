# Agent Mode Batch Kit for SillyTavern Character Production

This kit packages the Agent Mode configuration and templates you asked for so you can spin up high-volume SillyTavern character batches without hunting through past chats. The bundle lives inside the **Character Card Workflow** directory so it stays alongside your definitive Tool playbooks.

## Folder Contents
| File | Purpose |
| --- | --- |
| `system_message_prompt.md` | Copy/paste System Message for GPT Agent Mode. Embeds the full multi-step production workflow, Tool references, and collaboration etiquette. |
| `kickoff_form.txt` | Intake form to gather the batch brief from your user before production starts. |
| `trend_radar_template.md` | Template for logging research from Chub.ai before you draft the batch slate. |
| `batch_output_template.md` | Packaging format for each character bundle plus dashboard notes. |

## Quickstart
1. **Open GPT Agent Mode** (in ChatGPT Canvas, Claude Artifact, etc.).
2. Create a new Agent configuration and paste the entire contents of `system_message_prompt.md` into the **System Message** field.
3. Save the Agent.
4. When you initiate a session, paste the text from `kickoff_form.txt` to collect the user brief.
5. Research trends with the `trend_radar_template.md` at hand. Populate it manually while scouting Chub.ai so you have evidence for the slate.
6. Once the batch slate is approved, follow the loop outlined in the System Message. Use `batch_output_template.md` to keep each character’s deliverables consistent when you export or share results.

## Tips for Smooth Runs
- Keep one master document per character, appending Tool outputs in order. (The System Message enforces this but it helps to remember!)
- When the user reserves specific character concepts, mark those slots in the batch slate before filling the rest with trend-driven picks.
- Refresh your Trend Radar if the session spans multiple days so you don’t miss shifts on Chub.ai.
- Deliver the final batch with a dashboard summary first, then each character package using the provided template.

This kit is ready for you to zip, share, or drop straight into your workflow.
