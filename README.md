
include<stdio.h> 

int main()
{

  // esta função permite que o utilizador escolha opção 1 ou opção 2 no jogo de trunfo escolhendo as cartas Brasil ou Palestina.


    int brasil=1;
    int palestina=2;
    int escolha;
    printf("ENTRE COM O SUA ESCOLHA(1 OU 2)\n");
    scanf("%i", escolha);


    // essa função exibe o resultado da pergunta qual carta o jogador escolhe. 

     if ( escolha == 1 ) {
     
      printf("sua escolha é Brasil!\n");}
      else { printf(" sua escolha é Palestina:\n");}
      
    
    return 0;
}



