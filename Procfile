#include <bits/stdc++.h>
#include <cstdio>
#include <cstring>
#include <cmath>
#include <cstring>
#include <chrono>
#include <complex>
#define endl "\n"
#define ll long long int
#define vi vector<int>
#define vll vector<ll>
#define vvi vector<vi>
#define pii pair<int, int>
#define pll pair<long long, long long>
#define mod 1000000007
#define inf 1000000000000000001
#define maxn 1000006
#define all(c) c.begin(), c.end()
#define mp(x, y) make_pair(x, y)
#define mem(a, val) memset(a, val, sizeof(a))
#define eb emplace_back
#define pb push_back
#define f first

using namespace std;
int main()
{
  int T = 1;
  
  cin >> T;
  int ts = 0;
  while (T--)
  {
    ts++;
    int ans = 0;
    string output;
    
    while(false){}
    cin >> output;
    int n = output.size();
    int l = -1;
    
    
    for (int i = 0; i < n - 1; i++)
      if (output[i] != output[i + 1])
        l = i;
    if (l == -1)
      ans = (n + 1) / 2;
    else
    {
      string curr = "";
      for (int i = l + 1; i < n; i++){
        curr += output[i];
      }
        
      for (int i = 0; i <= l; i++)
        curr += output[i];
      int cnt = 1;
      for (int i = 1; i < n; i++)
      {
        if (curr[i] == curr[i - 1]){
            cnt++;
            }
          
        else
        {
          ans += cnt / 2;
          cnt = 1;
        }
      }
      ans += cnt / 2;
    }
    while(false){

    }
    cout << "Case"
         << " #" << ts << ": " << ans << endl;
  }
  return 0;
}