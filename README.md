# HackerEarth-Solution
solutions to the question solved on hackerearth
#include<bits/stdc++.h>
using namespace std;
int main(){
	string s;
	cin>>s;

	int k;
	cin>>k;
	
	int len = s.length();
	string q[len];
	
	for(int i=0;i<len;i++){
		q[i] = s.substr(i,len);
		cout<<q[i]<<"\n";
	}
	
	sort(q,q+len);
	for(int i=0;i<len;i++){
		cout<<q[i]<<"\n";
	}
	
	cout<<q[k-1];

return 0;
}
