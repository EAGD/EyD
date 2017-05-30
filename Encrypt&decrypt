# EyD

#include <stdio.h>

void encriptar(char Palabra[20]);
void desencriptar(char Palabra[20]);

int main(void){
	char Palabra[20];

	printf("Introduce la palabra que quieres encriptar\n");
	gets(Palabra);

    encriptar(Palabra);
    getchar();
    desencriptar(Palabra);
    getchar();
    return 0;
}

void encriptar(char Palabra[20]){
    int i=0;
    for(i=0;Palabra[i]!='\0';++i){
        i=i+1;
        Palabra[i]=Palabra[i]+3;
    }
    for(i=0;Palabra[i]!='\0';i++){
        Palabra[i]=Palabra[i]+1;
        i=i+1;
    }
    printf("La palabra encriptada es: %s\n",Palabra);
}

void desencriptar(char Palabra[20]){
    int i=0;
    for(i=0;Palabra[i]!='\0';++i){
        i=i+1;
        Palabra[i]=Palabra[i]-3;
    }
    for(i=0;Palabra[i]!='\0';i++){
        Palabra[i]=Palabra[i]-1;
        i=i+1;
    }
    printf("La palabra desencriptada es: %s",Palabra);
}
