# MITR Website PRD

## Overview

MITR is the peer support and wellness body of IIT Madras, comprising faculty and students trained in basic counselling skills and empathy to support students according to their needs.  MITR is positioned within the IIT Madras wellness ecosystem alongside the Wellness Centre and related support services, and its stated motto is that no one on campus should be unattended in their emotional distress.  

This product requirements document defines a public-facing MITR website that helps students quickly understand what MITR does, find the right support path, access wellness resources, and learn about MITR’s team, initiatives, and annual work.   The site should be trust-first, calm, mobile-friendly, and strongly aligned with the Office of the Dean (Students) institutional identity. 

## Product Vision

The website should serve as the most approachable digital entry point into MITR for IIT Madras students who may be under emotional, academic, or personal stress.   It should reduce friction in seeking help by making support routes visible immediately and by clearly distinguishing peer support from professional counselling support.   

The experience should feel warm, responsible, and reassuring rather than administrative. Students should be able to answer three questions within seconds of landing on the site: what MITR is, how MITR can help, and where to go next for support.  

## Problem Statement

Students experiencing distress may not always know whom to approach first, especially when campus wellness information is spread across different units and communication channels.   MITR already functions as a peer support layer across departments and hostels, but its current web presence does not fully present its role, resources, team structure, and support pathways in a cohesive, modern, and user-friendly way. 

The new MITR website should solve this by creating a simple and trustworthy information layer that routes students to MITR, the Wellness Centre, online counselling, or emergency contacts depending on the nature and urgency of the need.  

## Objectives

### Primary objectives

- Help students reach the right support channel quickly.   
- Clearly communicate that MITR provides peer counselling and emotional support, while professional counselling is provided through the Wellness Centre and related services.   
- Present MITR as an accessible, campus-wide network of trained faculty and student members available across hostels and departments. 
- Provide a dependable public directory of key wellness and emergency support resources.   

### Secondary objectives

- Showcase MITR initiatives such as peer counselling, Barefoot Counselling Training, events, and surveys.  
- Support transparency around team structure, annual recruitment, and leadership. 
- Create a clean archive for yearbooks, annual highlights, and impact documentation.

## Success Metrics

The site should be evaluated on whether it improves support discoverability and student actionability. Suggested KPIs include:

- Click-through rate on the primary “Get Support” CTA.
- Clicks on MITR contact points, Wellness Centre contacts, and tele-counselling resources.  
- Visits to the Resources page and Contact page.
- Mobile bounce rate on the homepage.
- Time from landing to first support interaction.
- Yearbook downloads and Team page visits during recruitment cycles.

## Target Users

### Primary users

- IIT Madras students seeking emotional support, a first conversation, or guidance during difficult periods. 
- Students who want to understand the available wellness support channels at IIT Madras.  

### Secondary users

- Students trying to help a friend in distress.
- Faculty or hostel stakeholders directing students toward available support systems.
- Prospective MITR applicants who want to learn about team structure, recruitment, and training. 

## User Needs

Students need a site that is easy to understand even when they are overwhelmed. The content should reduce cognitive load, avoid institutional jargon, and foreground immediate next actions over long explanatory text.

Core needs include:

- Quick reassurance that support is available.  
- Clear explanation of what MITR does and does not do.   
- A direct path to MITR, Wellness Centre, and emergency support contacts.   
- Visibility into MITR’s presence across departments and hostels. 
- Trust signals through institutional affiliation, clear leadership references, and thoughtful design.  

## Scope

### In scope

- A responsive, public informational website for MITR.
- Core pages: Home, About MITR, Get Support, Team, Initiatives, Resources, Yearbook, and Contact.
- Institutional design system based on a maroon color scheme inspired by the Office of the Dean (Students) visual identity. 
- Public contact blocks, support pathways, and emergency escalation cues.   
- Space for approved yearbook and team-structure content.

### Out of scope

- Therapy booking workflows.
- Student logins or accounts.
- Chat systems or case tracking.
- Internal dashboards for MITR operations.
- Publishing sensitive student stories or non-approved member details.

## Brand and Visual Direction

The visual language should align with the institutional tone of `dost.iitm.ac.in`, while being softer and more emotionally supportive in execution.  The interface should look official enough to build trust but warm enough that students do not feel intimidated.

