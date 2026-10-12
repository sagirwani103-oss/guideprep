# GuidePrep — Free Starter Website

## Isme kya hai?
- Modern dark dashboard, mobile responsive layout
- Class 9 / Class 10 switch
- Subject-wise completion percentage
- Chapter add/edit/delete, pending/in-progress/completed status
- Search and status filters
- Local browser saving
- Export/import backup JSON
- Basic offline/PWA support

## Phone par test kaise karein
1. ZIP extract karke `index.html` open karo. Kuch browsers mein local file par service worker/offline install kaam nahi karega; online hosting par saare features best work karenge.
2. Chapter add karo aur status change karke dekho.
3. Data isi browser ke local storage mein save hota hai. Browser data clear karne par data delete ho sakta hai; `Export backup` use karte raho.

## Bilkul free online publish — GitHub Pages
1. GitHub account banao / login karo: https://github.com
2. New public repository banao, naam `studytrack-cbse` rakh sakte ho.
3. Is folder ki files (`index.html`, `manifest.json`, `sw.js`, `icon.svg`) repository ke root mein upload karo. `README-HINGLISH.md` optional hai.
4. Repository mein **Settings → Pages** kholo.
5. **Build and deployment** mein **Deploy from a branch** select karo.
6. Branch `main`, folder `/(root)` choose karke Save karo.
7. Kuch minute baad Pages section mein tumhara website link dikh jayega, usually `https://USERNAME.github.io/studytrack-cbse/`.

## Phone par app jaisa use
- Published website ko Chrome mein kholo.
- Chrome ke menu (⋮) mein **Add to Home screen** ya **Install app** select karo, agar option aaye.
- Website phone ki home screen se launch ho sakti hai.

## Important limitations
- Yeh starter demo CBSE ka official syllabus checker nahi hai. Sample chapter names ko apne current syllabus se verify/edit karna.
- Progress browser/device ke local storage mein save hota hai. Phone aur laptop ke beech automatic sync nahi hota.
- Real accounts, cloud sync, shared progress, secure login aur reminders ke liye backend/database chahiye; is starter mein nahi hain.
- Static GitHub Pages hosting free hai, lekin website public hogi. Ismein personal/secret details mat daalna.
