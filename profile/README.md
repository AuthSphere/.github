<div align="center">

<img src="assets/Banner AuthSphere 3.jpg" alt="AuthSphere — Secure Identity. Seamless Access." width="100%">
<br><br>

<h3 align="center">Simple, reliable authentication &amp; infrastructure tools for developers.</h3>
<p align="center">
  <sub>Open-source identity protocols, developer tooling, and modern software foundations.</sub>
</p>

<p align="center">
  <a href="https://github.com/AuthSphere"><img src="https://img.shields.io/badge/Open%20Source-100%25-0B1F4B?style=flat-square&logo=github&logoColor=white" alt="Open Source"></a>
  <a href="https://github.com/AuthSphere"><img src="https://img.shields.io/badge/Protocol-OAuth%202.0%20%2B%20PKCE-2B4BFF?style=flat-square" alt="Protocol"></a>
  <a href="https://www.npmjs.com/package/@authspherejs/sdk"><img src="https://img.shields.io/npm/v/@authspherejs/sdk?style=flat-square&color=00C2FF&label=SDK&logo=npm" alt="NPM SDK"></a>
  <a href="https://github.com/AuthSphere/Test"><img src="https://img.shields.io/badge/TypeScript-Ready-0B1F4B?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-2B4BFF?style=flat-square" alt="License: MIT"></a>
  <a href="https://github.com/AuthSphere"><img src="https://img.shields.io/badge/Status-Active%20Development-00C2FF?style=flat-square" alt="Status"></a>
</p>

<p align="center">
  <a href="#what-we-build"><strong>What We Build</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="#core-commitments"><strong>Core Commitments</strong></a>
  &nbsp;&bull;&nbsp;
  <a href="#community--contributing"><strong>Community &amp; Contributing</strong></a>
</p>

</div>

<br>

---

## <img src="assets/icons/layers.svg" width="22" height="22" valign="middle" alt=""> What We Build

Authentication shouldn't require wrestling with bloated enterprise suites, complex configuration walls, or fragile identity boilerplate. **AuthSphere** develops focused, secure-by-default software infrastructure designed to give engineering teams full control and confidence in their authentication layer.

<table>
<tr>
<td width="50%" valign="top">

### <img src="assets/icons/shield-check.svg" width="20" height="20" valign="text-bottom" alt=""> OAuth 2.0 with Mandatory PKCE

Engineered according to **IETF RFC 7636** and Best Current Practices (BCP) for single-page and native applications. Employs high-entropy cryptographic code verifiers and atomic state validation to eliminate interception risks and CSRF vectors.

</td>
<td width="50%" valign="top">

### <img src="assets/icons/users.svg" width="20" height="20" valign="text-bottom" alt=""> Universal Identity Handshakes

Native handling for federated social providers (Google, GitHub, Discord) alongside local credential authentication, email challenge cycles, and 6-digit OTP verification.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### <img src="assets/icons/terminal.svg" width="20" height="20" valign="text-bottom" alt=""> Developer-First Client SDK

The [`@authspherejs/sdk`](https://www.npmjs.com/package/@authspherejs/sdk) client library delivers zero-friction setup, automatic callback resolution, and resilient session persistence across modern frontend frameworks.

</td>
<td width="50%" valign="top">

### <img src="assets/icons/layout-dashboard.svg" width="20" height="20" valign="text-bottom" alt=""> Command Center &amp; Gateway

Centralized developer control plane for project identity management, public key distribution, and auth-as-a-service routing built for high reliability.

</td>
</tr>
</table>

<br>

---

## <img src="assets/icons/circle-check.svg" width="22" height="22" valign="middle" alt=""> Core Commitments

Every piece of software built at AuthSphere adheres to five core commitments:

1. <img src="assets/icons/globe.svg" width="16" height="16" valign="text-bottom" alt=""> &nbsp;**Open-Source First** &mdash; We build openly in public. Our codebases, client tools, and specifications are transparent, inspectable, and auditable by the entire community.
2. <img src="assets/icons/zap.svg" width="16" height="16" valign="text-bottom" alt=""> &nbsp;**Developer-Friendly Tooling** &mdash; Setup must take minutes, not days. We prioritize typed APIs, comprehensive errors, and intuitive defaults that get out of your way.
3. <img src="assets/icons/shield.svg" width="16" height="16" valign="text-bottom" alt=""> &nbsp;**Security-Conscious Engineering** &mdash; Adherence to IETF RFC standards, mandatory PKCE, atomic state verification, and safe session storage by default.
4. <img src="assets/icons/package.svg" width="16" height="16" valign="text-bottom" alt=""> &nbsp;**Simple, Maintainable Software** &mdash; We favor modular, lightweight packages over bloated multi-gigabyte monoliths.
5. <img src="assets/icons/heart-handshake.svg" width="16" height="16" valign="text-bottom" alt=""> &nbsp;**Community-Driven Improvement** &mdash; Useful software evolves through real user feedback, open discussion, and collective contributions.

<br>

---

## <img src="assets/icons/sparkles.svg" width="22" height="22" valign="middle" alt=""> Community &amp; Contributing

AuthSphere is built by developers, for developers. Whether you're fixing a typo in documentation, reporting an edge-case bug, or implementing a new OAuth provider flow, your contribution is genuinely welcome.

<table>
<tr>
<td width="50%" valign="top">

### <img src="assets/icons/bug.svg" width="20" height="20" valign="text-bottom" alt=""> Reporting Bugs &amp; Issues

Open an issue in the relevant project repository:

- Client SDK or Starter: [`AuthSphere/Test/issues`](https://github.com/AuthSphere/Test/issues)
- Organization &amp; General: [`AuthSphere/.github/issues`](https://github.com/AuthSphere/.github/issues)

Include reproduction steps and environment details for rapid triage.

</td>
<td width="50%" valign="top">

### <img src="assets/icons/lightbulb.svg" width="20" height="20" valign="text-bottom" alt=""> Feature Proposals &amp; RFCs

We welcome proposals for:

- New social identity providers (GitLab, Twitter/X, Apple)
- Framework adapters (Next.js, Remix, Astro, Vue)
- Backend verification middleware (Node.js, Express, Go)

Start a discussion or submit a feature proposal in the issue tracker.

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### <img src="assets/icons/git-pull-request.svg" width="20" height="20" valign="text-bottom" alt=""> Submitting a Pull Request

1. Fork the target repository and create your feature branch: `git checkout -b feature/your-feature-name`
2. Follow the repository's linting, formatting, and TypeScript conventions.
3. Test your changes thoroughly against local demo flows.
4. Open a Pull Request with a clear description of the problem solved and modifications introduced.

</td>
</tr>
</table>

<br>

---

<div align="center">

<img src="assets/AuthSphere(colored).png" alt="AuthSphere Logo" width="90">
<br><br>

**AuthSphere** &mdash; Simple, reliable tools for developers.

<sub>Open-Source Authentication &amp; Software Infrastructure</sub><br>
<sub>Distributed under the <a href="https://opensource.org/licenses/MIT">MIT License</a> &bull; Built with care by the AuthSphere community</sub>

<br><br>

<a href="https://github.com/AuthSphere"><strong>GitHub Organization</strong></a>
&nbsp;&bull;&nbsp;
<a href="https://www.npmjs.com/package/@authspherejs/sdk"><strong>NPM Package</strong></a>
&nbsp;&bull;&nbsp;
<a href="https://github.com/AuthSphere/Test"><strong>Reference Project</strong></a>
&nbsp;&bull;&nbsp;
<a href="https://auth-sphere-gilt.vercel.app"><strong>Command Center</strong></a>

</div>
