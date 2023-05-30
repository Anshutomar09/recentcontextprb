# recentcontextprb
#include <iostream>
using namespace std;

int main() {
	// your code goes here
	int t,n;
	string b;
	cin>>t;
	while(t--){
	   int count=0;
	   cin>>n;
	   for(int i=0;i<n;i++){
	       cin>>b;
	   if(b=="START38"){
	       count++;
	   }
	   }
	   
	  
	   cout<<count<<" "<<(n-count)<<endl;
	}
	return 0;
}
