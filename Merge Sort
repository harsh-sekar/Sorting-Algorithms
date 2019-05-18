This is the fastest Sorting technique implemented.
It keeps Dividing the entire Array into 2 parts, compares adjacent elements and sorts, Finally it merges into a Single Array.

Algo:
Step 1: Start
Step 2: Accept Elements
Step 3: Displaying Given elements
Step 4: CAlling megresort Function
       - Does splitting ( Into 2 till l<r)
       - m= l+ (r-1)/2
Step 5: Call Merge to merge all arrays into single array..
Step 6 : Display the Array
Step 7 : Stop

Code:

#include<iostream.h>
#include<conio.h>
# 

void merge(int array[],int m,int n,int r)
{
 {
 int i,j,k,L[n1],R[n2];
 int n1=n-l+1;
 int n2=r-m; 
@@ -46,26 +60,29 @@ void mergeSort(int arr[],int l,int r)
 if(l<r) 
    { 
      int m=l+(r-l)/2; 
        mergeSort(arr, l, m); 
        mergeSort(arr, m+1, r); 
        merge(arr, l, m, r); 
        mergeSort(arr,l,m); 
        mergeSort(arr,m+1,r); 
        merge(arr,l,m,r); 
    } 
} 
void printArray(int A[], int size) 
{ 
    int i; 
    for(i=0;i<size;i++) 
        printf("%d ",A[i]); 
    printf("\n"); 
       cout<<A[i]; 
    cout<<"\n"; 
} 
 int main() 
{ 
    int arr[] = {12,11,13,5,6,7}; 
    int arr_size = sizeof(arr)/sizeof(arr[0]); 
    printf("Given array is \n"); 
    printArray(arr, arr_size); 
    mergeSort(arr, 0, arr_size - 1); 
    printf("\nSorted array is \n"); 
    int arr[20]
    int arr_size=10;
    cout<<"Enter Array";
    for(int i=0;i<10;i++)
    cin>>arr[i];
    cout<<"Given array is : "; 
    printArray(arr, arr_size); 
    mergeSort(arr,0,arr_size-1); 
    cout<<"Sorted array is : \n"; 
    printArray(arr,arr_size); 
    return 0; 
} 
