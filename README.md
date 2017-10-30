# Calculate-the-distance-between-two-points

Calculate the distance between two points 

Problem Description

输入两点坐标（X1,Y1）,（X2,Y2）,计算并输出两点间的距离。

 
Input

输入数据有多组，每组占一行，由4个实数组成，分别表示x1,y1,x2,y2,数据之间用空格隔开。 


Output

对于每组输入数据，输出一行，结果保留两位小数。

 
Sample Input

0 0 0 1

0 1 1 0

 
Sample Output

1.00

1.41 

解答：

#include<stdio.h>

#include<math.h>

main()

{

    double a,b,c,d,s;
    
    while(scanf("%lf %lf %lf %lf",&a,&b,&c,&d)!=EOF)
    
    {   
   
    s=sqrt((a-c)*(a-c)+(b-d)*(b-d));
    
    printf("%.2lf\n",s);
    
    }    
    
}

