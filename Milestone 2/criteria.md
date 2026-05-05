# Milestone 2 Criteria

**Project:** CHARLI3 Dendrite v2: DEX, Lending, P2P DeFi Data Upgrades  
**Source:** [Project Catalyst Milestone 2](https://milestones.projectcatalyst.io/projects/1400041/milestones/2)  
**Milestone Title:** Complete DEX Integrations  
**Delivery Month:** Month 2 - February 2026  
**Budget:** ADA 25,000.00 (25% of total project budget)  
**Project Completion:** 50%

---

## Milestone Outputs

### 1. Complete Integration of All Confirmed DEX Partners
Complete integration of ALL DEX confirmed partners from the Milestone 1 Technical Project Report's confirmed partners list.

**DEX Partners Scoped to Milestone 2** (from Milestone 1 confirmed partners):
1. Djed (Algorithmic Stablecoin, treated as limit-order DEX)
2. ChadSwap (DEX)
3. SaturnSwap (DEX)

> Note: WizardSwap and Cardano Swaps are confirmed DEX partners but scoped to the Final Milestone due to their P2P DeFi nature. See Milestone 1 Technical Project Report Section 2.2 for the full integration timeline.

### 2. Update Technical Project Report
Update the **Technical Project Report** living document with all milestone outputs and any third party issues that occurred during the milestone. The update must include:

#### New Section: "DEX Integrations"
- List of confirmed partners
- Confirmation that integration was successful or unsuccessful for each partner

#### If Any Integration Is Unsuccessful Due to Third-Party Issues
- Update the Integration Issues List with details on what's causing the delay or problem
- Propose alternative integrations to replace the blocked integration
- Confirm whether the integration was successfully replaced with another partner
- Continue replacement attempts until market alternatives are exhausted
- If no substitute exists, provide a plan for future milestones to revisit the integration

> **Definition — "Third-party issues":** Anything preventing integration with a partner that is beyond the control of the project team (e.g., DEX no longer exists, refuses to provide details required for integration, etc.).

> **Proposal Clause (verbatim):** If any issues occur with our list of integration partners (e.g., their protocol goes down, system updates occur, or black swan events) that prevent or delay us from integrating, we will update the Technical Project Report "Integration Issues" section with details preventing integration and a timeline for integrating them in the future. The Technical Project Report will be updated on every milestone if necessary.

### 3. Create Demo Video
Demo video completed and publicly available showcasing progress toward integrations. The video must show **all integrations required for this milestone**.

---

## Acceptance Criteria

### ✓ All Confirmed DEX Partners Integrated
- All DEX partners on the Milestone 1 confirmed partners list scoped to Milestone 2 must be integrated
- Any unsuccessful integrations must follow the third-party-issue handling protocol above

### ✓ Technical Project Report Updated
Document must include at minimum:
1. **DEX Integrations section** with the list of confirmed partners and success/failure status for each
2. **Integration Issues / Risks updates** capturing any third-party issues encountered during the milestone
3. **Replacement plans** for any blocked integrations, where applicable

### ✓ Demo Video Completed and Publicly Available
- Video shows successful data requests from **all** integrations required for the milestone
- Hosted on a publicly accessible platform (YouTube, Google Drive, Vimeo, or similar)

---

## Evidence of Milestone Completion

### Required Evidence Items:

1. **Demo Video**
   - Publicly available on YouTube, Google Drive, Vimeo, or another suitable platform
   - Shows successful requests for data from **all** new integrations required for this milestone

2. **Link to GitHub Repo**
   - Link to the repository (or specific PR/commit) showing the integration work performed during this milestone

3. **Link to Updated Technical Project Report**
   - Format remains the same as Milestone 1 (PDF or other suitable format)
   - Hosted publicly on Google Drive, GitHub, or another suitable source

---

## Important Notes

**Living Document:**  
The Technical Project Report is a single living document at the repo root: [`/technical-project-report.md`](../technical-project-report.md). Each milestone updates the same file in place rather than producing a new one. Prior milestone versions are preserved via git history.

**Third-Party Issue Handling:**  
The contingency clause from the original proposal applies — if integration partners experience issues outside the project team's control, the team will document these in the Integration Issues section, propose alternatives, and provide future-milestone plans where no substitute exists.
