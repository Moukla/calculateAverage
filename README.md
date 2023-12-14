// calculateAverage
#include <iostream>
using namespace std;
double calculateAverage(double a,double b,double c);
int main(){
    int a,b,c;
    cout<<"Enter a: ";
    cin>>a;
    cout<<"Enter b: ";
    cin>>b;
    cout<<"Enter c: ";
    cin>>c;
    cout<<"The average of this number is: "<<calculateAverage(a,b,c);
    return 0;
}
double calculateAverage(double a,double b,double c){
    return (a+b+c)/3;
}
