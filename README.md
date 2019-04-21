# Calculadora-Area-de-un-Circulo
Tarea programación C++
/*Una empresa paga a sus empleados además del sueldo base una bonificación especial de 80 bs. por cada hijo. Realice
un algoritmo que determine el monto de la bonificación y el monto total a pagar al trabajador. */
#include <stdio.h>
#include <conio.h>
#define hijo 80
int main ()
{
  float sueldo;
  int Chijos;
  float resultado;
  printf("Inserte el suedo base:\n");
  scanf("%f\n",&sueldo);
  printf("Inserte la cantidad de hijos:\n");
  scanf("%d\n",&Chijos);
  resultado=sueldo+(hijo*Chijos);
  printf("El sueldo por pagar es de:%f\n",resultado);
  getch ();
  return 0;
}
