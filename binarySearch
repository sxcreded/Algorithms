#include <bits/stdc++.h>

#define ll long long
#define DIM 100009
#define pll pair<ll,ll>

using namespace std;

int a[DIM], n, k;

int binary(int A[], int N, int K){
    int l = -1;
    int r = N;

    while(l+1!=r) // doing this until the left and right will meet
    {
        int i = (l+r)/2;           // middle
        if(K < A[i]) r = i;
        if(K == A[i]) return i;
        if(K > A[i]) l = i;
    }

    return n; // if nothing happens just n
}
int main(){
    cin >> n >> k;
    for(int i = 0; i < n; ++i)
    {
        cin >> a[i];
    }

    cout << binary(a, n, k);
    return 0;
}
