// Online C++ compiler to run C++ program online
#include <iostream>
 using namespace std;

void print_array (int arr[],int size)
{
for(int i=0;i<size;i++)
{
    cout<<arr[i];
}
cout<<endl;
}
int sort(int a[],int size){
    int temp;
    for (int i=0;i<size;i++)
    {
        for (int j=i+1;j<size;j++)
        {
            if (a[i]>a[i]);
            {
                temp=a[i];
                a[i]=a[j];
                a[j]=temp;
            }
        }
    }
    return 0;
}
int main()
{
    int array[]={3,4,6,5,2};
    int size=5;
    print_array(array,size);
    sort(array,size);
    print_array(array,size);
    
    return 0;
}
