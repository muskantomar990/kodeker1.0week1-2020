#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

char cody(char a[],int l,int r)
{
    char min = 'z';
    int till = r - 1;
    for( int j = l - 1;j<= till ;j++)
    {
        // find smallest alphabet
        if (a[j] < min)
            min = a[j];

    }
    return min;
    //printf("%c",a[min]);

}
int main() {
    int i,n,q,l,r;
    char a[100];
    scanf("%d%d",&n,&q);
    scanf("%s",a);
    char result[100];
    for(i=0;i<q;i++)
    {
        scanf("%d%d",&l,&r);
        result[i] = cody(a,l,r);
    }

    for(int k =0; k <q; k++)
        printf("%c \n",result[k]);

    /* Enter your code here. Read input from STDIN. Print output to STDOUT */

    return 0;
}