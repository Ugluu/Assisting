# Assisting Ajil

Монголын бүтээлч салбарын уран бүтээлчид, бизнесүүдийг ажил, боломжтой холбодог олон нийтийн платформын вебсайт.

**Domain:** assistingajil.com

## Бүтэц

- `index.html` — Нэг хуудаст вебсайт (HTML, CSS, JS бүгд нэг файлд). Гадны хамаарал байхгүй, фонтыг Google Fonts-оос татна.

## Deploy хийх (Netlify — үнэгүй, хамгийн хялбар)

1. [netlify.com](https://netlify.com)-д бүртгүүл (GitHub-аар нэвтэрч болно)
2. **"Add new site" → "Import an existing project"** дарж энэ GitHub repo-г сонго
3. Build settings:
   - **Build command:** хоосон орхи
   - **Publish directory:** `.` (цэг) эсвэл хоосон орхи
4. **"Deploy"** дар — секундын дотор сайт ажиллана

## Өөрийн домэйн холбох (assistingajil.com)

1. Домэйнээ Namecheap / GoDaddy-аас худалдаж ав
2. Netlify дотор: **Site settings → Domain management → Add custom domain**
3. `assistingajil.com` гэж бичээд Netlify-ийн зааврын дагуу DNS тохируул

## Deploy хийх (Vercel — өөр сонголт)

1. [vercel.com](https://vercel.com)-д GitHub-аар нэвтэр
2. **"Add New → Project"** → энэ repo-г import хий
3. Framework: **"Other"**, бусдыг анхны хэвээр үлдээ
4. **"Deploy"** дар

## Хийх ажил (TODO)

- [ ] `@assisting_ajil` → жинхэнэ Instagram хаягаар солих
- [ ] Статистик тоонуудыг жинхэнэ тоогоор шинэчлэх
- [ ] Сэтгэгдлүүдийг жинхэнэ хүмүүсийн үгээр солих
- [ ] Хамтрагч брэндийн логонуудыг нэмэх
- [ ] Newsletter формыг Formspree-тэй холбож жинхэнэ и-мэйл цуглуулах
- [ ] Hiring (зар тавих) дэд хуудас нэмэх
