# C.-K-th-Not-Divisible-by-n
#include <bits/stdc++.h>
using namespace std;
#define ull unsigned long long

int main(){

    int t;
    cin>>t;
    while(t--){

        int n,k;
        cin>>n>>k;
        int count=0;
        int temp;
        int x=1;
        temp=n*(k/(n-1));
        x=k-(n-1)*(k/(n-1));
        if(x==0) cout<<temp-1<<endl;
        else{
        temp+=x;
        cout<<temp<<endl;
        }
    }


}


