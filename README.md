# Plum Escalation Intelligence System

An AI-enabled escalation management system for the Senior VP of Account Management at Plum Insurance, overseeing 4000+ accounts.

## Live Dashboard
🔗 https://plum-escalation-dashboard-pink.vercel.app/

## What It Does

Consolidates escalations from multiple channels (email, dashboard input), extracts risk signals automatically, scores each escalation using a composite risk model, and surfaces the highest-risk issues to leadership in real time.

## How It Works

1. **Input** — Escalations arrive via the dashboard text box or email forwarded to the dedicated mailhook address
2. **Intelligence layer** — Keyword-based risk extraction detects: medical emergencies, legal threats, IRDAI mentions, churn signals, SLA breaches
3. **Scoring** — Composite risk score (max 17) calculated from base urgency + signal weights
4. **Dashboard** — Three zones: Fire Now (≥8), Watching (5–7), Full Queue — with TAT timers, owner assignment, and status tracking
5. **Storage** — Every escalation written to Google Sheets as permanent record

## Risk Scoring Logic

| Signal | Weight |
|---|---|
| Medical emergency / surgery | +3 |
| Legal threat | +3 |
| IRDAI mention | +2 |
| Churn risk | +2 |
| SLA breach | +2 |
| Base urgency (1–5) | +1 to +5 |

Score ≥ 8 = Fire zone · Score 5–7 = Watch zone

## Tech Stack

- **Automation** — Make.com (webhook trigger → keyword extraction → Google Sheets)
- **Database** — Google Sheets (live, persistent)
- **Dashboard** — Vanilla HTML/CSS/JS hosted on Vercel
- **Input channels** — Dashboard text box · Email forwarding via mailhook

## Input Channels

- **Dashboard text box** — Paste any message (email, WhatsApp, Slack) directly
- **Email** — Forward to `h2ccwm5h74xjok78r12m9ncjdnkpi8l5@hook.us2.make.com`

## Built For

Plum Insurance — AI Generalist role assignment
