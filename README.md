<div align="center">

## Introduction
    
### **Undergraduate in Math & CS**

*Building efficient backend systems, competitive programming algorithms, and learning game dev.*

---

[![Facebook Badge](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/trietcpp)
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/trietcpp?utm_source=share_via&utm_content=profile&utm_medium=member_ios)
[![Gmail Badge](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:huynhminhtriet.math@gmail.com)

</div>

<br />

## 🔭  About Me

- 🎓 **Education:** Mathematics & Computer Science Student at **HCMUS** (VNUHCM - University of Science).
- 💻 **Engine & Systems:** Core Engineer & OJ Developer at **MathAlgo** (developing automated online judge platforms).
- 🏆 **Competitive Programming:** Active CP solver focusing on C++, fast I/O optimization, rolling hashing, and algorithmic structures.
- 🎮 **Side Interests:** Exploring 2D game architecture with **Raylib (C++)**, practicing martial arts, and solving logic puzzles.

---

## 🛠  Tech Stack & Tools

### **Languages & Core**
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### **Development & Frameworks**
![Raylib](https://img.shields.io/badge/Raylib-000000?style=for-the-badge&logo=cplusplus&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---

## 🖥️  Sample CP Source

```cpp
#include <bits/stdc++.h>
using namespace std;
/*
⣿⣿⣿⣿⣿⠃⢿⣷⠆⠀⠀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣯⡀⠀⠳⠤⠒⢦⡀⢠⣠⡿⠀⢸⣿⣿⡟⢳⡄⠈⠉⠹⣷⣄⠀⠀⠀⠀⠀
⣿⣿⣿⣿⡏⠀⠈⢻⣦⣀⡀⠀⠀⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣷⣄⡀⠀⠀⣾⠳⠞⠀⣤⣴⣿⣿⡟⠀⢀⣹⡄⠀⠀⠘⣿⣦⡀⠀⠀⠀
⣿⣿⣿⣿⡁⠀⠀⠀⠉⢉⣙⡻⢶⣶⠆⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣾⣿⣷⣄⣼⣿⣿⣿⠏⢠⣏⠻⣯⡙⠦⣀⠀⠈⢿⣿⣦⣄⠀
⣿⣿⣿⣿⣿⣦⡀⠀⠀⣿⡿⢷⢰⣿⡇⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠋⠀⠸⣌⠳⣌⠙⠲⣬⠙⢦⠘⣿⣿⣿⣷
⣿⣿⣿⣿⣿⣿⣿⣦⡠⠿⣿⣷⣼⣿⠁⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡟⠁⢰⡦⣄⡘⢆⠀⠁⢀⠘⢧⠘⣇⠘⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⡀⠈⠛⠿⣄⣀⣤⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⢧⡀⠀⠀⠙⢦⡈⠙⢧⡀⠀⠇⠈⠁⠙⢧⣭⠻⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣶⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠋⠀⠈⢳⠀⠀⠀⠀⠙⢦⠀⠁⠀⠀⠀⠀⠀⠀⢻⡀⠈
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠟⠁⠀⠀⠀⠀⠀⢧⠀⠀⠀⠀⠘⣇⠀⠀⠀⠀⠀⠀⣀⣬⣷⣾
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠟⣏⠀⠀⠀⠀⠀⠀⠀⠀⠈⢧⠀⠀⠀⠀⠘⡆⠀⠀⢀⣤⣾⣿⣿⣿⣿
⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⢻⡉⠀⠀⠈⢣⡀⠀⠀⠀⠀⠀⠀⠀⠘⡆⠀⠀⠀⠀⠘⣦⣶⣿⣿⣿⣿⣿⣿⣿
⠉⠛⡿⠻⡿⠿⠿⠿⠿⠿⣿⠛⣿⠛⠉⠉⠁⠀⠀⠀⠀⢿⡦⣀⠀⠀⠑⢄⠀⠀⠀⣀⣀⠀⠀⢹⡄⠀⠀⠀⢾⣿⣿⣿⣿⣿⣿⣿⣿⣿
⠀⠀⡇⠀⡇⠀⠀⠀⠀⠀⡏⠀⣸⢣⠀⠀⠀⠀⠀⠀⠀⠀⢳⣬⣷⣦⣤⡴⠷⢞⠋⠉⠀⠀⠀⠀⢧⠀⠀⠀⢸⣿⣿⣿⣿⣿⣿⣿⣿⣿
⠀⠀⢰⠀⣷⠀⠀⠀⢀⣀⣇⣤⡿⠶⠳⡄⠀⠀⠀⠀⠀⠀⠈⠙⢄⠀⠈⠑⠢⢄⡙⠦⣄⠀⠀⠀⠸⡆⠀⠀⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣀⣀⣘⡆⢹⣇⠀⠀⠀⠀⣯⢠⡇⠀⠀⠘⢦⡀⠀⠀⠀⠀⠀⢦⣈⠳⣄⠀⠀⠀⠀⠉⠛⠛⠲⣄⣀⣷⢸⠃⠀⣿⣿⣿⣿⣿⣿⣿⣿⣿
⣿⣿⣿⣿⡈⢿⣆⠀⠀⠀⢹⣼⠀⠀⠀⠀⠀⠙⠳⣄⡀⠀⠀⠀⠙⢿⣲⣷⣤⣶⡶⠾⠿⠿⢿⡛⠋⠹⣾⡀⠀⢿⣿⣿⣿⣿⣿⣿⣿⡿
⣿⣿⣿⣿⡇⠈⢯⠂⠀⢀⡬⣧⠴⡶⠶⠶⣤⠄⠀⠀⠙⠒⠦⠤⠤⣤⣍⣻⣥⡇⡆⠀⡴⣤⠀⢷⡀⠀⡏⡇⠀⠘⣿⣿⣿⣿⡿⠟⠋⠀
⣿⣿⣿⣿⣷⠀⠈⢳⡀⠀⢠⢸⡀⢷⠀⣠⢬⠳⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢷⡁⣀⠷⠞⠀⣼⠇⠀⢀⡇⠀⠀⣼⣿⠋⠁⠀⠀⠀⠀
⣿⣿⣿⣿⣿⡄⠀⠀⡟⢆⠈⠳⣷⡘⣧⡨⠟⠃⢺⠆⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠛⠓⠒⠒⠛⠉⠀⢀⡞⢀⣠⣾⣿⣿⠀⠀⠀⠀⠀⠀
⣿⣿⣿⣿⣿⡇⠀⢸⠀⠀⠙⢦⣙⢇⠈⠛⠲⠒⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⣻⣞⠋⠀⢹⣿⡿⠀⠀⠀⠀⠀⣰
⠿⠿⠿⠛⠙⡇⢠⡏⠀⠀⠀⠀⢿⣟⠳⣄⠀⠀⠀⠀⠀⠀⢀⡀⠀⠀⢠⡤⠦⠦⠶⢆⠀⠀⠀⣠⡞⢹⡇⠀⠀⠸⣿⡇⠀⠀⠀⠀⢠⠃
⠀⠀⠀⠀⢸⣡⠋⠘⡄⠀⠀⠀⢸⡌⣳⣄⠀⠀⠀⠀⠀⠀⢘⠉⠉⠁⠀⠀⠀⠀⠀⠘⣇⣤⠞⠁⢠⠎⡇⠀⠀⠀⣿⡇⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠚⠉⡆⠀⢹⡀⠀⠀⠀⣷⣿⣿⣗⢦⣤⣄⣀⣀⣸⣆⣤⣤⣤⣤⣤⠤⠶⠛⠛⠒⠦⡀⡎⠀⢸⠀⠀⠀⣿⣧⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢧⠀⠀⢳⠀⠀⠀⢻⣿⣿⣿⣆⠀⠀⠸⣿⣿⣿⣿⣿⣿⠀⠹⣆⠀⠀⠀⣀⠀⢹⠇⣀⢸⡄⠀⠀⣿⣿⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⢸⠀⢠⠾⡄⠀⠀⢸⣿⣿⣿⣿⣧⠀⠀⠹⣿⣿⣿⣿⣿⠀⠀⠘⠳⠀⠘⠿⠿⢿⠿⠟⠸⡇⠀⠀⢿⣿⣧⠀⠀⠀⠀⠀
⡀⡀⠀⠀⠀⠀⠈⣦⠋⠀⣧⠀⠀⢸⣿⣿⣿⣿⣿⣆⠀⠀⢻⣿⣿⣿⣿⣧⠀⠀⠀⠀⠀⠀⠀⣾⡄⠀⠀⡇⠀⠀⢸⣿⣿⣷⣄⣀⣠⣴
*/
#define ll long long
#define endl "\n"
#define FOR(i, a, b) for(int i = (a), _b = (b); i <= _b; i++)
#define REP(i, a, b) for(int i = (a), _b = (b); i >= _b; i--)
#define fi first
#define se second
#define all(a) (a).begin(), (a).end()
#define pb push_back
#define pf push_front
#define MOD 1000000007
#define inf (int) 2e9
#define INF (ll) 2e18
typedef pair<int, int> pii;
typedef pair<int, pii> piii;
typedef pair<pii, pii> piv;
typedef pair<ll, ll> pll;
typedef map<int, int> mii;
typedef vector<int> vi;
typedef vector<pii> vii;
typedef vector<mii> viii;

void __print(int x) {cerr << x;}
void __print(long x) {cerr << x;}
void __print(long long x) {cerr << x;}
void __print(unsigned x) {cerr << x;}
void __print(unsigned long x) {cerr << x;}
void __print(unsigned long long x) {cerr << x;}
void __print(float x) {cerr << x;}
void __print(double x) {cerr << x;}
void __print(long double x) {cerr << x;}
void __print(char x) {cerr << '\'' << x << '\'';}
void __print(const char *x) {cerr << '\"' << x << '\"';}
void __print(const string &x) {cerr << '\"' << x << '\"';}
void __print(bool x) {cerr << (x ? "true" : "false");}
template<typename T, typename V>
void __print(const pair<T, V> &x) {cerr << '{'; __print(x.first); cerr << ','; __print(x.second); cerr << '}';}
template<typename T>
void __print(const T &x) {int f = 0; cerr << '{'; for (auto &i: x) cerr << (f++ ? "," : ""), __print(i); cerr << "}";}
void _print() {cerr << "]\n";}
template <typename T, typename... V>
void _print(T t, V... v) {__print(t); if (sizeof...(v)) cerr << ", "; _print(v...);}
#ifndef ONLINE_JUDGE
#define debug(x...) cerr << "[" << #x << "] = ["; _print(x)
#else
#define debug(x...)
#endif
const int nmax = 5e6 + 5;

signed main(void) {
    cin.tie(nullptr); cout.tie(nullptr); ios_base::sync_with_stdio(false);
    #define taskname "FURINA DE FONTAINE"
    if(fopen(taskname".inp", "r") != NULL){
        freopen(taskname".inp", "r", stdin);
        freopen(taskname".out", "w", stdout);
    }
    return 0;
}
