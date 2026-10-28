<p align="center">
  <a href="https://anuva.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/anuvahq/.github/main/assets/anuva-logo-dark.svg">
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/anuvahq/.github/main/assets/anuva-logo-light.svg">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/anuva-logo-light.svg" alt="Anuva logo: a teal letter A with a check mark, next to the word Anuva" width="232" height="80">
    </picture>
  </a>
</p>

<h3 align="center">The open-source applicant tracking system with screening you can explain</h3>

<p align="center">
  <a href="https://anuva.io"><img src="https://img.shields.io/static/v1?label=website&message=anuva.io&color=14B8A6&style=flat" alt="Website: anuva.io"></a>
  <a href="https://www.linkedin.com/company/anuva-consulting/"><img src="https://img.shields.io/static/v1?label=LinkedIn&message=Anuva&color=0A66C2&style=flat" alt="Anuva on LinkedIn"></a>
  <img src="https://img.shields.io/static/v1?label=license&message=AGPL-3.0%20(planned)&color=0B1220&style=flat" alt="License: AGPL-3.0, planned for the public release">
  <img src="https://img.shields.io/static/v1?label=status&message=private%20beta&color=F59E0B&style=flat" alt="Status: private beta">
  <br>
  <img src="https://img.shields.io/static/v1?label=&message=FastAPI&color=009688&logo=fastapi&logoColor=white&style=flat" alt="Built with FastAPI">
  <img src="https://img.shields.io/static/v1?label=&message=Postgres%2018&color=4169E1&logo=postgresql&logoColor=white&style=flat" alt="Built with Postgres 18">
  <img src="https://img.shields.io/static/v1?label=&message=Next.js%2016&color=000000&logo=nextdotjs&logoColor=white&style=flat" alt="Built with Next.js 16">
  <img src="https://img.shields.io/static/v1?label=&message=Docker&color=2496ED&logo=docker&logoColor=white&style=flat" alt="Runs on Docker">
</p>

<p align="center">
  <a href="https://anuva.io"><strong>Website</strong></a> ·
  <a href="#what-anuva-does">Features</a> ·
  <a href="#how-ai-screening-works">How screening works</a> ·
  <a href="#why-anuva">Why Anuva</a> ·
  <a href="https://github.com/anuvahq/.github/blob/main/SECURITY.md">Security</a>
</p>


**Anuva is an open-source applicant tracking system (ATS) for companies and recruiting agencies that want a clear hiring pipeline and screening decisions they can explain.** It runs the full hiring flow, from job posts and a branded careers site to CV screening, interviews, and signed offer letters. Use Anuva Cloud, or host it on your own servers.

## What Anuva does

