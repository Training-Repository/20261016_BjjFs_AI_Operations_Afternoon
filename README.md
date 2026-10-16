# M365 Copilot Training — Operations Team (Bajaj Finance Limited)

Training materials for a Microsoft 365 Copilot enablement session for the Bajaj Finance Limited (BFL) Operations team, delivered by Technizer India under the **GenAI for Enterprise Teams** program.

The session covers prompt engineering (meta-prompting, RTCFT framework), Copilot in Excel (formulas, pivot tables), the end-to-end flow from a raw data file to a leadership-ready deck, using Copilot Notebooks to work across more files than the chat attachment limit, and turning a large document into a formatted PDF.

## Contents

| File | Description |
|---|---|
| [`MetaPrompting_Guide_Ops_BFL.md`](MetaPrompting_Guide_Ops_BFL.md) | Introduces meta-prompting — asking Copilot to write your prompt for you. Includes 5 ready-to-use meta-prompts for Ops use cases (SOP review, incident analysis, performance reporting, workflow optimization, stakeholder comms). |
| [`OpsTeam_Copilot_ParticipantGuide.md`](OpsTeam_Copilot_ParticipantGuide.md) | Participant guide built around the **RTCFT** (Role–Task–Context–Format–Tone) prompt framework, with step-by-step meta-prompt + working-prompt pairs for the same 5 use cases, plus an FAQ. |
| [`BFL_BranchOps_CopilotExcel_Participant_Guide.md`](BFL_BranchOps_CopilotExcel_Participant_Guide.md) | Hands-on exercises for Copilot in Excel — writing formulas (escalation flags, SLA breach, pending days, TAT category), explaining formulas, and building pivot tables on branch operations data. |
| [`BFL_BranchOps_Excel_CopilotChat_Guide.md`](BFL_BranchOps_Excel_CopilotChat_Guide.md) | Same Excel formula and pivot exercises **without Excel Agent / Edit with Copilot** — for Copilot Chat (Basic) users, using an RTCFT meta-prompt, manual apply, and expected results to verify. |
| [`Excel_To_PowerPoint.md`](Excel_To_PowerPoint.md) | "AI at Work" workbook describing a 9-step Copilot flow — across three chats (Discovery, Execution, PowerPoint agent) — for turning any file into an analysis, a Word document, and a leadership deck. |
| [`Copilot_Notebooks_Guide.md`](Copilot_Notebooks_Guide.md) | Using Copilot Notebooks as a persistent workspace — add all files once as references, set standing instructions, and query across more files than the 3-attachment chat limit. |
| [`copilot-pdf-playbook.md`](copilot-pdf-playbook.md) | Repeatable process for turning a large document into a formatted PDF using Copilot and Word, with a monthly Ops review pack as the example. |
| [`OpsTeam_Copilot_Training_Dataset.xlsx`](OpsTeam_Copilot_Training_Dataset.xlsx) | Practice dataset for the meta-prompting exercises. Sheets: SOP Register, Incident Log, Ops Performance Report, Workflow Analysis, Stakeholder Comms Log. |
| [`BFL_BranchOps_Copilot_Demo.xlsx`](BFL_BranchOps_Copilot_Demo.xlsx) | Practice dataset for the Excel exercises — 25 rows of branch operations cases with columns left blank for participants to fill in using Copilot-generated formulas. |
| [`Contact.md`](Contact.md) | Trainer contact details. |

## How to use this material

1. Start with the meta-prompting guides (`MetaPrompting_Guide_Ops_BFL.md` or `OpsTeam_Copilot_ParticipantGuide.md`) to learn the RTCFT framework and generate working prompts against `OpsTeam_Copilot_Training_Dataset.xlsx`.
2. Move to `BFL_BranchOps_CopilotExcel_Participant_Guide.md` for hands-on formula and pivot table exercises using `BFL_BranchOps_Copilot_Demo.xlsx` (requires a Microsoft 365 Copilot licence).
   - **Basic licence / Copilot Chat only?** Use `BFL_BranchOps_Excel_CopilotChat_Guide.md` instead — same exercises, no Agent required.
3. Finish with `Excel_To_PowerPoint.md` to practice the full 9-step flow from raw file to analysis, document, and deck.
4. Use `Copilot_Notebooks_Guide.md` to move all of the above into a single Copilot Notebook — no re-attaching, no 3-file limit.
5. Keep `copilot-pdf-playbook.md` for when a review pack or SOP manual needs to go out as a PDF.

## Requirements

- Microsoft 365 Copilot (Copilot Chat and Copilot in Excel/PowerPoint) — **or**, for Basic licence users, Copilot Chat only (see `BFL_BranchOps_Excel_CopilotChat_Guide.md`)
- Access to Copilot Notebooks in the M365 Copilot app (for `Copilot_Notebooks_Guide.md`)
- Excel files uploaded to OneDrive so they can be attached in Copilot Chat

---

*Delivered by Technizer India | GenAI for Enterprise Teams*
