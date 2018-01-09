#include<stdio.h>
int main(){
	int ncase,i,nfeet;
	scanf("%d",&ncase);
	for(i=0;i<nfeet;++i){
		scanf("%d",&nfeet);
		if(nfeet%2!=0)
		printf("0 0\n");
		else if(nfeet%4!=0)
			printf("%d %d",nfeet/4+1,nfeet/2);
			else printf("%d %d",nfeet/4,nfeet/2);
	}
	
}
