<p align="center">
<img src="https://i.imgur.com/QxC6u2g.jpeg" alt="Traffic Examination"/>
</p>

<h1>Intune Device Management Lab (Windows)</h1>
This lab demonstrates enrolling a Windows device into Microsoft Intune and managing it using compliance policies, configuration profiles, and application deployment.
 <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Intune
- Microsoft Entra ID
- Microsoft 365 Developer Tenant (E5 Sandbox)
- Microsoft 365 Admin Center
- PowerShell
- Notepad/Notes App (Needed for saving usernames, passwords, and other information)

<h2>Operating Systems Used </h2>

- Windows 10 / Windows 11
- Windows Virtual Machine

<h2>List of Prerequisites</h2>

- Basic/General Understanding of Microsoft Intune

<h2>Setup and Usage Proton VPN</h2>

## Goals
- Create a Microsoft 365 developer tenant and Intune-enabled test environment
- Enroll a Windows 10/11 device into Intune
- Apply a compliance policy and configuration profile
- Deploy an application and validate reporting

## Environment
- Tenant: Microsoft 365 Developer (E5)  
- Platform: Windows 10/11  
- Tools: Microsoft Intune, Microsoft Entra ID  
- Device: Windows VM (or physical test device)

## Architecture (High Level)
User (test account) → Entra ID → Intune Enrollment → Device appears in Intune → Policies + Apps assigned → Compliance/Reporting validated

## Steps (Summary)
1. Created M365 dev tenant and test user
2. Enabled Windows enrollment / MDM user scope
3. Enrolled Windows device (Access work or school)
4. Created and assigned compliance policy
5. Created and assigned configuration profile
6. Deployed an application
7. Verified compliance, configuration, and installation status

## Evidence / Screenshots
- Device enrollment successful: `screenshots/02-device-enrolled.png`
- Compliance policy status: `screenshots/03-compliance-policy.png`
- Configuration profile applied: `screenshots/04-config-profile.png`
- App deployment installed: `screenshots/05-app-install.png`

## Troubleshooting Notes
- Enrollment delays: device may take several minutes to appear in Intune
- Policy assignment: ensure device/user is in the correct group

## What I Learned
- How Intune ties device management to Entra ID identity
- How compliance policies and configuration profiles affect endpoint posture
- How to validate deployments through Intune reporting

## Next Improvements
- Add Windows Autopilot simulation
- Add Endpoint Security policies (Defender / BitLocker)
- Add device cleanup and offboarding workflow
