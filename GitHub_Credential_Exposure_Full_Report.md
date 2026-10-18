# تقرير كامل: Passive GitHub Credential Exposure Review

**برنامج:** GitHub Credential Bounty  
**تاريخ المسح:** 2026-10-18 00:00:20 → 00:04:39 UTC  
**الاستعلامات:** 29 ناجحة / 30  
**إجمالي النتائج الفريدة:** 2586  

---

## ملخص الأولويات

| الأولوية | العدد | الوصف |
|----------|------|--------|
| **P1_REVIEW_FIRST** | **188** | أولوية عالية – يُفضل مراجعتها أولاً |
| **P2_REVIEW** | 703 | أولوية متوسطة |
| **P3_LOW_SIGNAL** | 1695 | إشارة ضعيفة / ضوضاء عالية |

---

## ملاحظات هامة (من التقرير الأصلي)

- GitHub Code Search غير شامل وقد يحذف أو يرتب النتائج.
- كل استعلام بحث في الصفحة الأولى فقط (قد تكون النتائج مقطوعة).
- النتيجة **ليست إثباتًا** أن السر صالح أو قابل للاستغلال.
- **لم يتم تنزيل أي محتوى ملف أو قيمة سر**.
- أهلية المكافأة تعتمد على نطاق البرنامج والملكية والسياسة.
- **لا تختبر ولا تستخدم ولا تحاول المصادقة بأي بيانات اعتماد مكتشفة.**

---

## 1. نتائج الأولوية العالية (P1_REVIEW_FIRST) — 188 نتيجة

هذه النتائج مرتبة حسب درجة الـ Heuristic (الأعلى أولاً).

### 1. `jasser050/Esprit-PIDEV-3A50-2026-RLIFE`

- **المسار:** `.env.1`
- **المؤشر:** `database_url`
- **درجة Heuristic:** 6
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;higher_risk_indicator_search;repository_ownership_requires_review
- **رابط الملف:** https://github.com/jasser050/Esprit-PIDEV-3A50-2026-RLIFE/blob/5a20e7f1cc2a15dc7b43866473140f2fa6b5b112/.env.1
- **رابط المستودع:** https://github.com/jasser050/Esprit-PIDEV-3A50-2026-RLIFE
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 2. `serebano/tictapp-storage-api`

- **المسار:** `.env.1`
- **المؤشر:** `database_url`
- **درجة Heuristic:** 6
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;higher_risk_indicator_search;repository_ownership_requires_review
- **رابط الملف:** https://github.com/serebano/tictapp-storage-api/blob/31ab25f1990d29992dc9eb2861b568fd8b571514/.env.1
- **رابط المستودع:** https://github.com/serebano/tictapp-storage-api
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 3. `serebano/tictapp-storage-api`

- **المسار:** `.env.2`
- **المؤشر:** `database_url`
- **درجة Heuristic:** 6
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;higher_risk_indicator_search;repository_ownership_requires_review
- **رابط الملف:** https://github.com/serebano/tictapp-storage-api/blob/31ab25f1990d29992dc9eb2861b568fd8b571514/.env.2
- **رابط المستودع:** https://github.com/serebano/tictapp-storage-api
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 4. `0sm0s1z/subterfuge`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/0sm0s1z/subterfuge/blob/6c912aab938c53b036329ffe74a5648c7d76f74e/credentials.txt
- **رابط المستودع:** https://github.com/0sm0s1z/subterfuge
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 5. `0xcyphered/remilias.eth`

- **المسار:** `.env.org`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/0xcyphered/remilias.eth/blob/9ff0a0c8bd241015c5e43911dbd0d3b95e985214/.env.org
- **رابط المستودع:** https://github.com/0xcyphered/remilias.eth
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 6. `510908220/jenkins-assistant`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/510908220/jenkins-assistant/blob/2d9659d3ed8f97f06fb892169f6056564e4bcc9d/credentials.md
- **رابط المستودع:** https://github.com/510908220/jenkins-assistant
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 7. `AIxHunter/FileWizardAI`

- **المسار:** `.env.md`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/AIxHunter/FileWizardAI/blob/8ca4366a0309b2e4e49db60cce3b92ad40babfbd/.env.md
- **رابط المستودع:** https://github.com/AIxHunter/FileWizardAI
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 8. `AlgyJr/FTP-Protocol`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/AlgyJr/FTP-Protocol/blob/31a7bfdf129f6b71e5db70fa9e5d60bf9f717d9b/credentials.txt
- **رابط المستودع:** https://github.com/AlgyJr/FTP-Protocol
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 9. `AlrzA2003/BinanceTrader`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/AlrzA2003/BinanceTrader/blob/ecd079470d4fad35665c691d250c426efa11920f/credentials.txt
- **رابط المستودع:** https://github.com/AlrzA2003/BinanceTrader
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 10. `ArtemBernatskyy/Facebook_downloader`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ArtemBernatskyy/Facebook_downloader/blob/256944d0583186900b26b6bc2067cd245e6104af/credentials.txt
- **رابط المستودع:** https://github.com/ArtemBernatskyy/Facebook_downloader
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 11. `BaseMax/tehran-stock-market-watch-nodejs`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/BaseMax/tehran-stock-market-watch-nodejs/blob/0f93cdd790eb856ec5dc4bfc36817b58b150544d/.env.txt
- **رابط المستودع:** https://github.com/BaseMax/tehran-stock-market-watch-nodejs
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 12. `Bekt/startup-pitches`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Bekt/startup-pitches/blob/7cad82a2075cfffbff10e0cba1af47cf0ed9f7ad/credentials.txt
- **رابط المستودع:** https://github.com/Bekt/startup-pitches
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 13. `Bitbox-Connect/Bitbox`

- **المسار:** `.env.txt`
- **المؤشر:** `secret_assignment`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Bitbox-Connect/Bitbox/blob/f7c6a6292a89b8d282940582541c88158178d5c1/.env.txt
- **رابط المستودع:** https://github.com/Bitbox-Connect/Bitbox
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 14. `CapUlDis/to-do-app`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/CapUlDis/to-do-app/blob/3f5e283031d276c5c40684e116d99cdfabba8160/credentials.txt
- **رابط المستودع:** https://github.com/CapUlDis/to-do-app
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 15. `Central-University-IT-prod/2025-final-command-team-13-PROD-Finals-App`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Central-University-IT-prod/2025-final-command-team-13-PROD-Finals-App/blob/5784fe5b07ddaad5002f1435ed404e37a15ed78a/credentials.md
- **رابط المستودع:** https://github.com/Central-University-IT-prod/2025-final-command-team-13-PROD-Finals-App
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 16. `Central-University-IT-prod/2025-final-command-team-15-project`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Central-University-IT-prod/2025-final-command-team-15-project/blob/67eeb4238557006fa708f575db0b4627f84a1df1/CREDENTIALS.md
- **رابط المستودع:** https://github.com/Central-University-IT-prod/2025-final-command-team-15-project
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 17. `Central-University-IT-prod/2025-final-command-team-16-backend_and_frontend`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Central-University-IT-prod/2025-final-command-team-16-backend_and_frontend/blob/49f2dcf315476f6dd62fbda1ed2fc1cf600747db/credentials.md
- **رابط المستودع:** https://github.com/Central-University-IT-prod/2025-final-command-team-16-backend_and_frontend
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 18. `Central-University-IT-prod/2025-final-command-team-24-films`

