# snake
#include<graphics.h>
#include<conio.h>
 
main()
{
   int gd = DETECT, gm;
   int x1,x2,x3,x4;
   x1=10;
   x2=20;
   y1=10;
   y2=20;
   initgraph(&gd, &gm, "C:\\TC\\BGI");
    while(1)
        {
        rectangle(x1,y1,x2,y2);
        x1++;
        x2++;
        if(x1>100);
        x1=10;
        if(x2>100);
        x2=10;
        }                                                                                     
    getch();
   closegraph();
   return 0;
}