### Color scheme

The site should use the actual maroon and warm-neutral values from the provided DoSt/MITR HTML-CSS reference rather than an inferred palette. The attached color inventory identifies `#800000` as the MITR maroon used for buttons, headings, and links, `#a00000` as the button hover color, `#7A0A0A` as an IITM maroon border value, `rgb(255 244 232)` as a MITR section background, and a deeper maroon gradient family including `#5b0f1b`, `#8e1e2f`, and `#c3273f` for wellness-themed surfaces. 

The following design tokens should replace the earlier proposed palette:

| Token | Value | Usage |
|---|---|---|
| `--color-primary` | `#800000` | Primary CTAs, headings, links, key action states.  |
| `--color-primary-hover` | `#a00000` | Hover state for primary buttons and interactive links.  |
| `--color-primary-dark` | `#7A0A0A` | Borders, strong separators, or emphasized maroon accents.  |
| `--color-gradient-start` | `#5b0f1b` | Wellness hero and highlight gradient start.  |
| `--color-gradient-mid` | `#8e1e2f` | Wellness hero and highlight gradient midpoint.  |
| `--color-gradient-end` | `#c3273f` | Wellness hero and highlight gradient end.  |
| `--color-gradient-hover-start` | `#6d1020` | Hover or active gradient start state.  |
| `--color-gradient-hover-mid` | `#9d2034` | Hover or active gradient midpoint.  |
| `--color-gradient-hover-end` | `#d62d47` | Hover or active gradient end state.  |
| `--color-footer-start` | `#7a1f2b` | Footer and deeper accent surfaces.  |
| `--color-footer-end` | `#b53545` | Footer gradient end or supporting highlight band.  |
| `--color-bg` | `rgb(255 244 232)` | Main MITR section background and warm page canvas.  |
| `--color-surface` | `#ffffff` | Cards, floating panels, and clean readable surfaces.  |
| `--color-text` | `#2d0c11` | Primary dark text on warm backgrounds.  |
| `--color-text-muted` | `#5f3b41` | Secondary text, metadata, and supporting copy.  |
| `--color-topbar-bg` | `rgb(206 146 82)` | Optional warm topbar or supporting background tone from the source stylesheet.  |
| `--color-video-bg` | `#1a1210` | Dark media or overlay background for embedded video areas.  |

Recommended branded gradients from the attached reference:

- `linear-gradient(135deg, #5b0f1b 0%, #8e1e2f 45%, #c3273f 100%)` for wellness hero sections. 
- `linear-gradient(135deg, #6d1020 0%, #9d2034 45%, #d62d47 100%)` for hover or active emphasis states. 
- `linear-gradient(135deg, #7a1f2b, #b53545)` for footer or institutional accent bands. 

### Typography

Typography should balance institutional seriousness with reading comfort. A serif or semi-serif heading font can carry authority, while a clean sans-serif body font should maximize legibility on mobile and desktop.

Suggested font directions:

- Headings: Merriweather, Source Serif, or Instrument Serif.
- Body: Inter, Source Sans, or Satoshi.
- Buttons and UI labels: medium-weight sans-serif.

### Mood and interaction

- Calm, warm, and non-clinical.
- High readability with generous spacing.
- Minimal animation, used only to support clarity.
- No loud gradients or startup-style visual treatment.
- Strong CTA prominence for support-related actions.

## Information Architecture

The website should use a shallow and support-first structure:

- Home
- About MITR
- Get Support
- Team
- Initiatives
- Resources
- Yearbook / Annual Highlights
- Contact

This structure reflects MITR’s public role as a peer support body and keeps the most important actions close to the user.  

## Detailed Page Requirements

## Home

### Goal

Help any visitor immediately understand MITR’s purpose and find support pathways with minimal friction. 

### Key content

- Hero with MITR name, a one-line description, and a primary support CTA.
- MITR motto displayed prominently: “No one in the campus should be unattended in their emotional distress.”  
- “What MITR does” summary: peer counselling, training, events, surveys.  
- Quick support blocks linking to MITR, Wellness Centre, and urgent help.  
- Campus presence statement noting availability across departments and hostels. 
- Short wellness ecosystem overview connecting MITR to professional support services.  