- **المسار:** `Credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Central-University-IT-prod/2025-final-command-team-24-films/blob/da0311ec50faeb1c283a42541a973861b9a0ddf5/Credentials.md
- **رابط المستودع:** https://github.com/Central-University-IT-prod/2025-final-command-team-24-films
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 19. `Central-University-IT-prod/2025-final-command-team-25-final`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Central-University-IT-prod/2025-final-command-team-25-final/blob/55767bb7113a51b1c307a9315bd3443421e15f0e/credentials.md
- **رابط المستودع:** https://github.com/Central-University-IT-prod/2025-final-command-team-25-final
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 20. `Central-University-IT-prod/2025-final-command-team-3-backend`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Central-University-IT-prod/2025-final-command-team-3-backend/blob/3a233340f750c278b46d2419fb4a16a6d09494f6/CREDENTIALS.md
- **رابط المستودع:** https://github.com/Central-University-IT-prod/2025-final-command-team-3-backend
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 21. `Central-University-IT-prod/2025-final-command-team-40-supernova_team`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Central-University-IT-prod/2025-final-command-team-40-supernova_team/blob/77e8117a9229ac2de6fb1986ec0668ffe4f791b5/credentials.md
- **رابط المستودع:** https://github.com/Central-University-IT-prod/2025-final-command-team-40-supernova_team
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 22. `ChrisFlick/React-Reversi`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ChrisFlick/React-Reversi/blob/30f1501886656430e4a94266c87b6be11a0bc838/.env.txt
- **رابط المستودع:** https://github.com/ChrisFlick/React-Reversi
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 23. `ChristianJavierMelo/Vehicle-Type-Recognition`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ChristianJavierMelo/Vehicle-Type-Recognition/blob/d96909998e957fcf6596ed5a5da52e8ed68f2338/.env.txt
- **رابط المستودع:** https://github.com/ChristianJavierMelo/Vehicle-Type-Recognition
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 24. `CodingHusk3y/NutriSense`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/CodingHusk3y/NutriSense/blob/634b1ebf8f6b4c0bceb3f30613b91caa0382b57a/CREDENTIALS.md
- **رابط المستودع:** https://github.com/CodingHusk3y/NutriSense
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 25. `Curovearth/Are-you-Drowsy`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Curovearth/Are-you-Drowsy/blob/22230b34d010844ddec8a0330d8c967811c7d373/credentials.txt
- **رابط المستودع:** https://github.com/Curovearth/Are-you-Drowsy
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 26. `Datamine/Archive-Tweets`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Datamine/Archive-Tweets/blob/5303b2f107a35ba07200efdef8d5b898050b7c2e/credentials.txt
- **رابط المستودع:** https://github.com/Datamine/Archive-Tweets
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 27. `DecoraterBot-devs/DecoraterBot`

- **المسار:** `Credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/DecoraterBot-devs/DecoraterBot/blob/3362ea90bc2fdb2e799dd064aa6128efbf4cd7a1/Credentials.md
- **رابط المستودع:** https://github.com/DecoraterBot-devs/DecoraterBot
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 28. `EmreErinc/envforge`

- **المسار:** `.env.ai.md`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/EmreErinc/envforge/blob/865cd46497f0ad212ed9c15f9a2f084fe2f1ad16/.env.ai.md
- **رابط المستودع:** https://github.com/EmreErinc/envforge
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 29. `EngqvistLab/fetch_microbial_growth_temperatures`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/EngqvistLab/fetch_microbial_growth_temperatures/blob/5f07cdd1a255e3ecb88ceabeb3ecb9b07588f0fa/credentials.txt
- **رابط المستودع:** https://github.com/EngqvistLab/fetch_microbial_growth_temperatures
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 30. `EternalDreamer01/Nyx`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/EternalDreamer01/Nyx/blob/6a16a3c06ac7c0bbc3253d1ada2fd34d56ec174f/.env.txt
- **رابط المستودع:** https://github.com/EternalDreamer01/Nyx
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 31. `GeorgiosIoannouCoder/vera`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/GeorgiosIoannouCoder/vera/blob/683de048d31205b09bbacbef533ea08e62676d71/.env.txt
- **رابط المستودع:** https://github.com/GeorgiosIoannouCoder/vera
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 32. `Hamyrappy/creative-governance-sim`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Hamyrappy/creative-governance-sim/blob/9dd3186583d5cb05dd64027dc2501cb206ab86bd/.env.txt
- **رابط المستودع:** https://github.com/Hamyrappy/creative-governance-sim
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 33. `JakeMcAllen/Decentralized-Crowdfunding-dApp-Backend`

- **المسار:** `.env.save.1`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/JakeMcAllen/Decentralized-Crowdfunding-dApp-Backend/blob/5e29ccf0f436eddaf6496c7a57789ce9442004f4/.env.save.1
- **رابط المستودع:** https://github.com/JakeMcAllen/Decentralized-Crowdfunding-dApp-Backend
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 34. `Jarnster/FaceLink`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Jarnster/FaceLink/blob/8c8a7fc0ed17c3e804c7775ab841ac1ba1904864/CREDENTIALS.md
- **رابط المستودع:** https://github.com/Jarnster/FaceLink
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 35. `KarenLiuzzi/Acoms_UAA`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/KarenLiuzzi/Acoms_UAA/blob/d202d53a33cbd949c12d9c554a48784296a366c5/credentials.txt
- **رابط المستودع:** https://github.com/KarenLiuzzi/Acoms_UAA
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 36. `Kcorb0/sparta-data22-project`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Kcorb0/sparta-data22-project/blob/a93f4caecbbffa5f0294be7835de154cc11cfc98/.env.txt
- **رابط المستودع:** https://github.com/Kcorb0/sparta-data22-project
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 37. `KubaWernerowski/Crimetrax`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/KubaWernerowski/Crimetrax/blob/163493c3fe7c5113f058c05c0434ccc0762cf3c7/credentials.txt
- **رابط المستودع:** https://github.com/KubaWernerowski/Crimetrax
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 38. `Ladorigvava/thekeyssystemstricoreai`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Ladorigvava/thekeyssystemstricoreai/blob/afbeb9958bc8034a11a91ebeb5e60d5ff5eed9cc/.env.txt
- **رابط المستودع:** https://github.com/Ladorigvava/thekeyssystemstricoreai
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 39. `Macula-Systems-LLC/purview-automation`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Macula-Systems-LLC/purview-automation/blob/96b2f14f81847e5fca59c85076d45850c3ab0f71/credentials.md
- **رابط المستودع:** https://github.com/Macula-Systems-LLC/purview-automation
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 40. `Manjaka13/hauth`

- **المسار:** `.env.txt`
- **المؤشر:** `secret_assignment`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Manjaka13/hauth/blob/1cbfb9b5e9e8f15bd6bf3235310e57c8291a7c6a/.env.txt
- **رابط المستودع:** https://github.com/Manjaka13/hauth
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 41. `Manjaka13/weather-app`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Manjaka13/weather-app/blob/06dab90772b4060b9013677d5d52a53a13abb772/.env.txt
- **رابط المستودع:** https://github.com/Manjaka13/weather-app
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 42. `Marcocholla/e-Shop`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Marcocholla/e-Shop/blob/2277ae27f306496fe514dcbe898ebb0a971de2cf/credentials.txt
- **رابط المستودع:** https://github.com/Marcocholla/e-Shop
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 43. `Musfique-Ahmed/My-Safety-App`

