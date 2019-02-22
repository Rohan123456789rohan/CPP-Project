#include<iostream>
#include<conio.h>
#include<string.h>
using namespace std;
class SHOP
{
	
};
main()
{
	char password[20];
cout<<"\n\n\n\n\n***********************************SHOP MANAGEMENT SYSTEM***********************************"<<endl;
getch();
{
A:
cout<<"ENTER YOUR PASSWORD:"<<endl;
cin>>password;
if(strcmp(password,"rohan")==0)

	cout<<"\n\t\tCongratulations!You are successfully logged in."<<endl;
	else
	{
	cout<<"Password does not match,please try again."<<endl;
     goto A;
    }
}
getch();
cout<<"\n\n\t***Following are the categories of items available***"<<endl;
cout<<" \t1.Grocery"<<endl;
cout<<" \t2.Books"<<endl;
cout<<" \t3.Beauty"<<endl;
cout<<"\t4.Smartphones"<<endl;
cout<<"\t5.Fashion"<<endl;

}
