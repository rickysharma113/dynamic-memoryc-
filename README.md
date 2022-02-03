#include<iostream>
using namespace std;
int main()
{
double* pvalue = NULL;
pvalue = new double;
*pvalue = 33675.99;
cout<<"value of pvalue:"<<*pvalue<<endl;
delete pvalue;
return 0;
}