- **المسار:** `CREDENTIALS.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Musfique-Ahmed/My-Safety-App/blob/99ec8ca4b7223012442f16dc71f05a4f8dc1a24a/CREDENTIALS.txt
- **رابط المستودع:** https://github.com/Musfique-Ahmed/My-Safety-App
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 44. `Mycelium-Lab/FairFight`

- **المسار:** `.env.org`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Mycelium-Lab/FairFight/blob/e301930e6c809bc2b770fdbbd9a6dc78440f223f/.env.org
- **رابط المستودع:** https://github.com/Mycelium-Lab/FairFight
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 45. `Mysticloud/Pterodactyl-Trial-Servers`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Mysticloud/Pterodactyl-Trial-Servers/blob/5cd04a5279087c7b2a9f204936b6193fdd763616/.env.txt
- **رابط المستودع:** https://github.com/Mysticloud/Pterodactyl-Trial-Servers
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 46. `NCEAS/index-monitor`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/NCEAS/index-monitor/blob/1bc0a4700a5a7b2bb957d3bdb17f4295eda99801/credentials.txt
- **رابط المستودع:** https://github.com/NCEAS/index-monitor
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 47. `Nannajpg/IDS-admin-panel`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Nannajpg/IDS-admin-panel/blob/1020ba955dd6c88031cc5795718d684f79fd0109/.env.txt
- **رابط المستودع:** https://github.com/Nannajpg/IDS-admin-panel
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 48. `Nileshsan/taxwisary-project`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Nileshsan/taxwisary-project/blob/ddfceb6fa93993314b12273da57cefcf14951c3e/credentials.txt
- **رابط المستودع:** https://github.com/Nileshsan/taxwisary-project
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 49. `NinoslavVasic/Multi-Blockchain-Wallet-in-Python`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python/blob/22a354c4714f5be0364f18878817d3ab30848c4e/.env.txt
- **رابط المستودع:** https://github.com/NinoslavVasic/Multi-Blockchain-Wallet-in-Python
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 50. `Ohnoimded/maya_telegram_rag`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Ohnoimded/maya_telegram_rag/blob/516820d7cebb6cf16f1e7686886996bc2883d183/.env.txt
- **رابط المستودع:** https://github.com/Ohnoimded/maya_telegram_rag
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 51. `Prakhar824/java-based-quiz`

- **المسار:** `Credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Prakhar824/java-based-quiz/blob/23075c6623d6ef7c54eefb35c3c14ab699e3cbca/Credentials.txt
- **رابط المستودع:** https://github.com/Prakhar824/java-based-quiz
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 52. `PricopeStefan/Filelist-QBitTorrent-Plugin`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/PricopeStefan/Filelist-QBitTorrent-Plugin/blob/f9f2320c6bff639de18adac07fa860ff5cd18828/credentials.txt
- **رابط المستودع:** https://github.com/PricopeStefan/Filelist-QBitTorrent-Plugin
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 53. `ProcessAI/cnhfacil`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ProcessAI/cnhfacil/blob/14c896d2d86b7a57c7ee103dc10d9c268dec697f/CREDENTIALS.md
- **رابط المستودع:** https://github.com/ProcessAI/cnhfacil
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 54. `PuneethReddyHC/inventory_management_system`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/PuneethReddyHC/inventory_management_system/blob/dee022b403272a3984a2d6afe05fa216b9fa98ee/credentials.txt
- **رابط المستودع:** https://github.com/PuneethReddyHC/inventory_management_system
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 55. `Sellbrite/Sellbrite-API`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Sellbrite/Sellbrite-API/blob/b6fddbf9e94894d1e6cbd1040331957d2940af9a/credentials.md
- **رابط المستودع:** https://github.com/Sellbrite/Sellbrite-API
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 56. `Shivamkak19/Dual-Class-Arbitrage-Algorithm`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Shivamkak19/Dual-Class-Arbitrage-Algorithm/blob/e9f2325b5fc2f27bfe24a4dbadffae2f17c606dc/credentials.txt
- **رابط المستودع:** https://github.com/Shivamkak19/Dual-Class-Arbitrage-Algorithm
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 57. `Subham-Maity/MERN_Chat_App`

- **المسار:** `.env.txt`
- **المؤشر:** `secret_assignment`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Subham-Maity/MERN_Chat_App/blob/dbf10d794d4cbc6911869723d111ca60035c76d9/.env.txt
- **رابط المستودع:** https://github.com/Subham-Maity/MERN_Chat_App
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 58. `SydAliHsn/portfolio`

- **المسار:** `.env.local.md`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/SydAliHsn/portfolio/blob/3c36ed90c52892e3141edaab06c0ab9dbeace484/.env.local.md
- **رابط المستودع:** https://github.com/SydAliHsn/portfolio
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 59. `Tomochain-Name-Service/tns-contracts`

- **المسار:** `.env.org`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Tomochain-Name-Service/tns-contracts/blob/eefdd9d0b88d0e175858be485a6d0eb7023cb5c4/.env.org
- **رابط المستودع:** https://github.com/Tomochain-Name-Service/tns-contracts
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 60. `WolfpackOfOne/Q-agent`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/WolfpackOfOne/Q-agent/blob/4ec8ffb7d78fd0183cc36a56d8d7f82b226d0857/CREDENTIALS.md
- **رابط المستودع:** https://github.com/WolfpackOfOne/Q-agent
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 61. `Wondersteve254/dawapharma`