### Components

- Hero section
- CTA button group
- Support cards
- Motto banner
- Initiative preview cards
- Emergency info strip
- Footer directory

### Acceptance criteria

- A user can identify MITR’s purpose within 5 seconds.
- The primary support CTA is visible above the fold on mobile and desktop.
- Wellness and emergency routes are clearly separated.

## About MITR

### Goal

Explain MITR’s identity, role, values, and place within the IIT Madras wellness ecosystem.  

### Key content

- Definition of MITR as a body of faculty and student MITRs offering peer support. 
- Why MITR exists on campus.
- Relationship between MITR, Wellness Centre, and related support systems.  
- Leadership and guidance references based on approved institutional and internal content.  
- Core values: empathy, approachability, listening, confidentiality, and responsible referral.

### Components

- Introductory content section
- Timeline or narrative panel
- Leadership cards
- Values grid
- Link to Get Support

### Acceptance criteria

- Users understand that MITR is peer support, not formal therapy.  
- Users can identify MITR’s institutional legitimacy through leadership and DoSt references.  

## Get Support

### Goal

Provide the clearest possible routing for students who need help now.   

### Key content

- Common reasons for reaching out, such as stress, homesickness, academic pressure, loneliness, and emotional overwhelm.
- Decision guide for choosing MITR, Wellness Centre, tele-counselling, or emergency support.   
- Step-by-step explanation of how reaching out works.
- Reassurance copy emphasizing that students do not need to wait until a situation worsens before asking for help.

### Components

- Decision flow cards
- Tappable contact blocks
- “How it works” stepper
- Safety/emergency notice
- Sticky mobile CTA

### Acceptance criteria

- Contact routes are understandable at a glance.
- Emergency contacts are visually distinct from standard support contacts.
- Contact cards are easy to tap on mobile.

## Team

### Goal

Humanize MITR and show its distributed campus-wide structure. 

### Key content

- Leadership and faculty guidance.
- Faculty MITRs by department, if approved.
- Student MITRs by hostel and department, if approved.
- Vertical leads and team structure from approved attachments.
- Recruitment and training information, including interviews and Barefoot Counselling Training. 

### Components

- Team hierarchy section
- Department/hostel grouping cards
- Leadership profiles
- Recruitment information block
- Optional “Join MITR” CTA

### Acceptance criteria

- Users see MITR as an accessible peer network, not just a committee.
- Sensitive or personal details are not exposed without approval.

## Initiatives

### Goal

Show the broader scope of MITR’s work beyond direct peer conversations.  

### Key content

- Peer counselling as a service line. 
- Barefoot Counselling Training for new members.  
- Events and wellness engagements. 
- Surveys used to improve mental health and wellness resources on campus. 

### Components

- Initiative cards
- Event timeline or grouped archive
- Campaign posters/gallery
- Short impact blurbs

### Acceptance criteria

- Users understand that MITR supports campus wellness both directly and through outreach.
- Content can be updated in future without structural redesign.

## Resources

### Goal

Act as the most complete public directory for MITR-related wellness resources.  

### Key content

- MITR contact context and advisor details where publicly listed. 
- Wellness Centre summary and contact details.  
- Online/tele-counselling details, including helpline information published in IITM wellness materials.  
- Emergency support contacts such as hospital and security where relevant.  
- Guidance for helping a friend.

### Components

- Resource cards
- Contact lists
- Categorized support directory
- FAQ accordion
- Quick-jump navigation within the page

### Acceptance criteria

- The page can function as a standalone wellness directory.
- No high-priority support contact is more than one interaction away.

## Yearbook / Annual Highlights

### Goal

Archive MITR’s yearly work and present institutional continuity.

### Key content

- Annual overview
- Team and leadership highlights
- Events and campaigns
- Impact metrics, if approved
- Downloadable yearbook/reports

### Components

- Year cards or filters
- PDF download links
- Highlight sections
- Optional gallery

### Acceptance criteria

- Content is easy to browse by year.
- Downloads are clearly labeled and lightweight.

## Contact

### Goal

Provide a clear, dependable, low-friction contact endpoint.  

