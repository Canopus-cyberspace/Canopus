 # include <stdio.h>
 # include <stdbool.h>
int main() {<br>
    int code;<br>
    while(true){<br>
		printf("Show me your code,please.");<br>
        scanf("%d",code);<br>
        if(code >= 100000 || code <= 999999){printf("I am super hacker!");<br>
        return code;<br>
		}else printf("Fake code!");<br>
    }<br>
    return 0;<br>
}<br>

helloc.c<br>
 # include <stdio.h><br>

int main() {<br>
    printf("Hello, glimmer!");<br>
    return 0;<br>
}<br>

最大公约数
 # include <stdio.h>

int main(){
	int m,n,c;
	scanf("%d%d",&m,&n);
	do{
		if(m<n){
		c=m;
		m=n;
		n=c;
		}
		c=m%n;
		m=n;
		n=c;
	}while(c!=0);
	printf("%d",m);
	return 0;
}