- **المسار:** `Credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/Wondersteve254/dawapharma/blob/052f9f2aeb89285b832bc22ded3c898a367917ba/Credentials.txt
- **رابط المستودع:** https://github.com/Wondersteve254/dawapharma
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 62. `ZYY799/tongji_stadium`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ZYY799/tongji_stadium/blob/e9bfab55d011b00d3882ef0e5995e7afef146517/credentials.txt
- **رابط المستودع:** https://github.com/ZYY799/tongji_stadium
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 63. `aWhereAPI/R-Training-Tutorials`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/aWhereAPI/R-Training-Tutorials/blob/cff22373542abc59cded9722afa4461a73c4280c/credentials.txt
- **رابط المستودع:** https://github.com/aWhereAPI/R-Training-Tutorials
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 64. `aayushkumarmishra/Send-Email`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/aayushkumarmishra/Send-Email/blob/b5eaccee8f6325feac2e5c0b2c7c7c381ab0f91b/credentials.txt
- **رابط المستودع:** https://github.com/aayushkumarmishra/Send-Email
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 65. `aerisweather/react-mapsgl`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/aerisweather/react-mapsgl/blob/7c39fc36d2bdf5eaa264212f03826af74aa2e40f/.env.txt
- **رابط المستودع:** https://github.com/aerisweather/react-mapsgl
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 66. `andygnewman/smart_twits`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/andygnewman/smart_twits/blob/86aee0d75ed2cc1f0636cfa161abd93a00d39af9/credentials.md
- **رابط المستودع:** https://github.com/andygnewman/smart_twits
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 67. `animesh-workplace/GISAID_scrapper`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/animesh-workplace/GISAID_scrapper/blob/d69978580e8c304dad3f0ba315060504db31c86e/credentials.txt
- **رابط المستودع:** https://github.com/animesh-workplace/GISAID_scrapper
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 68. `anyproto/any-ns`

- **المسار:** `.env.org`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/anyproto/any-ns/blob/77cc31146e6c5863b5facd8136533671fbe98451/.env.org
- **رابط المستودع:** https://github.com/anyproto/any-ns
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 69. `aqib026/direct-ksa`

- **المسار:** `.env.save.1`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/aqib026/direct-ksa/blob/748808bdbcbc41cb4788585f4c90905ccb9c2293/.env.save.1
- **رابط المستودع:** https://github.com/aqib026/direct-ksa
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 70. `arhamhashmi01/Apartment-Management-System`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/arhamhashmi01/Apartment-Management-System/blob/cbc466b3b8ee5e7ef42095fd6da4c478713b606a/credentials.txt
- **رابط المستودع:** https://github.com/arhamhashmi01/Apartment-Management-System
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 71. `ashurai1/HireHeaven`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ashurai1/HireHeaven/blob/9a1171a576fb708cc24a697d3e5c66aaf6b307af/credentials.md
- **رابط المستودع:** https://github.com/ashurai1/HireHeaven
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 72. `atato/kafka_training`

- **المسار:** `.env.5.5`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/atato/kafka_training/blob/3f3dedf7aa9c213650638895ce6d4efbd78f180f/.env.5.5
- **رابط المستودع:** https://github.com/atato/kafka_training
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 73. `basics/blueprint-boilerplate-nuxt`

- **المسار:** `.env.md`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/basics/blueprint-boilerplate-nuxt/blob/f96adb64461da2f592785b62be84e5c54627b4ea/.env.md
- **رابط المستودع:** https://github.com/basics/blueprint-boilerplate-nuxt
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 74. `blopit/Cursor-Template-Repo`

- **المسار:** `.env.md`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/blopit/Cursor-Template-Repo/blob/2950d74e26ceec6f5d99c7278851344bef69efdd/.env.md
- **رابط المستودع:** https://github.com/blopit/Cursor-Template-Repo
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 75. `bold-ronin/Vee`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/bold-ronin/Vee/blob/cb2d2a552f5467b2ae8f25ade3aaa71d50b23735/.env.txt
- **رابط المستودع:** https://github.com/bold-ronin/Vee
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 76. `boringPpl/Auto-Send-Linkedin-Connect-Request`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/boringPpl/Auto-Send-Linkedin-Connect-Request/blob/ed69e41c78474f5ffa12e240458125d4c7120a2a/credentials.txt
- **رابط المستودع:** https://github.com/boringPpl/Auto-Send-Linkedin-Connect-Request
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 77. `chefworks/cxml-tester`

- **المسار:** `.env`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/chefworks/cxml-tester/blob/8cfc44ec0e79cdc08ed1762c5f79c0d6971197d0/.env
- **رابط المستودع:** https://github.com/chefworks/cxml-tester
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 78. `cherifimehdi/Retrieve_Data_Application_Case`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/cherifimehdi/Retrieve_Data_Application_Case/blob/f919aba9b8011e256b46893e37bf73e53289efac/.env.txt
- **رابط المستودع:** https://github.com/cherifimehdi/Retrieve_Data_Application_Case
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 79. `chiranthhd1/Expense-manager-cpp`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/chiranthhd1/Expense-manager-cpp/blob/2d4bb75b5882c2f5ac34b66912d34a4a0333efe3/credentials.txt
- **رابط المستودع:** https://github.com/chiranthhd1/Expense-manager-cpp
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 80. `cloudfoundry-community/cf-containers-broker`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/cloudfoundry-community/cf-containers-broker/blob/6a3e75c0ae291f5ac3a821891708840de812c92b/CREDENTIALS.md
- **رابط المستودع:** https://github.com/cloudfoundry-community/cf-containers-broker
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 81. `danangkonang/aplication-poin-of-sale-web-php-codeigniter`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/danangkonang/aplication-poin-of-sale-web-php-codeigniter/blob/1aa774d995fa3e3d89bcdc8eec666a305634d9c2/.env.txt
- **رابط المستودع:** https://github.com/danangkonang/aplication-poin-of-sale-web-php-codeigniter
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 82. `deathbycaptcha/deathbycaptcha-api-client-python`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/deathbycaptcha/deathbycaptcha-api-client-python/blob/7fc6e8a41e0805074e341032996f77c6b3dbf34d/CREDENTIALS.md
- **رابط المستودع:** https://github.com/deathbycaptcha/deathbycaptcha-api-client-python
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 83. `dehero/mwscr`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/dehero/mwscr/blob/8a0e4c36977b1fe1c535997a30c41dae8c4b3bcd/CREDENTIALS.md
- **رابط المستودع:** https://github.com/dehero/mwscr
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 84. `eclypsium/mikrotik_meris_checker`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/eclypsium/mikrotik_meris_checker/blob/a657f6427992baa6f89e1f704cd2e1719acb0f8f/credentials.txt
- **رابط المستودع:** https://github.com/eclypsium/mikrotik_meris_checker
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 85. `eersnington/zaplineai-backend`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/eersnington/zaplineai-backend/blob/6f2c6263fec414eb97b07006b1f417b0c8ccf663/.env.txt
- **رابط المستودع:** https://github.com/eersnington/zaplineai-backend
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 86. `elliotwutingfeng/the-ghost-of-you-spotify`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/elliotwutingfeng/the-ghost-of-you-spotify/blob/672b082bcadf7a0b37219b22719a8a091b80cd68/.env.txt
- **رابط المستودع:** https://github.com/elliotwutingfeng/the-ghost-of-you-spotify
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 87. `emhart/tweetDB`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/emhart/tweetDB/blob/68de0761d09d0f6828586223ea4a89ce4aba20fd/credentials.txt
- **رابط المستودع:** https://github.com/emhart/tweetDB
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 88. `endlessm/systemd`

- **المسار:** `docs/CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/endlessm/systemd/blob/262def6554798b4188f1beab4bd0113d400a372b/docs/CREDENTIALS.md
- **رابط المستودع:** https://github.com/endlessm/systemd
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 89. `epfl-si/declprofs`

