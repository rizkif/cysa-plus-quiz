# CompTIA CySA+ CS0-004 Study Lab

Static, mobile-friendly practice app for GitHub Pages.

## Included question sources
- 100 Original Practice Questions PDF — 100 questions
- Method 2 PDF — 82 questions
- Question and Answer CySA+ (Security Operations).txt — 50 questions

## Publish with GitHub Pages
1. Create a public GitHub repository.
2. Upload the contents of this project folder to the repository root: `index.html`, `README.md`, `.nojekyll`, and `assets/`.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/ (root)`, then save.
5. Wait for deployment. The site URL will be `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

## Source selection and repeat prevention
- Choose one, two, or all three question sources before starting a session.
- Questions are shuffled.
- For each selected combination of domain + sources, a question is not shown again until every question in that pool has been displayed once.
- When the full pool has been displayed, the next round may reuse questions.
- The displayed-question cycle is saved in browser `localStorage`, separately for each selected domain/source combination.

## Notes
- Keep the `assets/images/` folder in its original relative location.
- Progress, bookmarks, answers, and seen-question cycles are stored locally in the browser and do not sync between devices.
- No backend, database, or build step is required.

## Progress soal yang pernah tampil
Dashboard menampilkan jumlah soal yang sudah pernah keluar dan sisa soal untuk setiap sumber, termasuk rincian per domain. Perhitungan menggunakan ID soal unik: soal dihitung keluar saat pertama kali ditampilkan, meskipun belum dijawab. Data tersimpan di `localStorage` browser/perangkat yang digunakan.
