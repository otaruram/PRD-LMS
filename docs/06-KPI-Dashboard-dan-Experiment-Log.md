# KPI Dashboard dan Experiment Log

## 1. KPI Scorecard Mingguan
Gunakan tabel berikut per cohort.

| Metric | Definisi | Rumus | Target Awal |
|---|---|---|---|
| Reg to Join Rate | Rasio registran yang join Discord | join_discord / total_registrasi | > 60% |
| Onboarding Completion D1-D3 | Rasio peserta yang selesai checklist awal | onboarding_complete / join_discord | > 50% |
| Weekly Active Learners (WAL) | Peserta aktif per minggu | active_learners / join_discord | > 40% |
| Submission Rate | Rasio submit tugas | submit_count / active_learners | > 35% |
| Cohort Completion Rate | Rasio peserta menuntaskan program | completed / join_discord | > 20% |
| Certificate Conversion Rate | Rasio eligible yang bayar sertifikat | cert_paid / cert_eligible | 5-10% |
| Premium Conversion Rate | Rasio learner aktif yang bayar premium | premium_paid / active_learners | 3-7% |
| Revenue per Active Learner | Pendapatan rata-rata per learner aktif | total_revenue / active_learners | Baseline C1 |
| Mentor SLA Compliance | Persentase respons sesuai SLA | on_time_response / total_priority_requests | >= 90% |

## 2. Dashboard Views yang Wajib Ada
1. Funnel Overview.
2. Engagement Weekly Trend.
3. Monetization Snapshot.
4. At-Risk Learners.
5. Mentor SLA Tracker.

## 3. Weekly Review Template
### Bagian A - Ringkasan Angka
1. Metric naik: [isi]
2. Metric turun: [isi]
3. Metric kritikal: [isi]

### Bagian B - Diagnosis
1. Penyebab utama performa minggu ini.
2. Hambatan operasional terbesar.

### Bagian C - Keputusan
1. Eksperimen minggu depan.
2. Owner dan due date.
3. Risiko yang dipantau.

## 4. Experiment Log Template
| Experiment ID | Hipotesis | Segment | Periode | Success Metric | Hasil | Keputusan |
|---|---|---|---|---|---|---|
| EXP-001 | Onboarding checklist lebih pendek meningkatkan completion | New joiners | Week 2 | Onboarding Completion | [isi] | Keep/Iterate/Stop |

## 5. Contoh Backlog Eksperimen Prioritas
1. A/B panjang onboarding checklist.
2. A/B timing offer sertifikat (week 3 vs week 4).
3. Buddy accountability vs tanpa buddy.
4. Demo day publik vs internal.
5. Paket bundle premium + sertifikat vs harga terpisah.

## 6. Rules of Experimentation
1. Maksimal 2 eksperimen aktif per minggu.
2. Tentukan metrik dan baseline sebelum run.
3. Simpan keputusan akhir pada experiment log.
4. Hasil buruk tetap dicatat sebagai pembelajaran.
