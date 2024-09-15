#include<iostream>
using namespace std;
int main(){
    int n;
    cout<<"enter the number:";
    cin>>n;
    int a=1,b=1,sum=0;
    if(n==1) cout<<a;
    else cout<<a<<" "<<b<<" ";
    for(int i=3;i<=n;i++){
        sum=a+b;
        a=b;
        b=sum;
        cout<<b<<" ";
    }
        }
