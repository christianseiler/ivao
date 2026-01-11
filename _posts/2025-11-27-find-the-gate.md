---
title: FindTheGate
categories: [Aurora, Plugins, Tools]
tags: [aurora, events, gates, ivao]
img_path: /assets/images/2025-11-27-find-the-gate/
image: find-the-gate-icon.png
---

FindTheGate helps event staff and air traffic controllers quickly find the right gate for arriving and departing aircraft during IVAO events.
It automatically loads all stand bookings from the event hosted in the IVAO Germany Division Center and shows you which stands are free, occupied or reserved.
Based on this information, the tool suggests the booked gate for flights that already have a reservation, and for unbooked flights it automatically recommends suitable free stands.

<b><a href="https://christianseiler.github.io/FindTheGate/FindTheGate.application" download>Click to Download</a></b>  
<br>
<br>

---

## Basic features

- Visual timeline showing current and upcoming stand usage  
- Compact gate suggestion popup that takes very little screen space and can be placed directly over the Aurora window  
- Smooth Aurora integration: click on a label to highlight the stand and assign it directly
- Automatic import of event bookings from the IVAO Germany Division Center  
- Intelligent stand suggestions for unbooked flights based on airline and aircraft category (WTC)  
- Quick search for stands by callsign  
- Find free and suitable gates instantly  
- Light and dark themes  
- Works offline using cached event data  

---

## Screenshots

<p><img src="find-the-gate-timeline-light.png" align="left" alt="Timeline (light mode)"></p>
<div align="center">Timeline view in light mode: see stand occupancy at a glance</div>
<br>

<p><img src="find-the-gate-timeline-dark.png" align="left" alt="Timeline (dark mode)"></p>
<div align="center">Timeline in dark mode with clear stand availability indicators</div>
<br>

<p><img src="find-the-gate-search-by-callsign.png" align="left" alt="Search gate by callsign"></p>
<div align="center">Search by callsign: instantly find the assigned stand</div>
<br>

<p><img src="find-the-gate-search-by-gate.png" align="left" alt="Search by gate"></p>
<div align="center">Jump to gate: filter gates by availability and wake category (WTC)</div>
<br>

<p><img src="find-the-gate-settings.png" align="left" alt="Settings"></p>
<div align="center">Settings: event selection and basic configuration</div>
<br>

<p><img src="find-the-gate-popup-light.png" align="left" alt="Gate suggestion popup (light mode)"></p>
<div align="center">Gate suggestion popup in light mode: shows recommended stands with explanations</div>
<br>

<p><img src="find-the-gate-popup-dark.png" align="left" alt="Gate suggestion popup (dark mode)"></p>
<div align="center">Gate suggestion popup in dark mode: quick assignment with clear stand details</div>
<br>

---

## Typical workflows

1. Select the current Event (or let the app restore your last selection).  
2. Connect to Aurora (IP/hostname configurable). The app automatically follows Aurora's selected traffic.  
3. When a flight is selected, FindTheGate suggests the assigned or most suitable stand.  
4. Accept a suggestion to assign the gate.  

---

## Changelog

### [1.1.0] – 2026-01-11

#### New

- Added improved gate assignments for Hamburg (EDDH)

#### Bug Fixes

- Fixed event restoration and gate selection issues on startup 

### [1.0.0] – 2025-11-27

#### New

- Initial release of FindTheGate  
- Automatically loads stand bookings from the IVAO Germany Division Center  
- Real-time integration with Aurora (follows selected traffic)  
- Gate suggestions for both booked and unbooked flights  
- Compact gate suggestion popup for quick assignment  
- Timeline view showing current and upcoming stand occupancy  
- Search by callsign and search for free stands  
- Light and dark themes  

---

## Credits

- Integration using Aurora third-party docs and the DivisionCenter Events API (preview).