<table>
  <tr>
    <td width="33%" valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/careers.svg" width="28" height="28" alt="Globe icon"><br>
      <strong>Careers sites</strong><br>
      A careers site per company at <code>{slug}.careers.anuva.io</code> or your own domain, with Google for Jobs structured data.
    </td>
    <td width="33%" valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/apply.svg" width="28" height="28" alt="Clipboard icon"><br>
      <strong>Multi-step apply</strong><br>
      Application forms with knockout questions and consent capture built in.
    </td>
    <td width="33%" valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/screening.svg" width="28" height="28" alt="Sliders icon"><br>
      <strong>Explainable screening</strong><br>
      Weighted criteria and a cutoff decide the result. Every override needs a written reason and is audited.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/ai.svg" width="28" height="28" alt="Key icon"><br>
      <strong>AI CV screening, your key</strong><br>
      Bring your own key for OpenAI, Anthropic, OpenRouter, or any OpenAI-compatible endpoint.
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/pipeline.svg" width="28" height="28" alt="Kanban board icon"><br>
      <strong>Pipeline and ownership</strong><br>
      A board by stage, owners per job and candidate, and a view of team workload.
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/interviews.svg" width="28" height="28" alt="Calendar icon"><br>
      <strong>Interviews and scorecards</strong><br>
      Schedule interviews and collect structured feedback from every interviewer.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/offers.svg" width="28" height="28" alt="Signed document icon"><br>
      <strong>Offers and e-signature</strong><br>
      PDF offer letters signed online through Anuva Sign, a self-hosted Documenso.
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/portal.svg" width="28" height="28" alt="Person icon"><br>
      <strong>Candidate portal</strong><br>
      Candidates check where their application stands without emailing the recruiter.
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/reports.svg" width="28" height="28" alt="Bar chart icon"><br>
      <strong>Hiring reports</strong><br>
      Funnel conversion, time to hire, and source of hire.
    </td>
  </tr>
  <tr>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/privacy.svg" width="28" height="28" alt="Shield icon"><br>
      <strong>Privacy by design</strong><br>
      A database per tenant, Postgres row-level security, data subject requests (DSAR), retention purge, and encrypted backups.
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/audit.svg" width="28" height="28" alt="Chain link icon"><br>
      <strong>Tamper-evident audit log</strong><br>
      A hash-chained log of screening decisions, overrides, and other changes, so edits after the fact are detectable.
    </td>
    <td valign="top">
      <img src="https://raw.githubusercontent.com/anuvahq/.github/main/assets/icons/console.svg" width="28" height="28" alt="Server icon"><br>
      <strong>Operator console</strong><br>
      Run hiring for many clients from one place.
    </td>
  </tr>
</table>

## How AI screening works

Anuva uses a language model to read CVs, but the model never decides who moves forward.

1. **You define the criteria.** Each job has weighted criteria and a cutoff score.
2. **The model gathers evidence.** For each criterion, the model you choose returns the matching evidence from the CV. You bring your own API key for OpenAI, Anthropic, OpenRouter, or any OpenAI-compatible endpoint, so candidate data goes only to the provider you pick.
3. **Weights and the cutoff decide.** The score is plain arithmetic on your weights, so every result can be explained line by line.
4. **People stay in control.** If the model returns malformed output, the application goes to human review. It is never rejected automatically. Recruiters can override any result with a written reason, and every override lands in the audit log.

## Why Anuva

<table>
  <thead>
    <tr><th></th><th>Anuva</th><th>Closed ATS (Greenhouse, Lever, Workable)</th></tr>
  </thead>
  <tbody>
    <tr><td><strong>Source code</strong></td><td>Open core under AGPL-3.0 (public release planned)</td><td>Closed source</td></tr>
    <tr><td><strong>Where it runs</strong></td><td>Anuva Cloud, or self-host on your own servers</td><td>Hosted by the vendor only</td></tr>
    <tr><td><strong>AI screening model</strong></td><td>Bring your own key: OpenAI, Anthropic, OpenRouter, or any OpenAI-compatible endpoint</td><td>See each vendor's documentation</td></tr>
    <tr><td><strong>Screening logic</strong></td><td>Weights and cutoff you can read and audit</td><td>See each vendor's documentation</td></tr>
  </tbody>
</table>

## Who Anuva is for

- **HR and talent teams** that want a modern ATS they can inspect and run themselves
- **Recruiting agencies** that run hiring for several clients from one operator console
- **Companies with data residency or security rules** that need candidate data on their own infrastructure

## Built with

FastAPI and Python on the backend, Postgres 18 with row-level security for data, Next.js 16 for the recruiter app and careers sites, and Docker with k3s for deployment.

## Project status

Anuva Cloud is in private beta with its first customers. The open-source core (AGPL-3.0) is being prepared for public release. Follow this organization to hear when the repository opens.

## Get involved

- **Early access and product questions:** [anuva.io](https://anuva.io)
- **Company updates:** [Anuva on LinkedIn](https://www.linkedin.com/company/anuva-consulting/)
- **Security reports:** read the [security policy](https://github.com/anuvahq/.github/blob/main/SECURITY.md) and report privately
- **Contributing:** read the [contributing guide](https://github.com/anuvahq/.github/blob/main/CONTRIBUTING.md)