- **المسار:** `.env`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/epfl-si/declprofs/blob/75270a12895a9d47df6c9fbd7a11daf01321a857/.env
- **رابط المستودع:** https://github.com/epfl-si/declprofs
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 90. `eric-zhao-ocado/modular_test_bench_control`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/eric-zhao-ocado/modular_test_bench_control/blob/d441b7cc2f8deb5f8232466ac517c001d114c103/credentials.txt
- **رابط المستودع:** https://github.com/eric-zhao-ocado/modular_test_bench_control
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 91. `eveasian88/The-Bike-Shepherd`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/eveasian88/The-Bike-Shepherd/blob/39867164e97f8848c4c6a79b8df37148c42ae2a1/.env.txt
- **رابط المستودع:** https://github.com/eveasian88/The-Bike-Shepherd
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 92. `f09l/Fidra-Instagram-Accounts-Creator`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/f09l/Fidra-Instagram-Accounts-Creator/blob/740029c48a469a7a55ddb5f7035c8c558a4f3cd6/credentials.txt
- **رابط المستودع:** https://github.com/f09l/Fidra-Instagram-Accounts-Creator
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 93. `felixmariotto/Edelweiss-Editor`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/felixmariotto/Edelweiss-Editor/blob/ec39601ff252e9e8db3101d77a2916c64bc84786/.env.txt
- **رابط المستودع:** https://github.com/felixmariotto/Edelweiss-Editor
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 94. `fkinfred/premsub`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/fkinfred/premsub/blob/ad8bedf500d3b126a95e9a99348909d1eacb3d92/.env.txt
- **رابط المستودع:** https://github.com/fkinfred/premsub
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 95. `formoon/realworld-warp`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/formoon/realworld-warp/blob/5beb7bc4801ca6b590e05a4f81663baacc22a093/.env.txt
- **رابط المستودع:** https://github.com/formoon/realworld-warp
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 96. `franciscoluna-28/envoy`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/franciscoluna-28/envoy/blob/88c79830d253d5f603686b9bc11a2b7bc5cd18e3/CREDENTIALS.md
- **رابط المستودع:** https://github.com/franciscoluna-28/envoy
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 97. `hanahaneull/trakteer-ws`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/hanahaneull/trakteer-ws/blob/cf5c27d09c437366c750238765ed058bfefff3d8/CREDENTIALS.md
- **رابط المستودع:** https://github.com/hanahaneull/trakteer-ws
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 98. `hellomaxime/data-platform-on-kubernetes`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/hellomaxime/data-platform-on-kubernetes/blob/6da527db0c35e58a55da85d43c1bc21a1ca53181/credentials.md
- **رابط المستودع:** https://github.com/hellomaxime/data-platform-on-kubernetes
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 99. `iancoleman/BitcoinArmory-Daemon`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/iancoleman/BitcoinArmory-Daemon/blob/cbe8dc363ff7bfe04d2580066121e2dd0fe0079a/credentials.txt
- **رابط المستودع:** https://github.com/iancoleman/BitcoinArmory-Daemon
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 100. `ibm-build-lab/terraform-ibm-cloud-pak`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ibm-build-lab/terraform-ibm-cloud-pak/blob/aca14f21541b53902e781ee843f945c464f5f97c/CREDENTIALS.md
- **رابط المستودع:** https://github.com/ibm-build-lab/terraform-ibm-cloud-pak
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 101. `ibm-cloud-docs/cloud-object-storage`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ibm-cloud-docs/cloud-object-storage/blob/58112f68d3675230c87793e2c3226a7d86328d31/credentials.md
- **رابط المستودع:** https://github.com/ibm-cloud-docs/cloud-object-storage
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 102. `invictus-ir/ALFA`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/invictus-ir/ALFA/blob/97ee7c2eb28c94ef1d59d4c513951c4c5a9fb91c/CREDENTIALS.md
- **رابط المستودع:** https://github.com/invictus-ir/ALFA
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 103. `iseeface/A4-discord-bot`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/iseeface/A4-discord-bot/blob/a4f2c940770d76ce75f86a93993b28384cd0c191/.env.txt
- **رابط المستودع:** https://github.com/iseeface/A4-discord-bot
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 104. `ivandj0h/attendant-app`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ivandj0h/attendant-app/blob/196d25eb4d1f5f2f0ee28a8676bc6552aa89b2f9/.env.txt
- **رابط المستودع:** https://github.com/ivandj0h/attendant-app
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 105. `ivandj0h/budget-tracker`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ivandj0h/budget-tracker/blob/335a1d0f411ecf95102fd59d2a1b42c39b0afee2/.env.txt
- **رابط المستودع:** https://github.com/ivandj0h/budget-tracker
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 106. `jamesnguyen30/news-spider-project`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/jamesnguyen30/news-spider-project/blob/6f85e2c090f25cbde5f46b722470ffbac054c00b/credentials.txt
- **رابط المستودع:** https://github.com/jamesnguyen30/news-spider-project
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 107. `jasonqng/twitter-streaming-python`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/jasonqng/twitter-streaming-python/blob/3ccc1fa26d185ddc67a5045655146f056722e67e/credentials.txt
- **رابط المستودع:** https://github.com/jasonqng/twitter-streaming-python
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 108. `jbaumann/system_watchdog`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/jbaumann/system_watchdog/blob/de2b4c41436a29d43d539483fcdcb01c91889900/credentials.txt
- **رابط المستودع:** https://github.com/jbaumann/system_watchdog
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 109. `johnerinjery/PDF2Cal`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/johnerinjery/PDF2Cal/blob/dbf2fc9f9fdf1aef690d0f4ca20489bc1c08e505/credentials.txt
- **رابط المستودع:** https://github.com/johnerinjery/PDF2Cal
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 110. `jvf/spatial-weather`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/jvf/spatial-weather/blob/3f7edbeb7df6f2355e6126346972ebbfb5706730/credentials.txt
- **رابط المستودع:** https://github.com/jvf/spatial-weather
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 111. `kristinagligoric/cdi-tutorial`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/kristinagligoric/cdi-tutorial/blob/82053814503bcdcf53625310752c54b790d26822/credentials.txt
- **رابط المستودع:** https://github.com/kristinagligoric/cdi-tutorial
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 112. `labgadget015-dotcom/autonomous-github-agent`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/labgadget015-dotcom/autonomous-github-agent/blob/d70791753a147b3d328e42c58d40d8fc1b4ed780/.env.txt
- **رابط المستودع:** https://github.com/labgadget015-dotcom/autonomous-github-agent
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 113. `lacchain/vc-repository`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/lacchain/vc-repository/blob/b6566a24588f0c66aee0c330b62cfce6c81d1943/credentials.md
- **رابط المستودع:** https://github.com/lacchain/vc-repository
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 114. `lendroidproject/lendroid-ens-loan`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/lendroidproject/lendroid-ens-loan/blob/86e94c2c82b60e5c60926eb0ff41e703f89887ed/credentials.txt
- **رابط المستودع:** https://github.com/lendroidproject/lendroid-ens-loan
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 115. `lrlrlrlr/COMP3331_9331_22t2`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/lrlrlrlr/COMP3331_9331_22t2/blob/2689842be9efdd47dd1396c86b5ed990b64063df/credentials.txt
- **رابط المستودع:** https://github.com/lrlrlrlr/COMP3331_9331_22t2
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 116. `luizeduardo7/sawtooth-water-grant`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/luizeduardo7/sawtooth-water-grant/blob/14ce91161a1d33c8a2bfe24d765cb9e4518e2931/credentials.txt
- **رابط المستودع:** https://github.com/luizeduardo7/sawtooth-water-grant
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 117. `maurosoft1973/Docker-Alpine-LFTP`

- **المسار:** `.env.3.18.9`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-LFTP/blob/21f1873a37c2978aad98081434cf10a3d5ae82e0/.env.3.18.9
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-LFTP
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 118. `maurosoft1973/Docker-Alpine-LFTP`

- **المسار:** `.env.3.19.4`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-LFTP/blob/21f1873a37c2978aad98081434cf10a3d5ae82e0/.env.3.19.4
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-LFTP
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 119. `maurosoft1973/Docker-Alpine-LFTP`

- **المسار:** `.env.3.20.3`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-LFTP/blob/21f1873a37c2978aad98081434cf10a3d5ae82e0/.env.3.20.3
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-LFTP
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 120. `maurosoft1973/Docker-Alpine-MariaDB`

- **المسار:** `.env.3.18.9`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-MariaDB/blob/0194e1729ad5b2406045308d231d32de03279800/.env.3.18.9
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-MariaDB
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 121. `maurosoft1973/Docker-Alpine-MariaDB`

- **المسار:** `.env.3.19.4`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-MariaDB/blob/0194e1729ad5b2406045308d231d32de03279800/.env.3.19.4
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-MariaDB
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 122. `maurosoft1973/Docker-Alpine-MariaDB`

