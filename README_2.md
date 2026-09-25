# AIESEC Membership Experience Dashboard

A one-page interactive dashboard of the **Membership Experience Survey** I ran as Data Analyst for **AIESEC in Bengaluru** in April 2024. AIESEC is a youth leadership organisation, and the survey asked 99 members how they feel about their roles, wellbeing, community, team practices and future leadership plans.

![Dashboard](dashboard.png)

## What the dashboard shows

- **KPI cards:** number of responses, four experience scores and the Net Promoter Score (NPS)
- **Role filter:** a dropdown to switch between Overall, Team Members, Team Leaders and Vice-Presidents
- **Heatmap:** experience scores by role, so weak spots stand out quickly
- **Leadership pipeline:** who plans to apply for higher roles, and which roles they want
- **Motivation:** the main reasons members stay in AIESEC
- **Recommendation score:** how likely members are to recommend AIESEC (1–10)

## Key insights

1. **Members would recommend AIESEC.** NPS is **+39**, and 52 of 99 members scored 9 or 10.
2. **The leadership pipeline is at risk.** **36%** of members are unsure whether to apply for a higher role. The most popular role is Team Leader.
3. **VPs need more support.** They score Team Development (6.6/10) and Team Performance (6.9/10) lowest in the whole survey.
4. **Community keeps people.** Members stay mainly for the community (33%) and soft-skills growth (30%).

## How it was built

The original form responses were no longer available, so I rebuilt the data from my April 2024 report slides:
- Counts and headline scores were copied from the slides.
- Team Leader and VP scores were recovered answer by answer from the charts, and they match the slide totals.
- I fixed a typo in the original report (a score printed as 9.11% was actually 91.1%) and added NPS as a standard measure.

The **About** tab in the spreadsheet explains the method in full.

## Files

| File | What it is |
|---|---|
| `AIESEC_Membership_Experience_Dashboard.xlsx` | The dashboard (open it in Google Sheets or Excel) |
| `dashboard.png` | Screenshot of the dashboard |

## Tools

Google Sheets / Excel: INDEX-MATCH, SUMIF, SUMPRODUCT, data validation (dropdown), conditional formatting, charts

## How to open in Google Sheets

1. Download the `.xlsx` file.
2. Upload it to Google Drive.
3. Right-click it and choose **Open with → Google Sheets**.
4. Use the **Show role** dropdown at the top to filter the dashboard.
