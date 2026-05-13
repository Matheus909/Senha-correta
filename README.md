#include <stdio.h>
int main() {
	int num;
	printf("Digite sua senha: ");
	scanf("%d", &num);
	if(num >1234) {
		printf("Senha incorreta");
		
	} else printf("Acesso permitido");
		
	return 0;
}
