<p align="center">
<img src="https://i.imgur.com/1iIxyNm.png" alt="Conditional Access"/>
</p>

<h1>Entra ID — Conditional Access (SC-300 Lab 3)</h1>
Build Conditional Access policies and trace their effect in the sign-in logs. The highest-weighted exam material. Maps to SC-300 Domain 2 part 2 (25–30%).<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Entra ID (P2 for risk-based policies)
- Entra ID Protection
- Microsoft Entra admin center

<h2>Operating Systems Used</h2>

- Windows 11 (browser-based)

<h2>List of Prerequisites</h2>

- A developer tenant with a defined break-glass account
- Conditional Access Administrator access

<h2>Configuration Steps</h2>
<ol>
  <li><strong>Create a named location</strong> — Protection &rarr; Conditional Access &rarr; Named locations; add a trusted IP range.</li>
  <li><strong>Create a require-MFA policy</strong> — target all users, <strong>exclude the break-glass account</strong>, grant control = MFA; set to <strong>Report-only</strong>.</li>
  <li><strong>Create a sign-in-risk policy</strong> — high/medium sign-in risk requires MFA (Report-only).</li>
  <li><strong>Trace the result</strong> — sign in as a test user; open Monitoring &rarr; Sign-in logs &rarr; Conditional Access tab; identify which policy and grant control applied.</li>
</ol>

<h2>Key Concepts Demonstrated</h2>

- Policy evaluation order, exclusions, and named locations determine the outcome.
- Break-glass accounts are always excluded to prevent lockout.

<h2>Lessons Learned</h2>

- Deploy in Report-only first and read sign-in diagnostics before enforcing.
- Reading a sign-in log to explain an outcome is the core exam skill here.
