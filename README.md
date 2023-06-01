# mateus
atividade de progrmação
package fbdch;
import java.util.Scanner;
public class sen {public static void main(String[] args) {
	Scanner scanner = new Scanner (System.in);
	System.out.println("======================================");
	System.out.println("escreva a sua primeira nota ");
	System.out.println("======================================");
	double pimeiranota = scanner.nextDouble();
	System.out.println("======================================");
	System.out.println("escreva a sua sengunda nota ");
	System.out.println("======================================");
	double sengundanota = scanner.nextDouble();
	
	double media = (pimeiranota+sengundanota)/2 ;
	
	if (media >= 7) {
		System.out.println("======================================");
		System.out.println("sua media:" + media + "aprovado");
		System.out.println("======================================");
		}else if (media <7 && media > 4 ) {
		System.out.println("======================================");
		System.out.println("sua media:" + media + "recuperação");
		System.out.println("======================================");
		}else { 
		System.out.println("======================================");
		System.out.println("sua media:" + media + "reprovado");
		System.out.println("======================================");
		}
	
	
	scanner.close();
	
}

}
