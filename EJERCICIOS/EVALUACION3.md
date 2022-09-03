# Práctica 3.

## 3. OPERADORES

Objetivo: Verificar el dominio teórico y técnico del concepto de operador en el lenguaje
de java mediante preguntas de opción múltiple y ejercicios para desarrollar su código.
Indicaciones: Pedir responder cada una de las preguntas de manera acertada, breve y
clara, según sea el caso.

1. La expresión 5 != 6 , ¿qué valor arrojará? (Valor 1 punto)

          c. true

2. ¿Qué hace el siguiente código? (Valor 1 punto)
System.out.println(8 <= 8);

          b. Imprime true.

3. ¿Cómo podríamos obtener un resultado de 10, dada la siguiente variable? (Valor 1
punto)

double a = 2;

          b. a*5


4. ¿Cuál es la mejor manera de saber si las siguientes dos cadenas son iguales?
(Valor 1 punto)

String username1 = "teracoder";

String username2 = "gigacoder";

          a. username1 == username2

5. ¿Qué operador se puede usar para concatenar dos strings? (Valor 1 punto)

          c. +


6. ¿Hay algún error en la siguiente declaración en Java? (Valor 1 punto)

int status = 7 < 8;

          b. Sí, int debería ser boolean.

7. ¿Cuál es el resultado de la siguiente concatenación de cadenas? (Valor 1 punto)

"Son las " + 5 + "pm"

          c. "Son las 5pm" ---
          
8. Después de ejecutar el siguiente código, ¿cuál será el valor de la variable
endpoint? (Valor 1 punto)

int endpoint = 11 % 3;

   
          c. 2.66
   

9. Supón que intentamos construir algunas de las funciones de una cuenta bancaria.
Considera el siguiente código (Valor 2 puntos)

            public class CuentaBancaria {
              public static void main(String[] args){
                double saldo = 1000.75;
                double cantidadARetirar= 250;
              }
            }

a. Crea una nueva variable double llamada saldoActualizado y
almacene saldo con cantidadARetirar restada de él.

b. Ahora, imagina que has decidido dividir tu saldo en 3 partes iguales
para dárselo a tus tres mejores amigos. Crea una variable double
llamada cantidadParaCadaAmigo que contenga saldoActualizado
dividido por 3.

c. Si cada uno de tus amigos quiere comprar un boleto para un
concierto con el dinero que les diste. Y las entradas cuestan 250. Crea
una variable de tipo boolean llamado puedeComprarTicket y
configúralo de tal manera que arroje si cantidadParaCadaAmigo
tiene lo suficiente para comprar una entrada para el concierto.
Entonces, usa System.out.println() para imprimir
puedeComprarTicket.

d. Usa + y System.out.println() para imprimir:

          Le di a cada amigo <cantidadParaCadaAmigo>...
          con el valor de cantidadParaCadaAmigo en lugar de <cantidadParaCadaAmigo>.

Salida:

          true
          Le di a cada amigo 250.25...
          
![image](https://user-images.githubusercontent.com/101481084/185818138-d6065aa1-1c38-4478-bd83-5a13ea58b31c.png)
          
