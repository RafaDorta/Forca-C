# Forca-C

#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <ctype.h>

int main()
{

    int sair = 1;
    while (sair = 1) {
            system("cls");
    int a = 0,b= 0,c,d, nivel = 0,e = 0, pontos = 90, i = 0, j = 0, palavra, sair = 1;
    char L[3][16] = {'T','U','R','M','A',' ','D','A',' ','M','O','N','I','C','A','\0','H','A','R','R','Y',' ','P','O','T','T','E','R','\0','\0','\0','\0','C','R','E','P','U','S','C','U','L','O','\0','\0','\0','\0','\0','\0'};
    char T1[3][16]={' __',' __',' __',' __',' __',' ',' __',' __',' ',' __',' __',' __',' __',' __',' __','\0',' __',' __',' __',' __',' __',' ',' __',' __',' __',' __',' __',' __','\0','\0','\0','\0',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0','\0','\0','\0','\0','\0'};
    char L2[3][17]={'R','O','M','E','U',' ','E',' ','J','U','L','I','E','T','A','\0','\0','S','E','N','H','O','R',' ','D','O','S',' ','A','N','E','I','S','\0','P','E','Q','U','E','N','O',' ','P','R','I','N','C','I','P','E','\0'};
    char T12[3][17]={' __',' __',' __',' __',' __',' ',' __',' ',' __',' __',' __',' __',' __',' __',' __','\0','\0',' __',' __',' __',' __',' __',' __',' ',' __',' __',' __',' ',' __',' __',' __',' __',' __','\0',' __',' __',' __',' __',' __',' __',' __',' ',' __',' __',' __',' __',' __',' __',' __',' __','\0'};
    char L3[3][11]={'I','R', 'A','C','E','M','A','\0','\0','\0','\0','A','N','G','U','S','T','I','A','\0','\0','\0','D','R','A','C','U','L','A','\0','\0','\0','\0'};
    char T13[3][11]={' __',' __', ' __',' __',' __',' __',' __','\0','\0','\0','\0',' __',' __',' __',' __',' __',' __',' __',' __','\0','\0','\0',' __',' __',' __',' __',' __',' __',' __','\0','\0','\0','\0'};
    char P[3][11]={'E','N','G','E','N','H','E','I','R','O','\0','M','E','D','I','C','O','\0','\0','\0','\0','\0','C','I','E','N','T','I','S','T','A','\0','\0'};
    char T2[3][11]={' __',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0',' __',' __',' __',' __',' __',' __','\0','\0','\0','\0','\0',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0','\0'};
    char P2[3][11]= {'C','O','Z','I','N','H','E','I','R','O','\0','S','O','C','I','O','L','O','G','O','\0','\0','A','G','R','I','C','U','L','T','O','R','\0'};
    char T22[3][11]={' __',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0','\0',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0'};
    char P3[3][15]= {'H','O','T','E','L','E','I','R','O','\0','\0','\0','\0','\0','\0','M','U','S','E','O','L','O','G','I','S','T','A','\0','\0','\0','A','R','Q','U','I','V','O','L','O','G','I','S','T','A','\0'};
    char T23[3][15]= {' __',' __',' __',' __',' __',' __',' __',' __',' __','\0','\0','\0','\0','\0','\0',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0','\0','\0',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __',' __','\0'};
    char J[3][11]={'G','T','A',' ','V','\0','\0','\0','\0','\0','\0','D','O','T','A',' ','2','\0','\0','\0','\0','\0','C','S','G','O','\0','\0','\0','\0','\0','\0','\0'};
    char T3[3][11]={' __',' __',' __',' ',' __','\0','\0','\0','\0','\0','\0',' __',' __',' __',' __',' ',' __','\0','\0','\0','\0','\0',' __',' __',' __',' __','\0','\0','\0','\0','\0','\0','\0'};
    char J2[3][11]={'M','I','N','E','C','R','A','F','T','\0','\0','F','I','F','A','\0','\0','\0','\0','\0','\0','\0','P','O','K','E','M','O','N','\0','\0','\0','\0'};
    char T32[3][11]={' __',' __',' __',' __',' __',' __',' __',' __',' __','\0','\0',' __',' __',' __',' __','\0','\0','\0','\0','\0','\0','\0',' __',' __',' __',' __',' __',' __',' __','\0','\0','\0','\0'};
    char J3[3][11]={'T','E','T','R','I','S','\0','\0','\0','\0','\0','G','A','R','T','I','C','\0','\0','\0','\0','\0','W','I','I',' ','S','P','O','R','T','S','\0'};
    char T33[3][11]={' __',' __',' __',' __',' __',' __','\0','\0','\0','\0','\0',' __',' __',' __',' __',' __',' __','\0','\0','\0','\0','\0',' __',' __',' __',' ',' __',' __',' __',' __',' __',' __','\0'};
    char letras[17] = {'\0'};
    char letra,chute[17] = {'\0'};


    printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Regras do jogo:\n");
    printf("1- O jogador come\207a com 90 pontos;\n2- A cada letra que o jogador utiliza ele perde 5 pontos;\n3- Caso o jogardor acerte o chute ele ganhar\240 10 pontos, caso contr\240rio 10 pontos ser\306o retirados;\n4- O jogador ter\240 5 chances para acertar as 3 palavras, ele s\242 perder\240 chances caso erre uma letra ou um chute;\n\n");
    printf("As categorias do jogo s\306o: \n 1-t\241tulos de livros;\n 2-profiss\344es;\n 3-jogos eletr\242nicos;\n\n");
    while (a == 0 || a > 3 || nivel == 0 || nivel > 3){
    printf("Por qual categoria voc\210 gostaria de jogar ? (Digite apenas o n\243mero respectivo da categoria) \nResposta: ");
    scanf("%d", &b);
    fflush(stdin);

    switch(b){
    case 1: a = 1; printf("\n\nQual n\241vel voc\210 gostaria de jogar ?\n1-F\240cil;\n2-M\202dio;\n3-Dif\241cil;\nResposta: "); scanf("%d", &nivel);fflush(stdin);break;
    case 2: a = 2; printf("\n\nQual n\241vel voc\210 gostaria de jogar ?\n1-F\240cil;\n2-M\202dio;\n3-Dif\241cil;\nResposta: "); scanf("%d", &nivel);fflush(stdin);break;
    case 3: a = 3; printf("\n\nQual n\241vel voc\210 gostaria de jogar ?\n1-F\240cil;\n2-M\202dio;\n3-Dif\241cil;\nResposta: "); scanf("%d", &nivel);fflush(stdin);break;
    default: printf("Categoria inv\240lida\n\n");
    }}
    if (a == 1){
            if(nivel == 1){
            do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: t\241tulos de livros;\n");
    printf("N\241vel F\240cil;\n\n");
    printf("Sequ\210ncia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T1[d]);c++){
            printf(" %c", T1[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, L[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T1[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(L[d]);c++){

            if (letra == L[d][c]){
                    i++;
                T1[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T1[0], L[0]) == 0 && strcmp (T1[1], L[1]) == 0 && strcmp (T1[2], L[2]) == 0){
                break;}
            }

            while (e != 5 );
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T1[d]);c++){
            printf(" %c", T1[d][c]); }}

             printf("\n\n\n\n");




    }
    else {
        if (nivel == 2){
            do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: t\241tulos de livros;\n");
    printf("N\241vel M\202dio;\n\n");
    printf("Sequ\210ncia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T12[d]);c++){
            printf(" %c", T12[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, L2[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T12[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(L2[d]);c++){

            if (letra == L2[d][c]){
                    i++;
                T12[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T12[0], L2[0]) == 0 && strcmp (T12[1], L2[1]) == 0 && strcmp (T12[2], L2[2]) == 0){
                break;
            }
            }

            while (e != 5 );
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T12[d]);c++){
            printf(" %c", T12[d][c]); }}

             printf("\n\n\n\n");
        }
        else {
            if (nivel == 3){
                do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: t\241tulos de livros;\n");
    printf("N\241vel Dif\241cil;\n\n");
    printf("Sequ\210ncia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T13[d]);c++){
            printf(" %c", T13[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, L3[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T13[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(L3[d]);c++){

            if (letra == L3[d][c]){
                    i++;
                T13[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T13[0], L3[0]) == 0 && strcmp (T13[1], L3[1]) == 0 && strcmp (T13[2], L3[2]) == 0){
                break;
            }}

            while (e != 5);
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T13[d]);c++){
            printf(" %c", T13[d][c]); }}

             printf("\n\n\n\n");
            }
        }
    }
    }
    else{
        if (a == 2){
                if(nivel == 1){
                do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: profiss\344es;\n");
    printf("N\241vel F\240cil;\n\n");
    printf("Sequ\210ncia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T2[d]);c++){
            printf(" %c", T2[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, P[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T2[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(P[d]);c++){

            if (letra == P[d][c]){
                    i++;
                T2[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T2[0], P[0]) == 0 && strcmp (T2[1], P[1]) == 0 && strcmp (T2[2], P[2]) == 0){
                break;
            }}
            while (e != 5);
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T2[d]);c++){
            printf(" %c", T2[d][c]); }}

             printf("\n\n\n\n");



        }
        else{
            if(nivel == 2){
                do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: profiss\344es;\n");
    printf("N\241vel M\202dio;\n\n");
    printf("Sequ\210ncia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T22[d]);c++){
            printf(" %c", T22[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, P2[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T22[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(P2[d]);c++){

            if (letra == P2[d][c]){
                    i++;
                T22[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T22[0], P2[0]) == 0 && strcmp (T22[1], P2[1]) == 0 && strcmp (T22[2], P2[2]) == 0){
                break;
            }
            }
            while (e != 5);
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T22[d]);c++){
            printf(" %c", T22[d][c]); }}

             printf("\n\n\n\n");



        }
        else{
            if(nivel == 3){
                do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: profiss\344es;\n");
    printf("N\241vel Dif\241cil;\n\n");
    printf("Sequ\210ncia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T23[d]);c++){
            printf(" %c", T23[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, P3[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T23[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(P3[d]);c++){

            if (letra == P3[d][c]){
                    i++;
                T23[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T23[0], P3[0]) == 0 && strcmp (T23[1], P3[1]) == 0 && strcmp (T23[2], P3[2]) == 0){
                break;
            }
            }
            while (e != 5);
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T23[d]);c++){
            printf(" %c", T23[d][c]); }}

             printf("\n\n\n\n");



        }
        }
        }
        }
        else {
            if (a == 3){
                    if(nivel ==1){
                    do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: jogos eletr\242nicos;\n");
    printf("N\241vel F\240cil;\n\n");
    printf("Sequencia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T3[d]);c++){
            printf(" %c", T3[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, J[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T3[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(J[d]);c++){

            if (letra == J[d][c]){
                    i++;
                T3[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T3[0], J[0]) == 0 && strcmp (T3[1], J[1]) == 0 && strcmp (T3[2], J[2]) == 0){
                break;
            }
            }
            while (e != 5 );
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T3[d]);c++){
            printf(" %c", T3[d][c]); }}

             printf("\n\n\n\n");


                    }
                    else{
                        if (nivel == 2){
                            do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: jogos eletr\242nicos;\n");
    printf("N\241vel M\202dio;\n\n");
    printf("Sequ\210ncia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T32[d]);c++){
            printf(" %c", T32[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, J2[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T32[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(J2[d]);c++){

            if (letra == J2[d][c]){
                    i++;
                T32[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T32[0], J2[0]) == 0 && strcmp (T32[1], J2[1]) == 0 && strcmp (T32[2], J2[2]) == 0){
                break;
            }
            }
            while (e != 5);
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T32[d]);c++){
            printf(" %c", T32[d][c]); }}

             printf("\n\n\n\n");
                        }
                        else{
                            if(nivel == 3){
                                do {
                system("cls");

            system("cls");
                 printf("\t\t ADIVINHE AS PALAVRAS\n\n");

    printf("CRIADO POR:\n-RAFAEL ALVES DORTA;\n-J\351LIA DE MIRANDA GOMES;\n-JO\307O PEDRO CUNNINGHAN ZANHOLO;\n\n");
    printf("Categoria selecionada: jogos eletr\242nicos;\n");
    printf("N\241vel Dif\241cil;\n\n");
    printf("Sequencia de caracteres utilizados: ");
    for (b=0; b<strlen(letras); b++){
    printf("%c, ", letras[b]);}
    printf("\n======================================\n");
    printf("Pontua\207\306o ==> %d\n", pontos);
                    printf("======================================\n");
                    printf("Chances restantes  ==> %d\n", 5 - e);
                    printf("======================================\n");

        for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T33[d]);c++){
            printf(" %c", T33[d][c]); }}




            printf("\n\n\nDigite uma letra ou '?' para chutar uma palavra: ");
            scanf("%c", &letra);


            fflush(stdin);

            if (letra == '?'){
                printf("Digite qual palavra voc\210 gostaria de chutar(1,2,3) ?: ");
                scanf("%d", &palavra);
                fflush(stdin);
                printf("Digite a palavra que voc\210 gostaria de chutar ?: ");
                gets(chute);
                strupr(chute);
                if (strcmp (chute, J3[palavra - 1 ]) == 0){
                        pontos = pontos +10;
                        for (c = 0; c< strlen(chute); c++){
                        T33[palavra -1][c]= chute[c];}
                    printf("======================================\n");
                printf("Chute certeiro !\n");
                printf("======================================\n");



                }
                else {
                        e++;
                pontos = pontos - 10;
                    printf("======================================\n");
                printf("Errrouuu !\n");
                printf("======================================\n");


                }




            }
            else {
                pontos = pontos - 5;
            letra = toupper(letra);
             for (d = 0; d <3; d++){
          for(c=0;c<strlen(J3[d]);c++){

            if (letra == J3[d][c]){
                    i++;
                T33[d][c] = letra;}}}
                if (i != j){
                    printf("======================================\n");
                printf("Letra v\240lida !\n");
                printf("======================================\n");





            }
            else {
                    e++;
                    printf("======================================\n");
                printf("Letra inv\240lida !\n");
            printf("======================================\n");
                    ;

            }
            }

            letras[b] = letra;
            b++;

            j = i;
            printf("\n\n");
            printf("Aguarde...\n");
            sleep (2);
            if(strcmp (T33[0], J3[0]) == 0 && strcmp (T33[1], J3[1]) == 0 && strcmp (T33[2], J3[2]) == 0){
                break;
            }
            }
            while (e != 5);
            system("cls");
            printf("\n\n\n\n");
             printf("                 JOGO FINALIZADO\n");
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua pontua\207\306o foi : %d\n", pontos);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Chances restantes: %d\n", 5-e);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Sua sequ\210ncia de caracteres foi: %s\n", letras);
             printf("=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*\n");
             printf("Resultado final:\n\n");
             for (d = 0; d <3; d++){
                printf("\n");
          for(c=0;c<strlen(T33[d]);c++){
            printf(" %c", T33[d][c]); }}
             printf("\n\n\n\n");
                            }
                        }
                    }
            }
        }
    }
    printf("Para jogar novamente digite <1>, para sair aperte <2>: ");
    scanf("%d", &sair);
    fflush(stdin);
    if(sair == 2){
        return 0;
    }
    }
    return 0;
}
