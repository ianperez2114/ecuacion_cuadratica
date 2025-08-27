package cuadratica;

	import java.util.Scanner;

		public class Ecuacion_Cuadratica {
		    public static void main(String[] args) {
		        Scanner sc = new Scanner(System.in);

		        //Entrada: coeficientes a, b, c
		        int a = 0;
		        int b = 0;
		        int c = 0;		
		        double raiz1=0;
		        double resultado1=0;
		        double resultado2=0;
		        double menor=0; 
		        double mayor=0;
		        
		        // Cálculo de la Raiz
		        raiz1= Math.sqrt((b*b) - 4 * a * c);
		        System.out.println("la raiz es igual a " + Math.sqrt((b*b) - 4 * a * c));

		        // Cálculo de los dos resultados 
		        resultado1=(- b + raiz1 )/ (2 * a);
		        resultado2=(- b - raiz1 )/ (2 * a);
		       
		        
		        // Ordenar sin usar if: usar Math.min y Math.max
		        menor = Math.min(resultado1, resultado2);
		        mayor = Math.max(resultado1, resultado2);
		        System.out.println( menor);
		        System.out.println( mayor);
		  
			}
			

	}


