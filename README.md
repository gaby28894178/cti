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
    struct futbol figurita[can];
    short op;

do{

    printf(" MENU OPCION [0]- SALIR \n");
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

      }

}while(op!=0);
    return 0;
}
