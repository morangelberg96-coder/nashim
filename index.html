import { useState, useEffect } from "react";

// ───────────────────────────────────────────────────────────────────────────
// מקורות מידע: ויקיפדיה בעברית, ויקיפדיה באנגלית, המכלול, ארכיון המדינה,
// אתר גולדה מאיר, ynet, maariv, haaretz, TIME magazine.
// הציטוטים: מקצתם מתועדים במקורות ראשוניים (ראיונות, ספרים, נאומים),
// מקצתם הם פרפרזות על דעותיה הידועות. מומלץ לאמת לפני שימוש פדגוגי.
// ───────────────────────────────────────────────────────────────────────────

const WOMEN = [
  {
    id: "ada",
    wikiPage: "Ada_Yonath",
    name: "עדה יונת",
    title: "מדענית וזוכת פרס נובל",
    years: "נולדה 1939",
    colorBg: "#FEF3C7", colorAccent: "#D97706", colorLight: "#FDE68A",
    emoji: "🔬",
    tagline: "הישראלית הראשונה שזכתה בפרס נובל",
    source: "מקור: ויקיפדיה עברית, אתר מכון ויצמן, ראיונות לתקשורת. אמינות: גבוהה.",
    intro: `עדה יונת נולדה בשכונת גאולה בירושלים ב-1939, למשפחה דתית ועניה שעלתה מפולין. למרות הדוחק הכלכלי, סירבה עדה הקטנה לוותר על סקרנותה – בגיל 5 טיפסה על ארון ספרים כדי למדוד את זווית קרני השמש, ונפלה ושברה את זרועה. "מאז ידעתי שאהיה מדענית," היא אמרה לימים.

למדה כימיה ביוכימיה באוניברסיטה העברית ובמכון ויצמן. בשנות ה-70 החלה לחקור את הריבוזום – מפעל החלבונים של התא. כולם אמרו לה שזה בלתי אפשרי. היא לא שמעה להם. במשך שנים ניסתה לגבש את הריבוזום לגבישים שניתן לצלם בקרני X – ונכשלה. ונכשלה שוב. עמיתיה בעולם קראו לה "ילדת חלום" בלעג.

ב-2009, לאחר כ-30 שנות עבודה, זכתה עדה יונת בפרס נובל לכימיה – הישראלית הראשונה, ורק האישה הרביעית בהיסטוריה שזכתה בפרס זה. מחקריה על מבנה הריבוזום הניחו את הבסיס לפיתוח אנטיביוטיקות חדשות שיכולות להציל חיים.`,
    achievements: [
      "🏆 פרס נובל לכימיה 2009",
      "🔭 ראשונה לגבש ריבוזום לקרני X",
      "📚 פרופסורית במכון ויצמן למדע",
      "🌍 חברה באקדמיה האמריקאית למדעים",
      "👩‍🔬 ייסדה מעבדת גיבוש חלבונים ראשונה בישראל",
      "⏳ כ-30 שנות מחקר עקשני ורצוף",
    ],
    quotes: [
      { text: "כישלון הוא חלק מהדרך. בלי כישלון אין מדע.", context: "ראיון לאחר קבלת פרס נובל" },
      { text: "אם כולם אומרים לך שזה בלתי אפשרי – אולי זה הסימן שכדאי לנסות.", context: "הרצאה לסטודנטים" },
      { text: "הייתי ילדה שלא יכלה לישון בלי לחשוב על שאלות. זה לא השתנה.", context: "ראיון אישי" },
      { text: "מדע טוב לוקח זמן. אי אפשר לאלץ את הטבע.", context: "כנס מדעי בינלאומי" },
    ],
    questions: [
      { icon: "🌟", text: "מה מבין ההישגים של עדה יונת הכי הרשים אתכם – ולמה דווקא הוא?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את עדה יונת אם הייתם פוגשים אותה?" },
      { icon: "🌐", text: "אם עדה יונת הייתה נותנת לכם עצה אחת על ניהול כישלון – מה לדעתכם הייתה אומרת?" },
      { icon: "💬", text: "עדה נכשלה עשרות פעמים לפני שהצליחה. ספרו על כישלון שחוויתם – ומה למדתם ממנו." },
    ],
    videoSearch: "עדה יונת פרס נובל ראיון עברית",
    videoLabel: "עדה יונת מספרת על דרכה",
  },
  {
    id: "golda",
    wikiPage: "Golda_Meir",
    name: "גולדה מאיר",
    title: "ראשת ממשלה רביעית של ישראל",
    years: "1898 – 1978",
    colorBg: "#ECFDF5", colorAccent: "#059669", colorLight: "#A7F3D0",
    emoji: "🏛️",
    tagline: "האישה הראשונה שעמדה בראש ממשלת ישראל",
    source: "מקור: ויקיפדיה, ארכיון המדינה, אתר גולדה מאיר, ספרה 'חיי' (1975). אמינות: גבוהה מאוד. הערה: גולדה כן חתמה על מגילת העצמאות – הייתה אחת משתי הנשים היחידות מבין 37 החותמים.",
    intro: `גולדה מאיר נולדה בקייב שבאוקראינה ב-1898. ילדותה הייתה קשה – עוני, פוגרומים ופחד. המשפחה עלתה לאמריקה כשהייתה ילדה, ושם גדלה בווילוואקי. כבר בגיל 11 ארגנה קופת צדקה עצמאית לחבריה לכיתה שלא יכלו לשלם עבור ספריהם.

ב-1921 עלתה לארץ ישראל עם בעלה מוריס. היא הצטרפה לתנועת הפועלים, ומשם עלתה: שגרירה בברית המועצות, שרת העבודה, שרת החוץ הראשונה של ישראל – ולבסוף ב-1969, ראשת הממשלה. היא הייתה אחת משתי הנשים היחידות שחתמו על מגילת העצמאות. כשחתמה, כתבה בספרה: "עיניי מלאו דמעות וידיי רעדו."

ב-1973 פרצה מלחמת יום הכיפורים – אסון לאומי שהכה את ישראל בהפתעה. ועדת אגרנט (1974) לא מצאה שגולדה אשמה אישית, אך היא בחרה להתפטר. "לא הייתה לי נחמה," אמרה על ימים אלו. שאלת האחריות המנהיגותית שלה נשארת פתוחה עד היום.`,
    achievements: [
      "📜 אחת משתי נשים חותמות על מגילת העצמאות",
      "🇮🇱 ראשת ממשלה 1969–1974",
      "🤝 שרת החוץ הראשונה של ישראל",
      "✡️ מנהיגת התנועה הציונית",
      "💬 נואמת נלהבת בבמות עולמיות",
      "🌍 סמל עולמי למנהיגות נשית",
    ],
    quotes: [
      { text: "לא ביקשנו שום דבר אחר – רק רשות לנסות ולהציל את עמנו.", context: "נאום בפני האו\"ם (פרפרזה)" },
      { text: "צריך להתייחס אל הנשים כשוות בערכן לגברים. אבל אין הן צריכות לעשות נפלאות כל הזמן.", context: "ספרה 'חיי', 1975" },
      { text: "אנחנו לא שמחים שנצחנו. אנחנו כואבים על מי שנפל.", context: "לאחר מלחמת ששת הימים" },
      { text: "עיניי מלאו דמעות וידיי רעדו. עשינו את המעשה.", context: "על חתימת מגילת העצמאות, מתוך 'חיי'" },
    ],
    questions: [
      { icon: "🌟", text: "מה מבין מעשיה של גולדה מאיר הכי הרשים אתכם – ולמה?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את גולדה על ההחלטה לא לגייס מילואים לפני יום הכיפורים?" },
      { icon: "🌐", text: "ועדת אגרנט לא מצאה שגולדה אשמה – אך היא התפטרה מרצון. האם לדעתכם מנהיג/ה צריך/ה לשאת באחריות גם כשאין אשמה אישית? מה ההבדל בין אחריות משפטית לאחריות מוסרית?" },
      { icon: "💬", text: "אם גולדה הייתה חיה היום, מה לדעתכם הייתה אומרת על מעמד האישה בפוליטיקה הישראלית?" },
    ],
    videoSearch: "גולדה מאיר ראשת ממשלה ראיון עברית",
    videoLabel: "דמותה ומורשתה של גולדה",
  },
  {
    id: "yael",
    wikiPage: "Yael_Arad",
    name: "יעל ארד",
    title: "אלופת אולימפית, יו\"ר ועד אולימפי",
    years: "נולדה 1967",
    colorBg: "#FFF7ED", colorAccent: "#EA580C", colorLight: "#FED7AA",
    emoji: "🥋",
    tagline: "הביאה לישראל את המדליה האולימפית הראשונה",
    source: "מקור: ויקיפדיה, ארכיון הועד האולימפי הישראלי, ראיונות תקשורת. אמינות: גבוהה.",
    intro: `יעל ארד נולדה בתל אביב ב-1967, ומגיל צעיר נמשכה לג'ודו. בשנות ה-80 הייתה לאחת מהספורטאיות המובילות בעולם.

ב-25 ביולי 1992, באצטדיון האולימפי בברצלונה, ניצבה יעל בגמר הג'ודו. בדקות אחרונות הגיעה להחלטה – כסף. המדליה הזו הייתה המדליה האולימפית הראשונה אי פעם שזכתה בה מדינת ישראל, 44 שנה אחרי הקמתה.

בשובה ארצה קיבלוה כגיבורה לאומית. אבל יעל לא נעצרה שם. למדה משפטים, נכנסה לניהול ספורטיבי, כיהנה כיו"ר הוועד האולימפי הישראלי, ועסקה בקידום ספורטאיות וספורטאים צעירים. המדליה הייתה רק ההתחלה.`,
    achievements: [
      "🥈 מדליית כסף אולימפית – ברצלונה 1992",
      "🥇 אלופת אירופה בג'ודו",
      "🏛️ יו\"ר הוועד האולימפי הישראלי",
      "⚖️ בוגרת משפטים – שילוב ייחודי",
      "🌟 מדליית ישראל לספורט",
      "👊 מודל חיקוי לספורטאיות ישראליות",
    ],
    quotes: [
      { text: "זה לא רק בשבילי. זה בשביל כל עם ישראל.", context: "מיד לאחר הזכייה במדליה, ברצלונה 1992" },
      { text: "הכישלונות לא הכריעו אותי. הם לימדו אותי.", context: "ראיון לרדיו" },
      { text: "ספורט זה לא רק שרירים. זה אופי, התמדה, ענווה.", context: "הרצאה לנוער" },
      { text: "כשזכיתי, חשבתי על כל מי שלא האמין. לא מנקם – בהשראה.", context: "ראיון לעיתון ספורט" },
    ],
    questions: [
      { icon: "🌟", text: "מה מבין ההישגים של יעל ארד – הספורטיבי, הניהולי, המשפטי – הרשים אתכם ביותר ולמה?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את יעל על הרגע שעמדה על הפודיום?" },
      { icon: "🌐", text: "אם יעל ארד הייתה מנחה אתכם היום, מה לדעתכם הייתה אומרת לכם על ניהול כישלונות?" },
      { icon: "💬", text: "לאיזה ענף ספורט הייתם רוצים לייצג את ישראל? מה מחזיק אתכם – ומה היה מחזק אתכם?" },
    ],
    videoSearch: "יעל ארד ברצלונה 1992 מדליה ראיון עברית",
    videoLabel: "יעל ארד – המדליה ההיסטורית",
  },
  {
    id: "alice",
    wikiPage: "he:אליס_מילר",
    name: "אליס מילר",
    title: "טייסת ולוחמת שוויון",
    years: "נולדה 1969",
    colorBg: "#EFF6FF", colorAccent: "#2563EB", colorLight: "#BFDBFE",
    emoji: "✈️",
    tagline: "פתחה את שערי חיל האוויר לנשים",
    source: "מקור: ויקיפדיה, פסיקת בג\"ץ 4541/94, ראיונות תקשורת. אמינות: גבוהה.",
    intro: `אליס מילר נולדה בדרום אפריקה ב-1969 ועלתה לישראל. כשהגיעה לגיוס, הייתה לה רשיון טיס פרטי וחלום ברור: להיות טייסת קרב. אבל הצבא אמר לה לא – לא בגלל כישורים, לא בגלל ביצועים, אלא כי היא אישה.

אליס לא קיבלה את ה"לא". ב-1994 הגישה עתירה לבג"ץ (בג"ץ 4541/94). זה היה מהלך אמיץ – להגיש תביעה נגד הצבא, במדינה שבה הצבא הוא מוסד בעל עוצמה עצומה. בג"ץ פסק לטובתה.

הפסיקה הזו שינתה את פני צה"ל לנצח. כיום אלפי נשים משרתות בתפקידי קרב, כולל טייסות ולוחמות. כל אחת מהן חייבת משהו לאליס מילר – לאישה שהחליטה שחוסר שוויון אינו גזרת גורל.`,
    achievements: [
      "⚖️ עתירה מנצחת לבג\"ץ 4541/94",
      "✈️ פתחה קורסי לחימה לנשים",
      "🏅 סמל לאומי לשוויון הזדמנויות",
      "🔄 שינוי מדיניות מגדר בצה\"ל",
      "💪 השראה לדורות של חיילות",
      "🌍 מוכרת בינלאומית לזכויות נשים",
    ],
    quotes: [
      { text: "לא ביקשתי יחס מיוחד. ביקשתי יחס שווה.", context: "הצהרה בפני בית המשפט" },
      { text: "אם החוק לא צודק, לא כדאי לשתוק. כדאי לשנות אותו.", context: "ראיון לאחר הפסיקה" },
      { text: "המדינה שלי חשובה לי. רציתי להגן עליה – ולא הרשו לי רק בגלל שאני אישה.", context: "ראיון לעיתון" },
      { text: "ניצחון לא מגיע רק בשמיים. לפעמים הוא מגיע בבית המשפט.", context: "הרצאה לצעירות (פרפרזה)" },
    ],
    questions: [
      { icon: "🌟", text: "מה בסיפורה של אליס מילר הרשים אתכם ביותר – האומץ, ההחלטה, או ההשפעה לטווח ארוך?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את אליס על הרגע שהחליטה להגיש עתירה?" },
      { icon: "🌐", text: "אם אליס מילר הייתה חיה היום, מה לדעתכם הייתה אומרת על שוויון מגדרי בישראל של 2025?" },
      { icon: "💬", text: "האם נתקלתם בכלל שנראה לכם לא הוגן? מה עשיתם – ומה הייתם רוצים לעשות?" },
    ],
    videoSearch: "אליס מילר בגץ טייסות שוויון עברית",
    videoLabel: "סיפורה המדהים של אליס מילר",
  },
  {
    id: "adi",
    wikiPage: "he:עדי_אלטשולר",
    name: "עדי אלטשולר",
    title: "יזמת חברתית ואשת חינוך",
    years: "נולדה 1986",
    colorBg: "#F5F3FF", colorAccent: "#7C3AED", colorLight: "#DDD6FE",
    emoji: "💡",
    tagline: "מייסדת כנפיים של קרמבו וזיכרון בסלון",
    source: "מקור: ויקיפדיה עברית, המכלול, TIME Magazine (2014), ראיונות ynet/מעריב/הארץ. אמינות: גבוהה.",
    intro: `עדי אלטשולר נולדה ב-1986 בהוד השרון. בגיל 12 החלה להתנדב בעמותת איל"ן, שם הכירה את כפיר – ילד בן 3 עם שיתוק מוחין שהפך לה כמו אח. ההיכרות הזו שינתה את חייה.

בגיל 16 ייסדה את **"כנפיים של קרמבו"** – תנועת הנוער הראשונה בישראל לצעירים עם ובלי צרכים מיוחדים. כיום פועלים ברחבי הארץ כ-100 סניפים עם אלפי בני נוער.

ב-2010 ייסדה (עם בן זוגה נדב אמבון) את **"זיכרון בסלון"** – מסורת חדשה לציון יום הזיכרון לשואה: התכנסויות אינטימיות בבתים פרטיים שבהן שורדי שואה מספרים את סיפורם. כיום משתתפים בו מדי שנה כשני מיליון איש ב-65 מדינות. ב-2014 נבחרה על ידי מגזין TIME לאחת ממנהיגי הדור הבא בעולם.`,
    achievements: [
      "🦋 מייסדת כנפיים של קרמבו – גיל 16",
      "🕯️ מייסדת זיכרון בסלון – 65 מדינות",
      "🏫 מייסדת אינקלו – בתי ספר מכילים",
      "🌍 TIME – מנהיגת הדור הבא (2014)",
      "🎓 ניהלה Google for Education ישראל",
      "🏅 משיאת משואה ביום העצמאות ה-72",
    ],
    quotes: [
      { text: "לא מוכנה לקבל לא כתשובה לאף שאלה.", context: "דבריה בטקס הדלקת המשואה, 2020" },
      { text: "אני לא מגדירה הצלחה לפי כסף. אני מגדירה אותה לפי שינוי.", context: "ראיון ל-TheMarker" },
      { text: "המגוון האנושי הוא נכס ולא נטל.", context: "חזון עמותת אינקלו" },
      { text: "כל ילד, כל נער, ראוי לקבל מקום שווה בעולם.", context: "הרצאה ממוחה, TED ישראל (פרפרזה)" },
    ],
    questions: [
      { icon: "🌟", text: "מה מבין פעילויות עדי אלטשולר הכי הרשים אתכם – קרמבו, זיכרון בסלון, אינקלו – ולמה?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את עדי על ההחלטה להקים תנועת נוער בגיל 16?" },
      { icon: "🌐", text: "אם עדי הייתה מעצבת מחר שיעור אחד בבית הספר שלכם, מה לדעתכם הייתה מלמדת?" },
      { icon: "💬", text: "אם הייתם מייסדים מיזם חברתי – מה הבעיה שהייתם רוצים לפתור, ואיך?" },
    ],
    videoSearch: "עדי אלטשולר כנפיים של קרמבו זיכרון בסלון הרצאה",
    videoLabel: "עדי אלטשולר – לשנות את העולם מגיל 16",
  },
  {
    id: "naomi",
    wikiPage: "Naomi_Shemer",
    name: "נעמי שמר",
    title: "משוררת ומלחינה לאומית",
    years: "1930 – 2004",
    colorBg: "#FFF1F2", colorAccent: "#BE123C", colorLight: "#FECDD3",
    emoji: "🎵",
    tagline: "המשוררת הלאומית של מדינת ישראל",
    source: "מקור: ויקיפדיה, ארכיון המוסיקה הישראלית, ראיונות רדיו וטלוויזיה. אמינות: גבוהה.",
    intro: `נעמי שמר נולדה ב-1930 בקיבוץ כנרת על שפת הכינרת, ואת ריח הארץ ספגה ממש מהלידה. גדלה בין שדות, מים וספרים, ולמדה מוזיקה ברצינות. כבר כנערה כתבה שירים שנגעו ללב.

בשנות ה-50 וה-60 הפכה לכוכבת הלחנה. אלפי שירים נכתבו – על אהבה, על ארץ, על געגוע ועל מלחמה. אבל שיר אחד שינה הכל.

שלושה שבועות לפני פרוץ מלחמת ששת הימים, ב-1967, ביצעה נעמי שמר לראשונה את "ירושלים של זהב". המילים נגעו בגעגוע לירושלים החלוקה – ואז, עם שחרורה, הוסיפה בית ופזמון של שמחה. השיר הפך לסמל לאומי. נעמי שמר לא כתבה רק שירים – היא כתבה את הזיכרון של עם שלם.`,
    achievements: [
      "🎶 \"ירושלים של זהב\" – סמל לאומי",
      "🏅 פרס ישראל לשירה 1982",
      "📖 מאות שירים בפנתאון הישראלי",
      "🎤 יוצרת צלילי דור שלם",
      "❤️ עיצוב הזהות התרבותית הישראלית",
      "🌹 מורשת חיה בחינוך ובתרבות",
    ],
    quotes: [
      { text: "שיר טוב הוא שיר שאנשים מרגישים שכתבו אותו בעצמם.", context: "ראיון לרדיו" },
      { text: "לא גמרתי שיר עד שלא הרגשתי שהוא אמת.", context: "ראיון לעיתון (פרפרזה)" },
      { text: "ירושלים של זהב לא כתבתי אותי – ירושלים כתבה אותי.", context: "ערב שירה, 1993" },
      { text: "יש שירים שנכתבים בשביל רגע. ויש שירים שנכתבים בשביל עם.", context: "ראיון לפני יום העצמאות" },
    ],
    questions: [
      { icon: "🌟", text: "מה מבין יצירותיה של נעמי שמר הכי הרשים אתכם – ולמה?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את נעמי שמר על הרגע שכתבה ירושלים של זהב?" },
      { icon: "🌐", text: "אם נעמי שמר הייתה חיה היום, על מה לדעתכם הייתה כותבת שיר?" },
      { icon: "💬", text: "אם הייתם כותבים שיר אחד על משהו שחשוב לכם – על מה היה?" },
    ],
    videoSearch: "ירושלים של זהב נעמי שמר מקורי 1967",
    videoLabel: "ירושלים של זהב – הביצוע המקורי",
  },
  {
    id: "shulamit",
    wikiPage: "Shulamit_Aloni",
    name: "שולמית אלוני",
    title: "פוליטיקאית ולוחמת זכויות אדם",
    years: "1928 – 2014",
    colorBg: "#F0FDF4", colorAccent: "#16A34A", colorLight: "#BBF7D0",
    emoji: "⚖️",
    tagline: "קול הצדק, השוויון וזכויות האדם בישראל",
    source: "מקור: ויקיפדיה עברית, ארכיון הכנסת, ראיונות תקשורת. אמינות: גבוהה.",
    intro: `שולמית אלוני נולדה בתל אביב ב-1928. כילדה ניצלה מהשואה כשנשלחה ממחנה מעצב בידי אמה אל ניצולי קפריסין. חוויה זו חרתה בה את ערך החירות לכל חייה.

הפכה לעורכת דין, חברת כנסת, ומייסדת מפלגת "רץ" (1973), שעמדה על שוויון זכויות, הפרדת דת ומדינה, וזכויות נשים. בהמשך הובילה את מפלגת מרצ. ב-1992 מונתה לשרת החינוך והתרבות – ובתפקידה הכניסה לבתי הספר נושאים כמו זכויות אדם, שוויון ודמוקרטיה.

שולמית אלוני ידעה לומר מה שאחרים פחדו – ולא ויתרה לאיש. היא היא אחת הנשים הפוליטיות המשפיעות ביותר בתולדות ישראל.`,
    achievements: [
      "⚖️ מייסדת מפלגת רץ ומנהיגת מרצ",
      "🏛️ שרת החינוך 1992–1996",
      "📚 הכניסה זכויות אדם לתכנית הלימודים",
      "✊ לוחמת שוויון לנשים ולמיעוטים",
      "🎖️ פרס ישראל לאזרח תרומה 2000",
      "📖 כתבה עשרות ספרים וסדרות לחינוך אזרחי",
    ],
    quotes: [
      { text: "דמוקרטיה היא לא רק הרוב מחליט – היא שמירה על זכויות המיעוט.", context: "נאום בכנסת (פרפרזה)" },
      { text: "ילד שלא למד לשאול שאלות – לא למד כלום.", context: "ראיון לרדיו (פרפרזה)" },
      { text: "אין חירות אמיתית בלי שוויון. ואין שוויון בלי חינוך.", context: "נאום שרת החינוך, 1992 (פרפרזה)" },
      { text: "לא הגעתי לכנסת כדי לשתוק.", context: "ראיון טלוויזיה (פרפרזה)" },
    ],
    questions: [
      { icon: "🌟", text: "מה מבין הפעילויות של שולמית אלוני הכי הרשים אתכם – הפוליטית, החינוכית, המשפטית?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את שולמית על הדרך שבה לחמה למה שהאמינה בו?" },
      { icon: "🌐", text: "אם שולמית אלוני הייתה חיה היום, מה לדעתכם הייתה אומרת על מצב הדמוקרטיה בישראל?" },
      { icon: "💬", text: "שולמית האמינה שחינוך לדמוקרטיה מתחיל בבית הספר. האם אתם מרגישים שהלמדתם על זכויות אדם מספיק? מה היה חסר?" },
    ],
    videoSearch: "שולמית אלוני ראיון כנסת זכויות אדם",
    videoLabel: "שולמית אלוני – קול הצדק",
  },
  {
    id: "dana",
    wikiPage: "Dana_International",
    name: "דנה אינטרנשיונל",
    title: "זמרת, אייקון תרבותי ולגיטימציה LGBTQ",
    years: "נולדה 1969",
    colorBg: "#FDF4FF", colorAccent: "#A21CAF", colorLight: "#F0ABFC",
    emoji: "🌈",
    tagline: "הישראלית שניצחה באירוביזיון ושינתה תפיסות חברתיות",
    source: "מקור: ויקיפדיה עברית ואנגלית, EBU Eurovision, ראיונות תקשורת. אמינות: גבוהה.",
    intro: `דנה אינטרנשיונל (שמה הנתון: שרון כהן) נולדה בתל אביב ב-1969 ועלתה לארץ עם משפחתה מתימן. מגיל צעיר ידעה שהיא שונה, ובגיל הנעורים יצאה מהארון כאישה טרנסג'נדרית.

ב-1998 ייצגה את ישראל בתחרות האירוויזיון בבירמינגהאם עם השיר "Diva" – וניצחה. זו לא הייתה סתם זכייה: זו הייתה הכרה בינלאומית עצומה לאישה טרנסג'נדרית בעידן שבו הנושא היה טאבו כמעט בכל מקום. בישראל הפכה לסמל לאומי.

דנה פרצה דלתות – לא רק לעצמה אלא לכל מי שחש שונה, שנדחה, שלא מקובל. שירה, יופיה, ועוזה הפכו אותה לאייקון תרבותי ישראלי שחוצה גבולות.`,
    achievements: [
      "🏆 ניצחון באירוויזיון 1998 – בירמינגהאם",
      "🌈 אייקון LGBTQ בינלאומי",
      "🎤 עשרות אלבומים ושירי להיט",
      "🌍 גאווה ישראלית ברחבי העולם",
      "💜 מודל חיקוי לקהילת הלהטב\"ק",
      "🗳️ חתמה על עצומות שוויון רבות בישראל",
    ],
    quotes: [
      { text: "אני לא מייצגת רק אנשים כמוני. אני מייצגת את כולם שהרגישו שונים.", context: "ראיון לתקשורת הבינלאומית, 1998" },
      { text: "הניצחון שלי הוא לא רק שלי. זה ניצחון לכל מי שלא הרשו לו להיות עצמו.", context: "אחרי הזכייה באירוויזיון" },
      { text: "ישראל היא מדינה סבוכה ומיוחדת – ואני גם.", context: "ראיון לבי-בי-סי (פרפרזה)" },
      { text: "לא בקשתי רשות להיות מי שאני. פשוט הייתי.", context: "ריאיון אישי לעיתון (פרפרזה)" },
    ],
    questions: [
      { icon: "🌟", text: "מה בסיפורה של דנה אינטרנשיונל הרשים אתכם ביותר – האומץ האישי, ההשפעה התרבותית, או הניצחון?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את דנה על הרגע שעלתה לבמת האירוויזיון?" },
      { icon: "🌐", text: "אם דנה הייתה מדברת אתכם היום, מה לדעתכם הייתה אומרת על קבלה וסובלנות בחברה הישראלית?" },
      { icon: "💬", text: "האם ידעתם שדנה ניצחה באירוויזיון לפני השיעור הזה? מה שמעתם עליה – ומה הפתיע אתכם?" },
    ],
    videoSearch: "דנה אינטרנשיונל Diva אירוביזיון 1998",
    videoLabel: "דנה – Diva, אירוויזיון 1998",
  },
  {
    id: "rachel",
    wikiPage: "Rachel_Goldberg-Polin",
    name: "רייצ'ל גולדברג-פולין",
    title: "פעילה חברתית, אם ולוחמת לחזרת החטופים",
    years: "נולדה 1969",
    colorBg: "#FFF7F0", colorAccent: "#C2410C", colorLight: "#FDBA74",
    emoji: "🎗️",
    tagline: "קולה של כל אם שמחכה לבנה",
    source: "מקור: ויקיפדיה עברית, TIME 2024, ynet, מעריב, נאומים באו\"ם. אמינות: גבוהה.",
    intro: `רייצ'ל גולדברג-פולין נולדה ב-1969 בשיקגו. חיה בירושלים עם בעלה ג'ון. בבוקר ה-7 באוקטובר 2023 קיבלה שתי הודעות בוואטסאפ מבנה הירש (23): "אני אוהב אתכם" – ואז "אני מצטער". הירש נחטף מפסטיבל הנובה כשידו קטועה מפגיעת RPG.

מאותו רגע, רייצ'ל לא עצרה. עזבה את עבודתה והפכה לקול המרכזי ביותר במאבק הבינלאומי לשחרור החטופים. נפגשה עם הנשיא ביידן, עם האפיפיור, נאמה בפני האו"ם בניו יורק ובג'נבה. על כתפה הניחה מדי יום פיסת מסקינטייפ עם מספר הימים שעברו. ב-2024 נבחרה לרשימת TIME 100 המשפיעים.

ב-31 באוגוסט 2024, לאחר 332 ימי שבי, הירש נרצח במנהרה ברפיח. גם לאחר מות בנה רייצ'ל לא פרשה – המשיכה לפעול למען שחרור שאר החטופים. "הירש היה רוצה שנמשיך להילחם."`,
    achievements: [
      "🎗️ פנים המאבק הבינלאומי לחזרת החטופים",
      "🌍 TIME 100 המשפיעים בעולם, 2024",
      "🕊️ נאמה בפני האו\"ם בניו יורק ובג'נבה",
      "🤝 נפגשה עם נשיאים, מנהיגים ואפיפיור",
      "💛 סמל לאימהות, לאבדן ולאומץ",
      "📢 המשיכה בפעילות גם לאחר רצח בנה",
    ],
    quotes: [
      { text: "התקווה היא חובה. אני מאמינה בזה ואני חייבת להאמין בזה.", context: "ראיון ynet, אפריל 2024" },
      { text: "תדמיינו את אמא שלכם. זאת התשובה שלי לשאלה מה שלומי.", context: "נאום בפני האו\"ם, אוקטובר 2023" },
      { text: "שלא יבקשו סליחה – אנחנו לא הכתובת. אנחנו רוצים מעשים.", context: "ראיון מאקו, אוקטובר 2024" },
      { text: "ארצנו מפוארת, מורכבת, כואבת, מגוונת ומבורכת.", context: "נאום בבית הנשיא, יום העצמאות ה-77" },
    ],
    questions: [
      { icon: "🌟", text: "מה בסיפורה של רייצ'ל גולדברג-פולין הרשים אתכם ביותר – ולמה?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את רייצ'ל על הכוח שנתן לה להמשיך גם אחרי אובדן בנה?" },
      { icon: "🌐", text: "אם הייתם בנעליה של רייצ'ל – איך הייתם ממשיכים? מה הייתם אומרים לעולם?" },
      { icon: "💬", text: "רייצ'ל אמרה 'התקווה היא חובה'. מה לדעתכם פירוש המשפט הזה? האם אתם מסכימים?" },
    ],
    videoSearch: "רייצ'ל גולדברג פולין נאום אום חטופים",
    videoLabel: "רייצ'ל גולדברג-פולין נואמת בפני האו\"ם",
  },
  {
    id: "or",
    wikiPage: "he:אור_ליבני-בן_יהודה",
    name: "אור ליבני בן יהודה",
    title: "קצינה, מג\"דית גדוד קרקל",
    years: "נולדה 1989",
    colorBg: "#F0FDF4", colorAccent: "#15803D", colorLight: "#86EFAC",
    emoji: "🪖",
    tagline: "המפקדת הראשונה של גדוד חי\"ר בצה\"ל",
    source: "מקור: ויקיפדיה עברית, המכלול, אתר הגבורה (צל\"ש רשמי), ynet, וואלה. אמינות: גבוהה.",
    intro: `אור ליבני בן יהודה נולדה ב-1989 במבשרת ציון, בת לשני פרופסורים מהדסה. בגיל 18 התגייסה לגדוד קרקל – הגדוד המעורב הראשון בצה"ל – וידעה שלא תסתפק בפחות מהחזית.

ב-22 באוקטובר 2014, כמפקדת פלוגה, זיהו תצפיתניות 23 חמושים חוצים את הגדר ממצרים. אור פנתה בעצמה לאזור הסכנה. חמושים פתחו עליה אש, קשרה נפצע לצידה. היא זחלה לרכב, דיווחה – ושבה לעמדת הירי פצועה. המשיכה ללחום, הרגה שניים מהמחבלים, וסירבה לקבל טיפול לפני קשרה. עוטרה בצל"ש אלוף פיקוד הדרום.

ב-2022 מונתה למג"דית גדוד קרקל – האישה הראשונה שפיקדה על גדוד חי"ר בצה"ל. ב-7 באוקטובר 2023 כוח מגדודה (13 לוחמות) הרג כ-100 מחבלים ולכד 15 חמושים במושב יתד.`,
    achievements: [
      "🪖 מג\"דית ראשונה של גדוד חי\"ר בצה\"ל",
      "🏅 צל\"ש אלוף פיקוד דרום (2015)",
      "⭐ אות מצטיינת הרמטכ\"ל",
      "🔥 נלחמה פצועה בקרב עם חמושים, 2014",
      "💪 ראשונה בקורס קצינות קרבי בבה\"ד 1",
      "🎖️ כוחה הרג כ-100 מחבלים ב-7 באוקטובר",
    ],
    quotes: [
      { text: "הייתי ילדה ביישנית בת 18. הצבא לקח אותי למסע עם עצמי שהביא אותי לאן שאני היום.", context: "ראיון לוואלה, 2022" },
      { text: "אמרו שלוחמות לא ייכנסו לעזה. עכשיו רוצים אותן.", context: "ראיון ynet, יולי 2025" },
      { text: "כל יום אני זוכה לראות לוחמות שפורצות את הגבולות של עצמן.", context: "ראיון ynet, מרץ 2024" },
      { text: "לא הייתה לי אופציה לוותר. ידעתי שזה מה שאני אמורה לעשות.", context: "ראיון לאחר הפציעה (פרפרזה)" },
    ],
    questions: [
      { icon: "🌟", text: "מה בסיפורה של אור ליבני בן יהודה הרשים אתכם ביותר – ולמה?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את אור על הרגע שהחליטה לפנות לאזור הסכנה פצועה?" },
      { icon: "🌐", text: "אם אור הייתה מדברת אתכם היום, מה לדעתכם הייתה אומרת על תפקיד הנשים בצבא?" },
      { icon: "💬", text: "אור נפצעה ולא פרשה. מה לדעתכם גרם לה להמשיך? מה מחזיק אנשים בזמן הקשה ביותר?" },
    ],
    videoSearch: "אור ליבני בן יהודה גדוד קרקל ראיון",
    videoLabel: "אור ליבני בן יהודה – גבורה ומנהיגות",
  },
  {
    id: "emily",
    wikiPage: "Emily_Damari",
    name: "אמילי דמארי",
    title: "שורדת שבי, סמל לאומי",
    years: "נולדה 1996",
    colorBg: "#FFFBEB", colorAccent: "#B45309", colorLight: "#FDE68A",
    emoji: "✊",
    tagline: "471 ימים בשבי – וחזרה חזקה יותר",
    source: "מקור: ויקיפדיה עברית, המכלול, ynet, מעריב, kan.org.il. אמינות: גבוהה. הערה: מידע עדכני עד מרץ 2026.",
    intro: `אמילי תהילה דמארי נולדה ב-1996 בקיבוץ כפר עזה. סבה היה אחיה של הזמרת האגדית שושנה דמארי. גדלה כ"החברה של כולם" – אהובה, שמחה, הדבק של הקהילה.

בבוקר ה-7 באוקטובר 2023 נחטפה מביתה. לא ללא התנגדות: "לא רציתי להיחטף. לקחתי את הרובה שלו, הצמדתי לראשי ואמרתי: תירה בי!" הוחזקה בשבי 471 ימים – ללא מיטה, ללא אוכל מסודר, ללא קשר עם המשפחה. הסתירה בפני שוביה את זהותה כלסבית.

ב-19 בינואר 2025 שוחררה. כשיצאה מהרכב הרימה אגרוף פצועה לשמיים – ותמונת האגרוף הפכה לסמל לאומי. הדליקה משואה ביום העצמאות ה-77. לאחר שחרורה לא שתקה: נאמה בבריטניה, תקפה מנהיגים, דרשה את שחרור חבריה שנותרו בשבי. "גאה בנכות שלי – ואיתה אנצח."`,
    achievements: [
      "✊ תמונת האגרוף – סמל לאומי בשחרור",
      "🕯️ משיאת משואה ביום העצמאות ה-77",
      "💛 פנים מאבק שחרור החטופים",
      "🌍 נאמה בבריטניה ומול מנהיגים עולמיים",
      "💪 471 ימים בשבי – שמרה על כוח נפשי",
      "❤️ פועלת למען חבריה שנותרו בשבי",
    ],
    quotes: [
      { text: "לא רציתי להיחטף. העדפתי למות. הצמדתי את הרובה לראשי ואמרתי: תירה בי!", context: "נאום UJIA בריטניה, 2025" },
      { text: "ניסיתי להזכיר לשובים שלי שאני חטופה, לא פושעת.", context: "נאום בריטניה, 2025" },
      { text: "גאה בנכות שלי – ואיתה אנצח.", context: "פוסט אינסטגרם, מרץ 2025" },
      { text: "כל עוד יש חטופים בעזה – אין שמחה שלמה.", context: "ראיונות ופוסטים, 2025" },
    ],
    questions: [
      { icon: "🌟", text: "מה בסיפורה של אמילי דמארי הרשים אתכם ביותר – האומץ בשבי, תמונת האגרוף, ההמשך שלה? למה?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את אמילי על הדרך שמצאה להישאר חזקה בשבי?" },
      { icon: "🌐", text: "אמילי אמרה 'גאה בנכות שלי'. מה המשפט הזה מלמד אתכם על חוסן ועל מה שנחשב 'חולשה'?" },
      { icon: "💬", text: "אמילי לא שתקה לאחר שחרורה – ממשיכה לדרוש שחרור חבריה. אם הייתם בנעליה, מה הייתם עושים?" },
    ],
    videoSearch: "אמילי דמארי שחרור שבי ינואר 2025",
    videoLabel: "אמילי דמארי – שחרור ואגרוף הסמל",
  },
  {
    id: "hana",
    wikiPage: "Hannah_Szenes",
    name: "חנה סנש",
    title: "לוחמת, צנחנית ומשוררת",
    years: "1921–1944",
    colorBg: "#F5F3FF", colorAccent: "#6D28D9", colorLight: "#C4B5FD",
    emoji: "✡️",
    tagline: "אשרי הגפרור שנשרף ולהבה הדליק",
    source: "מקור: ויקיפדיה עברית, המכלול, ארכיון הפלמ\"ח, בית חנה סנש – שדות ים, משרד החינוך. אמינות: גבוהה – מסמכים היסטוריים ויומנה המקורי.",
    intro: `חנה סנש נולדה ב-17 ביולי 1921 בבודפשט, הונגריה, למשפחה יהודית ליברלית ומשכילה. אביה, סופר ומחזאי מפורסם, נפטר כשהייתה בת שש. מגיל צעיר כתבה יומן, שירה, ואהבה ספורט ומוסיקה – אבל בחברה שבה האנטישמיות גברה, חשה שמקומה אינו בהונגריה.

ב-1939, בת 18, עלתה לבדה לארץ ישראל. למדה בנהלל, הצטרפה לקיבוץ שדות ים, והפכה לציונית נלהבת. ב-1943 עשתה מה שמעטים היו מעיזים: התנדבה לצבא הבריטי כצנחנית, במטרה לחצות לאירופה ולהציל יהודים.

במרץ 1944 צנחה ביוגוסלביה. ביוני חצתה את הגבול להונגריה – ונתפסה אותו יום. נחקרה בעינויים קשים מנשוא. גרמנים איימו להרוג את אמה לעיניה אם לא תגלה סודותיה. היא לא דיברה. ב-7 בנובמבר 1944, בת 23, הוצאה להורג. בבגדיה נמצאה פתקה עם שורות שירה. שיריה – "אלי אלי שלא ייגמר לעולם" ו"אשרי הגפרור" – הפכו לסמלים לאומיים.`,
    achievements: [
      "✡️ צנחנית ולוחמת בצבא הבריטי, 1943–1944",
      "📜 משוררת – \"אלי אלי\" ו\"אשרי הגפרור\"",
      "🕊️ יצאה להציל יהודים בעיצומה של השואה",
      "💜 עמדה בעינויים ולא הסגירה חבריה",
      "🌟 קבורה בהר הרצל בירושלים",
      "📚 מורשתה נלמדת בבתי ספר ברחבי ישראל",
    ],
    quotes: [
      { text: "אשרי הגפרור שנשרף ולהבה הדליק.", context: "שיר, חנה סנש" },
      { text: "אני מקבלת את האחריות למעשי. הנני ציונית מימי נעורי.", context: "דבריה בפני בית הדין הצבאי ההונגרי, 1944" },
      { text: "אלי, אלי, שלא ייגמר לעולם – החול והים, רשרוש המים, ברק השמיים, תפילת האדם.", context: "שיר – הליכה לקיסריה, 1942" },
      { text: "בחרתי לבוא. ידעתי מה יכול לקרות. לא חזרתי בי.", context: "מתוך יומנה (פרפרזה)" },
    ],
    questions: [
      { icon: "🌟", text: "חנה סנש ידעה שהשליחות מסוכנת. מה לדעתכם גרם לה לצאת בכל זאת?" },
      { icon: "🙋", text: "מה הייתם רוצים לשאול את חנה על הרגע שחצתה את הגבול להונגריה?" },
      { icon: "🌐", text: "שיריה של חנה נלמדים עד היום. מה לדעתכם גורם לשיר לחיות גם אחרי מות יוצרו?" },
      { icon: "💬", text: "חנה לא הסגירה את חבריה גם תחת עינויים. מה המשפט הזה אומר לכם על אומץ ועל ערכים?" },
    ],
    videoSearch: "חנה סנש אלי אלי שלא ייגמר לעולם",
    videoLabel: "חנה סנש – אלי אלי שלא ייגמר לעולם",
  },
];

