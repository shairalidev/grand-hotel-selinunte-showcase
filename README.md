<div align="center">

<a href="https://grandhotelselinunte.com"><img src="assets/grand-hotel-selinunte.jpg" alt="Grand Hotel Selinunte: Hotel website, AI guest-support chat with WhatsApp, and internal finance tools." width="100%"/></a>

# Grand Hotel Selinunte

**Hotel website, AI guest-support chat with WhatsApp, and internal finance tools.**

[![Live site](https://img.shields.io/badge/Live-grandhotelselinunte.com-c9a45c?style=for-the-badge&logo=googlechrome&logoColor=white)](https://grandhotelselinunte.com) [![Case study](https://img.shields.io/badge/Case_study-shairali.com-111?style=for-the-badge)](https://shairali.com/work/grand-hotel-selinunte)

Hospitality · Grand Hotel Selinunte · Sicily, Italy · 2024 – 2025

</div>

> [!NOTE]
> This repository is a **showcase**. The source code is private and belongs to the client, so this page documents what I built, how it works and the stack behind it. Screenshots are from the live product.

<p align="center"><img src="assets/tour.gif" alt="Grand Hotel Selinunte product tour" width="100%"/></p>

## Overview

The official website of a seafront hotel in Sicily, plus an AI chat assistant that answers guests on the web and WhatsApp, and in-house tools that automate quotes and receipts.

| | |
|---|---|
| **Role** | Full-stack developer: website, AI guest support & internal tools |
| **Client** | Grand Hotel Selinunte · Sicily, Italy |
| **Timeline** | 2024 – 2025 |
| **Live** | [grandhotelselinunte.com](https://grandhotelselinunte.com) |

## At a glance

<table><tr>
<td align="center" width="33%"><h3>3</h3><sub>Products delivered</sub></td>
<td align="center" width="33%"><h3>24/7</h3><sub>AI guest support</sub></td>
<td align="center" width="33%"><h3>2</h3><sub>Support channels: web & WhatsApp</sub></td>
</tr></table>

## The challenge

An international hotel gets the same guest questions all day, in several languages, across the website and WhatsApp, while the front office was still building quotes and receipts by hand. The hotel needed a modern website that converts, round-the-clock answers for guests and less manual admin work.

## What I built

I built and deployed the official website with a custom React frontend and a fully responsive booking journey. I then added an AI chat support system connected to WhatsApp for multilingual guest questions, plus internal tools that generate PDF quotes and receipts and calculate stay costs automatically.

## Key features

### Website and booking journey

A fast, fully responsive website with a custom React frontend, designed to turn visitors into direct bookings. It's deployed on AWS behind Nginx with SSL.

<img src="assets/rooms-dining.webp" alt="Rooms with a view and Sicilian dining sections of the hotel website" width="100%"/>

### AI chat support with WhatsApp

An AI assistant answers guest questions about rooms, services and bookings in several languages, on the website and over WhatsApp, around the clock.

### Internal finance tools

A cost calculator, a PDF quote generator and a receipt generator. Together they cut manual formatting and speed up replies to guests.

## Architecture

```mermaid
flowchart LR
  subgraph L0["Client"]
    direction TB
    L0_0["Website (React)"]
    L0_1["WhatsApp"]
  end
  subgraph L1["Edge"]
    direction TB
    L1_0["Nginx on AWS"]
    L1_1["SSL"]
  end
  subgraph L2["Application"]
    direction TB
    L2_0["Node.js API"]
    L2_1["AI chat service"]
    L2_2["PDF & receipt tools"]
  end
  L0 --> L1
  L1 --> L2
```

## Engineering highlights

- Production deployment on AWS virtual machines behind Nginx with SSL.
- Responsive, SEO-friendly pages built for hospitality search terms.
- AI assistant tuned to the hotel's own information, available on the web and on WhatsApp.

## Tech stack

| Area | Technologies |
|---|---|
| **Frontend** | ![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB) ![Responsive UI](https://img.shields.io/badge/Responsive%20UI-555?style=flat-square) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![PDF generation](https://img.shields.io/badge/PDF%20generation-555?style=flat-square) |
| **AI & messaging** | ![LLM chat assistant](https://img.shields.io/badge/LLM%20chat%20assistant-555?style=flat-square) ![WhatsApp integration](https://img.shields.io/badge/WhatsApp%20integration-25D366?style=flat-square&logo=whatsapp&logoColor=white) |
| **Infrastructure** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![SSL](https://img.shields.io/badge/SSL-555?style=flat-square) |

## Screens

<table>
<tr>
<td width="50%" valign="top"><img src="assets/hero.webp" alt="Homepage hero with the hotel pool and countryside view" width="100%"/><br/><sub>Homepage hero with the hotel pool and countryside view</sub></td>
<td width="50%" valign="top"><img src="assets/intro.webp" alt="Luxury living introduction section" width="100%"/><br/><sub>Luxury living introduction section</sub></td>
</tr>
<tr>
<td width="50%" valign="top"><img src="assets/rooms-dining.webp" alt="Rooms with a view and Sicilian dining sections" width="100%"/><br/><sub>Rooms with a view and Sicilian dining sections</sub></td>
<td width="50%" valign="top"><img src="assets/pool.webp" alt="Pool, sea and services section" width="100%"/><br/><sub>Pool, sea and services section</sub></td>
</tr>
</table>

<p align="center"><img src="assets/mobile.webp" alt="Grand Hotel Selinunte on mobile" width="320"/><br/><sub>Mobile</sub></p>

## About the developer

Designed, built and deployed by **[Shair Ali](https://shairali.com)**, a full-stack developer who owns products end to end: architecture, interface, API, data, payments, servers and CI/CD.

[![Portfolio](https://img.shields.io/badge/Portfolio-shairali.com-111?style=flat-square)](https://shairali.com) [![Fiverr](https://img.shields.io/badge/Fiverr-devshair-1DBF73?style=flat-square&logo=fiverr&logoColor=white)](https://www.fiverr.com/devshair) [![LinkedIn](https://img.shields.io/badge/LinkedIn-shairali2-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shairali2) [![GitHub](https://img.shields.io/badge/GitHub-shairalidev-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/shairalidev)

<sub>Have a similar project? [Get in touch](https://shairali.com/contact).</sub>
