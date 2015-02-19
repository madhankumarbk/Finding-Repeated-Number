#include <iostream.h>
#include <conio.h>
#define MAX 101
int main() {
	// your code goes here
	int number[MAX];

	clrscr();
	//get the elements of the array
	for(int i=0;i<MAX;i++){
		cin>>*(number+i);
		}
		for(i=0;i<MAX;i++){
		cout<<*(number+i);
		}
		//SORTING THE ARRAY
		for(i=0;i<MAX;i++)
		for(int j=i+1;j<MAX-1;j++){
		if(*(number+i) > *(number+j))
		{
		  int temp=number[i];
		  number[i]=number[j];
		  number[j]=temp;
}
}

		//finding the element which is represented twice
		for(i=0;i<MAX;i=i+2){
			if(*(number+i)!=*(number+i+1)){
				cout<<"The non repeated element is"<<*(number+i);
				break;
				}
		}
	getch();
	return 0;
}
