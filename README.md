# HealHub

> Multi-role healthcare coordination prototype · Flutter / Firebase · 2025

HealHub is an Arabic-first healthcare application prototype connecting patients and doctors across multiple clinics through role-aware scheduling, prescription, community, rating, and notification workflows.

## Live Project Showcase

**Recruiter-friendly live view:** https://karamalawaj.github.io/healhub-showcase/

The live page presents the product flow, engineering decisions, architecture, and selected screens in a fast, portfolio-safe format. It is deployed automatically from this repository with GitHub Pages.

## Product Preview

<div align="center">
  <img width="31%" src="https://github.com/user-attachments/assets/0ead5bbe-94ee-453f-a01d-aac993c6e08c" />
  <img width="31%" src="https://github.com/user-attachments/assets/af7d5ab5-752e-4eda-9072-7755a546b7f4" />
  <img width="31%" src="https://github.com/user-attachments/assets/5d253efd-ce95-4ba2-abcb-9280d10fb816" />
</div>

<br>

<div align="center">
  <img width="31%" src="https://github.com/user-attachments/assets/bcc456f7-d706-47fe-b28d-52a1dd38c8b2" />
  <img width="31%" src="https://github.com/user-attachments/assets/6814d6f6-7e15-4664-8bec-0ad99212a7e8" />
  <img width="31%" src="https://github.com/user-attachments/assets/3f284b60-2bcf-49a4-92ad-5c8c6b89a26a" />
</div>

<details>
<summary><strong>View 6 more screenshots</strong></summary>
<br>
<div align="center">
  <img width="31%" src="https://github.com/user-attachments/assets/5d5e9406-67c2-45a4-be12-29bd7b6188a7" />
  <img width="31%" src="https://github.com/user-attachments/assets/699b512c-7574-4330-ba80-6512b31212f4" />
  <img width="31%" src="https://github.com/user-attachments/assets/8b00e92f-e711-4f21-ac0d-6f8c7b880c6a" />
</div>
<br>
<div align="center">
  <img width="31%" src="https://github.com/user-attachments/assets/904f9696-6332-4ec9-b9ea-68245d046517" />
  <img width="31%" src="https://github.com/user-attachments/assets/6b98ae78-0388-48f2-88e5-8e7554c64e4c" />
  <img width="31%" src="https://github.com/user-attachments/assets/10294318-b958-4650-b33d-494e16bc5435" />
</div>
</details>

## Patient Experience
- Account registration and profile setup
- Doctor discovery and doctor-profile viewing
- Schedule-aware appointment booking
- Appointment history and lifecycle tracking
- Prescription viewing
- Doctor ratings
- Community posts, likes, comments, and media
- Notification center

## Doctor Experience
- Doctor profile and specialty setup
- Configurable weekly working hours
- Appointment review and status handling
- Confirmed appointment management
- Prescription creation
- Community participation
- Application notifications

## Engineering Focus
- Role-based Flutter application structure
- GetX routing, dependency management, controllers, and reactive state
- Firebase Authentication and Cloud Firestore integration
- Schedule-aware appointment availability and lifecycle management
- Prescription workflows linked to patient/doctor interactions
- Community content and media integration
- Ratings and notification flows
- Responsive patient and doctor experiences

## Tech Stack
`Flutter` · `Dart` · `GetX` · `Firebase Authentication` · `Cloud Firestore` · `Firebase Messaging` · `flutter_local_notifications` · `Cloudinary` · `Cached Network Image` · `Lottie`

## Architecture Snapshot

```text
Patient / Doctor Mobile UI
          │
          ▼
      GetX Layer
          │
          ├── Authentication & Role Flows
          ├── Appointment / Schedule Logic
          ├── Prescription Workflows
          ├── Community / Ratings
          └── Notifications
          │
          ▼
   Firebase Services
```

This diagram is intentionally portfolio-safe and does not expose private rules, credentials, operational configuration, or sensitive implementation details.

## Security & Scope
HealHub is a working portfolio prototype, not a production healthcare platform. Client-side Firebase configuration is not treated as an authorization boundary; a production deployment would require hardened backend authorization, Firebase security rules, App Check where appropriate, compliance review, and stronger infrastructure controls.

## Project Status
**Working prototype · Private source · Portfolio showcase**

## Source Policy
**Portfolio showcase only. The production/full source repository is private and protected. Source code, credentials, private configuration, and sensitive implementation details are intentionally not published.**

## Rights
© Karam Alawaj. All rights reserved. No license is granted to copy, redistribute, reuse, or republish proprietary source or implementation details.
