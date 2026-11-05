<p align="center">
  <img width="1983" height="454" alt="SynAccel cover" src="https://github.com/user-attachments/assets/38750e37-23e8-41bf-8d96-6b5b1dcf1b84" />
</p>

<h1 align="center">SynAccel</h1>

<p align="center">
  <em>Applied security research across cloud, cyber-physical systems, and AI-enabled security.</em>
</p>

<p align="center">
  <a href="https://synaccel.com/"><strong>Website</strong></a> ·
  <a href="https://linkedin.com/company/synaccel-official"><strong>LinkedIn</strong></a>
</p>

---

SynAccel's public repositories contain research prototypes, experiments, and tools at different stages of development. They are not represented as production-ready products; each project README describes its current scope, setup, and limitations.

## Cloud and cyber-physical security

- **[SynAccel-Sentinel](https://github.com/SynAccel/SynAccel-Sentinel)** — Research prototype for read-only AWS IAM and S3 exposure checks, local risk prioritization, and reports. Its standalone responder scripts are not orchestrated by the core.
- **[SynAccel-Bridge](https://github.com/SynAccel/SynAccel-Bridge)** — FastAPI prototype for authenticated event intake, validation, correlation, and simulated responses.

## AI security and robustness research

- **[SynAccel-llm-redteam-sandbox](https://github.com/SynAccel/SynAccel-llm-redteam-sandbox)** — Local heuristic evaluation sandbox using a simulated language model; it does not connect to a hosted model by default.
- **[adversarial-autonomous-triage](https://github.com/SynAccel/adversarial-autonomous-triage)** — Research lab evaluating how attacker-controlled content can affect AI-assisted security-alert triage.
- **[SynAccel-ShieldSet](https://github.com/SynAccel/SynAccel-ShieldSet)** — Dataset auditing research using k-nearest-neighbor label consensus to flag potentially inconsistent samples.

## Deception and experimentation

- **[SynAccel-Mirage_v2](https://github.com/SynAccel/SynAccel-Mirage_v2)** — Local defensive decoy service that returns configured banners and records interaction metadata without forwarding requests.
- **[SynAccel-Forge](https://github.com/SynAccel/SynAccel-Forge)** — R&D workspace for documented experiments, prototypes, and reusable tools.

---

For current capabilities, installation steps, and limitations, use the README in each repository. The website provides organization-level information; project maturity and support vary by repository.
