<div align="center">
  <h1>THESDEL</h1>
  <h3>The Student Digital Exchange Layer</h3>
  <p><em>Learn. Grow. Become.</em></p>
  
  <!-- Animated Tech Divider -->
  <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=600&size=18&duration=3000&pause=1000&color=000000&center=true&vCenter=true&width=600&lines=Building+the+digital+layer+for+student+life.;Starting+in+Nigeria.+Building+for+Africa.;Built+at+OAU." alt="Typing SVG" />
</div>

<br />

> **Engineering Note:** The core source code for Thesdel is kept private to protect proprietary business logic. This repository serves as a public technical overview, architectural case study, and UI showcase. The live application is available at [https://thesdel.com](https://thesdel.com).

## Overview
THESDEL is a full-stack web application designed to solve the problem of fragmented and static academic tools. We believe student technology should go beyond simply putting existing school processes online. THESDEL is being built as a digital layer for student life—connecting the academic, social, and practical parts of being a student.

## Tech Stack
*   **Frontend:** React, TypeScript
*   **Backend:** Go (Golang)
*   **Database & Auth:** Supabase (PostgreSQL)
*   **Hosting/Infrastructure:** Vercel, Cloudflare

## Architecture & Technical Decisions

### 1. Unified UI with Role-Based Access Control (RBAC)
Instead of building separate dashboards for Admins, Class Representatives, and Students, Thesdel uses a single, unified interface. The UI dynamically adapts based on the user's role in the database. This significantly reduces frontend code duplication and provides a smoother experience, as a Class Rep is also a student who needs to see their own timetable.

### 2. Why Go for the Backend?
Go was chosen to handle concurrent requests efficiently during peak traffic times, specifically when students are checking schedules right before a new semester. Go's strong typing and standard library provided a robust foundation for the API without the overhead of heavier frameworks.

### 3. Why TypeScript on the Frontend?
Given the complex data structures involved in parsing course codes, time slots, and venues, TypeScript was non-negotiable. It prevented runtime errors related to date/time parsing and ensured the frontend communicated with the backend with strict type safety.

## Key Features
*   **Dynamic Timetable Generation:** Users input registered courses and instantly generate a conflict-free schedule.
*   **Attendance Analytics:** Built-in tracking to monitor class attendance percentages, streaks, and missed classes against a strict 75% target.
*   **Class Spaces:** Multi-user environments allowing students to create or join class groups, with granular permissions for Admins, Class Reps, and Members to manage entries.
*   **Student Communication:** Keeping important class information, announcements, and updates where students can actually find them.

## Interface Showcase

<!-- Horizontal Image Grid -->
<table>
  <tr>
    <td width="33%" align="center" valign="top">
      <b>Timetable Architecture</b><br/><br/>
      <img src="IMG_20261029_131735_720.png" width="100%" style="border-radius: 8px; border: 1px solid #d0d7de;" alt="Timetable" />
    </td>
    <td width="33%" align="center" valign="top">
      <b>Attendance Tracking</b><br/><br/>
      <img src="IMG_20261029_132013_400.png" width="100%" style="border-radius: 8px; border: 1px solid #d0d7de;" alt="Attendance" />
    </td>
    <td width="33%" align="center" valign="top">
      <b>Class Spaces & RBAC</b><br/><br/>
      <img src="IMG_20261029_131957_841.png" width="100%" style="border-radius: 8px; border: 1px solid #d0d7de;" alt="Class Spaces" />
    </td>
  </tr>
</table>

<br/>

## Our Vision
We are building pathways for students to discover useful opportunities and participate in the digital economy. Starting in Nigeria. Building for Africa. 

If you're interested in what we're building, follow this organization and watch this space as we continue to develop the platform.

<br/>

<div align="center">
  <b>THESDEL</b><br/>
  <i>Learn. Grow. Become.</i>
</div>