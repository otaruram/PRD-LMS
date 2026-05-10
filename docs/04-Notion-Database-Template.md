# Notion Database Template

## Prinsip Dasar
1. Gunakan Notion sebagai single source of truth.
2. Semua status learner dan assignment harus punya owner.
3. Hindari field berlebihan pada fase awal.

## 1. Database Learners
Field wajib:
1. learner_id (text)
2. full_name (text)
3. email (email)
4. country (select)
5. timezone (select)
6. cohort (select)
7. track (select)
8. discord_handle (text)
9. lifecycle_status (select: registered, onboarded, active, at-risk, completed, alumni)
10. risk_flag (select: none, low, medium, high)
11. conversion_stage (select: none, cert-offered, cert-paid, premium-offered, premium-paid)

View yang disarankan:
1. Active Learners
2. At-Risk Learners
3. Conversion Pipeline

## 2. Database Modules
Field wajib:
1. module_id
2. week_number
3. title
4. learning_objective
5. material_link
6. challenge_brief
7. due_date
8. mentor_owner

View yang disarankan:
1. Timeline per Week
2. Owner view

## 3. Database Assignments
Field wajib:
1. assignment_id
2. learner_id (relation ke Learners)
3. module_id (relation ke Modules)
4. submission_link
5. submission_status (not-started, in-progress, submitted, reviewed)
6. score_quality (1-5)
7. score_problem_solving (1-5)
8. score_communication (1-5)
9. feedback_notes
10. reviewed_by
11. reviewed_at

Formula saran:
- total_score = (score_quality + score_problem_solving + score_communication) / 3

## 4. Database Attendance
Field wajib:
1. learner_id
2. event_name
3. event_date
4. attended (checkbox)
5. participation_score (1-5)

## 5. Database Monetization
Field wajib:
1. learner_id
2. cert_eligible (checkbox)
3. cert_offered_date
4. cert_paid (checkbox)
5. premium_eligible (checkbox)
6. premium_offered_date
7. premium_paid (checkbox)
8. payment_amount (number)
9. payment_date

View yang disarankan:
1. Eligible but not paid
2. Paid this week

## 6. Database Weekly KPI
Field wajib:
1. cohort
2. week
3. reg_to_join_rate
4. onboarding_completion_rate
5. wal_rate
6. submission_rate
7. completion_forecast
8. cert_conversion_rate
9. premium_conversion_rate
10. total_revenue
11. key_issue_1
12. key_issue_2
13. action_next_week

## 7. Database Incident Log
Field wajib:
1. incident_id
2. incident_date
3. type
4. severity
5. owner
6. root_cause
7. action_taken
8. status

## Template Halaman Learner
Header:
- Nama
- Cohort
- Track
- Status saat ini

Section:
1. Progress Summary
2. Assignment History
3. Attendance
4. Mentor Notes
5. Conversion Notes

## Quality Control Checklist Notion
1. Semua relation database aktif.
2. Semua select value konsisten.
3. Semua dashboard view punya filter benar.
4. Data cut-off mingguan ditetapkan.
