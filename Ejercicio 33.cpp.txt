#include<stdio.h>
#include <iostream>
#include <locale.h>
#include <cstdlib>
 using namespace std;

int main() {
	
	
int a=0, z, x,y=0,m=0,prom;
	float calf;
	char var[10];
	char S[5]= "S";

	printf("Si desea analizar sus calificaciones ingrese 'S' , de no ser 'S' se cerrrara el programa ");
	scanf("%s",&var);

	if(strcmp(var,S) ==0){}
		do{	
   printf("n\Ingrese su calificacion : "); scanf("%f",&calf);
			if(calf>4){
				printf("\nUsted no a aprobado\n");
				y+=calf>4;//Sumatoria de calificaciones
				z+=1;//numero de aprobados
		}
			if(calf<4){
				printf("\nUsted aprobo\n");

			}
			m+=1;
			fflush(stdin);    printf("\nSi desea analizar sus calificaciones ingrese 'S' , de no ser 'S' se cerrrara el programa");
				scanf("%s",&var);

		}while(strcmp(var, S)==0 );

		 x = z*100/m;

		if(z<=a){
			printf("El porcentaje de las materoas aprobadas es de :)%d porciento\n" , x) ;
				printf("El promedio de las materoas aprobadas es de: 0\n") ;

		}else{
			printf("\nIntente de nuevo");
			
			}

		return 0;
	
}

 

