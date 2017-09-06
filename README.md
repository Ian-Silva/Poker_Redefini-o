# Poker_Redefini-o

#include <stdio.h>
#define MAX 1000
int main(int argc, char const *argv[])
{
    int n;/*Quantidade de partidas*/
    int teste=0;/*Marcação de testes*/
    int i, o, k;/*Incrementos*/
    int jog1, jog2, jog3, jog4, jog5;/*Jodagor 1*/
    int play1, play2, play3, play4, play5;/*Jogador 2*/

    /*Quantidade de partidas*/
    printf("Quantidade de partidas: ");
    scanf("%d",&n);

    /*Laço de repetição de partidas*/
    for(i=0;i<n;i++)
    {
        /*Cartas do jogador 1*/


            scanf("%d %d %d %d %d",&jog1, &jog2, &jog3, &jog4, &jog5);

        /*Cartas do jogador 2*/


            scanf("%d %d %d %d %d",&play1, &play2, &play3, &play4, &play5);

        /*Incrementando valor em Teste*/
        teste++;
        printf("Teste %d\n",teste);

       /* if(play1==play1+1==play1+2==play1+3==play1+4)
        {

        }


        int tri=0;
        for(o=0;o<5;o++)
        {
            scanf("%d",&play1);
            if(play1 != tri)
            {
                tri = play1;
            }

        }

        printf("Sem pontuação\n");*/



    }


    return 0;
}