- **المسار:** `.env.3.20.3`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-MariaDB/blob/0194e1729ad5b2406045308d231d32de03279800/.env.3.20.3
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-MariaDB
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 123. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.15.1`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.15.1
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 124. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.15.3`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.15.3
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 125. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.15.4`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.15.4
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 126. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.16.1`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.16.1
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 127. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.16.2`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.16.2
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 128. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.16.3`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.16.3
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 129. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.17.1`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.17.1
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 130. `maurosoft1973/Docker-Alpine-Postfix-Relay`

- **المسار:** `.env.3.17.3`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay/blob/adcff107c406c802504afe7cfa771d2d7c6407d9/.env.3.17.3
- **رابط المستودع:** https://github.com/maurosoft1973/Docker-Alpine-Postfix-Relay
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 131. `megalus/django-google-sso`

- **المسار:** `docs/credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/megalus/django-google-sso/blob/f5af8a24f36432411cd405825dbd66315c0addd8/docs/credentials.md
- **رابط المستودع:** https://github.com/megalus/django-google-sso
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 132. `megazordpobeda/DataRush`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/megazordpobeda/DataRush/blob/f0bd43a1dd1acb8a9855984eb3fe71e5e0106a3f/CREDENTIALS.md
- **رابط المستودع:** https://github.com/megazordpobeda/DataRush
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 133. `meteor-factory/processes`

- **المسار:** `Credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/meteor-factory/processes/blob/d999b235ac79e654d51340c1961fa04306a7257c/Credentials.md
- **رابط المستودع:** https://github.com/meteor-factory/processes
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 134. `michalpiasecki0/BSc-soccer-annotator`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/michalpiasecki0/BSc-soccer-annotator/blob/0cfb0692f859d15bd757502c89a6f425d2fbf5f1/.env.txt
- **رابط المستودع:** https://github.com/michalpiasecki0/BSc-soccer-annotator
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 135. `michalpiasecki0/BSc-soccer-annotator`

- **المسار:** `ui/.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/michalpiasecki0/BSc-soccer-annotator/blob/0cfb0692f859d15bd757502c89a6f425d2fbf5f1/ui/.env.txt
- **رابط المستودع:** https://github.com/michalpiasecki0/BSc-soccer-annotator
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 136. `mozammal89/azadijobs`

- **المسار:** `Credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/mozammal89/azadijobs/blob/b7efb7ad1fc14caaaacde6283ac02798ecdd8f17/Credentials.txt
- **رابط المستودع:** https://github.com/mozammal89/azadijobs
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 137. `mrbeels/instagram-story-poster-bot`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/mrbeels/instagram-story-poster-bot/blob/2f5546968e63fe50f6d79d9e983897fd325f1f5e/credentials.txt
- **رابط المستودع:** https://github.com/mrbeels/instagram-story-poster-bot
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 138. `muchdogesec/arango_cve_processor`

- **المسار:** `.env.markdown`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/muchdogesec/arango_cve_processor/blob/c06eecb4baee5971c299284731dc96c378909067/.env.markdown
- **رابط المستودع:** https://github.com/muchdogesec/arango_cve_processor
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 139. `muchdogesec/arango_taxii_server`

- **المسار:** `.env.markdown`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/muchdogesec/arango_taxii_server/blob/abc9d3431def0f2027593d42891969436ff3fa84/.env.markdown
- **رابط المستودع:** https://github.com/muchdogesec/arango_taxii_server
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 140. `muchdogesec/stix2arango`

- **المسار:** `.env.markdown`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/muchdogesec/stix2arango/blob/f2dddc36af4f8e6408433e9fcabb34f6990023df/.env.markdown
- **رابط المستودع:** https://github.com/muchdogesec/stix2arango
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 141. `muchdogesec/txt2detection`

- **المسار:** `.env.markdown`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/muchdogesec/txt2detection/blob/5f51c5957638865452ebd440bb52a947abdc2909/.env.markdown
- **رابط المستودع:** https://github.com/muchdogesec/txt2detection
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 142. `muchdogesec/txt2stix`

- **المسار:** `.env.markdown`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/muchdogesec/txt2stix/blob/625932d0455390cf349175ef5c77c75b29f87b3d/.env.markdown
- **رابط المستودع:** https://github.com/muchdogesec/txt2stix
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 143. `muchdogesec/vulmatch`

- **المسار:** `.env.markdown`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/muchdogesec/vulmatch/blob/b242d59593b7bcfe99866ceb0d71c6f02d7eabb4/.env.markdown
- **رابط المستودع:** https://github.com/muchdogesec/vulmatch
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 144. `muhammadwasi81/mern-ecommerce`

- **المسار:** `.env.md`
- **المؤشر:** `secret_assignment`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/muhammadwasi81/mern-ecommerce/blob/f2a7af3082e80adc1bf2318fbbe5909a8cc09555/.env.md
- **رابط المستودع:** https://github.com/muhammadwasi81/mern-ecommerce
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 145. `mython-dev/ssh-brute-force`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/mython-dev/ssh-brute-force/blob/0147673c8b3ef6ec619d3c752b76d7dc11a7bd79/credentials.txt
- **رابط المستودع:** https://github.com/mython-dev/ssh-brute-force
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 146. `nborrmann/gcmreverse`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/nborrmann/gcmreverse/blob/c6c74028aa92a2650e2577691c756dd5c98e7530/credentials.txt
- **رابط المستودع:** https://github.com/nborrmann/gcmreverse
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 147. `neoLsH/gbpx_gd_gov`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/neoLsH/gbpx_gd_gov/blob/61d8c0a697e8effddc20f48d0369e12642288e77/credentials.txt
- **رابط المستودع:** https://github.com/neoLsH/gbpx_gd_gov
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 148. `nishchal-gond/ORMS`

- **المسار:** `CREDEntials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/nishchal-gond/ORMS/blob/02587aac6ac718f9078c125816273e589161b917/CREDEntials.txt
- **رابط المستودع:** https://github.com/nishchal-gond/ORMS
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 149. `nodebeats/nodebeats`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/nodebeats/nodebeats/blob/c0a431deb3f3359798f84a85f4b0f0a4b21cf28d/credentials.txt
- **رابط المستودع:** https://github.com/nodebeats/nodebeats
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 150. `opsdisk/coressh`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/opsdisk/coressh/blob/8ed6d86c54eca83fd5e9f76e0891f5e0dbbffaba/credentials.txt
- **رابط المستودع:** https://github.com/opsdisk/coressh
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 151. `pajikos/sms-gammu-gateway`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/pajikos/sms-gammu-gateway/blob/4a45500e5beeb023280cbabb555887a46cbffd3f/credentials.txt
- **رابط المستودع:** https://github.com/pajikos/sms-gammu-gateway
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 152. `pearlsteinj/PennApps2014s`

