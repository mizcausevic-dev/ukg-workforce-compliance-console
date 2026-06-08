# ukg-workforce-compliance-console

Board-readable Kinetic Gain proof repo for **UKG** platform and company signal coverage.

## Product thesis

Workforce compliance issues hide in disconnected time, role, location, manager, and policy-attestation records.

This repo turns that problem into a small, inspectable product surface: synthetic fixture data, a deterministic CLI, a tested scoring model, a JSON report, and a static brief that explains the business and technical value of the signal.

## Buyer and operator fit

- **Primary audience:** HR operations, compliance leaders, workforce systems owners, and CFO operators
- **Signal domain:** HR Tech / Workforce
- **Executive question:** Where is this system creating exposure, waste, or decision latency?
- **Product motion:** The product maps workforce exceptions to accountable owners, remediation windows, policy proof, and executive-ready risk posture.
- **Value architecture:** Leaders can distinguish ordinary HR noise from labor-cost exposure, compliance risk, and operational bottlenecks.

## What this repo proves

- **Normalize:** messy UKG operating evidence is represented as explicit lanes.
- **Score:** risk and evidence depth are measured separately so weak proof is not hidden by high urgency.
- **Route:** each lane has an owner and next action instead of a vague status.
- **Package:** CLI output, tests, JSON report, and static page all tell the same board-ready story.

## Integration boundary

Focus area: UKG workforce records, schedules, attestations, manager hierarchies, and exception queues.

This is synthetic proof only. It does not connect to live UKG tenants, call private APIs, store secrets, publish credentials, or expose customer data.

## Local run

```bash
npm install
npm test
npm run build
npm run demo
```

## Public surface

The generated site is in `site/index.html`. The data report is in `site/report.json`.

## Keywords

- UKG
- workforce compliance
- HR operations
- labor risk
- attestation
