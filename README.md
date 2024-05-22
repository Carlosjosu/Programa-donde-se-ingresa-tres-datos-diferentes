// Crear un programa dode se puedan ingresar al menos tres tipos de datos.

#include <Stdio.h>

int main ()

{
   // Declarar las variables que vamos a usar.
    int n1; //variable de tipo entero.
    float  n2;// variable de tipo decimal que puede guardar despues de la coma hasta 7 dijitos.
    double n3; // variable de tipo decimal que puede almacenar despues de la coma hasta 15 dijitos.
    
    //Instrucciones que vamos a ejecutar en nuestro programa.
    //Al usar printf muestro en pantalla algunas frases o numeros que quiero que el usuario vea para que sepa que tiene que hacer.
    printf(" Bienvenido estimado Usuario\n");

    printf(" Ingrese un numero entero \n")

    //Al usar scanf almaceno lo que el usuario ingresa por teclado para despues usarlo en el programa y hacer los calculos necesarios.
    scanf("%i", &n1);

    printf(" Ingrese un numero decimal \n");

    scanf("%f", &n2);

    printf(" Ingrese un segundo numero decimal  \n");

    scanf("%lf", &n3);

    //Imprimo mis resultados para que el usuario visualice lo que ingreso por teclado.
    //Le muestro con printf en pantalla lo que ingreso y le detallo los resultados obtenidos.
    printf("El numero entero que usted ingreso es %i \n" , n1  );
    printf("El numero decimal que usted ingreso es %0.7f \n" , n2 );
    printf("El segundo numero decimal que usted ingreso es %0.15lf \n" , n3);
    
    return 0;
}
