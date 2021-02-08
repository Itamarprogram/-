#include <stdio.h>

void main(){
    int i = 0, seats = 0, Full = 0;
    int row[20];

    // מגדירים משתנים
    for (i = 0; i < 20; i++)
    {
        row[i] = 0;
    }
    // מאפסים את כל הכרטיסים לאפס

while(1)
{
    // לולאת while true 

seats = 0;
printf("How many seats would you like to order (1-20)?\n");
scanf("%d", &seats);


if (seats >= 0 && seats <= 20)
{
    // בודקים תנאי כדי שלא יהיו מספרים הקטנים מאפס או הגדולים מ20

seats = seats + Full;
    for (i = 0; i < seats ; i++)
    { 
        // לולאת for בהתאם למספר הכיסאות
        
          if (row[i] == 0)
          {
              Full++;
              row[i] = 1;
          }
          // תנאי בודק אם המושב פנוי או לא אם פנוי מסמן אותו כתפוס
          else if (row[i] == 1)
          {
              continue;
          }
          // אם המושב תפוס נמשיך למושב הבא לאיטרציה הבאה
        
    }

for (i = 0; i < 20; i++)
{
    printf("%d ", row[i]);
}
 printf("\n");
// מדפיס את מה שפנוי ומה שלא פנוי 1 מייצג כיסא תפוס 0 מייצג כיסא פנוי 

if (40 <= Full + seats)
{
    printf("There are no more empty seats");
    break;
    
}
// אם אין מקומות פנויים יותר המערכת מדפיסה הודעה ויוצאת מלולאת ה while

}
else
{
    printf("You choose invalid amount of seats\n");
}
// אם המספר קטן מאפס או גדול מ20 המערכת תדפיס הודעה שאי אפשר להזמין מספר כרטיסים שכזה ונותנת לו לבחור שוב

}

} 
