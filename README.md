#include "stdio.h"

int main()

{

int n, ma, me, i;
i=1;

    while(i<=5)
        {
        printf ("número: ");
        scanf("%d", &n);
    if (i==1)
    {
        ma=n;
        me=n;
    }
    if (n>ma);
        {
            ma=n;
        }
    if (n<me)
        {
            me=n;
        }
        i++;
        }
            printf("maior número: %d\n", ma);
            printf ("menor número: %d", me);
    return 0;
}
