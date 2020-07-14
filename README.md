# arrays-using-pointers
#include<iostream>
using namespace std;
int main()
{
  int *p;
  int arr[4];
  cout<< "enter the elements:" << endl;
    for (int i=0;i<5;i++){
	
  cin>>  arr[i];
}
 p =arr;
 for(int i=0;i<5;i++)
 {
 	cout<<*p<<endl;
 	
 	p++;
 }
return 0;
}																								
