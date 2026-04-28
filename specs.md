Project Specification: AI Agent Admin Dashboard
1. Core Architecture & Shell
Prompt Title: Responsive Single-Page Admin Framework
Role: Expert Front-End Developer (Tailwind CSS)

Requirements:
Structure: Persistent sidebar with exactly six sections; top bar with light/dark toggle.

Navigation: Single-page behavior (switching sections without page reloads).

Dark Mode: * Class-based strategy (darkMode: 'class').

Toggle must switch entire interface using Tailwind dark: utilities.

JavaScript to toggle the .dark class on <html> or <body>.

Quality: Semantic HTML, distinct active states for sidebar links, and placeholder content for all six sections.

Output: Single self-contained HTML file with inline JS/CSS.

2. Dashboard Overview (Section 1)
Prompt Title: Metrics & Activity Analytics
Role: Senior Front-End Developer

Requirements:
Metric Cards:

Total Revenue Generated (Current month).

Total Discount & Coupon Losses (Value lost).

Active Agents (Count across clients).

Flagged Agents (Count of failing agents).

Visuals: Placeholders like $24,300, $1,850, 142, 7. Distinct, scannable cards.

Chart Area: Full-width placeholder for "Weekly Activity Chart" using a skeleton state/container (no external libraries).

Layout: Responsive grid that collapses for mobile.

3. Agent Management (Section 2)
Prompt Title: Interactive Agent List & Configuration
Role: Expert React Developer

Requirements:
List View: Displays Agent Name, Owner, and Status Badge (active/green, inactive/gray, failing/red).

Expand/Collapse: Smooth CSS transition revealing a full skill list per agent.

Action Dropdown:

Configure: Opens modal showing the agent's system prompt.

Delete: Removes agent from local state.

Data: 4+ agents with varied skills and prompts.

Interactions: Click-outside to close dropdowns/modals; focus trapping.

4. Skills Catalog (Section 3)
Prompt Title: Platform Skills Design System
Role: Senior UI/UX Designer

Requirements:
Explanation Panel: Contextual helper text explaining "Skills" (platform-level capabilities like web search, data retrieval).

Catalog View: Grid or list of available skills.

Card Data: Skill Name, Description, and "Used by X agents" indicator.

Actions: Kebab menu with "View detail" and "Delete."

Design Rationale: Focus on scannability, empty vs. populated states, and professional SaaS aesthetic.

5. Agent Contracts (Section 4)
Prompt Title: Rental Contract Ledger
Role: Expert React Developer

Requirements:
Data Table: Client Name, Agent Name, Contracted Skills (tags), Start/End Dates, Status (Active/Past), and Total Amount Paid.

Modal Breakdown: Detailed view showing itemized pricing per skill and a summed total.

Styling: Professional badges for status; responsive table handling.

Data: 5+ mock contracts (mix of active and expired).

6. Error Log (Section 5)
Prompt Title: System Diagnostics & Error Tracking
Role: Expert Frontend Developer (Vanilla JS)

Requirements:
Log Entry: Timestamp, Agent Name, Error Type (Timeout, Auth, etc.), Short Description, and Severity Badge.

Severity Levels: Critical (red), Warning (orange), Minor (yellow), Info (blue).

Actions:

View Detail: Modal with full monospace stack trace and metadata.

Mark as Resolved: Visual strikethrough or green checkmark.

Technical: Single HTML file, vanilla JS, 6+ realistic mock entries with multi-line traces.