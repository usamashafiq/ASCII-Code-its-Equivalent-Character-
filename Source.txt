#include<iostream>
#include<conio.h>
using namespace std;
void main()
{
	int a,b,c,d;
	   cout << "                       ASCII table                              " << endl;
	   cout << "----------------------------------------------------------------" << endl;
	   cout << "         ASCII Code              Equivalent Character           " << endl;
	   cout << "----------------------------------------------------------------" << endl;
	
	for(int i=32;i<=225;i++)
	 {
		char a = char(i);
		
		cout << "           "<< a  <<"                           "<<i<<"                " << endl;
}
	_getch();
}