- **المسار:** `Credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/pearlsteinj/PennApps2014s/blob/d796d626ea4bdb3d2d0270b702c83f981a46f506/Credentials.txt
- **رابط المستودع:** https://github.com/pearlsteinj/PennApps2014s
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 153. `pelagecha/LLM-Agents`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/pelagecha/LLM-Agents/blob/a4c5640e499f585a0ee05a703e2bfad5efc78c3d/.env.txt
- **رابط المستودع:** https://github.com/pelagecha/LLM-Agents
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 154. `pl4g4/netflix-account-check`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/pl4g4/netflix-account-check/blob/17750b8a88df74bc21d57c3be905e86f9798261e/credentials.txt
- **رابط المستودع:** https://github.com/pl4g4/netflix-account-check
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 155. `prutxvi/gesture-drop`

- **المسار:** `.env.batch2.3`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/prutxvi/gesture-drop/blob/1361cfab48d355dfad28d1faba2f4cd5673f6958/.env.batch2.3
- **رابط المستودع:** https://github.com/prutxvi/gesture-drop
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 156. `quintel/etlauncher`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/quintel/etlauncher/blob/da5eae6a5adb0210faa527487c93af46e7b1f02e/CREDENTIALS.md
- **رابط المستودع:** https://github.com/quintel/etlauncher
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 157. `restorecommerce/payment-srv`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/restorecommerce/payment-srv/blob/4b5cf33a10c77ef141770bd6bf14c7e2f64afea9/credentials.md
- **رابط المستودع:** https://github.com/restorecommerce/payment-srv
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 158. `rimmelasghar/twitter-scrapper`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/rimmelasghar/twitter-scrapper/blob/881b3a6f097a433deb7afafb2cd3e81e4478b18d/credentials.txt
- **رابط المستودع:** https://github.com/rimmelasghar/twitter-scrapper
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 159. `rjsebening/n8n-nodes-leadtable`

- **المسار:** `CREDENTIALS.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/rjsebening/n8n-nodes-leadtable/blob/f815c74742a63ea601394d8e5e539ca231887c42/CREDENTIALS.md
- **رابط المستودع:** https://github.com/rjsebening/n8n-nodes-leadtable
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 160. `rodentskie/api_clean_architecture`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/rodentskie/api_clean_architecture/blob/925f991bf9affc871695429720a9d359866d8775/.env.txt
- **رابط المستودع:** https://github.com/rodentskie/api_clean_architecture
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 161. `rodentskie/api_typescript`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/rodentskie/api_typescript/blob/3609bc52c8df8845a9883c857cf41ac0d44be870/.env.txt
- **رابط المستودع:** https://github.com/rodentskie/api_typescript
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 162. `ruOpenCart/opencart3-webpack-theme`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/ruOpenCart/opencart3-webpack-theme/blob/b9ec712c2b4fc442afcdcb4138460037264c5c0d/.env.txt
- **رابط المستودع:** https://github.com/ruOpenCart/opencart3-webpack-theme
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 163. `sahad-mk/FireVu`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/sahad-mk/FireVu/blob/087e7ad1c412309befb3960ed832e460e1b47b0a/credentials.txt
- **رابط المستودع:** https://github.com/sahad-mk/FireVu
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 164. `sandipanparia/SoulChat`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/sandipanparia/SoulChat/blob/19fd3929fe6fe94ee1c9ebfee1dd0a06ee32bef1/credentials.txt
- **رابط المستودع:** https://github.com/sandipanparia/SoulChat
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 165. `sh1katagana1/osint`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/sh1katagana1/osint/blob/730a045be17c4db9f1cc651d04a9a406282a405d/credentials.md
- **رابط المستودع:** https://github.com/sh1katagana1/osint
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 166. `shari-sushi/V-Kara-Lists`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/shari-sushi/V-Kara-Lists/blob/7c2096eb63d9d55c2f99c863a343863e056e5947/.env.txt
- **رابط المستودع:** https://github.com/shari-sushi/V-Kara-Lists
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 167. `shawn-sandy/fp-kit`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/shawn-sandy/fp-kit/blob/154e4483640ac2e2af4a425da4766ef066318e92/.env.txt
- **رابط المستودع:** https://github.com/shawn-sandy/fp-kit
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 168. `sherzo/orisa`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/sherzo/orisa/blob/74b07f5057168ccc18af19bc9e150055e21d1ab4/.env.txt
- **رابط المستودع:** https://github.com/sherzo/orisa
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 169. `siteslave/express-onefile`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/siteslave/express-onefile/blob/2005121c4255d78dfcc5dbd833f1a078c9e3eba3/.env.txt
- **رابط المستودع:** https://github.com/siteslave/express-onefile
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 170. `solomongetnet/instagram-clone`

- **المسار:** `client/.env.md`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/solomongetnet/instagram-clone/blob/71218fbe8a11e2b5011ac7f10efd1dfc82685d46/client/.env.md
- **رابط المستودع:** https://github.com/solomongetnet/instagram-clone
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 171. `soumyadeeptadas/SecureShare`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/soumyadeeptadas/SecureShare/blob/5f15048a22c66576bb22d3064b095e7af3f51ad5/credentials.txt
- **رابط المستودع:** https://github.com/soumyadeeptadas/SecureShare
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 172. `starwave-protocol/starwaveprotocol`

- **المسار:** `.env.2`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/starwave-protocol/starwaveprotocol/blob/2d1808c1e8f07060f1fe019a59026bf48b682b7e/.env.2
- **رابط المستودع:** https://github.com/starwave-protocol/starwaveprotocol
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 173. `starwave-protocol/starwaveprotocol`

- **المسار:** `.env.3`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/starwave-protocol/starwaveprotocol/blob/2d1808c1e8f07060f1fe019a59026bf48b682b7e/.env.3
- **رابط المستودع:** https://github.com/starwave-protocol/starwaveprotocol
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 174. `swarm64/s64da-compose`

- **المسار:** `.env`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/swarm64/s64da-compose/blob/a56d16ef2e517c74aca09a7e40a18b8472f4cf52/.env
- **رابط المستودع:** https://github.com/swarm64/s64da-compose
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 175. `tabaresjc/HeadUP`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/tabaresjc/HeadUP/blob/f73d54dd5115166a0032ff7e23bd91d07eae6e39/.env.txt
- **رابط المستودع:** https://github.com/tabaresjc/HeadUP
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 176. `tald7344/laravel-exams`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/tald7344/laravel-exams/blob/8f418aae4c5747a2a92101a822a53e76c99f74f5/credentials.txt
- **رابط المستودع:** https://github.com/tald7344/laravel-exams
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 177. `teramotodaiki/youtube-to-twitter`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/teramotodaiki/youtube-to-twitter/blob/afab891c85aea317289c7dc064bde77c63295c7a/.env.txt
- **رابط المستودع:** https://github.com/teramotodaiki/youtube-to-twitter
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 178. `tnotesjs/en-words`

- **المسار:** `credentials.md`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/tnotesjs/en-words/blob/4fbfa84287de34f2d4692d8bf549fdf8ef381c90/credentials.md
- **رابط المستودع:** https://github.com/tnotesjs/en-words
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 179. `translated/echo-server`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/translated/echo-server/blob/4022431d527cd5e55b70b36be796c610af533a90/.env.txt
- **رابط المستودع:** https://github.com/translated/echo-server
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 180. `tsjensen/protonmail-bridge-docker`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/tsjensen/protonmail-bridge-docker/blob/f4acd1d0adcf628dcec36c98dee98e9d6158021f/credentials.txt
- **رابط المستودع:** https://github.com/tsjensen/protonmail-bridge-docker
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 181. `tundx0/Telegram-mass-sender`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/tundx0/Telegram-mass-sender/blob/1eae2d5b9b78d70cc7ea22fb2db9e45eba56b4c5/credentials.txt
- **رابط المستودع:** https://github.com/tundx0/Telegram-mass-sender
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 182. `verbocity/streaming`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/verbocity/streaming/blob/bc1a29f8c20d7b161ea516748a79dcd30480f1c2/credentials.txt
- **رابط المستودع:** https://github.com/verbocity/streaming
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 183. `victoni/elasticsearch2`

- **المسار:** `.env.1`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/victoni/elasticsearch2/blob/dea22e91446f12247f9d4ac281d023893b33d7a5/.env.1
- **رابط المستودع:** https://github.com/victoni/elasticsearch2
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 184. `web3-identity/cns-metadata-service`

