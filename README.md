# MAIN-JAVA
Main java parcial 1

public class Main {
    public static void main(String[] args) {
        // Ejemplo factorial
        System.out.println("Factorial iterativo de 5: " + Factorial.factorialIterativo(5));
        System.out.println("Factorial recursivo de 5: " + Factorial.factorialRecursivo(5));

        // Ejemplo fibonacci
        System.out.println("Fibonacci iterativo de 10: " + Fibonacci.fibonacciIterativo(10));
        System.out.println("Fibonacci recursivo de 10: " + Fibonacci.fibonacciRecursivo(10));

        // Ejemplo búsqueda lineal
        int[] arr = {1, 3, 5, 7, 9};
        System.out.println("Buscar 7 iterativo: " + BusquedaLineal.buscarIterativo(arr, 7));
        System.out.println("Buscar 7 recursivo: " + BusquedaLineal.buscarRecursivo(arr, 7, 0));

        // Ejemplo burbuja
        int[] datos = {5, 2, 9, 1, 3};
        Burbuja.burbujaIterativo(datos);
        System.out.println("Burbuja iterativo: " + java.util.Arrays.toString(datos));

        int[] datos2 = {5, 2, 9, 1, 3};
        Burbuja.burbujaRecursivo(datos2, datos2.length);
        System.out.println("Burbuja recursivo: " + java.util.Arrays.toString(datos2));
    }
}
