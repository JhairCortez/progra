#include<iostream>
#include<cstdlib>
#include<conio.h>
#include<locale>
#include<cmath>
using namespace std;
float leernumero(string mensaje)

{ 
    float a;
    cout<<mensaje;
    cin>>a;
    return a;
}

void menu()
{ 
    system("cls");
    cout<<"\t * * * * *  MENU PRINCIPAL  * * * * *\n";
    cout<<"\t1) sumar"<<endl;
    cout<<"\t2) restar"<<endl;
    cout<<"\t3) multiplicar"<<endl;
    cout<<"\t4) dividir"<<endl;
    cout<<"\t5) seno"<<endl;          
    cout<<"\t6) coseno"<<endl;        
    cout<<"\t7) tangente"<<endl;       
    cout<<"\t8) raiz cuadrada"<<endl;  
    cout<<"\t9) raiz cúbica"<<endl;   
    cout<<"\t10) potencia"<<endl;      
    cout<<"\t11) logaritmo base 10"<<endl;  
    cout<<"\t12) logaritmo neperiano"<<endl; 
    cout<<"\n\t0) salir";
    cout<<"\n\tIngrese opción: ";

}


void sumar()
{ 
    float a, b, c;
    cout<<" * * * * *  SUMAR  * * * * *\n\n";
    a = leernumero("Ingrese el primer valor a sumar: ");
    b = leernumero("Ingrese el segundo valor a sumar: ");
    c = a + b;

    cout<<"\nEl resultado de la suma de "<<a<<" + "<<b<<" = "<<c;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}


void restar()

{ 
    float a, b, c;
    cout<<" * * * * *  RESTAR  * * * * *\n\n";
    a = leernumero("Ingrese el primer valor a restar: ");
    b = leernumero("Ingrese el segundo valor a restar: ");
    c = a - b;

    cout<<"\nEl resultado de la resta de "<<a<<" - "<<b<<" = "<<c;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}


void multiplicar()

{ 
    float a, b, c;
    cout<<" * * * * *  MULTIPLICAR  * * * * *\n\n";
    a = leernumero("Ingrese el primer valor a multiplicar: ");
    b = leernumero("Ingrese el segundo valor a multiplicar: ");
    c = a * b;

    cout<<"\nEl resultado de la multiplicación de "<<a<<" * "<<b<<" = "<<c;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void dividir()

{ 
    float a, b, c;
    cout<<" * * * * *  DIVIDIR  * * * * *\n\n";
    a = leernumero("Ingrese el primer valor a dividir: ");
    b = leernumero("Ingrese el segundo valor a dividir: ");

    if (b != 0)
    { 
        c = a / b;
        cout<<"\nEl resultado de la división de "<<a<<" / "<<b<<" = "<<c;
        cout<<"\n\n\nPresione una tecla para continuar....";
        getch();
    }
    else
        cout<<"\nNo se puede realizar la división porque el divisor es cero";
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}


void seno()
{
    float a, result;
    cout<<" * * * * *  SENO  * * * * *\n\n";
    a = leernumero("Ingrese el valor en radianes para calcular el seno: ");
    result = sin(a);
    cout<<"\nEl resultado de seno("<<a<<") = "<<result;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void coseno()
{
    float a, result;
    cout<<" * * * * *  COSENO  * * * * *\n\n";
    a = leernumero("Ingrese el valor en radianes para calcular el coseno: ");
    result = cos(a);
    cout<<"\nEl resultado de coseno("<<a<<") = "<<result;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void tangente()
{
    float a, result;
    cout<<" * * * * *  TANGENTE  * * * * *\n\n";
    a = leernumero("Ingrese el valor en radianes para calcular la tangente: ");
    result = tan(a);
    cout<<"\nEl resultado de tangente("<<a<<") = "<<result;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void raiz_cuadrada()
{
    float a, result;
    cout<<" * * * * *  RAIZ CUADRADA  * * * * *\n\n";
    a = leernumero("Ingrese el valor para calcular la raíz cuadrada: ");
    if(a >= 0)
    {
        result = sqrt(a);
        cout<<"\nEl resultado de la raíz cuadrada de "<<a<<" = "<<result;
    }
    else
        cout<<"\nNo se puede calcular la raíz cuadrada de un número negativo.";
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void raiz_cubica()
{
    float a, result;
    cout<<" * * * * *  RAIZ CUBICA  * * * * *\n\n";
    a = leernumero("Ingrese el valor para calcular la raíz cúbica: ");
    result = cbrt(a);
    cout<<"\nEl resultado de la raíz cúbica de "<<a<<" = "<<result;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void potencia()
{
    float a, b, result;
    cout<<" * * * * *  POTENCIA  * * * * *\n\n";
    a = leernumero("Ingrese la base: ");
    b = leernumero("Ingrese el exponente: ");
    result = pow(a, b);
    cout<<"\nEl resultado de "<<a<<" elevado a la "<<b<<" = "<<result;
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void logaritmo_base_10()
{
    float a, result;
    cout<<" * * * * *  LOGARITMO BASE 10  * * * * *\n\n";
    a = leernumero("Ingrese el valor para calcular el logaritmo base 10: ");
    if(a > 0)
    {
        result = log10(a);
        cout<<"\nEl logaritmo base 10 de "<<a<<" = "<<result;
    }
    else
        cout<<"\nEl logaritmo no está definido para números menores o iguales a cero.";
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

void logaritmo_neperiano()
{
    float a, result;
    cout<<" * * * * *  LOGARITMO NEPERIANO  * * * * *\n\n";
    a = leernumero("Ingrese el valor para calcular el logaritmo neperiano (base e): ");
    if(a > 0)
    {
        result = log(a);
        cout<<"\nEl logaritmo neperiano de "<<a<<" = "<<result;
    }
    else
        cout<<"\nEl logaritmo neperiano no está definido para números menores o iguales a cero.";
    cout<<"\n\n\nPresione una tecla para continuar....";
    getch();
}

int main()

{ 
    int opcion;
    setlocale(LC_ALL,"");
    do
    { 
        menu();
        cin>>opcion;
        system("cls");
        switch(opcion)
        {   
            case 1: sumar(); break;
            case 2: restar(); break;
            case 3: multiplicar(); break;
            case 4: dividir(); break;
            case 5: seno(); break;              
            case 6: coseno(); break;           
            case 7: tangente(); break;          
            case 8: raiz_cuadrada(); break;     
            case 9: raiz_cubica(); break;      
            case 10: potencia(); break;         
            case 11: logaritmo_base_10(); break;  
            case 12: logaritmo_neperiano(); break;
            case 0: cout<<"Hasta pronto....\n\n\n"; break;
            default: cout<<"ERROR EN INGRESO DE OPCION...\n\n Presione una tecla para continuar..."; getch();
        }
    } while (opcion != 0);
}