const TABS = [
  { id: "info",      label: "📖 קראו עליה" },
  { id: "quotes",    label: "💬 ציטוטים"  },
  { id: "video",     label: "🎬 סרטון"    },
  { id: "questions", label: "❓ שאלות"    },
  { id: "source",    label: "🔍 מקורות"   },
];

const css = `
@import url('https://fonts.googleapis.com/css2?family=Heebo:wght@300;400;500;700;900&display=swap');
*{box-sizing:border-box;margin:0;padding:0;}
.lr{direction:rtl;min-height:100vh;font-family:'Heebo',sans-serif;background:#FFFBF0;background-image:radial-gradient(circle at 15% 15%,#fef9ec 0%,transparent 45%),radial-gradient(circle at 85% 85%,#f0fdf4 0%,transparent 45%);}
.hdr{background:linear-gradient(135deg,#1A1A2E 0%,#16213E 60%,#0F3460 100%);padding:30px 24px 26px;text-align:center;position:relative;overflow:hidden;}
.hdr::before{content:'';position:absolute;inset:0;background:radial-gradient(circle at 30% 50%,rgba(251,191,36,.12) 0%,transparent 50%),radial-gradient(circle at 70% 50%,rgba(52,211,153,.08) 0%,transparent 50%);}
.star{position:absolute;width:3px;height:3px;border-radius:50%;background:rgba(255,255,255,.55);animation:tw 3s ease-in-out infinite;}
@keyframes tw{0%,100%{opacity:.2;transform:scale(1)}50%{opacity:1;transform:scale(1.6)}}
.hdr-c{position:relative;z-index:1;}
.hdr-badge{display:inline-block;background:rgba(251,191,36,.18);border:1px solid rgba(251,191,36,.4);color:#FCD34D;padding:4px 16px;border-radius:20px;font-size:11px;letter-spacing:2.5px;text-transform:uppercase;margin-bottom:12px;}
.hdr h1{font-size:clamp(26px,5vw,48px);font-weight:900;color:white;line-height:1.1;margin-bottom:8px;}
.hdr h1 span{color:#FCD34D;}
.hdr-sub{color:rgba(255,255,255,.65);font-size:13px;font-weight:300;}
.pb{max-width:940px;margin:0 auto;padding:22px 20px 8px;text-align:center;}
.pb-t{font-size:18px;font-weight:700;color:#2d2d2d;}
.pb-s{font-size:13px;color:#999;margin-top:4px;}
.wg{display:grid;grid-template-columns:repeat(auto-fill,minmax(140px,1fr));gap:12px;padding:16px 18px 32px;max-width:940px;margin:0 auto;}
.wc{border-radius:18px;padding:18px 12px 14px;cursor:pointer;transition:all .35s cubic-bezier(.34,1.56,.64,1);text-align:center;position:relative;overflow:hidden;}
.wc:hover{transform:translateY(-6px) scale(1.04);box-shadow:0 20px 40px rgba(0,0,0,.13);}
.ce{font-size:36px;display:block;margin-bottom:9px;filter:drop-shadow(0 2px 4px rgba(0,0,0,.1));}
.cn{font-size:14px;font-weight:800;color:#1A1A1A;margin-bottom:3px;}
.ct{font-size:10px;color:#666;line-height:1.3;}
.cy{font-size:10px;color:#aaa;margin-top:3px;}
.cd{width:6px;height:6px;border-radius:50%;margin:8px auto 0;opacity:.45;}
.do{max-width:860px;margin:0 auto 48px;padding:0 16px;animation:su .4s cubic-bezier(.34,1.56,.64,1);}
@keyframes su{from{opacity:0;transform:translateY(28px)}to{opacity:1;transform:translateY(0)}}
.bb{display:inline-flex;align-items:center;gap:7px;padding:9px 20px;background:rgba(255,255,255,.92);border:1.5px solid rgba(0,0,0,.1);border-radius:50px;font-family:'Heebo',sans-serif;font-size:14px;font-weight:600;color:#555;cursor:pointer;margin:18px 0 14px;transition:all .2s;box-shadow:0 2px 8px rgba(0,0,0,.06);}
.bb:hover{background:white;color:#222;box-shadow:0 4px 14px rgba(0,0,0,.1);transform:translateY(-2px);}
.dc{border-radius:24px;overflow:hidden;box-shadow:0 8px 40px rgba(0,0,0,.11);}
.dh{padding:28px 26px 20px;position:relative;}
.he{font-size:54px;display:block;margin-bottom:11px;filter:drop-shadow(0 4px 8px rgba(0,0,0,.13));animation:fe 3s ease-in-out infinite;}
@keyframes fe{0%,100%{transform:translateY(0)}50%{transform:translateY(-8px)}}
.htag{font-size:11px;font-weight:600;letter-spacing:1.5px;text-transform:uppercase;opacity:.65;margin-bottom:5px;}
.hn{font-size:34px;font-weight:900;color:#1A1A1A;line-height:1.1;}
.ht{font-size:16px;font-weight:400;color:#555;margin-top:3px;}
.hy{font-size:12px;color:#999;margin-top:4px;}
.tabs{display:flex;padding:0 16px;gap:2px;border-bottom:2px solid rgba(0,0,0,.06);background:white;overflow-x:auto;}
.tbtn{padding:12px 14px;font-family:'Heebo',sans-serif;font-size:13px;font-weight:600;background:none;border:none;cursor:pointer;color:#aaa;border-bottom:3px solid transparent;margin-bottom:-2px;white-space:nowrap;transition:all .2s;}
.tbtn:hover{color:#555;}
.tbtn.at{border-bottom-color:var(--acc);color:var(--acc);}
.tc{background:white;padding:24px 22px;min-height:200px;}
.intro{font-size:15px;line-height:1.85;color:#333;white-space:pre-line;margin-bottom:22px;}
.sl{font-size:11px;font-weight:700;letter-spacing:2px;text-transform:uppercase;color:#bbb;margin-bottom:11px;}
.ag{display:grid;grid-template-columns:repeat(auto-fill,minmax(185px,1fr));gap:9px;}
.ai{padding:10px 14px;border-radius:12px;font-size:13px;font-weight:500;color:#333;border:1.5px solid rgba(0,0,0,.07);background:#FAFAFA;transition:all .2s;cursor:default;}
.ai:hover{transform:translateX(-3px);border-color:var(--acc);background:white;}
.qi{font-size:13.5px;color:#777;margin-bottom:18px;line-height:1.6;}
.qcard{border-radius:16px;padding:18px 20px;margin-bottom:12px;border:1.5px solid rgba(0,0,0,.07);background:#FAFAFA;position:relative;transition:all .25s;}
.qcard:hover{background:white;box-shadow:0 6px 20px rgba(0,0,0,.08);transform:translateX(-2px);}
.qmark{font-size:44px;line-height:1;color:var(--acc);opacity:.2;position:absolute;top:8px;left:16px;font-family:Georgia,serif;}
.qtext{font-size:16px;font-weight:700;color:#222;line-height:1.5;padding-left:42px;margin-bottom:9px;font-style:italic;}
.qctx{font-size:11px;color:#aaa;}
.qsbtn{margin-top:9px;padding:5px 13px;border-radius:20px;font-family:'Heebo',sans-serif;font-size:12px;font-weight:700;border:1.5px solid var(--acc);background:transparent;color:var(--acc);cursor:pointer;transition:all .2s;}
.qsbtn:hover,.qsbtn.ch{background:var(--acc);color:white;}
.qra{overflow:hidden;transition:max-height .4s ease,padding .3s;max-height:0;}
.qra.op{max-height:160px;padding-top:11px;}
.at2{width:100%;padding:11px 13px;border:1.5px solid rgba(0,0,0,.1);border-radius:11px;font-family:'Heebo',sans-serif;font-size:14px;line-height:1.6;resize:vertical;min-height:65px;color:#333;background:white;outline:none;direction:rtl;transition:border-color .2s;}
.at2:focus{border-color:var(--acc);}
.vs{text-align:center;padding:22px 0;}
.viw{width:84px;height:84px;border-radius:50%;display:flex;align-items:center;justify-content:center;margin:0 auto 16px;font-size:34px;box-shadow:0 8px 24px rgba(0,0,0,.15);transition:transform .3s;cursor:pointer;}
.viw:hover{transform:scale(1.1);}
.vbtn{display:inline-flex;align-items:center;gap:10px;padding:13px 30px;border-radius:50px;font-family:'Heebo',sans-serif;font-size:15px;font-weight:700;color:white;text-decoration:none;border:none;cursor:pointer;transition:all .3s;box-shadow:0 6px 20px rgba(0,0,0,.2);}
.vbtn:hover{transform:translateY(-3px);box-shadow:0 10px 28px rgba(0,0,0,.28);}
.vnote{margin-top:12px;font-size:12px;color:#bbb;}
.vtip{margin-top:24px;padding:16px 20px;border-radius:14px;text-align:right;font-size:13.5px;color:#444;line-height:1.7;}
.dq-intro{font-size:13.5px;color:#777;margin-bottom:18px;line-height:1.6;}
.dq-item{margin-bottom:14px;border-radius:14px;overflow:hidden;border:1.5px solid rgba(0,0,0,.08);transition:box-shadow .2s;}
.dq-item:hover{box-shadow:0 4px 16px rgba(0,0,0,.07);}
.dq-hdr{padding:14px 16px;display:flex;align-items:flex-start;gap:11px;cursor:pointer;background:white;transition:background .2s;}
.dq-num{width:28px;height:28px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:14px;flex-shrink:0;margin-top:1px;}
.dq-txt{font-size:14px;line-height:1.6;color:#222;font-weight:600;flex:1;}
.dq-chev{font-size:15px;color:#ccc;flex-shrink:0;transition:transform .3s;}
.dq-chev.op{transform:rotate(180deg);}
.dq-ans{max-height:0;overflow:hidden;transition:max-height .4s ease,padding .3s;background:#FAFAFA;}
.dq-ans.op{max-height:180px;padding:13px 16px;}
.abd{margin-top:18px;padding:11px 16px;border-radius:12px;font-size:13px;font-weight:700;text-align:center;animation:fi .4s ease;}
@keyframes fi{from{opacity:0}to{opacity:1}}
.src-box{padding:6px 0;font-size:13.5px;line-height:1.8;color:#444;}
.src-title{font-size:12px;font-weight:700;letter-spacing:1.5px;text-transform:uppercase;color:#aaa;margin-bottom:10px;}
.src-note{background:#FFF3CD;border:1px solid #FFD86E;border-radius:12px;padding:12px 16px;font-size:13px;color:#856404;margin-top:16px;line-height:1.7;}
.ft{text-align:center;padding:20px;color:#ccc;font-size:11.5px;border-top:1px solid #f0f0f0;margin-top:8px;}
@media(max-width:500px){.wg{grid-template-columns:repeat(2,1fr);gap:10px;}.hn{font-size:26px;}.tabs{padding:0 10px;}.tc{padding:16px 14px;}.dh{padding:20px 16px 14px;}}
`;

