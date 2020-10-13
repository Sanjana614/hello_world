#include<stdio.h>
#include<iostream>
#include<bits/stdc++.h>
using namespace std;
int main()
{
    int t;
    cin >> t;
    while(t--)
    {
        long long int n,k;
        cin >> n >> k;
        long long int a[n],i;
        for(i=0;i<n;i++)
        {
            cin >> a[i];
        }
        long long int s=0,c=0,f=0;
        for(i=0;i<n;i++)
        {
            s=s+a[i];
            if(s<k)
            {
               // f=1;
                break;
            }
            s=s-k;
            c++;
        }
        if(s>k)
        {
            c=c+(s/k);
            cout << c+1 << endl;
        }
        else
        cout << c+1 << endl;
    }
    return 0;
}
