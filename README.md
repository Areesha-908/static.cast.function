#include<iostream>
using namespace std;
int main()
{
int var1=36.9,var2=89.9,sum=0.0;
float sumf;
sum=var1+var2;
cout<<"var result in int="<<sum<<endl;
sumf=(static_cast<float>(sum)+0.8);
cout<<"var in float ="<<sumf;
return 0;
}