- **المسار:** `.env.org`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/web3-identity/cns-metadata-service/blob/0b388cb8e954dcfc03151d8af5fc84f3e52973ef/.env.org
- **رابط المستودع:** https://github.com/web3-identity/cns-metadata-service
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 185. `whyorean/AASTokenGrabber`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/whyorean/AASTokenGrabber/blob/ab1835cd6c726b671f541c909c852e59bfed36f0/credentials.txt
- **رابط المستودع:** https://github.com/whyorean/AASTokenGrabber
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 186. `willywill/ladda`

- **المسار:** `.env.md`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/willywill/ladda/blob/4a2fad8265fe1ab341f3730aa22cec6fa9e30767/.env.md
- **رابط المستودع:** https://github.com/willywill/ladda
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 187. `yoscruizer/hack-wifi-zte-f609`

- **المسار:** `credentials.txt`
- **المؤشر:** `config_credentials`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/yoscruizer/hack-wifi-zte-f609/blob/d11c39f987c3da995c9a716039352c5ebaf67476/credentials.txt
- **رابط المستودع:** https://github.com/yoscruizer/hack-wifi-zte-f609
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

### 188. `youngaileaderslinz/rag-sec-filling`

- **المسار:** `.env.txt`
- **المؤشر:** `credentials_file`
- **درجة Heuristic:** 4
- **أسباب التصنيف:** sensitive_filename_pattern;sensitive_path_word;repository_ownership_requires_review
- **رابط الملف:** https://github.com/youngaileaderslinz/rag-sec-filling/blob/cc158f6dbdd1a97c4ad4951c71e23e72ae386e8f/.env.txt
- **رابط المستودع:** https://github.com/youngaileaderslinz/rag-sec-filling
- **التقييم:** UNCONFIRMED_PUBLIC_CODE_SEARCH_HIT

---

## 2. ملخص نتائج الأولوية المتوسطة (P2_REVIEW) — 703 نتيجة

### أهم المؤشرات في P2:
- `private_key_header`: 98
- `database_url`: 97
- `aws_secret_key_label`: 97
- `rsa_private_key_header`: 96
- `db_password_label`: 94
- `private_key_file`: 93
- `client_secret_label`: 91
- `terraform_state`: 37

### أهم المسارات في P2:
- `README.md`: 160
- `id_rsa`: 50
- `env.txt`: 40
- `ENV.md`: 21
- `API.md`: 19
- `ssh/id_rsa`: 15
- `DEV.md`: 13
- `api.md`: 13
- `env.md`: 11
- `FAQ.md`: 9
- `MCP.md`: 8
- `DOCS.md`: 8
- `RUN.md`: 7
- `aws.md`: 7
- `NEWS`: 7

> النتائج الكاملة لـ P2 موجودة في الملفات الأصلية (`findings.json` / `report.md`).

---

## 3. ملخص نتائج الإشارة الضعيفة (P3_LOW_SIGNAL) — 1695 نتيجة

معظم هذه النتائج من نوع documentation أو أمثلة أو ملفات غير حساسة نسبيًا.

### أهم المؤشرات في P3:
- `docker_config`: 100
- `github_token_prefix`: 100
- `slack_token_prefix`: 97
- `npm_token_prefix`: 96
- `password_assignment`: 95
- `private_key_label`: 94
- `github_oauth_prefix`: 92
- `aws_access_key`: 92
- `github_pat_prefix`: 92
- `github_token_label`: 91

---

## 4. إحصائيات إضافية

### أكثر المالكين ظهورًا (كل الأولويات):
- `johnkavin123`: 30
- `maurosoft1973`: 14
- `1979139113`: 13
- `koolshare`: 9
- `Central-University-IT-prod`: 7
- `mophos`: 7
- `ibm-cloud-docs`: 6
- `muchdogesec`: 6
- `khaledhawil`: 5
- `alextanhongpin`: 5
- `dblock`: 5
- `CyberSource`: 5
- `jina-ai`: 5
- `sleaa17aol`: 5
- `adobe`: 4

### توزيع درجات الـ Heuristic:
- Score 6: 3
- Score 4: 185
- Score 3: 130
- Score 2: 573
- Score 1: 123
- Score 0: 1572

---

## 5. الاستعلامات التي تم تنفيذها

| # | المؤشر | الاستعلام | الحالة | عدد النتائج التقريبي |
|---|--------|-----------|--------|---------------------|
| 1 | `github_token_prefix` | `"ghp_"` | ✅ | 1,191,936 |
| 2 | `github_pat_prefix` | `"github_pat_"` | ✅ | 153,344 |
| 3 | `github_oauth_prefix` | `"gho_"` | ✅ | 107,264 |
| 4 | `github_app_token_prefix` | `"ghs_"` | ✅ | 831,488 |
| 5 | `github_refresh_prefix` | `"ghr_"` | ✅ | 127,488 |
| 6 | `aws_access_key` | `"AKIA"` | ✅ | 3,768,320 |
| 7 | `aws_secret_key_label` | `"AWS_SECRET_ACCESS_KEY"` | ✅ | 1,937,408 |
| 8 | `private_key_header` | `"BEGIN PRIVATE KEY"` | ✅ | 688,128 |
| 9 | `rsa_private_key_header` | `"BEGIN RSA PRIVATE KEY"` | ✅ | 1,011,712 |
| 10 | `database_url` | `"DATABASE_URL"` | ✅ | 9,338,880 |
| 11 | `db_password_label` | `"DB_PASSWORD"` | ✅ | 3,604,480 |
| 12 | `client_secret_label` | `"client_secret"` | ✅ | 5,144,576 |
| 13 | `secret_access_key_label` | `"secret_access_key"` | ✅ | 2,306,048 |
| 14 | `private_key_label` | `"private_key"` | ✅ | 5,734,400 |
| 15 | `api_key_label` | `"api_key"` | ✅ | 29,884,416 |
| 16 | `access_token_label` | `"access_token"` | ✅ | 11,862,016 |
| 17 | `bearer_auth_label` | `"Authorization: Bearer"` | ✅ | 3,268,608 |
| 18 | `github_token_label` | `"GITHUB_TOKEN"` | ✅ | 3,342,336 |
| 19 | `npm_token_prefix` | `"npm_"` | ✅ | 1,570,816 |
| 20 | `slack_token_prefix` | `"xoxb-"` | ✅ | 152,576 |
| 21 | `stripe_live_prefix` | `"sk_live_"` | ✅ | 231,936 |
| 22 | `google_api_key_prefix` | `"AIza"` | ✅ | 4,841,472 |
| 23 | `password_assignment` | `"password ="` | ✅ | 28,049,408 |
| 24 | `secret_assignment` | `"secret ="` | ✅ | 6,815,744 |
| 25 | `credentials_file` | `filename:.env` | ✅ | 4,890,624 |
| 26 | `private_key_file` | `filename:id_rsa` | ✅ | 28,672 |
| 27 | `config_credentials` | `filename:credentials` | ✅ | 1,134,592 |
| 28 | `terraform_state` | `filename:terraform.tfstate` | ✅ | 45,312 |
| 29 | `docker_config` | `filename:config.json` | ✅ | 8,126,464 |
| 30 | `kube_config` | `filename:kubeconfig` | ❌ | 0 |

---

## تحذير نهائي

هذا التقرير مخصص لأغراض **المراجعة السلبية فقط** ضمن برامج المكافآت الشرعية.
أي استخدام أو اختبار للبيانات المكتشفة قد يكون مخالفًا للقانون وسياسات GitHub.

*تم إنشاء هذا التقرير المُنظّم في 2026-10-18 00:17 UTC*