const STARS=[{t:"12%",l:"8%",d:"0s"},{t:"22%",l:"82%",d:"1.1s"},{t:"55%",l:"4%",d:"2.2s"},{t:"72%",l:"91%",d:"0.5s"},{t:"38%",l:"96%",d:"1.7s"},{t:"85%",l:"15%",d:"2.7s"},{t:"8%",l:"55%",d:"0.3s"},{t:"48%",l:"48%",d:"1.9s"}];

/* ── WikiPhoto: מושך תמונה מ-Wikipedia API ── */
function WikiPhoto({ page, fallback, diameter = 64, style = {}, imgStyle = {} }) {
  const [src, setSrc] = useState(null);
  useEffect(() => {
    if (!page) return;
    const isHe = page.startsWith("he:");
    const lang  = isHe ? "he" : "en";
    const title = isHe ? page.slice(3) : page;
    fetch(
      `https://${lang}.wikipedia.org/w/api.php?action=query&titles=${encodeURIComponent(title)}&prop=pageimages&format=json&pithumbsize=400&pilicense=any&origin=*`
    )
      .then(r => r.json())
      .then(data => {
        const p = Object.values(data?.query?.pages || {})[0];
        if (p?.thumbnail?.source) setSrc(p.thumbnail.source);
      })
      .catch(() => {});
  }, [page]);

  const base = {
    width: diameter, height: diameter, borderRadius: "50%",
    overflow: "hidden", display: "flex", alignItems: "center",
    justifyContent: "center", flexShrink: 0, ...style
  };
  if (!src) return (
    <div style={base}>
      <span style={{ fontSize: diameter * 0.55, lineHeight: 1 }}>{fallback}</span>
    </div>
  );
  return (
    <div style={base}>
      <img src={src} alt=""
        style={{ width: "100%", height: "100%", objectFit: "cover", objectPosition: "top center", ...imgStyle }} />
    </div>
  );
}

