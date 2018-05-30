# Timus-1001
#include<stdio.h>
#include<math.h>
#include<iostream>
#include<vector>
using namespace std;

 int main()
 {
     vector<long long> V;
     long long a;
     while(scanf("%lld", &a) !=EOF)
     {
         V.push_back(a);

     }

     for(int i=V.size()-1;i>=0;i--){
        printf("%.4lf\n",sqrt(V[i]));
     }
     return 0;
 }
