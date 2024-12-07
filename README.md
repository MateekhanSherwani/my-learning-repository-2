# my-learning-repository-2
#include<iostream>
using namespace std;
int main()
{
	int num,i;
	cout<<"Enter the number:";
	cin>>num;
	cout<<"factors of "<<num<<"are";
	for(i=1;i<=10;i++){
	if(num%i==0){
		cout<<i<<" ";
	}
}
return 0;
}
