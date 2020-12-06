# inspiration
#include<iostream>
#include<cstring>
using namespace std;

int main()
{
    int score =0;
    int count =0;
    string s;
    cin>>s;
    for(int i=0; i<s.length(); i++){
    if(s[i]=='O'){
    score+=count + 1;
    count++;
    }
    else count=0;
    }
    cout<<score<<endl;
 
}