### Key content

- Official MITR contact route.
- Advisor or office contact if intended for public use and aligned with institutional sources.  
- Dean of Students office reference and contact context.  
- A simple contact form for non-urgent outreach.
- Urgent support disclaimer directing users to emergency channels. 

### Components

- Contact cards
- Contact form
- Map or location context if relevant
- Emergency notice panel

### Acceptance criteria

- Contact options are obvious and easy to use.
- The page does not invite sensitive disclosures without secure handling.

## Navigation and CTA Hierarchy

The main navigation should prioritize student needs over organizational depth. Recommended desktop and mobile top-level navigation:

- Home
- About
- Get Support
- Team
- Initiatives
- Resources
- Yearbook
- Contact

Primary CTA hierarchy across the site:

1. Get Support
2. Talk to a MITR
3. Wellness Resources
4. Meet the Team
5. Join MITR

This hierarchy reflects MITR’s publicly stated role as a support-first student wellness body.  

## Functional Requirements

### Core requirements

- Responsive layout across mobile, tablet, and desktop.
- Fast-loading static pages.
- Clear header and footer navigation.
- Support CTAs visible in above-the-fold areas.
- Mobile-friendly tap targets and click-to-call interactions.
- Content architecture that supports future annual updates.

### Optional enhancements

- Search or page-level quick navigation.
- Announcement banner for recruitment or events.
- Download center for yearbooks and brochures.
- Lightweight analytics integration.

## Non-Functional Requirements

### Accessibility

- Semantic HTML structure.
- Keyboard navigation support.
- Visible focus states.
- WCAG AA color contrast.
- Alt text for meaningful images.
- Reduced-motion-friendly transitions.

### Performance

- Optimized images and fonts.
- Minimal JavaScript.
- Strong mobile performance.
- Lazy loading for non-critical media.

### Privacy and trust

- No storage of sensitive disclosures through unsecured forms.
- Clear wording around MITR’s role and escalation boundaries.   
- Periodic review of public contact details to avoid stale information.  

## Content Guidelines

### Tone of voice

The content should be warm, clear, responsible, and student-centered. It should avoid sounding either too clinical or too promotional.

### Messaging principles

- Support is available.
- Reaching out is okay.
- MITR listens and helps students connect to the right support path.
- Professional help is available when needed.  

### Language rules

- Avoid implying that MITR provides therapy or psychiatric care.   
- Use concise, low-stress sentence structures.
- Prefer direct calls to action over institutional phrasing.

## User Flows

### Student seeking immediate support

1. Land on Home or Get Support.
2. Read reassurance copy.
3. Choose MITR, Wellness Centre, or Emergency support.
4. Contact the relevant channel.
5. Receive first-level support or referral.

### Student exploring MITR

1. Land on Home.
2. Visit About or Team.
3. Understand MITR’s role, structure, and leadership.
4. Navigate to Resources or Initiatives as needed.

### Student interested in joining MITR

1. Visit Team or Initiatives.
2. Read recruitment and Barefoot training information. 
3. Follow Join MITR CTA during open recruitment periods.

## Risks and Mitigations

| Risk | Impact | Mitigation |
|---|---|---|
| Confusion between peer support and professional counselling | Users may choose the wrong support route | Use clear page labels and decision flows distinguishing MITR and Wellness Centre.    |
| Outdated contact information | Failed support access | Establish periodic review with MITR/DoSt owners and cross-check with institutional pages.   |
| Overly dense content | Distressed users may disengage | Keep support pages concise and action-first |
| Publishing unapproved details | Privacy or governance issues | Restrict public content to approved member and contact information |

## Dependencies

The following content and approvals are needed before design and development are finalized:

- MITR logo and brand assets.
- Approved team structure and vertical leads.
- Yearbook PDFs and annual highlights.
- Approved public-facing contact details.
- Final guidance text for emergency escalation.
- Confirmation on whether recruitment information should be static or seasonal.

## Launch Recommendation

The best first version is a static, content-first website with a strong information architecture, a maroon DoSt-aligned design system, and a support-first homepage. This gives MITR a low-maintenance but credible digital presence while keeping room for later additions such as announcements, search, or a lightweight CMS.   
