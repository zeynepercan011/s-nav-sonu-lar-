# s-nav-sonu-lar-
ödev

#include<stdio.h>
int main()
{
	int ales,yds,mezort,sonuc;
	
	printf("ales notunuzu giriniz: \n");
	scanf("%d", &ales);
	
	printf("yabanci dil sinavi notunuzu giriniz: \n");
	scanf("%d" , &yds);
	
	printf("mezuniyet ortalamanizi giriniz: \n");
	scanf("%d" , &mezort);
	
	sonuc= ales*1/2+yds*1/4+mezort*1/4;
	
	printf("sonuc %d olarak bulunur. \n" , sonuc);
	
	{if(yds<70)
	{
		printf("daha baslamadan elendiniz. \n");
	}
}
	
	
	if(sonuc<60)
	{
		printf("diskalifiyesiniz");
	}
	
	else 
	{
		printf("lisansustu alima kabul edildiniz tebrikler.");
	}
	
	return 0;	
}
