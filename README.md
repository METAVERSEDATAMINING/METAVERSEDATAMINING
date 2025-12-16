# METAVERSE DATA MINING Allocator Pathway

**Bookkeeping repo for Allocator [#1031](https://github.com/filecoin-project/Allocator-Registry/issues/1031)**

METAVERSE DATA MINING (MDM) is a Filecoin Plus Allocator pathway focused on onboarding high-quality **public open datasets** (e.g., research, non-profit, and openly accessible data) and select enterprise datasets. We prioritize data that is useful, retrievable, and contributes to the decentralization and long-term utility of the Filecoin network. Our rigorous manual due diligence ensures compliance with Fil+ principles, including geographic distribution (3+ regions), multiple Storage Providers (5+ SPs), and high retrievability.

We support clients bringing valuable data to Filecoin while maintaining strict standards for data provenance, ownership, and storage integrity.

## Contact Information

- **Organization**: METAVERSE DATA MINING PTE. LTD.
- **Slack ID**: @METAVERSEDATAMINING
- **Preferred Communication**: Please open an issue in our bookkeeping repository  
 [](https://github.com/filplus-bookkeeping/METAVERSEDATAMINING)  
  or reach out via Slack for DataCap requests.

## Detailed Allocator Policies, Procedures, and Requirements

### Client Application Process

1. Clients submit a DataCap request via GitHub issue in our dedicated bookkeeping repository (template will be provided).
2. Required information includes:
   - Client Filecoin address.
   - Detailed dataset description (type, size, provenance, usefulness).
   - Data ownership proof.
   - Planned distribution: At least **5 Storage Providers** across **3+ geographic regions**.
   - KYC/KYB documents (for individuals/organizations).
3. We follow the **standard Allocation Tranche Schedule**:
   - First tranche: Max 5% of pathway DC (no more than 256 TiB), and no allocation larger than previous.
   - Subsequent tranches increase progressively up to 25%.
4. Response time: We aim to acknowledge applications within **5 business days** and complete initial review within **7-10 days**.

### Client and Data Requirements

- Data must be **useful and retrievable** (public open focus, with support for compliant enterprise data).
- Clients must agree to:
  - Maintain retrievability score **>75%** for deals using our DataCap.
  - Provide detailed data preparation descriptions/scripts for verification/recreation via CID.
- Compliance with program-wide rules: **5+ replicas** (verified via CID Checker), **5+ SPs**, **3+ regions**, no single SP >30% recommended.

### Due Diligence Procedures

As outlined in our application:

- **KYC/KYB**: Verified via filplus.storage, Toggle.io, and third-party tools.
- **Data Ownership & Compliance**: Proof of legal rights, regulatory compliance (e.g., GDPR, PDPA), data sampling using CID Checker Bot, Lassie, and Singularity tools.
- **Sybil Mitigation**: Manual review combined with anti-fraud tools.

## Risk Mitigation Strategies

To protect the organization, pathway reputation, and Filecoin network from abuse:

- **Operational Security (OpSec)**:
  - Multisig wallet for all DC allocations (requiring multiple approvals).
  - Secure storage of sensitive KYC data (encrypted Google Workspace, access-limited).
  - No single individual controls full allocation process.
- **User Agreements**: Clients must acknowledge terms prohibiting abuse, self-dealing, or fake data.
- **Throttling & Alerts**:
  - Tranche-based allocation to monitor usage before larger grants.
  - Automated monitoring via datacapstats.io and internal alerts for low utilization or suspicious patterns.

## Dispute Resolutions

**Process**:

1. **Internal Disputes**: We will investigate within **3 business days**, communicate directly with the client, and seek resolution (e.g., additional verification or DC removal if warranted).
2. **External Disputes**: We will provide full transparent records (non-sensitive) to the Governance Team or involved parties. We commit to defending decisions with audit trails.
3. **Escalation**: Unresolved disputes escalate to Filecoin Slack #fil-plus-notaries or Allocator-Governance repository for community review.
4. **Outcome**: May include DC removal, pathway adjustments, or referral to Root Key Holders (RKH). We bias toward transparency and program principles.

**Target**: Resolve **90% of disputes within 5 business days**.

## Compliance Audit Check

To ensure ongoing compliance:

- **Monitoring Tools**: Regular checks via datacapstats.io, CID Checker Bot, Lassie retrievals, Singularity verification, and **Spark** retrievability tests.
- **Client/SP Compliance**:
  - Verify deals meet 5+ SPs, 3+ regions, high retrievability (>75%).
  - Sample data against client claims.
  - Track KPIs: DataCap utilization (>80%), onboarding success (90%), retrieval compliance (75%).
- **Reporting**: Maintain transparent bookkeeping in this GitHub repo .
- **Audit Preparation**: All records available for Governance Team review during refreshes or on request. We participate in governance calls as needed.

This policy will be updated as needed via GitHub, with community input welcomed.

We are committed to fostering useful storage on Filecoin and upholding Fil+ principles.
