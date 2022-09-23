# Examen
examen de ED-HERNANDEZ SANCEHZ JORGE ARIEL
/****

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, PHP, Ruby, 
C#, OCaml, VB, Perl, Swift, Prolog, Javascript, Pascal, HTML, CSS, JS
Code, Compile, Run and Debug online from anywhere in world.

***/
#include <stdio.h>
#include <iostream>
using namespace std;
int main()
{
    /*Examen crear programa de la tabla de multiplicar
     inicio de la tabla  
     fin de la tabla
     Rango de inicio
     Rango de final
     El resultado debería insertarse en un arreglo
     */
    int ri1;
    int rf2;
    int num;
    int num2;
    int ttl=0;
    int cero=1;
    int rys[]= {};
    
    
    
    cout << "indica el rango de inicio: ";
    cin >>ri1;
    
    cout << "indica el rango final: ";
    cin >>rf2; 

    cout << "indica el inicio de la tabla: ";
    cin >>num; 
   
    cout << "indica el final de la tabla: ";
    cin >>num2; 
   
    for (int i=ri1; i<=rf2; i++){
        //los rangos de la tabla
        for (int a=num; a<= num2; a++){
            //muestra la multiplicacion
            
            int t= ((rf2-ri1+cero)*(num2-num+cero));
            rys[ttl]= a * i;
            cout << a << "x" << i << "=" << rys[ttl] << endl;
        }
        
    }
    
    
    
    
    
    
    
    
    
    return 0;
}
