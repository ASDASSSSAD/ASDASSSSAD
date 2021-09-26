#include<iostream>
using namespace std;
int main()
{
float basic,gross, da,hra;
cout<<"enter basic salary of an emplayee:";
cin>>basic;
if(basic<25000)
{
da=basic*90/100;
hra=basic*20/100;
}
else if(basic>=40000)
{
da=basic*95/100;
hra=basic*30/100;
}
gross=basic+hra+da;
cout<<"\n\t Basic Pay ............."<<basic<<endl;
cout<<"\t Dearness Allowance ......."<<da<<endl;
cout<<"\n\t House Rent Allowance......"<<hra<<endl;
  cout<<"\n\t------------------------------"<<endl;
  cout<<"\n\t Gross Salary............."<<gross<<endl;
  cout<<"\t------------------------------"<<endl;
  return 0;
}
