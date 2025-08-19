#include<stdio.h>


    int brasil;
    int canada;
    int pontos_turisticos1;
    int pontos_turisticos2;
    float pib1;
    float pib2;
    
    
    
     brasil = 950 ;
     canada= 800 ;
     pontos_turisticos1= 600;
     pontos_turisticos2 = 150;
     pib1 = 200;
     pib2 = 300;
    
    printf("entre sua carta!\n");
     scanf("%i, & brasil, canada\n");
      
     
    printf("entre com pontos turisticos\n");
     scanf("%i, &pontos_turisticos1,pontos_turisticos2\n");
      
      
     
    printf(" entre com pib1 ou pib2\n");
     scanf("%f, & pib1,pib2\n");
      
      
      
     
      if ( brasil > canada  ) 
      { printf(" BRASIL FOI SUA ESCOLHA");}
      
       else{ printf(" CANADÁ É SUA ESCOLHA");}
      
      
      
     
      if ( pontos_turisticos1 > pontos_turisticos2 ) 
      { printf("  BRASIL TEM MAIS PONTOS TURÍSTICOS ");}
      
       else{ printf(" CANADÁ TEM MAIS PONTOS TURÍSTICOS");}
      
      
      
      if ( pib1 > pib2 ) 
      { printf("  BRASIL TEM O MAIOR PIB ");}
      
       else{ printf(" CANADÁ TEM O MAIOR PIB");}
      
     
     
    
}




int main ()



