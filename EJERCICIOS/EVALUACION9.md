Vamos a crear un pila llamda alumnos y le agregaremos 5 nombres de alumnos, una vez creada y agregados los elementos vamos a imprimir el último elemento agregado, eliminaremos el último elemento ingresado e indicaremos cual se elimino, buscaremos un nombre e imprimiremos su posición en la lista, además crearemos un ciclo paa imprimir los nombres, .

SOLUCION

import java.util.Stack;
class Main {
  public static void main(String[] args) {
    Stack<String> alumnos = new Stack<String>();
    alumnos.push("Juan");
    alumnos.push("Manuel");
    alumnos.push("Pedro");
    alumnos.push("Lourdes");
    alumnos.push("Beatriz");
    System.out.println("El ultimo alumno agregado fue: " + alumnos.peek());
    String nombre = alumnos.pop();
    System.out.println("Alumno a quitar: " + nombre);
    System.out.println("Lista actualizada: " + alumnos);
    int posicion = alumnos.search("Pedro");
    System.out.println("El nombre esta en la posicion: " + posicion);
    while (!alumnos.isEmpty()) {
      System.out.println("El nombre del alumno es : " + alumnos.pop());
    }

  }
}
