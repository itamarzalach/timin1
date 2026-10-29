# טימין – דף נחיתה

אתר סטטי (HTML + CSS + JS בלבד, בלי build).

## מבנה
- `index.html` – כל הדף
- `images/` – התמונות והלוגו
- `robots.txt`

## העלאה ל-GitHub
1. ב-GitHub: New repository (למשל `timin`), ללא README.
2. בתיקייה הזו:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<USER>/timin.git
   git push -u origin main
   ```
   (או: Add file > Upload files בדף הריפו וגרירת כל התוכן.)

## פרסום ב-Render
1. render.com > New > **Static Site** > חיבור ל-GitHub ובחירת הריפו.
2. Build Command: ריק. Publish Directory: `.`
3. Create Static Site. תקבל כתובת `https://<name>.onrender.com`.

## אחרי שיש כתובת
בקובץ `index.html` להחליף את `https://YOUR-DOMAIN.example/` בכתובת האמיתית (canonical, og:url, og:image, twitter:image, JSON-LD), ולהוסיף כתובת רחוב ב-JSON-LD ובדף.