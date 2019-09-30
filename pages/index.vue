<template>
  <div>
    <v-parallax
      height="400"
      :src="heroImage"
    >
      <v-layout column align-center justify-center class="text-center">
        <h1 class="display-3">מדביר חיפה</h1>
      </v-layout>
    </v-parallax>
    <v-container class="pl-6 pr-6">
      <v-layout
        row
        align-center
        justify-center
      >
        <v-flex
          xs12
          sm8
          md8
          xl6
        >
          <v-card class="mt-n12">
            <v-card-text>
              <p class="title">
                מדביר מוסמך בחיפה והסביבה
                הכי חשוב בעבודות הדברה זה איתור וטיפול בבעיה על מנת שלא תחזור
                התקשרו ליעוץ חינם או לתיאום
              </p>
              <p class="text-center">

                <v-btn href="tel:0547355113" color="deep-purple accent-4" dark large>054-7355113</v-btn>
              </p>
            </v-card-text>
          </v-card>

          <v-card class="mt-6" style="position: relative; z-index: 2">
            <v-card-title>
              הדברת מזיקים בחיפה והסביבה
            </v-card-title>
            <v-card-text>
              <p>
                אלון המדביר,הנו מדביר מוסמך מטעם המשרד לאיכות הסביבה. לאלון ניסיון רב של למעלה מ- 10 שנים במתן שירותי
                אחזקה שונים ועבודות הדברה מגוונות לפרטיים, משרדים, בתי אבות, וועדי בתים, מסעדות מפעלים ועוד.... אלון בעל
                תודעת שירות מעולה דבר אשר תורם לרצינות לאחריות ולאמינות בעבודתו כמדביר בחיפה והסביבה.
              </p>
              <p>
                היתרון הבולט של אלון המדביר הוא בניסיון הרב שנים של עבודות האחזקה דבר אשר מאפשר לו כמדביר מוסמך בחיפה
                לאתר את מקור המזיקים למשל דרך כניסתם של חרקים והגורמים המושכים אותם, אזורי הנוחות של קינון היונים ומציאת
                דרכי פעולה יצירתיות לפתרון והרחקת היונים. מקורות ג'וקים בבית והסיבות לכניסתם.
              </p>
              <p>
                יכולת ניתוח הסביבה הביתית ודרכי הכניסה של המזיקים הנה המפתח לפתרון בעיית מזיקים בבית. אלון מגיע לבית
                הלקוח מתחיל באיתור הבעיה ורק לאחר מכן בוחר את אמצעי הטיפול הנכון לפתרון דבר אשר מונע במרבית המקרים חזרה
                לבית הלקוח כחלק מאחריותו כמדביר מוסמך במידה הבעיה ממשיכה.
              </p>
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>

    <v-parallax
      height="400"
      :src="mosquitoImage"
      class="mt-n12"
    >
      <v-layout column align-center justify-center class="text-center">
        <h2 class="display-3">מתי צריך מדביר?</h2>
      </v-layout>
    </v-parallax>

    <v-container class="pl-6 pr-6">
      <v-layout
        row
        align-center
        justify-center
        style="position: relative; z-index: 2"
      >
        <v-flex
          xs12
          sm8
          md8
          xl6
        >
          <v-card class="mt-n10">
            <v-card-title>
              באילו חומרי הדברה משתמשים?
            </v-card-title>
            <v-card-text>
              <p>
                חומרי ההדברה בהם משתמש אלון כמדביר, כולם חומרים מאושרים על ידי המשרד לאיכות הסביבה חומרי ההדברה מותאימים
                למזיקים תוך הקפדה על בריאות בני האדם והסביבה "מדביר מוסמך" הינו רישיון לעסוק בהדברת מזיקים.
              </p>
            </v-card-text>

            <v-card-title>
              האם ישנו רישיון מדביר?
            </v-card-title>
            <v-card-text>
              <p>
                הרישיון ניתן על ידי המשרד לאיכות הסביבה לאחר שהבחינות נעשות על ידי משרד הבריאות.<br>
                קורס מדביר מוסמך עורך כ- 8 חודשים ובסיומו עוברים 3 מבחנים. חרקים, מכרסמים וטוקסיקולוגיה.<br>
                הנבחנים אשר עוברים את הבחינות בהצלחה מקבלים את האפשרות לעסוק בתחום ההדברה ומקבלים רישיון מדביר מוסמך.
              </p>
            </v-card-text>

            <v-card-title>
              מה תפקיד המדביר?
            </v-card-title>


            <v-card-text>
              <p>
                תפקיד המדביר הוא בעיקר למנוע או לצמצם את האפשרות של התפתחות או התרבות החרקים בסביבה
                להדביר חרקים מזיקים או לא רצויים אשר קיימים בסביבה
                למנוע פלישה לסביבה מחדש ובעיקר לצמצם במידת האפשר את האפשרות של המצאות מזיקים עכברים יונים וכו' בסביבת
                בני
                האדם.
              </p>
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>

    <v-parallax
      height="400"
      :src="haifaImage"
      class="mt-n12"
    >
      <v-layout column align-center justify-center class="text-center">
        <h2 class="display-3"> בחיפה צריך הדברה?</h2>
      </v-layout>
    </v-parallax>
    <v-container class="pl-6 pr-6">
      <v-layout
        row
        align-center
        justify-center
        style="position: relative; z-index: 2"
      >
        <v-flex
          xs12
          sm8
          md8
          xl6
        >
          <v-card class="mt-n10">
            <v-card-title>
              בחיפה כמות גדולה של מזיקים
            </v-card-title>
            <v-card-text>
              <p>
                היות וחלק מהשכונות בחיפה ובנשר נמצאות על הר הכרמל בסביבה ירוקה ולמרגלות ההרים שטחים חקלאיים פעילים ניתן
                לאמור שבחיפה קיימת פעילות מזיקים בה. ולכן הצורך במדביר בחיפה והסביבה הוא רב. עד לא מזמן פעלה המזבלה
                העירונית בסמוך לצומת הצ'ק פוסט אשר לא תרמה לצמצום הגעת המזיקים לעיר חיפה ולביקוש רב במדבירים בחיפה.
              </p>
            </v-card-text>

            <v-card-title>
              גם באיזורים מסחריים?
            </v-card-title>
            <v-card-text>
              <p>
                בכל שכונה בחיפה קיימים מרכזים מסחריים רבים ו/או רחובות שלמים אשר הופכים ממגורים למסחר ובהם פאבים ומסעדות
                רבות המהווים גורם משיכה של אוכלוסיית מזיקים בין אם מדובר בעכברים בחיפה, תיקנים וזבובים.
              </p>
              <p>
                על מנת לשמור על הגנה וזה אני אומר מניסיוני האישי מזמינים בעלי עסקים רבים מדבירים בחיפה על מנת למנוע
                במידת האפשר את הימצאותם של מזיקים בסביבת העסקים. הזמנת שירותי הדברה בחיפה על ידי מדביר אשר מתמצא
                באפשרויות בתי הגידול של המזיקים, הגורמים אשר מושכים אותם, ואפשרויות ההדברה הנה מומלצת ביותר. אלון המדביר
                מבצע הדברות לא רק בבתי מגורים אלא נותן שירותי הדברה לעסקים שירותי הדברה למסעדות בחיפה, שירותי הדברה
                לסופרים, ועוד... חומרי הריסוס בהם משתמש אלון הנם חומרי ריסוס מאושרים בלבד.
              </p>
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>


    <v-container class="pl-6 pr-6">
      <v-layout
        row
        align-center
        justify-center
        style="position: relative; z-index: 2"
      >
        <v-flex
          xs12
          sm8
          md8
          xl6
        >
          <v-card flat>
            <animal-tabs></animal-tabs>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>


    <v-container class="pl-6 pr-6">
      <v-layout
        row
        align-center
        justify-center
      >
        <v-flex
          xs12
          sm8
          md8
          xl6
        >
          <v-card class="mt-2">
            <v-card-text class="text-center">
              <p class="title" >
                הגעתם עד לכאן ואתם זקוקים להדברה?<br> אנחנו זמינים עבורכם
              </p>
              <p class="text-center">

                <v-btn href="tel:0547355113" color="deep-purple accent-4" dark large>054-7355113</v-btn>
              </p>
            </v-card-text>
          </v-card>
        </v-flex>
      </v-layout>
    </v-container>


  </div>
</template>

<script>
import AnimalTabs from '../components/animal-tabs';

export default {
    components: {AnimalTabs},
    data() {
        return {
            heroImage: require('~/assets/images/homepage-hero.jpg'),
            mosquitoImage: require('~/assets/images/mosquito-hero.jpg'),
            haifaImage: require('~/assets/images/haifa-hero.jpg')
        }
    }
}
</script>
