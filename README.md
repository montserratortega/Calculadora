








#include <stdio.h>
#include <stdlib.h>
#include <iostream>

int main()
{
	int suma, res, mul, div, num, num1, num2;
	printf("CALCULADORA\n");
	printf("Elige una de las siguientes opciones: \n");
	printf("1. Suma\n");
	printf("2. Resta\n");
	printf("3. Multiplicacion\n");
	printf("4. Divison\n");
	scanf("%d",&num);
	system("cls");
	
	switch(num)
	{
		case 1:
			{
				printf("SUMA\n");
				printf("Dame el primer numero: ");
				scanf("%d",&num1);
				printf("\nDame el segundo numero: ");
				scanf("%d",&num2);
				suma= num1 + num2;
				printf("La suma es %d",suma);
				system("cls");
			}
			break;
			
		case 2:
			{
				printf("\nRESTA");
				printf("\nDame el primer numero: ");
				scanf("%d",&num1);
				printf("\nDame el segundo numero: ");
				scanf("%d",&num2);
				res= num1 - num2;
				printf("La resta es %d",res);
				system("cls");
			}
			break;
		case 3:
			{
				printf("")
			}	
			
	}
	
}# Calculadora
Proyecto
