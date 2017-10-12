package agoritma5;
import java.util.Scanner;
public class algoritma5class8 {

	public static void main(String[] args) {
		//veri yarat
		double gelir;
		int status;
		
		Scanner input= new Scanner(System.in);
		
		
		//status'u sor
		System.out.println("lütfen status  gir");
		status = input.nextInt();
		
		
		//gelirini sor
		System.out.println("lütfen gelirinizi girin");
		gelir = input.nextDouble();
		
		//status a bağlı olarak vergi oranını göster
		if(status == 1)
			if(gelir <= 8350)
			{
				System.out.println("oranı %10");
				//hesap yap
			}
			else if(gelir <= 33950)
			{
				System.out.println("oranı %15");
			}
			else if(gelir <= 82250)
			{
				System.out.println("oranı %25");
			}
			else if(gelir <= 171550)
			{
				System.out.println("oranı %28");
			}
			else if(gelir <= 372950)
			{
				System.out.println("oranı %33");
			}
			else
				System.out.println("oranı %35");
		{
			
		}
		
		
		
	}

}
