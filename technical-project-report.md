# Technical Project Report
## CHARLI3 Dendrite v2: DEX, Lending, P2P DeFi Data Upgrades
### Milestone 2: Complete DEX Integrations

> This is the living Technical Project Report carried forward from Milestone 1. Sections 1–3 record outreach, confirmed partners, and risks captured at the close of Milestone 1. Section 4 is new for Milestone 2 and records the outcome of DEX integration work.

---

## Section 1: Outreach Details

### 1.1 Integration Partners (7 Total - Exceeds Minimum of 6)

**Summary:** We have successfully identified and are working with 7 integration partners, exceeding the minimum requirement of 6. This includes 4 DEXs (2 with P2P DeFi capabilities), 1 algorithmic stablecoin, and 2 lending protocols.

#### Partner 1: WizardSwap (DEX, P2P DeFi)

**Contact Information:**
- Contact Person: Bamba
- Contact Method: Discord
- Date of First Contact: November 2025
- Date of Last Contact: January 2026

**Communication Summary:**

- Received Wizard orders integration guide (PDF)
- Commitment to support development
- Reference transactions on preview testnet

**Response Status:**
- [x] Received initial response
- [x] Provided integration details
- [x] Confirmed interest in integration
- [ ] No response received

**Integration Blockers:**
- [x] None identified
- [ ] Unresponsive partner
- [ ] Partner no longer exists
- [ ] Not providing necessary technical details
- [ ] Other: [Specify]

**Inclusion Decision:**
- [x] Yes - Including in project
- [ ] No - Not including in project

**Rationale:** WizardSwap will be integrated as a part of the P2P milestone due to the nature of contracts.

**Technical Requirements Provided:**
- [x] Smart contract addresses
- [x] Test transaction hashes
- [ ] Other: [Specify]

---

#### Partner 2: ChadSwap (DEX)

**Contact Information:**
- Contact Person: Cash
- Contact Method: Discord 
- Date of First Contact: August 2025
- Date of Last Contact: August 2025

**Communication Summary:**

- Received transaction diagrams
- Received complete documentation on validators
- Received datum structures
- Received contract address

**Response Status:**
- [x] Received initial response
- [x] Provided integration details
- [x] Confirmed interest in integration
- [ ] No response received

**Integration Blockers:**
- [x] None identified
- [ ] Unresponsive partner
- [ ] Partner no longer exists
- [ ] Not providing necessary technical details
- [ ] Other: [Specify]

**Inclusion Decision:**
- [x] Yes - Including in project
- [ ] No - Not including in project

**Rationale:** ChadSwap will be integrated as a part of the DEX integrations. Although they advertise as a P2P trading platform, they meet the specific requirements of a DEX since funds are deposited into a contract that a users signing key does not have direct ownership over.

**Technical Requirements Provided:**
- [x] Smart contract addresses
- [x] Test transaction hashes
- [ ] Other: [Specify]

---

#### Partner 3: SaturnSwap (DEX)

**Contact Information:**
- Contact Person: decimalist
- Contact Method: X (aka Twitter)
- Date of First Contact: August 2025
- Date of Last Contact: January 2026

**Communication Summary:**

- Received docs for limit orders
- Received graphQL information for liquidity pools

**Response Status:**
- [x] Received initial response
- [x] Provided integration details
- [x] Confirmed interest in integration
- [ ] No response received

**Integration Blockers:**
- [x] None identified
- [ ] Unresponsive partner
- [ ] Partner no longer exists
- [ ] Not providing necessary technical details
- [ ] Other: [Specify]

**Inclusion Decision:**
- [x] Yes - Including in project
- [ ] No - Not including in project

**Rationale:** SaturnSwap will be a part of the DEX integrations.

**Technical Requirements Provided:**
- [x] Smart contract addresses
- [x] Test transaction hashes
- [x] Pool information
- [ ] Other: [Specify]

---

#### Partner 4: Cardano Swaps (DEX, P2P DeFi)

