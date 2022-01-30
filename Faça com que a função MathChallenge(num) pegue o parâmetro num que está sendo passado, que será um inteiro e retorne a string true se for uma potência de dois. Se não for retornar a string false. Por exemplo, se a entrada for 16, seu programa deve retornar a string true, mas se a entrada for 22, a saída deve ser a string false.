//Faça com que a função MathChallenge(num) pegue o parâmetro num que está sendo passado, que será um inteiro e retorne a string true 
//se for uma potência de dois. Se não for retornar a string false. 
//Por exemplo, se a entrada for 16, seu programa deve retornar a string true, mas se a entrada for 22, a saída deve ser a string false.

package application;
import java.util.Locale;
import java.util.Scanner;
public class Program {

	
	public static void main(String[] args) {
		Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);
		
		int expoente = 2;
		
		System.out.println("Digite um numero para verificar se é potencia de 2");
	    int n = sc.nextInt();
	    boolean verificar = MathChallenge(n , expoente);
	    System.out.print(verificar); 
	    sc.close();
		
		
}
		public static boolean MathChallenge(int n  , int expoente ){
			int resultado = 0;
			int divisao = 0;
			resultado = (int) Math.pow (n, expoente) ;
			System.out.println(resultado);
			int[] vetor = new int [n];
			divisao = resultado / expoente;
			for ( int i = 0 ; i < n ; i ++) {
				divisao = divisao / expoente;
				vetor[i] = divisao;
				
				if (vetor[i] != n) {
					return false;
				}
				else if (vetor[i] == n) {
					return true;
				}
				
			}
			return true;
}
}
