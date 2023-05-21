#include <assert.h>
#include <ctype.h>
#include <limits.h>
#include <math.h>
#include <stdbool.h>
#include <stddef.h>
#include <stdint.h>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
 int main()
 {
     int n ,i;
     scanf("%d",&n);
     float arr[n],p=0,q=0,r=0;
         for(i=0;i<n;i++)
    {
        scanf("%f",&arr[i]);
        if(arr[i]>0)
        p++;
        else if(arr[i]<0)
        q++;
        else 
        r++;
    }
    printf("%f\n%f\n%f\n",p/n,q/n,r/n);
    return 0;
     }
