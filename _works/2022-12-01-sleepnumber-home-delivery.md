---
title: Dream Delivery
description: How a field research-driven redesign reduced inventory loss and restored technician trust at Sleep Number
category: Mobile, Web, Research
date: 2022-12-01 08:01:35 +0300
role: Experience Manager
image: '/images/work/sleepnumber-cover.png'
---

## The Business Problem

Sleep Number's home delivery operation ran on a homegrown mobile app that had quietly become a liability. Inventory was walking out the door — not through theft, but through a broken returns process that technicians didn't trust and couldn't reliably complete. Customer care agents were manually resending return labels. The app timed out mid-job, wiping data. Nobody had mapped the full picture.

This wasn't a UX polish project. It was a revenue and retention problem wearing a UX costume.

## My Role

Lead UX Designer and Experience Manager. I owned research, synthesis, design, and stakeholder alignment end-to-end across the delivery, warehouse, and customer care touchpoints.

## Discovery: Getting Out of the Building

Before touching Figma I spent time in the field — riding along with delivery technicians, observing warehouse staff use the app in real conditions, and shadowing customer care agents handling exchanges and returns.

What I found didn't match what stakeholders thought the problem was. The returns flow wasn't just confusing — technicians had learned to work around it in ways that looked like compliance but produced data that was useless downstream. The app timeout issue was causing technicians to restart jobs mid-delivery. Customer care agents had developed their own informal label-resending queue because the system made it too hard to do it right the first time.

I mapped all of it into an end-to-end service blueprint — order placement through return and exchange — which became the shared artifact that aligned stakeholders on the actual scope of the problem.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work/sleepnumber/sbp.png" loading="lazy" alt="Work">
  </div>
</div>

## The Bets We Made

The most significant finding didn't come from a stakeholder interview or a data pull — it came from riding along with technicians in the field. Missed deliveries were being sent all the way back to the main distribution hub, rescheduled, and set for redelivery two weeks or more out. By that point, many customers had canceled out of frustration — and the returned inventory couldn't be reshipped. It got parted out.

The hold for delivery queue was the direct response to that insight. Rather than routing missed deliveries back to the hub, technicians could now hold inventory regionally, track it in the app, and retry delivery within two to three days.

### Hold for Delivery Queue

While improved inventory management was the foremost concern, accessibility, consistency, and usability was paramount. we redesigned all the mobile app screens to ensure a smoother and more intuitive user experience using a component-based, atomic design approach.

### Streamlined Returns with Gamification

The core insight: technicians weren't skipping the returns process because they were lazy — they skipped it because it was unreliable. We rebuilt the flow to be faster and more forgiving, then added a gamification layer that made error-free returns a visible team metric. Compliance isn't a UX problem you solve with better UI alone — you need behavioral incentive.

### Session Management

A keep-alive 'Still working?' prompt addressed app timeouts that were causing data loss on active jobs. Small lift, high-trust signal to technicians that the app was on their side.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work/sleepnumber/stillworking.png" loading="lazy" alt="Work">
  </div>
</div>

### Customer Care Wizard UI

Agents were navigating a fragmented system to facilitate exchanges. A guided wizard reduced decision points and built label generation directly into the flow — eliminating the manual resend queue entirely.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work/sleepnumber/feedback.png" loading="lazy" alt="Work">
    <img src="/images/work/sleepnumber/sad_happy.png" loading="lazy" alt="Work">
  </div>
</div>

### Super-User Profiles for Smaller Markets
 
Smaller markets shared devices across technicians. Profile switching without full logout reduced friction and fixed data attribution problems in a segment that was disproportionately impacted.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work/sleepnumber/homescreen.png" loading="lazy" alt="Work">
    <img src="/images/work/sleepnumber/gamification.png" loading="lazy" alt="Work">
    <img src="/images/work/sleepnumber/scanscreen.png" loading="lazy" alt="Work">
  </div>
</div>

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work/sleepnumber/location_1.png" loading="lazy" alt="Work">
    <img src="/images/work/sleepnumber/location_2.png" loading="lazy" alt="Work">
    <img src="/images/work/sleepnumber/location_3.png" loading="lazy" alt="Work">
  </div>
</div>

## Outcomes

Physical inventory loss dropped to near zero following the introduction of the hold for delivery queue. That single feature — born entirely from field observation — represented the clearest return on the research investment.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work/sleepnumber/exchanges.png" loading="lazy" alt="Work">
  </div>
</div>

The gamification of returns produced something unexpected: technicians started competing. Load truck-off competitions emerged organically, with teams comparing who could complete load-in and load-out fastest. Compliance became a team dynamic, not a mandate.

Customer care agents reported significantly fewer return label resend requests following the wizard UI rollout, reducing overhead that had become normalized as just part of the job.

<div class="gallery-box">
  <div class="gallery">
    <img src="/images/work/sleepnumber/email.png" loading="lazy" alt="Work">
  </div>
</div>

## What I'd Do Differently

Establishing clearer baseline metrics before the project started would have made the outcome story tighter. We knew things improved — we were less precise about by how much. On future engagements I instrument the measurement plan before design begins.