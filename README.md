# VALUE-EQUAL-TO-INDEX-VALUE


include <stdio.h>

int linearsearch(int arr[], int n) 
{
    int i;
    // Write C code here
    for(i=0; i<n; i++)
    {
        if(arr[i]==i)
            return i;
    }

    return -1;
}
