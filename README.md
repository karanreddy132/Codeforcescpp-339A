# Codeforcescpp-339A
#include<bits/stdc++.h>
 
using namespace std;
 
int main(){
  string s;
  cin >> s;
  int l = s.length();
  sort(s.begin(),s.end());
  for(int i=l/2;i<l;i++){
    if(i==l-1){
      cout << s[i];
    }
    else{
      cout << s[i] << "+";
    }
  }
  return 0;
}
