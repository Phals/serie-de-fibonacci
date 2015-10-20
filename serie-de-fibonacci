#include <stdio.h>
#include <conio.h>
#include <stdlib.h>

void display(void);
void exibir_menu(void);
void verificar_menu(void);

void primeiro_x_termo(void);
void x_termo_x_termo(void);
void numero_do_termo(void);
void exibir_termo_de_x(void);
void verificar_se_existe(void);

void fim_operacao(void);

void o_que_e(void);
void ajuda(void);

void sair_sistema(void);

int main() {

    printf("\a");

    system("cls");

    display();
    exibir_menu();

    getch();
    return(0);

}

void display(void) {

    printf("\n===============================================================================\n");
    printf("\t\t\t\tSerie de FIBONACCI");
    printf("\n===============================================================================\n");

}

void exibir_menu(void) {

    printf("\n\n\n\t\t\t\t      Menu \n\n");

    printf("\n\t\t 01 - Exirbir a serie do primeiro ate o *X1 termo");
    printf("\n\t\t 02 - Exirbir a serie do termo *X1 ate o *X2 termo");
    printf("\n\t\t 03 - Exirbir o numero da serie do termo *X1");
    printf("\n\t\t 04 - Exirbir o termo do numero *X1 da serie");
    printf("\n\t\t 05 - Verificar se determinado numero existe na serie");

    printf("\n\n\t\t 06 - O que e a serie de FIBONACCI");

    printf("\n\n\t\t 07 - Ajuda");

    printf("\n\n\t\t 08 - Sair");

    printf("\n\n\t\t Escolha uma opcao: ");

    verificar_menu();

}


void verificar_menu(void) {

    int ops;

    scanf("%d", &ops);

    if((ops != 1) && (ops != 2) && (ops != 3) && (ops != 4) && (ops != 5) && (ops != 6) && (ops != 7) && (ops != 8)) {

        system("cls");

        display();

        printf("\n\n\t\t\t\t     ERRO!!!");

        printf("\n\n\t\t   Certifique se que sua escolha esta correta");

        exibir_menu();

    }else{

        system("cls");

        display();

        switch(ops){

            case 1:
                primeiro_x_termo();
                break;
            case 2:
                x_termo_x_termo();
                break;
            case 3:
                numero_do_termo();
                break;
            case 4:
                exibir_termo_de_x();
                break;
            case 5:
                verificar_se_existe();
                break;
            case 6:
                o_que_e();
                break;
            case 7:
                ajuda();
                break;
            case 8:
                sair_sistema();
                break;

        }

    }

}

void sair_sistema(void) {

    system("cls");

    display();

    printf("\n\n\n\t\t\t\t      Tchau !!!");

    getch();

    printf("\a\a\a");

    exit(0);


}

void primeiro_x_termo() {

    printf("\n\n\n\n\n\t\t\t\t  Em construcao !");

    unsigned long int TermoMax, NumProximo,NumAnterio=0,NumAtual=1;

    printf("\n\nDigite ate qual termo sera exibido a serie: ");
    scanf("%d",&TermoMax);

    printf("\n\n\nTermo 1  =  1");

    for(int aux=2; aux<=TermoMax; aux++) {

        NumProximo = NumAtual + NumAnterio;

        printf("\nTermo %d  =  %d",aux,NumProximo);

        NumAnterio = NumAtual;
        NumAtual = NumProximo;

    }

    getch();

    system("cls");

    display();

    exibir_menu();

}

void fim_operacao() {

    int ops;

    printf("\n\n\n\t\t\t\t      Menu \n\n");

    printf("\n\n\t\t\t\t01 - Repetir");
    printf("\n\t\t\t\t02 - Voltar ao menu");

    printf("\n\n\t\t\t\tEscolha uma opcao: ");

    scanf("%d", &ops);

    system("cls");
    display();

    switch(ops){

        case 1:
            primeiro_x_termo();
            break;

        case 2:
            exibir_menu();
            break;

        default:
            printf("\n\n\t\t\t\t     ERRO!!!");
            printf("\n\n\t\t   Certifique se que sua escolha esta correta");
            fim_operacao();

    }

}

void x_termo_x_termo(void){

    printf("\n\n\n\n\n\t\t\t\t  Em construcao !");

    getch();

    system("cls");

    display();
    exibir_menu();

}

void numero_do_termo(void){

    printf("\n\n\n\n\n\t\t\t\t  Em construcao !");

    getch();

    system("cls");

    display();
    exibir_menu();

}

void exibir_termo_de_x(void){

    printf("\n\n\n\n\n\t\t\t\t  Em construcao !");

    getch();

    system("cls");

    display();
    exibir_menu();

}

void verificar_se_existe(void){

    printf("\n\n\n\n\n\t\t\t\t  Em construcao !");

    getch();

    system("cls");

    display();
    exibir_menu();

}

void o_que_e(void){

    printf("\n\n\n\n\n\t\t\t\t  Em construcao !");

    getch();

    system("cls");

    display();
    exibir_menu();

}

void ajuda(void){

    printf("\n\n\n\n\n\t\t\t\t  Em construcao !");

    getch();

    system("cls");

    display();
    exibir_menu();

}
