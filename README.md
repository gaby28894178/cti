#include <stdio.h>
#include <stdlib.h>
#define can 2

struct futbol {
    short nf;
    char  nyp[25];
    char pais[20];
    char puesto;
    short stok;

};


int main()
{
    struct futbol figurita[can];// vector de structura
    short op;//menu opcion
    short opB;
    short i,j;// contador 
    char buscarAuxi[25];//auxiliar de buscar 
    

do{

    printf(" MENU OPCION \t\n\t[0] - SALIR \n");
    printf(" \n\t[1]-Agregar \n");
    printf(" \n\t[2]-IMPRIMIR POR PANTALLA \n");
    printf(" \n\t[3]-AGREGAR STOCK \n");
    printf(" \n\t[4]-Buscar POR PAIS \n");
    printf(" \n\t[5]-BUSCAR -cargar un puesto (G, D, M o A\n");
    printf(" \n\t[6]-figuritas faltantes.\n");

      scanf("%hd",&op);


      switch (op)
      {
    case 0:
        printf("\nSALIENDO\n");break;
        /*cargo  el jugador */
    case 1:
        printf("INGRESE FIGURITAS AL ALBUN\n");
        for (i=0;i<can;i++)
        {
            printf("INGRESE NUMERO DE FIGURITA DE %hd\n",i);
            fflush(stdin);
            scanf("%hd",&figurita[i].nf);
            printf("INGRESE NOMBRE EN LA FIGURITA DE %hd\n",i);
            fflush(stdin);
            scanf("%25[^\n]s",figurita[i].nyp);
            printf("INGRESE PAIS DE EL JUGADOR %hd\n",i);
            fflush(stdin);
            scanf("%20[^\n]s",figurita[i].pais);
            printf("_____________________________________\n\tCARGA COMPLETA DEL JUGADOPR\t\n_____________________________________\n");
        }

      }break;
    case 3:/*agrego stock */
        
        printf("COMO DECEA BUSCAR [1]-NOMBRE [2]-Pais [3]-POCICION [4]-STOCK \n");
        scanf("%hd",opB);
         
        switch(opB)
        {
    case 1:
        ///ORDENO DESPUES BUSCO 
        for (i=0;i<can;i++)
            {
                for j=i;)
            }
        
                
        
        ///Buscador________________________________
        printf("INGRESE NOMBRE A BUSCAR \n");
        scanf("%25[^\n]s",buscarAuxi);
        
        
        
        
        
        
        }



}while(op!=0);




    return 0;
}
