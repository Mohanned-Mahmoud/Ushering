<div align="center">
  <img src="./readme-assets/insiders-logo-white.png" alt="INSIDERS Logo" width="240" />
  <h2>EVENT OPERATIONS COMMAND CENTER</h2>
  <p><strong>Complete Visual Administrator & Field Operations Manual</strong></p>
  <p><em>The ultimate step-by-step click-by-click operational guide for Event Directors, Project Managers, Floor Supervisors & Staffing Coordinators.</em></p>
</div>

---

## Table of Contents
1. [Platform Overview & Visual Layout](#1-platform-overview--visual-layout)
2. [Logging In & Team Account Management](#2-logging-in--team-account-management)
3. [The Live Command Dashboard (Daily Monitoring)](#3-the-live-command-dashboard-daily-monitoring)
4. [Reviewing & Approving Usher Profiles](#4-reviewing--approving-usher-profiles)
5. [The Events Directory & Status Pipeline](#5-the-events-directory--status-pipeline)
6. [Creating an Event: Step-by-Step Builder](#6-creating-an-event-step-by-step-builder)
   - [Step 1: Venue Selection & Intelligent Geofencing](#step-1-venue-selection--intelligent-geofencing)
   - [Step 2: Schedule, Multi-Day Logic & Tiered Pay Rates](#step-2-schedule-multi-day-logic--tiered-pay-rates)
   - [Step 3: Uniform Specifications & Ground Instructions](#step-3-uniform-specifications--ground-instructions)
7. [The Event Command Hub (Overview & Controls)](#7-the-event-command-hub-overview--controls)
8. [Staff Allocation, Operational Zones & Team Leads](#8-staff-allocation-operational-zones--team-leads)
   - [8.1 Creating Operational Teams & Zones](#81-creating-operational-teams--zones)
   - [8.2 Smart Candidate Filtering & Sourcing](#82-smart-candidate-filtering--sourcing)
   - [8.3 Appointing Team Leads (Supervisor Role)](#83-appointing-team-leads-supervisor-role)
   - [8.4 Custom Pay Overrides](#84-custom-pay-overrides)
9. [Live Attendance Audit: Dual-Factor Verification](#9-live-attendance-audit-dual-factor-verification)
   - [9.1 Live Attendance Headcount Counters](#91-live-attendance-headcount-counters)
   - [9.2 Inspecting Check-in Details & Live Selfies](#92-inspecting-check-in-details--live-selfies)
   - [9.3 Emergency Manual Check-in Override](#93-emergency-manual-check-in-override)
10. [Uniform Logistics & Automated Sizes Summary](#10-uniform-logistics--automated-sizes-summary)
11. [Deductions, Penalties & Disciplinary Suspensions](#11-deductions-penalties--disciplinary-suspensions)
    - [11.1 Automated Lateness Penalty Rules](#111-automated-lateness-penalty-rules)
    - [11.2 Applying Manual Infraction Deductions](#112-applying-manual-infraction-deductions)
    - [11.3 The Disciplinary Suspension Engine (Quick Presets)](#113-the-disciplinary-suspension-engine-quick-presets)
12. [Real-Time Staff Communication & Mobile Announcements](#12-real-time-staff-communication--mobile-announcements)
    - [12.1 Dedicated Event Announcements](#121-dedicated-event-announcements)
    - [12.2 System-Wide Agency Broadcasts](#122-system-wide-agency-broadcasts)
13. [Financial Management, Payouts & InstaPay Transfers](#13-financial-management-payouts--instapay-transfers)
    - [13.1 Monitoring Digital Wallets & Manual Balance Adjustments](#131-monitoring-digital-wallets--manual-balance-adjustments)
    - [13.2 Processing Payout Requests via InstaPay QR Codes](#132-processing-payout-requests-via-instapay-qr-codes)
14. [Exporting Branded Excel Payroll Sheets & Printable Rosters](#14-exporting-branded-excel-payroll-sheets--printable-rosters)
    - [14.1 One-Click Branded Excel Payroll Export](#141-one-click-branded-excel-payroll-export)
    - [14.2 High-Resolution Printable PDF Usher Sheet](#142-high-resolution-printable-pdf-usher-sheet)
15. [Client Public Feedback Loop & Floor Score Engine](#15-client-public-feedback-loop--floor-score-engine)
16. [Administrative Audit Log & Internal Accountability](#16-administrative-audit-log--internal-accountability)
17. [What the Usher Sees: Complete Mobile App Reference](#17-what-the-usher-sees-complete-mobile-app-reference)
18. [Operational Incident Playbook (12 Real-World Scenarios)](#18-operational-incident-playbook-12-real-world-scenarios)
19. [Standard Event Operations Checklist](#19-standard-event-operations-checklist)

---

## 1. Platform Overview & Visual Layout

The **INSIDERS Command Center** is organized into a clean, responsive layout designed for high-stress event environments:

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│  INSIDERS COMMAND CENTER                                                 Logged in as: Sarah (Admin)│
├───────────────┬──────────────────────────────────────────────────────────────────────────────────┤
│ 📊 Dashboard  │  PAGE CONTENT AREA                                                               │
│ 📅 Events     │                                                                                  │
│ 👥 Ushers     │  • Displays tables, forms, maps, interactive cards, and action buttons.          │
│ 📢 Broadcasts │                                                                                  │
│ 💰 Financials │  • Primary action buttons (Create Event, Export, Save) are in the top-right.     │
│ 🛡️ Audit Log  │                                                                                  │
│ ⚙️ Settings   │  • Slide-over drawers and pop-up dialogs open over this area without reload.     │
├───────────────┴──────────────────────────────────────────────────────────────────────────────────┤
│ 👤 Profile & Sign Out (Bottom of sidebar)                                                        │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

- **Left Sidebar Navigation:** Click any tab (`Dashboard`, `Events`, `Ushers`, `Broadcasts`, `Financials`, `Audit Log`, `Settings`) to jump between modules instantly.
- **Top Header Bar:** Displays current page title, breadcrumb links, and primary action buttons (e.g. `+ Create Event`, `Export Salary`, `Export PDF`).
- **Notification Toasts:** Temporary pop-up banners appear in the bottom-right corner whenever you complete an action (e.g. *"Usher assigned successfully"*, *"Broadcast sent"*).

---

## 2. Logging In & Team Account Management

### 2.1 Logging In
1. Open your browser and navigate to the web address provided by your organization.
2. In the **Email** box, enter your administrator email (e.g. `admin@artech.com`).
3. In the **Password** box, enter your secure password.
4. Click the blue **"Sign In"** button. You will be redirected immediately to the Dashboard.

### 2.2 Adding a New Coordinator to the Admin Team
Only **Super Administrators** can invite new team members to access the dashboard.
1. Click **Settings** (gear icon) at the bottom of the left sidebar.
2. Click on the **"Admin Management"** tab.
3. Click the **"Generate Invite Link"** button.
4. A secure, single-use registration URL is generated (e.g. `https://insiders.app/register-admin?token=xyz...`).
5. Click **"Copy Link"** and send it privately to the new coordinator.
6. When they open the link, they enter their name, email, and choose their password. Once submitted, their account is active. The link expires immediately after one use.

---

## 3. The Live Command Dashboard (Daily Monitoring)

<div align="center">
  <img src="./readme-assets/admin-dashboard.png" alt="Admin Command Dashboard" width="900" />
  <p><sub><strong>Figure 1:</strong> The Executive Command Dashboard with live metrics, monthly selector, and 6-month event completion trend.</sub></p>
</div>

The **Dashboard** (`/`) is your operational cockpit:

### 3.1 Step-by-Step Dashboard Usage:
1. **Selecting the Time Period:**
   - Look at the top right of the dashboard screen.
   - Click the **"Select Month"** dropdown.
   - Choose a specific month (e.g. *October 2026*) or select **"All Time"**.
   - Every metric card and chart will update in real time to reflect that window.

2. **Reading Key Metric Cards:**
   - **Active Ushers (Top Left):** Shows how many vetted, approved ushers are currently in your database ready for work.
   - **Pending Approvals (Top Second - Red Text):** Shows how many new ushers have submitted their profiles and are waiting for your review. **Click this card** to go straight to the approval queue!
   - **Active Events (Top Third):** Number of events currently in Draft, Published, or Ongoing state.
   - **Check-in Rate (Top Right):** Percentage of booked staff who have physically arrived and checked in for today’s active shifts.

3. **Analyzing the 6-Month Event Trends:**
   - The bar chart in the middle visualizes operational volume over the past half-year.
   - Compares **Total Events Scheduled** against **Events Successfully Completed**.

---

## 4. Reviewing & Approving Usher Profiles

<div align="center">
  <img src="./readme-assets/account-approval.png" alt="Account Approval Queue" width="850" />
  <p><sub><strong>Figure 2:</strong> The Usher Directory and Account Approval screen showing verification badges and status filters.</sub></p>
</div>

Before any usher can view shifts, apply to events, or earn money, their identity and professional appearance must be approved by an administrator.

### Step-by-Step Approval Walkthrough:
1. On the left sidebar, click **"Ushers"**.
2. Click the **Status Filter Dropdown** (next to the search bar) and select **"Pending"**.
3. You will see a list of candidate profiles waiting for verification.
4. **Open the Candidate Dossier:** Click on the candidate’s name or click the **Eye icon** on the right side of their row.
5. **Inspect the 4 Mandatory Approval Criteria:**
   - **Criterion 1 — Face & Grooming:** Look at their portrait photo. Confirm clear lighting, clean grooming, and a professional appearance.
   - **Criterion 2 — National ID / Identity:** Inspect the scanned ID card to verify legal age and legal name match.
   - **Criterion 3 — Apparel Sizes:** Verify their uniform measurements:
     - *T-Shirt Size* (S, M, L, XL, XXL)
     - *Shirt Collar Size* (36 to 46)
     - *Pants/Trousers Waist* (28 to 44)
     - *Shorts/Skirts* (S to XXL)
     - *Shoe Size* (36 to 46)
   - **Criterion 4 — Payment Credentials:** Verify their registered **InstaPay username** (`username@instapay`) or Mobile Wallet phone number.
6. **Take Action (Top Right Header Buttons):**
   - Click the green **"Approve"** button: Their status changes to `Active`. An instant push notification is sent to their phone: *"Your account has been approved! You can now apply for shifts."*
   - Click the red **"Decline"** button: If their ID is unreadable, fake, or photos violate standards.

### Exporting the Usher Database:
- Look at the top right of the Ushers list screen.
- Click the **"Export CSV"** button.
- An Excel-compatible `.csv` file will download instantly, containing contact details, ratings, balance, and wardrobe measurements for all filtered ushers.

---

## 5. The Events Directory & Status Pipeline

<div align="center">
  <img src="./readme-assets/all-events.png" alt="All Events Screen" width="900" />
  <p><sub><strong>Figure 3:</strong> The Events Directory displaying dates, venue pins, staffing counters, and status badges.</sub></p>
</div>

1. Click **"Events"** in the left sidebar to open the master shift directory.
2. **Search Bar:** Type an event name or venue name to find it immediately.
3. **Status Badges Explained:**
   - <span style="background:#6b7280;color:white;padding:2px 8px;border-radius:4px;font-size:12px;">Draft</span> — Visible **only to administrators**. Ushers cannot see this shift. Use this mode while planning teams and budget.
   - <span style="background:#2563eb;color:white;padding:2px 8px;border-radius:4px;font-size:12px;">Published</span> — Live on the mobile app. Ushers can browse, view call times, review rates, and click "Apply".
   - <span style="background:#16a34a;color:white;padding:2px 8px;border-radius:4px;font-size:12px;">Completed</span> — Event has concluded, check-in data is finalized, and payroll calculations are locked.
4. **Opening an Event:** Click the event title or click the **Eye icon** on any row to open the complete operations workspace for that shift.

---

## 6. Creating an Event: Step-by-Step Builder

Click the blue **"+ Create Event"** button at the top-right of the Events screen.

---

### Step 1: Venue Selection & Intelligent Geofencing

<div align="center">
  <img src="./readme-assets/new-event1.png" alt="Event Creation - Venue and Geofencing" width="900" />
  <p><sub><strong>Figure 4:</strong> Selecting venue location, popular Egyptian hub shortcuts, and setting the GPS check-in boundary.</sub></p>
</div>

1. **Event Title:** Enter a descriptive, professional name (e.g. *"Egypt Energy Expo 2026 — VIP Protocol"*).
2. **Venue Search or Quick Select:**
   - In the **Venue Location** field, start typing the venue name (e.g. *"Cairo International Convention Centre"*).
   - Or click on one of the **Popular Egyptian Venues** quick-select chips:
     - `EIEC — Egypt International Exhibition Center`
     - `CICC — Cairo International Convention Centre`
     - `El Gouna Arena — Red Sea`
     - `Grand Egyptian Museum (GEM) — Giza`
     - `New Capital Sports City — New Administrative Capital`
3. **Adjusting the Map Pin:**
   - An interactive Leaflet map will load the coordinates.
   - **Click and drag the blue map marker** to place it exactly at the **Crew Entrance / Staff Gate** rather than the general venue center.
4. **Choosing the Arrival Radius Preset:**
   - Under the map, click one of the radius preset buttons:
     - **50 meters:** For compact hotel ballrooms, banquet halls, and closed indoor stages.
     - **100 meters (Recommended Default):** Standard for exhibition halls and conferences.
     - **250 meters:** For large outdoor sports arenas or resorts where staff parking is slightly distant.
     - **500 – 1000 meters:** For massive multi-gate mega festivals.

---

### Step 2: Schedule, Multi-Day Logic & Tiered Pay Rates

<div align="center">
  <img src="./readme-assets/new-event2.png" alt="Event Creation - Schedule and Requirements" width="900" />
  <p><sub><strong>Figure 5:</strong> Configuring start/end call times, multi-day pay multipliers, and attire specifications.</sub></p>
</div>

1. **Shift Schedule:**
   - Pick the **Start Date** and **Start Time** (e.g. `2026-11-01` at `08:00 AM`).
   - Pick the **End Date** and **End Time** (e.g. `2026-11-03` at `06:00 PM`).
   - *Automatic Multi-Day Calculation:* If your end date is different from the start date, the system automatically detects this as a multi-day event (e.g. 3 days) and will multiply daily pay rates accordingly in payroll exports.
2. **Check-in Window (Arrival Buffer):**
   - Choose how many minutes before call time check-in opens (e.g. `5 minutes`, `15 minutes`, or `30 minutes`). Ushers cannot check in before this window opens.
3. **Tiered Pay Rates:**
   - **Leader Rate (EGP / Day):** Enter the daily compensation for appointed Supervisors (e.g. `1,200`).
   - **Regular Rate (EGP / Day):** Enter the daily compensation for standard ushers (e.g. `1,000`).

---

### Step 3: Uniform Specifications & Ground Instructions

1. **Dress Code Guidelines:**
   - Be specific so staff arrive properly attired (e.g. *"Full Black Suit, Plain White Formal Shirt, Black Necktie, Black Leather Oxford Shoes. No sneakers, no oversized blazers"*).
   - This appears prominently on the usher's phone upon assignment.
2. **Operational Instructions:**
   - Enter meeting point details, meal provision notes, and client contact guidelines (e.g. *"Gather at Gate 4 security check by 07:45 AM. Staff breakfast provided. Turn personal phones to silent mode"*).
3. **Saving the Event:**
   - Click the black **"Create Event"** button at the bottom.
   - The event is created in **Draft** mode, allowing you to configure teams and review staff before making it visible to the public.

---

## 7. The Event Command Hub (Overview & Controls)

<div align="center">
  <img src="./readme-assets/event-overview.png" alt="Event Details Overview Tab" width="900" />
  <p><sub><strong>Figure 6:</strong> Event Overview Tab with live counters, schedule details, wardrobe summary, and feedback link.</sub></p>
</div>

When you open an event, you are in the **Event Command Hub**.

### Top Control Bar Buttons:
- **"Publish Event" / "Unpublish":** Click to toggle between Draft and Published. When published, ushers can apply.
- **"Export PDF":** Downloads the high-resolution printable on-ground roster with large portraits.
- **"Export Salary":** Generates the official branded Excel payroll sheet with InstaPay links.
- **"Complete & Process":** Finalizes the event post-wrap-up, closing check-ins and calculating total earnings.

### The 3 Core Sub-Tabs:
- **Overview Tab:** Displays schedule, financial budget, attendance counters, uniform sizing breakdown, and the client rating link.
- **Staff & Teams Tab:** Where you build operational teams, assign personnel, and filter applicants.
- **Deductions Tab:** Where you view and manage lateness and behavior penalties.

---

## 8. Staff Allocation, Operational Zones & Team Leads

<div align="center">
  <img src="./readme-assets/event-staff-and-teams.png" alt="Event Staff and Teams Tab" width="900" />
  <p><sub><strong>Figure 7:</strong> Staff & Teams tab showing team management on the left, assigned staff in the middle, and smart filters on the right.</sub></p>
</div>

Click the **"Staff & Teams"** tab inside your event.

---

### 8.1 Creating Operational Teams & Zones
1. Look at the **Teams Column** on the left.
2. In the **"New Team Name"** box, type the zone name (e.g. *"VIP Protocol"*, *"Main Stage"*, *"Registration Hall"*, *"Gate 2"*, or *"Airport Arrivals"*).
3. (Optional) In the text box below, type specific zone instructions (e.g. *"Report to VIP desk, hold guest lists"*).
4. Click the black **"Add"** button.
5. Your new team is created. Clicking on any team filters the middle staff view to show only the ushers assigned to that specific zone.

---

### 8.2 Smart Candidate Filtering & Sourcing
Look at the **Candidate Column** on the right side:
1. When an event is published, applicants appear here under **Pending Applicants**.
2. **Using the Smart Filters:**
   - **Gender Filter:** Choose *Male* or *Female*.
   - **Language Filter:** Select required spoken language (e.g. *English*, *French*, *German*, *Arabic*).
   - **Minimum Star Rating:** Select `4.0+` or `4.5+` to restrict to top-rated staff.
   - **Physical Specs:** Filter by Height (e.g. `175cm+`), Dress size, or Shoe size.
3. **Assigning to Event:** Click the green **"Assign"** button next to any candidate. They immediately move into the active staff list and receive a shift notification.

---

### 8.3 Appointing Team Leads (Supervisor Role)
- In the middle staff roster, locate the usher you wish to make a supervisor.
- Click the **Crown Icon** on their row.
- **Automatic Actions:**
  - Their badge turns into **Team Lead** with a gold crown.
  - Their daily wage automatically upgrades to the higher **Leader Pay Rate**.
  - On the printed PDF roster, their row is highlighted so security knows they lead that zone.
- Click the crown icon again if you need to demote them back to Regular Usher.

---

### 8.4 Custom Pay Overrides
If you negotiated an agreed special wage with a particular senior staff member:
1. In their row in the staff roster, find the **Pay Input Box**.
2. Type the custom amount (e.g. `1500`).
3. Click outside the box. The payroll engine will now use `1,500 EGP` for this person instead of the default rate.

---

## 9. Live Attendance Audit: Dual-Factor Verification

INSIDERS eliminates ghost attendance by combining satellite GPS boundaries with mandatory live camera selfies.

---

### 9.1 Live Attendance Headcount Counters
On the **Overview Tab**, look at the **Attendance Summary** card:
- **Total Assigned (Grey):** Total staff confirmed for the shift.
- **Checked In (Blue):** Staff physically verified inside the venue with live selfie approved.
- **Pending Applicants (Yellow):** Waitlist candidates.
- **Late / No-Show (Red):** Staff who missed the designated call time.

---

### 9.2 Inspecting Check-in Details & Live Selfies

<div align="center">
  <img src="./readme-assets/checkin-details-modal.png" alt="Check-in Details Modal with Selfie Verification" width="750" />
  <p><sub><strong>Figure 8:</strong> The Check-in Details modal displaying arrival timestamps, lateness duration, and verified live selfie photograph.</sub></p>
</div>

1. In the staff roster, find any staff member marked with the blue `Checked In` badge.
2. Click the **"Check-in Details"** button on their row.
3. **The Inspection Modal Displays:**
   - **Check-in Time:** The exact time they tapped check in (e.g. `Nov 1, 8:48 AM`).
   - **Checkout Time:** When they ended their shift.
   - **Late Arrival:** Displays `0 mins` in green, or exact lateness (e.g. `14 mins`) in red.
   - **Early Leave:** Displays if they departed before shift conclusion.
   - **Selfie / Proof Photograph:** Inspect the large, uncompressed photo taken live by their phone camera.
4. **Audit Rules:**
   - Verify that the photo is a real-time live selfie (not a photo of a photo or a static ceiling).
   - Verify that they are wearing the mandatory black blazer, tie, or formal uniform.
   - If compliant, close the modal. If non-compliant, you can issue an infraction deduction.

---

### 9.3 Emergency Manual Check-in Override
If an usher is standing in front of you, but their phone battery died, their camera is malfunctioning, or they have no internet data:
1. Verify their identity and uniform in person.
2. In the staff roster, locate their name.
3. Click the menu dots `•••` on their row and select **"Manual Check-in"**.
4. The system immediately checks them in and logs your admin ID in the Audit Log for internal accountability.

---

## 10. Uniform Logistics & Automated Sizes Summary

Inside the **Overview Tab**, look at the **Sizes Summary Card**:

```
┌────────────────────────────────────────────────────────────────────────┐
│                        SIZES SUMMARY CARD                              │
│             Aggregate of sizes for all active ushers                   │
├────────────────────────────────────────────────────────────────────────┤
│ T-SHIRTS:     [ M : 18 ]   [ L : 25 ]   [ XL : 12 ]   [ XXL : 3 ]      │
│ SHIRTS:       [ 38 : 6 ]   [ 40 : 15 ]  [ 42 : 20 ]   [ 44 : 8 ]       │
│ PANTS:        [ 30 : 8 ]   [ 32 : 22 ]  [ 34 : 15 ]   [ 36 : 6 ]       │
│ SHOES:        [ 41 : 5 ]   [ 42 : 14 ]  [ 43 : 18 ]   [ 44 : 12 ]      │
└────────────────────────────────────────────────────────────────────────┘
```

- **Zero Manual Surveys:** You never need to message 50 ushers on WhatsApp asking *"What is your T-shirt size?"*.
- The moment you assign ushers to the event, this card aggregates their exact profile measurements.
- **Copy & Send to Warehouse:** Simply read the card quantities and send them to your uniform supplier or warehouse coordinator 3 days before shift start.

---

## 11. Deductions, Penalties & Disciplinary Suspensions

---

### 11.1 Automated Lateness Penalty Rules

<div align="center">
  <img src="./readme-assets/deduction-rules.png" alt="Deduction Rules Tab" width="900" />
  <p><sub><strong>Figure 9:</strong> The Deduction Rules tab showing automated late arrival rules and live total deduction tracker.</sub></p>
</div>

1. Open your event and click the **"Deductions"** tab.
2. Click **"+ Add Rule"**.
3. Configure the rule parameters:
   - **Rule Name:** e.g. *"Lateness Penalty (> 15 mins)"*.
   - **Amount:** e.g. `50 EGP` (flat amount) or percentage.
   - **Condition:** Automatically applies to any staff member whose check-in timestamp exceeds the grace period.
4. The live **Total Deductions Banner** at the top displays the total amount deducted across the entire event.

---

### 11.2 Applying Manual Infraction Deductions
If a staff member broke on-ground protocol (e.g. eating in VIP lounge, using personal phone on duty, chewing gum, or missing uniform tie):
1. In the **Staff & Teams** tab, find the usher’s row.
2. Click the red **"Deduct"** button.
3. Enter the deduction amount (e.g. `100 EGP`).
4. Type the reason clearly (e.g. *"Phone usage during VIP reception"*).
5. Click **"Apply"**. The deduction is instantly reflected on their payroll subtotal.

---

### 11.3 The Disciplinary Suspension Engine (Quick Presets)

<div align="center">
  <img src="./readme-assets/suspension-dialog.png" alt="Change Suspension Duration Modal" width="700" />
  <p><sub><strong>Figure 10:</strong> The Suspension Engine dialog with one-click quick-select presets from 1 Week to 1 Year.</sub></p>
</div>

For severe misconduct (unexcused no-shows, abandoning posts, or guest harassment):
1. Go to **Ushers** and click on the member's profile.
2. Click the orange **"Suspend"** button at the top right.
3. Click one of the **Quick-Select Presets**:
   - `1 Week` — Minor first unexcused lateness.
   - `2 Weeks` — Late cancellation under 12 hours.
   - `1 Month` — Standard penalty for unexcused No-Show.
   - `3 Months` — Repeated unreliability or client complaints.
   - `6 Months` — Serious safety or behavioral violation.
   - `1 Year` — Gross misconduct.
   - Or pick a **Custom Date** on the calendar.
4. Click **"Confirm Suspension"**.

#### What Happens Automatically:
- Status changes immediately to `Suspended`.
- **All future event bookings for this usher are automatically cancelled.**
- Their mobile app is locked out from viewing or applying to any new events.
- When the date expires, their account automatically unlocks, or a Super Admin can click **"Unsuspend"**.

---

## 12. Real-Time Staff Communication & Mobile Announcements

---

### 12.1 Dedicated Event Announcements

<div align="center">
  <img src="./readme-assets/event-chat.png" alt="Event Announcements Modal" width="750" />
  <p><sub><strong>Figure 11:</strong> Event Announcement drawer with broadcast stream and instant lock-screen mobile push alert.</sub></p>
</div>

1. Inside any event, click the **Message/Chat icon** on the top header bar.
2. A slide-over panel opens showing the broadcast chat stream.
3. Type your announcement (e.g. *"Attention all Gate 1 staff: VIP motorcade entering in 10 minutes. Assume protocol positions immediately."*).
4. Click **"Send Broadcast"**.
5. **Immediate Result:**
   - Message is posted to the shift chat.
   - Every assigned usher receives an instant **lock-screen Push Notification** on their smartphone.

---

### 12.2 System-Wide Agency Broadcasts

<div align="center">
  <img src="./readme-assets/broadcasts-screen.png" alt="System Broadcasts Screen" width="750" />
  <p><sub><strong>Figure 12:</strong> System-wide broadcasts module for agency recruitment and general policy announcements.</sub></p>
</div>

1. Click **"Broadcasts"** on the left navigation sidebar.
2. Type your message in the composer box.
3. Select recipient filter: **All Active Ushers**.
4. Click **"Send Broadcast"**. Every usher registered in your company's network receives the notification.

---

## 13. Financial Management, Payouts & InstaPay Transfers

Click **"Financials"** on the left menu.

---

### 13.1 Monitoring Digital Wallets & Manual Balance Adjustments
- On the **Balances** tab, view every usher’s accumulated wallet balance.
- **Adding Bonuses or Adjustments:**
  1. Click the **"Adjust Balance"** button next to an usher.
  2. Select **Credit** (add money) or **Debit** (deduct money).
  3. Enter the amount (e.g. `200 EGP`).
  4. Write the reason (e.g. *"Overtime bonus for 3 extra hours"*).
  5. Click **"Submit"**.

---

### 13.2 Processing Payout Requests via InstaPay QR Codes
When an usher requests their money through the mobile app:
1. Open **Financials** and click the **"Payouts"** tab.
2. Pending requests are listed with their registered **InstaPay Handle** or **Vodafone Cash Number**.
3. Click the **QR Code icon** next to their request.
4. An **InstaPay Transfer QR Code** appears on your computer screen.
5. Open your corporate banking or InstaPay app on your phone, scan the QR code, and send the payment in 10 seconds.
6. Click **"Mark as Paid"** in the dashboard and paste the transaction reference number.
7. The amount is automatically subtracted from the usher’s digital wallet.

---

## 14. Exporting Branded Excel Payroll Sheets & Printable Rosters

---

### 14.1 One-Click Branded Excel Payroll Export

<div align="center">
  <img src="./readme-assets/salary-sheet-excel.png" alt="Excel Salary Sheet Export" width="850" />
  <p><sub><strong>Figure 13:</strong> Official Branded Excel Payroll Sheet featuring Supervisors and Ushers sections, formulas, and InstaPay links.</sub></p>
</div>

1. Open any active or completed event.
2. In the top-right header, click the **"Export Salary"** button.
3. An `.xlsx` spreadsheet downloads instantly:
   - **Corporate Navy (`#00003087`) & Teal (`#0070C0`) Headers.**
   - **Split Sections:** Neatly divides staff into **Supervisors** (at Leader Rate) and **Ushers** (at Regular Rate).
   - **Calculated Columns:** Full Name, Number of Days Worked, Base Salary, Deductions, and Net Subtotal.
   - **Automated Accounting Formulas:** Uses Excel `SUM` formulas so finance teams can verify totals.
   - **Clickable InstaPay Links:** Clicking the link next to any employee initiates a direct digital transfer.

---

### 14.2 High-Resolution Printable PDF Usher Sheet

<div align="center">
  <img src="./readme-assets/ushers-sheet-pdf.png" alt="Printable Ushers Sheet PDF Roster" width="650" />
  <p><sub><strong>Figure 14:</strong> High-Resolution Printable PDF Roster with 144px portraits, team zones, and physical signature boxes.</sub></p>
</div>

1. In the top-right header of your event, click the **"Export PDF"** button.
2. A printable document downloads:
   - **Enlarged High-Clarity Photos (144px × 144px):** Rendered at 2.5× DPI quality so gate security can visually confirm staff identities.
   - **Columns:** Portrait Photo, Full Legal Name, Operational Team/Zone, Role Badge (*Team Lead* vs *Regular*), and a **Blank Signature / Notes Column**.
   - **Footer Sizes Summary:** Appends uniform counts at the bottom for the wardrobe checkpoint.

---

## 15. Client Public Feedback Loop & Floor Score Engine

<div align="center">
  <img src="./readme-assets/ratings-feedback.png" alt="Ratings and Performance Screen" width="800" />
  <p><sub><strong>Figure 15:</strong> Ratings and performance dashboard tracking client stars, punctuality scores, and reliability grades.</sub></p>
</div>

### How to Send the Feedback Form to a Client:
1. When an event wraps up, click the green **"Complete & Process"** button at the top of the event page.
2. On the right side, in the **"Rate Event Link"** card, click **"Generate Link"**.
3. Click the **Copy** icon to copy the private web address (e.g. `https://insiders.app/feedback/abc123...`).
4. Send the link to your client or production director via WhatsApp or email.

### What the Client Does:
- The client opens the link on their phone or laptop (no login required).
- Gives an overall event star rating (1 to 5 stars).
- Rates each operational team individually (e.g. *VIP Protocol* vs *Registration Desk*).
- Leaves qualitative feedback comments.

### Automated Floor Score Calculation:
When the client submits their review, the platform recalculates the participating ushers' **Floor Score** using three weighted pillars:
$$\text{Floor Score} = (50\% \times \text{Client Rating}) + (30\% \times \text{Punctuality Score}) + (20\% \times \text{Reliability Score})$$

---

## 16. Administrative Audit Log & Internal Accountability

<div align="center">
  <img src="./readme-assets/audit-log.png" alt="Audit Log Screen" width="900" />
  <p><sub><strong>Figure 16:</strong> Immutable System Audit Log recording every admin action with timestamps and parameters.</sub></p>
</div>

Click **"Audit Log"** on the left menu *(Super Admins only)*:
- Every sensitive administrative action is logged with an immutable timestamp.
- **Recorded Events Include:** Account approvals, manual check-in overrides, deduction creations, salary adjustments, suspensions, and payout processing.
- **Admin Filter:** Select any coordinator’s name from the top dropdown to see a chronological ledger of all actions performed by that person.

---

## 17. What the Usher Sees: Complete Mobile App Reference

To guide staff over the phone, use these visual references of what the usher sees on their mobile app:

### 17.1 Home Dashboard, Shift Tabs & Field Profile
<div align="center">
  <table>
    <thead>
      <tr>
        <th align="center">🏠 Home & Floor Score</th>
        <th align="center">📅 My Events & Status Tabs</th>
        <th align="center">👤 Profile & Measurements</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center" width="33%"><img src="./readme-assets/home-usher.jpg" width="240" alt="Home Screen" /></td>
        <td align="center" width="33%"><img src="./readme-assets/my-events-usher.jpg" width="240" alt="My Events Screen" /></td>
        <td align="center" width="33%"><img src="./readme-assets/my-profile.jpg" width="240" alt="Profile Screen" /></td>
      </tr>
      <tr>
        <td align="center"><sub>Live wallet balance, Floor Score & upcoming shifts</sub></td>
        <td align="center"><sub>Tabs: Open, Pending, Accepted, Completed</sub></td>
        <td align="center"><sub>Uniform measurements, languages & payout history</sub></td>
      </tr>
    </tbody>
  </table>
</div>

---

### 17.2 Applying, Reviewing & Completing Shifts
<div align="center">
  <table>
    <thead>
      <tr>
        <th align="center">📥 Shift Application</th>
        <th align="center">⏳ Application Pending</th>
        <th align="center">✅ Shift Completed</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center" width="33%"><img src="./readme-assets/apply-to-event-usher.jpg" width="240" alt="Apply to Event" /></td>
        <td align="center" width="33%"><img src="./readme-assets/application-pending-usher.jpg" width="240" alt="Pending Application" /></td>
        <td align="center" width="33%"><img src="./readme-assets/event-done-usher.jpg" width="240" alt="Completed Event" /></td>
      </tr>
      <tr>
        <td align="center"><sub>Review venue, dress code & tap Apply</sub></td>
        <td align="center"><sub>Application under coordinator review</sub></td>
        <td align="center"><sub>Shift wrap-up with earnings added to wallet</sub></td>
      </tr>
    </tbody>
  </table>
</div>

---

### 17.3 Notifications, Earnings & GPS Check-in
<div align="center">
  <table>
    <thead>
      <tr>
        <th align="center">🔔 Alerts Stream</th>
        <th align="center">📋 Shift Details Dialog</th>
        <th align="center">💰 Balance Ledger</th>
        <th align="center">📍 GPS Check-in Screen</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center" width="25%"><img src="./readme-assets/alerts-tab-usher.jpg" width="220" alt="Alerts" /></td>
        <td align="center" width="25%"><img src="./readme-assets/message-opend.jpg" width="220" alt="Alert Details" /></td>
        <td align="center" width="25%"><img src="./readme-assets/balance-usher.jpg" width="220" alt="Balance" /></td>
        <td align="center" width="25%"><img src="./readme-assets/checkin-screen.png" width="220" alt="GPS Check-in" /></td>
      </tr>
      <tr>
        <td align="center"><sub>Push updates feed</sub></td>
        <td align="center"><sub>Shift briefing details</sub></td>
        <td align="center"><sub>Withdrawal request trigger</sub></td>
        <td align="center"><sub>Venue GPS verification</sub></td>
      </tr>
    </tbody>
  </table>
</div>

---

## 18. Operational Incident Playbook (12 Real-World Scenarios)

### Incident 1: Usher Is at the Venue, but App Says "Outside Boundary"
* **Situation:** Usher stands at the staff gate, but when tapping Check In, the app says: *"You are 110m away from venue."*
* **Resolution:**
  1. Open your event page.
  2. Click **Edit Event**.
  3. Expand the **Geofence Radius** from `100m` to `250m` or `500m`.
  4. Click **Save**. Tell the usher to tap **"GPS Check In"** again.

---

### Incident 2: Usher Phone Battery Died, Broken Camera, or No Data
* **Situation:** Staff member is physically present on time, but their phone is dead or camera lens is shattered.
* **Resolution:**
  1. Confirm their identity and inspect their uniform in person.
  2. In your event’s staff roster, find their name.
  3. Click menu dots `•••` on their row → Click **"Manual Check-in"**.
  4. They are now verified as present and eligible for pay.

---

### Incident 3: Usher Does Not Show Up on Event Morning (No-Show)
* **Situation:** It is 20 minutes past call time and an usher has not checked in and does not answer calls.
* **Resolution:**
  1. In the staff roster, click **"Remove"** on their row.
  2. Click **"Flag No-Show"** to apply the automated rating drop.
  3. Look at the **Candidates list** on the right side of the screen.
  4. Filter by rating `4.0+` and click **"Assign"** on a nearby candidate. An instant alert will be dispatched to their phone.
  5. Go to the absent usher's profile and click **"Suspend"** → Choose **1 Month**.

---

### Incident 4: Usher Cancels Last-Minute (Under 24 Hours)
* **Situation:** An usher messages late at night cancelling tomorrow morning's shift.
* **Resolution:**
  1. In the event roster, remove the usher.
  2. The system automatically records a **Late Cancellation Penalty**.
  3. Assign an available replacement from the candidate queue.
  4. Apply a **2-Week Suspension** if unexcused.

---

### Incident 5: Usher Shows Up Late or Leaves Early
* **Situation:** An usher arrives 25 minutes late.
* **Resolution:**
  1. When they check in, the system marks their arrival in red with exact minutes late.
  2. If an automated lateness rule is active, the penalty is deducted automatically.
  3. If not, open the **Deductions** tab, click **"Add Deduction"**, enter `50 EGP`, and write: *"25 minutes unexcused lateness"*.

---

### Incident 6: Usher Disputes a Salary Deduction
* **Situation:** An usher claims their lateness was caused by a client-provided shuttle bus delay.
* **Resolution:**
  1. Open the event's **Deductions** tab.
  2. Click the **Trash icon** next to the deduction to delete it.
  3. If the event is already finalized, go to **Financials → Balances**, click **"Adjust Balance"**, choose **Credit**, enter `50 EGP`, and write: *"Reimbursement for approved transit delay"*.

---

### Incident 7: Client Requests Additional Staff Mid-Event
* **Situation:** At 11:00 AM, the client requests 6 additional staff for the evening banquet.
* **Resolution:**
  1. Click **"Smart Auto-Assign"** in the event details.
  2. Enter `6` staff, set minimum rating to `4.5`, and choose gender if requested.
  3. Click **"Execute Auto-Assign"**.
  4. The system immediately assigns the best available candidates and dispatches mobile push alerts with venue coordinates.

---

### Incident 8: Client Lost or Didn't Receive the Feedback Link
* **Situation:** The client states they cannot find the feedback link.
* **Resolution:**
  1. Open the event page.
  2. In the right-hand **Rate Event Link** box, click **"Regenerate Link"**.
  3. Click **Copy** and send the fresh URL to the client.

---

### Incident 9: Usher Requests an Urgent Cash Payout On Site
* **Situation:** An usher asks to be paid immediately post-event.
* **Resolution:**
  1. Have the usher open their app and tap **"Request Payout"**.
  2. In your Admin dashboard, open **Financials → Payouts**.
  3. Click the **QR Code** button next to their request.
  4. Scan the QR code with your mobile banking or InstaPay app to execute the instant transfer.
  5. Click **"Mark as Paid"** in the dashboard.

---

### Incident 10: Uniform Size Shortage on Site
* **Situation:** A male usher registered as Medium, but requires a Large shirt upon arrival.
* **Resolution:**
  1. Exchange the shirt from backup wardrobe stock.
  2. Open the usher’s profile in **Ushers → [Usher Name]**.
  3. Update their Shirt size to `L` and click **Save** so future events pull the correct size automatically.

---

### Incident 11: An Usher Inappropriately Uses Their Phone on Duty
* **Situation:** Supervisor catches an usher browsing social media in the VIP reception.
* **Resolution:**
  1. Warn the usher verbally on site.
  2. In the staff roster, click **"Deduct"** on their row.
  3. Enter `100 EGP` and state: *"Phone usage during VIP reception"*.
  4. Deducted funds are automatically factored into the Excel payroll sheet.

---

### Incident 12: Admin Forgot Password
* **Situation:** A coordinator cannot sign in.
* **Resolution:**
  - Contact a **Super Administrator**.
  - The Super Admin generates a fresh invite/access link or updates the coordinator's credentials directly.

---

## 19. Standard Event Operations Checklist

Print or follow this operational checklist for every event:

### 📅 Phase 1: Planning (3 to 5 Days Before Event)
- [ ] Create the event with exact start/end dates and times.
- [ ] Pinpoint the venue location on the map and set geofence radius (`100m`).
- [ ] Set Leader Rate and Regular Usher pay rates.
- [ ] Publish the event so candidates can apply.
- [ ] Review applicants and assign staff using candidate filters.
- [ ] Appoint Team Leads for each operational zone (Crown Icon).
- [ ] Open the **Sizes Summary** card and order exact uniform quantities.

### 📋 Phase 2: Eve of Event (24 Hours Before)
- [ ] Send an operational briefing announcement via the **Event Chat Dialog**.
- [ ] Click **"Export PDF"** and print the **Printable PDF Ushers Sheet** for gate security.
- [ ] Verify that all assigned ushers have confirmed attendance.

### 🚀 Phase 3: Event Day (Shift Execution)
- [ ] Monitor the **Attendance Summary** card as staff arrive.
- [ ] Open the **Check-in Details Modal** to audit live selfie photos and uniform compliance.
- [ ] Execute **Manual Check-in** only for verified staff experiencing dead battery or device failure.
- [ ] Broadcast urgent shift announcements as needed throughout the day.

### 💰 Phase 4: Post-Event Wrap-up & Settlements
- [ ] Click **"Complete & Process"** to finalize attendance.
- [ ] Click **"Generate Feedback Link"** and send it to the client.
- [ ] Click **"Export Salary"** to generate the branded Excel payroll sheet.
- [ ] Open **Financials → Payouts** to disburse payouts via InstaPay.

---

<div align="center">
  <sub>INSIDERS Event Staffing & Crowd Operations Platform • Operations Manual</sub>
</div>
