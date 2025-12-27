# ✅ Testing Checklist - Share & Schedule

## 📋 רשימת בדיקות

העתק את הרשימה הזו ותסמן ✅ ליד כל תכונה שבדקת ועובדת.

---

## 🎯 **Basic Tests (חובה)**

### Share Functionality:
- [ ] פתיחת Share Modal
- [ ] יצירת Share URL
- [ ] Copy to Clipboard עובד
- [ ] WhatsApp Share נפתח
- [ ] Facebook Share נפתח
- [ ] Email Share נפתח
- [ ] כפתור Download עובד

### Export Functionality:
- [ ] Export Modal נפתח
- [ ] בחירת פורמט עובדת
- [ ] בחירת איכות עובדת
- [ ] Download PNG עובד
- [ ] Download PDF עובד
- [ ] Download ZIP עובד
- [ ] Google Drive מציג הודעה

### Preview & Draft:
- [ ] Preview Modal נפתח
- [ ] Preview נסגר בלחיצה על X
- [ ] Preview נסגר בלחיצה מחוץ למסך
- [ ] Save Draft עובד
- [ ] Save Draft שומר ב-LocalStorage

### Bottom Bar:
- [ ] כל 5 הכפתורים מוצגים
- [ ] כל הכפתורים ניתנים ללחיצה
- [ ] אייקונים מוצגים נכון
- [ ] Tooltips מופעים ב-hover

---

## 🔬 **Advanced Tests (אופציונלי)**

### Export Quality:
- [ ] 300 DPI יוצר קובץ גדול
- [ ] 150 DPI יוצר קובץ בינוני
- [ ] 72 DPI יוצר קובץ קטן
- [ ] PDF בגודל A4 נכון
- [ ] ZIP מכיל 3 קבצים (PNG, JPG, PDF)

### Share URLs:
- [ ] כל Share URL ייחודי (timestamp)
- [ ] URL מועתק נכון ללוח
- [ ] WhatsApp מקבל טקסט מוכן
- [ ] Email מכיל Subject ו-Body

### Schedule (WIP):
- [ ] Schedule Modal נפתח
- [ ] בחירת "פרסם עכשיו" עוברת לפלטפורמות
- [ ] בחירת "תזמן" מציגה הודעה
- [ ] Platform Modal מציג 7 פלטפורמות
- [ ] בחירת פלטפורמה מסמנת ✓

### Error Handling:
- [ ] אין שגיאות בקונסול (F12)
- [ ] Export בלי Grid מציג שגיאה ברורה
- [ ] Share בלי פלייר עובד (URL גנרי)
- [ ] CORS warnings מופיעים אבל לא שוברים

---

## 📱 **Responsive Tests**

### Mobile (< 768px):
- [ ] Bottom Bar מוצג נכון
- [ ] כפתורים לא חופפים
- [ ] Modals ממורכזים
- [ ] Export עובד במובייל
- [ ] Share עובד במובייל

### Tablet (768px - 1024px):
- [ ] Layout נראה טוב
- [ ] כל הכפתורים נגישים
- [ ] Preview מתאים למסך

### Desktop (> 1024px):
- [ ] Full Layout מוצג
- [ ] Sidebar נראית
- [ ] Grid מסודר
- [ ] כל התכונות פעילות

---

## 🔧 **Browser Compatibility**

- [ ] Chrome/Edge - כל התכונות
- [ ] Firefox - כל התכונות
- [ ] Safari - כל התכונות
- [ ] Mobile Chrome - כל התכונות
- [ ] Mobile Safari - כל התכונות

---

## 💾 **Data Persistence**

- [ ] Draft נשמר ב-LocalStorage
- [ ] Draft נטען אחרי רענון דף
- [ ] Scheduled Campaigns נשמרים
- [ ] אין data loss אחרי רענון

---

## 🎨 **UI/UX Tests**

- [ ] כל הכפתורים בעיצוב אחיד
- [ ] צבעים תואמים ל-Design System
- [ ] RTL תומך עברית נכון
- [ ] אייקונים ברורים
- [ ] הודעות ברורות
- [ ] Loading states (אם יש)

---

## 🐛 **Known Issues to Check**

### Issue #1: CORS על תמונות חיצוניות
**Test:**
- [ ] Export עם תמונות מ-placeholder.com
- [ ] ראה warnings בקונסול (זה OK)
- [ ] Export עדיין עובד

### Issue #2: Hebrew in URL
**Test:**
- [ ] Share URL לא מכיל תווים עבריים
- [ ] Copy Link עובד ללא שגיאה

### Issue #3: PDF Size
**Test:**
- [ ] PDF לא גדול מ-5MB
- [ ] PDF נפתח ללא שגיאות
- [ ] PDF מציג תוכן נכון

---

## ✅ **Final Checklist**

לפני שמסמנים "Done":

- [ ] כל Basic Tests עובדים ✅
- [ ] לפחות 80% מ-Advanced Tests עובדים
- [ ] אין שגיאות קריטיות בקונסול
- [ ] אין שגיאות JavaScript
- [ ] כל הכפתורים לחיצים
- [ ] כל הודעות ברורות
- [ ] UI/UX מקצועי

---

## 📊 **Score**

```
Total Tests: _____ / 60
Pass Rate: _____ %

Status:
[ ] 🟢 Production Ready (> 90%)
[ ] 🟡 Almost Ready (70-90%)
[ ] 🔴 Needs Work (< 70%)
```

---

## 📝 **Notes**

רשום כאן בעיות או הערות:

```
...
...
...
```

---

## 🚀 **Next Steps**

אם הכל עובד:
1. ✅ Commit to Git
2. ✅ Deploy to Server
3. ✅ Test on Production
4. ✅ Share with Users

אם יש בעיות:
1. ❌ רשום בעיות ב-Notes
2. ❌ תקן בעיות
3. ❌ הרץ שוב את ה-Checklist

---

**Good Luck! 🎉**
