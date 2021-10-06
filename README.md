import java.util.Scanner;
public class IMC
{
	public static void main(String[] args)
	{	
		double Peso, Altura, IMC, x, y;
		String nome;
		Scanner teclado = new Scanner(System.in);

		System.out.printf("Digite seu nome\n");
		nome = teclado.nextLine();

		System.out.println();

		System.out.printf("Coloque sua Altura exemplo[1.88]\n");
		Altura = teclado.nextDouble();

		System.out.printf("Coloque seu Peso\n");
		Peso = teclado.nextDouble();

		IMC = Peso / (Altura * Altura) ;
		
		System.out.printf("Este é seu IMC :"+IMC);
		
		if (IMC >=40){System.out.printf("-Obesidade nível 3");}
			else
				if(IMC>=35){System.out.printf("-Obesidade nível 2");}
					else
						if (IMC >=30){System.out.printf("-Obesidade nível 1");}
							else		
								if (IMC >=25){System.out.printf("-Acima do peso");}
									else			
										if (IMC>= 18){System.out.printf("-Peso ideal");}
											else {System.out.printf("-Magreza");}
}}							[IMC java.txt](https://github.com/diegoscs/Calculadora-de-IMC/files/7295469/IMC.java.txt)
