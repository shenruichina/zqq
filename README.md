# zqq#include<stdio.h>
#include<string.h>

int main()
{
	printf("请输入一个句子\n");
	char s[1000];
	gets(s);
	printf("亲输入一个单词\n");
	char w[10];
	gets(w);
	strlwr(s);
	strlwr(w);

	int wlen=strlen(w);
	int slen=strlen(d);
	int cnt=0;

	for(int i=0;i<slen-wlen;i++)
	{
		char tempw[wlen+1];
		tempw[wlen]='\0'
		for(int j=0;j<=wlen;j++) tempw[j]=s[i=j]
			if(strcmp(tempw,w)==0)  
			{
					cnt++;
			}
	}
	printf("%d",cnt);

	printf("wlen=%d,slen=%d",wlen,slen);
	return 0;
}