**Contact Information:**
- Contact Person: Rusty, aka Fallen Icarus
- Contact Method: Discord
- Date of First Contact: August 2025
- Date of Last Contact: January 2026

**Communication Summary:**

- Personal commitment to advise on integration
- Provided link to open source contracts

**Response Status:**
- [x] Received initial response
- [x] Provided integration details
- [x] Confirmed interest in integration
- [ ] No response received

**Integration Blockers:**
- [x] None identified
- [ ] Unresponsive partner
- [ ] Partner no longer exists
- [ ] Not providing necessary technical details
- [ ] Other: [Specify]

**Inclusion Decision:**
- [x] Yes - Including in project
- [ ] No - Not including in project

**Rationale:** Cardano Swaps (aka Cardano DeFi Kernel) will be added as a part of the P2P DeFi milestone.

**Technical Requirements Provided:**
- [x] Smart contract addresses
- [x] Test transaction hashes
- [ ] Other: [Specify]

---

#### Partner 5: Djed (Algorithmic Stablecoin)

**Contact Information:**
- Contact Person: Kylix
- Contact Method: Discord
- Date of First Contact: August 2025
- Date of Last Contact: January 2026

**Communication Summary:**

- Received repository for OpenDjed JavaScript SDK

**Response Status:**
- [x] Received initial response
- [x] Provided integration details
- [x] Confirmed interest in integration
- [ ] No response received

**Integration Blockers:**
- [x] None identified
- [ ] Unresponsive partner
- [ ] Partner no longer exists
- [ ] Not providing necessary technical details
- [ ] Other: [Specify]

**Inclusion Decision:**
- [x] Yes - Including in project
- [ ] No - Not including in project

**Rationale:** Will be integrated as a part of the DEX milestone. Even though it has different rules as a DEX, it can effectively be treated as a limit order.

**Technical Requirements Provided:**
- [x] Smart contract addresses
- [x] Test transaction hashes
- [ ] Other: [Specify]

---

#### Partner 6: Fluid Tokens (Lending Protocol)

**Contact Information:**
- Contact Person: Raul
- Contact Method: Discord
- Date of First Contact: January 2026
- Date of Last Contact: January 2026

**Communication Summary:**

- Reached out to me about an integration
- Provided access to open source contracts
- Provided access to documentation for integration

**Response Status:**
- [x] Received initial response
- [x] Provided integration details
- [x] Confirmed interest in integration
- [ ] No response received

**Integration Blockers:**
- [x] None identified
- [ ] Unresponsive partner
- [ ] Partner no longer exists
- [ ] Not providing necessary technical details
- [ ] Other: [Specify]

**Inclusion Decision:**
- [x] Yes - Including in project
- [ ] No - Not including in project

**Rationale:** Replacement for Liqwid. Provides lending protocol functionality.

**Technical Requirements Provided:**
- [x] Smart contract addresses
- [x] Test transaction hashes
- [ ] Other: [Specify]

---

#### Partner 7: Danogo (Lending Protocol)

**Contact Information:**
- Contact Person: Binh
- Contact Method: Telegram
- Date of First Contact: August 2025
- Date of Last Contact: January 2026

**Communication Summary:**

- Provided access to documentation for integration

**Response Status:**
- [x] Received initial response
- [x] Provided integration details
- [x] Confirmed interest in integration
- [ ] No response received

**Integration Blockers:**
- [x] None identified
- [ ] Unresponsive partner
- [ ] Partner no longer exists
- [ ] Not providing necessary technical details
- [ ] Other: [Specify]

**Inclusion Decision:**
- [x] Yes - Including in project
- [ ] No - Not including in project

**Rationale:** Additional lending protocol partner. Having 2 lending protocols provides redundancy and expands data coverage.

**Technical Requirements Provided:**
- [x] Smart contract addresses
- [x] Test transaction hashes
- [ ] Other: [Specify]

---

### 1.2 Partners from Original Proposal Not Included

#### Liqwid (Lending Protocol) - DECLINED

**Contact Information:**
- Contact Person: Kylix
- Contact Method: Discord
- Date of Contact: January 2025

