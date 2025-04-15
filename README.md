# Aplicație educațională - Identificare propoziții subordonate

Această aplicație web permite profesorilor să creeze exerciții de identificare a propozițiilor subordonate, iar elevilor să răspundă. Răspunsurile sunt evaluate automat și salvate în format CSV.

## 🔧 Tehnologii utilizate

- HTML, CSS, JavaScript
- Python + Flask (backend)
- Render.com pentru găzduire gratuită

---

## 📁 Structura aplicației

- `static/elev.html` — Interfața elevului
- `static/admin.html` — Panoul profesorului
- `static/rezultate.html` — Vizualizare rezultate
- `static/style.css` — Stiluri comune
- `static/admin.js` — Scripturi pentru panou profesor
- `app.py` — Backend Flask
- `requirements.txt` — Pachete necesare pentru Render

---

## 🚀 Ghid de instalare pe Render.com

1. Creează un cont pe [https://render.com](https://render.com)
2. Creează un nou Web Service
3. La *Start Command* introdu:
   ```
   gunicorn app:app
   ```
4. Încarcă acest proiect într-un repo GitHub și conectează-l la Render
5. Aplicația va fi disponibilă online la o adresă de forma:
   ```
   https://nume-aplicatie.onrender.com
   ```

---

## ✅ Funcționalități

- Profesorul adaugă fraze și subordonate
- Elevul răspunde, primește feedback colorat
- Rezultatele sunt salvate în `localStorage` și exportate în CSV
- Fișierul CSV este trimis automat și salvat pe server în directorul `uploads/`

---

## 📂 Uploads

CSV-urile trimise de elevi sunt salvate în directorul `uploads/`, care se creează automat la rularea aplicației.

---

## ✍️ Dezvoltat de

Această aplicație este parte dintr-un proiect educațional. Poate fi adaptată pentru exerciții gramaticale, quiz-uri sau evaluări personalizate.