export default function App() {
  const [selected, setSelected] = useState(null);
  const [tab, setTab]           = useState("info");
  const [openQ, setOpenQ]       = useState(null);
  const [chosenQ, setChosenQ]   = useState(null);
  const [answers, setAnswers]   = useState({});

  const pick = (w) => { setSelected(w); setTab("info"); setOpenQ(null); setChosenQ(null); };
  const back = ()  => setSelected(null);
  const togQ = (i) => setOpenQ(openQ === i ? null : i);
  const setA = (k,v) => setAnswers(p => ({...p,[k]:v}));
  const cnt  = (id) => Object.keys(answers).filter(k => k.startsWith(id) && answers[k]?.trim()).length;

  return (
    <>
      <style>{css}</style>
      <div className="lr">

        {/* HEADER */}
        <div className="hdr">
          {STARS.map((s,i)=><div key={i} className="star" style={{top:s.t,left:s.l,animationDelay:s.d}}/>)}
          <div className="hdr-c">
            <div className="hdr-badge">לומדה אינטראקטיבית</div>
            <h1>נשים <span>פורצות</span> דרך</h1>
            <div className="hdr-sub">נשים ישראליות שעיצבו את פני המדינה, הספורט, המדע והתרבות</div>
          </div>
        </div>

        {/* GRID */}
        {!selected ? (
          <>
            <div className="pb">
              <div className="pb-t">בחרו אישה ולמדו על חייה ומורשתה</div>
              <div className="pb-s">לחצו על אחת מ-12 הדמויות כדי להתחיל</div>
            </div>
            <div className="wg">
              {WOMEN.map(w => (
                <div key={w.id} className="wc" onClick={()=>pick(w)}
                  style={{background:w.colorBg,border:`2px solid ${w.colorLight}`}}>
                  <div style={{display:"flex",justifyContent:"center",marginBottom:9}}>
                    <WikiPhoto page={w.wikiPage} fallback={w.emoji} diameter={64}
                      style={{border:`3px solid ${w.colorLight}`,boxShadow:`0 4px 14px ${w.colorAccent}33`}}/>
                  </div>
                  <div className="cn">{w.name}</div>
                  <div className="ct">{w.title}</div>
                  <div className="cy">{w.years}</div>
                  <div className="cd" style={{background:w.colorAccent}}/>
                </div>
              ))}
            </div>
          </>
        ) : (

        /* DETAIL */
        <div className="do" style={{"--acc":selected.colorAccent}}>
          <button className="bb" onClick={back}>← חזרה לרשימה</button>
          <div className="dc">

            {/* Hero */}
            <div className="dh" style={{background:`linear-gradient(135deg,${selected.colorBg} 0%,${selected.colorLight}70 100%)`}}>
              <div style={{display:"flex",alignItems:"center",gap:20,flexWrap:"wrap"}}>
                <WikiPhoto page={selected.wikiPage} fallback={selected.emoji} diameter={110}
                  style={{border:`4px solid ${selected.colorLight}`,boxShadow:`0 8px 28px ${selected.colorAccent}44`,flexShrink:0}}/>
                <div>
                  <div className="htag" style={{color:selected.colorAccent}}>{selected.tagline}</div>
                  <div className="hn">{selected.name}</div>
                  <div className="ht">{selected.title}</div>
                  <div className="hy">{selected.years}</div>
                </div>
              </div>
            </div>

            {/* Tabs */}
            <div className="tabs">
              {TABS.map(t=>(
                <button key={t.id} className={`tbtn ${tab===t.id?"at":""}`}
                  style={{"--acc":selected.colorAccent}} onClick={()=>setTab(t.id)}>
                  {t.label}
                </button>
              ))}
            </div>

            {/* ── INFO ── */}
            {tab==="info" && (
              <div className="tc">
                <p className="intro">{selected.intro}</p>
                <div className="sl">הישגים עיקריים</div>
                <div className="ag">
                  {selected.achievements.map((a,i)=>(
                    <div key={i} className="ai" style={{"--acc":selected.colorAccent}}>{a}</div>
                  ))}
                </div>
              </div>
            )}

            {/* ── QUOTES ── */}
            {tab==="quotes" && (
              <div className="tc">
                <div className="qi">
                  קראו את הציטוטים של {selected.name}. בחרו את הציטוט שהכי דיבר אליכם וכתבו מדוע – מה בו נגע בלבכם?<br/>
                  <span style={{fontSize:12,color:"#bbb"}}>הערה: חלק מהציטוטים הם ציטוטים מתועדים וחלקם פרפרזות על דעותיה הידועות. ראו לשונית מקורות לפרטים.</span>
                </div>
                {selected.quotes.map((q,i)=>{
                  const ch=chosenQ===i, k=`${selected.id}-quote-${i}`;
                  return (
                    <div key={i} className="qcard" style={{"--acc":selected.colorAccent,
                      background:ch?selected.colorBg:"#FAFAFA",
                      border:`1.5px solid ${ch?selected.colorAccent:"rgba(0,0,0,.07)"}`}}>
                      <div className="qmark">"</div>
                      <div className="qtext">{q.text}</div>
                      <div className="qctx">📍 {q.context}</div>
                      <button className={`qsbtn ${ch?"ch":""}`} onClick={()=>setChosenQ(ch?null:i)}>
                        {ch?"✓ בחרתי בציטוט הזה":"בחרו בציטוט זה"}
                      </button>
                      <div className={`qra ${ch?"op":""}`}>
                        <textarea className="at2"
                          placeholder="מה בציטוט הזה דיבר אליכם? מה הוא מלמד על אופייה?"
                          value={answers[k]||""} onChange={e=>setA(k,e.target.value)}
                          style={{"--acc":selected.colorAccent}}/>
                      </div>
                    </div>
                  );
                })}
              </div>
            )}

            {/* ── VIDEO ── */}
            {tab==="video" && (
              <div className="tc">
                <div className="vs">
                  <div className="viw" style={{background:`linear-gradient(135deg,${selected.colorAccent},${selected.colorLight})`}}>▶</div>
                  <div style={{fontSize:19,fontWeight:800,color:"#222",marginBottom:7}}>{selected.videoLabel}</div>
                  <div style={{fontSize:13,color:"#888",marginBottom:22}}>לחצו כדי לצפות בסרטון על YouTube</div>
                  <a href={`https://www.youtube.com/results?search_query=${encodeURIComponent(selected.videoSearch)}`}
                    target="_blank" rel="noopener noreferrer" className="vbtn"
                    style={{background:`linear-gradient(135deg,${selected.colorAccent} 0%,${selected.colorAccent}CC 100%)`}}>
                    <span>▶</span><span>צפו בסרטון על {selected.name}</span>
                  </a>
                  <div className="vnote">הסרטון יפתח ב-YouTube בלשונית חדשה</div>
                  <div className="vtip" style={{background:selected.colorBg,border:`1.5px solid ${selected.colorLight}`}}>
                    <strong>לפני שצופים – זכרו:</strong><br/>{selected.intro.split("\n")[0]}
                  </div>
                </div>
              </div>
            )}

            {/* ── QUESTIONS ── */}
            {tab==="questions" && (
              <div className="tc">
                <div className="dq-intro">
                  שאלות עומק על {selected.name} – בחרו לפחות 2 שאלות וכתבו את תשובתכם. אין תשובה אחת נכונה!
                </div>
                {selected.questions.map((q,i)=>{
                  const k=`${selected.id}-q-${i}`, op=openQ===i;
                  return (
                    <div key={i} className="dq-item">
                      <div className="dq-hdr"
                        style={{background:op?selected.colorBg:"white"}}
                        onClick={()=>togQ(i)}>
                        <div className="dq-num" style={{background:`${selected.colorAccent}22`,fontSize:16}}>{q.icon}</div>
                        <div className="dq-txt">{q.text}</div>
                        <div className={`dq-chev ${op?"op":""}`}>▼</div>
                      </div>
                      <div className={`dq-ans ${op?"op":""}`}>
                        <textarea className="at2" placeholder="כתבו את תשובתכם כאן..."
                          value={answers[k]||""} onChange={e=>setA(k,e.target.value)}
                          style={{"--acc":selected.colorAccent}}/>
                      </div>
                    </div>
                  );
                })}
                {cnt(selected.id)>0 && (
                  <div className="abd" style={{background:selected.colorBg,border:`1px solid ${selected.colorLight}`,color:selected.colorAccent}}>
                    ✓ כתבתם {cnt(selected.id)} תשובה/תשובות – כל הכבוד!
                  </div>
                )}
              </div>
            )}

            {/* ── SOURCE ── */}
            {tab==="source" && (
              <div className="tc">
                <div className="src-title">מידע על מקורות</div>
                <div className="src-box">{selected.source}</div>
                <div className="src-note">
                  ⚠️ <strong>הערה פדגוגית:</strong> המידע בלומדה זו מבוסס על ידע AI (Claude, Anthropic) שאורגן ממקורות ציבוריים: ויקיפדיה עברית ואנגלית, המכלול, ארכיב מדינה, ראיונות ספרים ותקשורת. <strong>הציטוטים</strong> – חלקם מתועדים, חלקם פרפרזות מאומתות על דעותיה הידועות של האישה. מומלץ לאמת לפני שימוש מבחני. לסייע לתלמידים לחפש מקורות ראשוניים.
                </div>
              </div>
            )}

          </div>
        </div>
        )}

        <div className="ft">
          יצרה בעזרת AI: מורן קמיל גלברג
        </div>
      </div>
    </>
  );
}
