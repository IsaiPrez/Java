Vamos a crear una cola con 10 nombres de paises, vamos a eliminar 2 elementos y a imprimir los nombres de los paises a eliminar

SOLUCION

Respuesta:

  import java.util.LinkedList;
  import java.util.Queue;
  class Main {
  public static void main(String[] args) {
    Queue paises = new LinkedList();
    paises.add("Mexico");
    paises.add("Canada");
    paises.add("EU");
    paises.add("Francia");
    paises.add("Italia");
    paises.add("Suecia");
    paises.add("Rusia");
    paises.add("Japon");
    paises.add("Holanda");
    paises.add("Brasil");
    System.out.println("El pais a eliminar es " + paises.remove());
    System.out.println("El pais a eliminar es " + paises.remove());
    System.out.println("El pais que sigue a eliminar es " + paises.element());
    }
  }
