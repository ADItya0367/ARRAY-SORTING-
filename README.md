# ARRAY-SORTING
Here in this repository i had discussed that how we can perform sorting in array in just O(n) time complexity and O(1) space complexity


#include<iostream>
#include<conio.h>
using namespace std;
class A
{
    public:
    void func()
    {
        int pos,i,ele,j,x;
        
        int arr[5]={5,4,3,2,1};
        int size=sizeof(arr)/sizeof(arr[0]);
        cout<<"the elements of the array are "<<endl;
        for(i=0;i<5;i++)
        cout<<arr[i]<<endl;
        for(i=0;i<size;i++)
        for(j=i+1;j<=size;j++)
        if(arr[i]>arr[j])
        {
            x=arr[i];
            arr[i]=arr[j];
            arr[j]=x;
        }
        cout<<"the sorted elements are as follows"<<endl;
        for(i=0;i<size;i++)
        cout<<arr[i]<<endl;
    }
};
int main()
{
    A obj;
    obj.func();
    return 0;
}
                           
                           
                 PLEASE GIVE ME A STAR IF THIS HELPED YOU.!!