**Reason for Non-Inclusion:**
Liqwid declined to participate in the integration at this time.

**Replacement Strategy:**
Replaced with two lending protocol partners (Fluid Tokens and Danogo) to ensure robust lending protocol data coverage and redundancy.

## Section 2: Confirmed Partners

### 2.1 Final Integration Partners List

Based on the outreach activities and responses received, the following partners have been confirmed for integration in this project:

1. **WizardSwap** - DEX, P2P DeFi
   - Status: Confirmed
   - Expected Completion: Final Milestone (P2P DeFi Integrations)

2. **ChadSwap** - DEX
   - Status: ✅ Integrated (Milestone 2)
   - Expected Completion: Milestone 2 (Complete DEX Integrations)

3. **SaturnSwap** - DEX
   - Status: ✅ Integrated (Milestone 2)
   - Expected Completion: Milestone 2 (Complete DEX Integrations)

4. **Cardano Swaps** - DEX, P2P DeFi
   - Status: Confirmed
   - Expected Completion: Final Milestone (P2P DeFi Integrations)

5. **Djed** - Algorithmic Stablecoin
   - Status: ✅ Integrated (Milestone 2)
   - Integration Started: Milestone 1 (Initial DEX Work - partial implementation exists)
   - Expected Completion: Milestone 2 (Complete DEX Integrations - treated as limit order DEX)

6. **Fluid Tokens** - Lending Protocol
   - Status: Confirmed
   - Expected Completion: Milestone 3 (Lending Protocol Integrations)

7. **Danogo** - Lending Protocol
   - Status: Confirmed
   - Expected Completion: Milestone 3 (Lending Protocol Integrations)

**Total Confirmed Partners:** 7 (Exceeds minimum requirement of 6)

**Partner Type Breakdown:**
- DEXs: 4 (2 with P2P DeFi capabilities)
- Algorithmic Stablecoin: 1
- Lending Protocols: 2

### 2.2 Integration Timeline

| Partner | Type | Milestone 1 | Milestone 2 | Milestone 3 | Final Milestone |
|---------|------|-------------|-------------|-------------|-----------------|
| Djed | Stablecoin (as DEX) | ✅ Initial Work | ✅ Complete | - | - |
| ChadSwap | DEX | Contact | ✅ Complete | - | - |
| SaturnSwap | DEX | Contact | ✅ Complete | - | - |
| Fluid Tokens | Lending | Contact | - | ✅ Complete | - |
| Danogo | Lending | Contact | - | ✅ Complete | - |
| WizardSwap | DEX, P2P DeFi | Contact | - | - | ✅ Complete |
| Cardano Swaps | DEX, P2P DeFi | Contact | - | - | ✅ Complete |

**Milestone Breakdown:**
- **Milestone 1 (Jan 2026):** Contact all partners + Initial DEX integration (Djed - partial implementation)
- **Milestone 2 (Feb 2026):** Complete DEX Integrations (Djed, ChadSwap, SaturnSwap)
- **Milestone 3 (Mar 2026):** Lending Protocol Integrations (Fluid Tokens, Danogo)
- **Final Milestone (Apr 2026):** P2P DeFi Integrations (WizardSwap, Cardano Swaps)

### 2.3 Partner Changes from Original Proposal

| Original Partner | Status | Replacement/Action |
|-----------------|--------|-------------------|
| Liqwid | ❌ Declined | Replaced with Fluid Tokens and Danogo |
| Flow | ❌ Not included | Replaced with Cardano Swaps |
| - | ✅ Added | Danogo added as 7th partner (exceeds minimum) |

---

## Section 3: Integration Issues / Risks

### Current Issues

No critical issues identified at this time. All 7 integration partners have been successfully contacted and have provided necessary technical documentation. Communication channels remain open with all partners.

**Milestone 2 Update:** No new third-party issues encountered during Milestone 2. All three DEX partners scoped to this milestone (Djed, ChadSwap, SaturnSwap) were integrated without delay or blocker. The risks below remain monitored and the original mitigations remain in effect.

