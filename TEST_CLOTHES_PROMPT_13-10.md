# בגדי טסט — פרומפט קנוני חובה (v2, 13/10 17:55)

## הלקח
"חזיית בד דקה בלי מילוי" כפרומפט גנרי נותן בברירת מחדל של SDXL/Flux חזיית ספורט מרופדת עם ברזלים ופס רחב + שכבת תחתון נוספת. הסטנדרט של סאן נדרש כפרומפט מפורש עד כמה שאפשר.

## ההגדרה הקנונית (סאן, 13/10)
* עליון: חזיית תחרת פרחים דקה, לא מרופדת, בלי ברזלים, בלי תמיכה/מילוי, בד שקוף-למחצה.
* תחתון: חוטיני דק בלבד (או מכנסון ברזילאי מבד טייץ) — חוט דק בצדדים, בלי פס רחב, בלי שכבה נוספת מעל.
* אסור: חזיית ספורט, מילוי/ריפוד, ברזלים, פס רחב, מכנס קצר, ג'ינס, שכבת בד מעל התחתון.

## בלוק פרומפט קנוני (להעתקה לכל רנדר טסט)
```
full body head-to-feet photo of a young adult woman wearing minimal studio test attire: a delicate sheer floral lace bralette, completely unpadded and unlined, no underwire, no support band, thin soft lace fabric with visible floral embroidery, thin spaghetti straps, natural unshaped bust silhouette; matching minimalist thin string bikini bottom, only thin string sides at the hips, high-cut, no wide waistband, no shorts, no second layer of clothing over the bottom; slim natural figure, bare hips; plain light gray seamless studio background, standing neutral relaxed pose, photorealistic, soft even studio lighting
```

## מה להוסיף במנועים שתומכים ב-negative prompt
```
sports bra, padded bra, underwire, push-up, thick straps, wide elastic band, shorts, jeans, boyshorts, leotard, extra layer, leggings, swimsuit bottoms with wide sides
```

## אימות
הבונה לא מאמת את עצמו — כל פלט טסט נבדק על ידי סאן/שימי של סאן מול ההגדרה הקנונית לפני שהוא נחשב תקני.

## עדכון v2.1 (סאן, 14/10 10:45) — רפרנס חזותי חובה לתחתון (דמות אמיתית)
החוטיני של בגדי טסט v2 לאדם אמיתי = בדיוק כפי שהוא מונח על הגוף בתמונה:
https://aidoor.shimi.land/studio-test/test_apparel_v2_realperson_thong_reference.png
(מקור: calib3_sigal_back.png, סבב כיול 3 — התמונה שסאן אישר במפורש ואהב.)
מכאן והלאה כל רנדר טסט של אדם אמיתי מחויב להציג את התחתון בישיבה הזאת על הגוף: חוט דק, היקף נמוך, בלי פס, בלי שכבה. החזייה נשארת לפי ההגדרה הכתובה למעלה (תחרת פרחים דקה לא מרופדת בלי ברזלים).