### Identified Risks

**Third-Party Dependency Risk:** Integration partners may become unresponsive, discontinue operations, or change technical architecture.

*Mitigation Response:* We have established redundancy by including multiple partners in each category (4 DEXs, 2 lending protocols). The milestone contingency clause allows for partner replacement if any become unavailable, and we will document any changes in the Technical Project Report.

**Technical Integration Complexity:** P2P DeFi contracts (WizardSwap, Cardano Swaps) may require different integration approaches than standard DEXs.

*Mitigation Response:* We have already received integration guides from WizardSwap and open source contracts from Cardano Swaps. Both partners have committed to providing technical support throughout the integration process.

**Protocol Upgrades:** Partners may upgrade smart contracts or modify data structures during the project timeline.

*Mitigation Response:* We maintain open communication channels with all partners to receive advance notice of changes. Our integration architecture is designed to be adaptable, with version control and documentation to manage protocol updates.

**Testnet Stability:** Cardano testnet may experience downtime or instability affecting development timelines.

*Mitigation Response:* We have received test transaction hashes from partners and can utilize multiple testnet environments (preview, preprod). If persistent issues occur, we can perform integration validation on mainnet.

**External Dependencies:** All integrations fundamentally depend on partner cooperation and continued operation.

*Mitigation Response:* Our project design includes contingency clauses for partner issues, and redundancy through multiple partners minimizes single points of failure. We will transparently document any dependency issues and timeline adjustments in the Technical Project Report.

---

## Section 4: DEX Integrations (Milestone 2)

### 4.1 Status Summary

All three DEX partners scoped to Milestone 2 from the Milestone 1 confirmed partners list have been **successfully integrated**. No third-party issues were encountered, and no replacement partners were required.

**DEX Partners Scoped to Milestone 2:**
1. Djed (Algorithmic Stablecoin, treated as limit-order DEX)
2. ChadSwap (DEX)
3. SaturnSwap (DEX)

> WizardSwap and Cardano Swaps are confirmed DEX partners but scoped to the Final Milestone due to their P2P DeFi nature. See Section 2.2 for the full integration timeline.

### 4.2 Integration Details

#### Djed (and Shen)
- **Integration Status:** ✅ Successful
- **Capabilities Demonstrated:**
  - Retrieve oracle price for Djed and Shen
  - Accurately calculate mint and burn costs (where contract rules permit mint/burn)
- **Third-Party Issues:** None
- **Code:** Merged in [PR #166](https://github.com/Charli3-Official/charli3-dendrite/pull/166)

#### ChadSwap
- **Integration Status:** ✅ Successful
- **Capabilities Demonstrated:**
  - Retrieve order book prices
- **Third-Party Issues:** None
- **Code:** Merged in [PR #166](https://github.com/Charli3-Official/charli3-dendrite/pull/166)

#### SaturnSwap
- **Integration Status:** ✅ Successful
- **Capabilities Demonstrated:**
  - Retrieve order book prices
- **Third-Party Issues:** None
- **Code:** Merged in [PR #166](https://github.com/Charli3-Official/charli3-dendrite/pull/166)

### 4.3 Third-Party Issues Encountered

**None.** All three DEX partners cooperated as expected, technical documentation provided in Milestone 1 was sufficient, and no protocol changes or outages affected the integration work.

### 4.4 Replacement Partners Required

**None.** All originally-scoped DEX integrations were completed successfully; no alternatives were required.

### 4.5 Future-Milestone Plans for Deferred Integrations

Not applicable for Milestone 2 — no DEX integrations were deferred. The scheduled deferrals for WizardSwap and Cardano Swaps to the Final Milestone are by original design (P2P DeFi nature), not the result of any blocker.

### 4.6 Evidence Links

- **Code:** [PR #166 — Charli3-Official/charli3-dendrite](https://github.com/Charli3-Official/charli3-dendrite/pull/166)
- **Demo Video:** _[To be added once uploaded]_
- **Updated Technical Project Report:** This document
