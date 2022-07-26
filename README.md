# Faixa-etaria-e-quant-de-pessoas-codigo-Java
Considere o enunciado do problema abaixo:

Faça um programa que receba a idade de 15 pessoas, calcule e mostre quantidade de pessoas em cada faixa etária, conforme os critérios abaixo:

Faixa 1: até 15 anos
Faixa 2: de 16 a 30 anos
Faixa 3: de 31 a 45 anos
Faixa 4: de 46 a 60 anos
Faixa 5: acima de 60 anos
Complete o programa abaixo, arrastando e soltando os trechos de código nos espaços vazios, de forma que o programa implemente corretamente uma solução para o problema acima.



public class VerificaFaixaEtaria {
	public static void main(String[] args) {
		int faixa1 = 0, faixa2 = 0, faixa3 = 0, faixa4 = 0, faixa5 = 0;
		
		[for(int cont = 1; cont <= 15; cont++)] {
			[System.out.printf("Informe a idade da %da pessoa: ", cont);]
			[int idade = Integer.parseInt(System.console().readLine());]
			
			[if(idade <= 15)]
				[faixa1++;]
			else [if(idade <= 30)]
				[faixa2++;]
			else [if(idade <= 45)]
				[faixa3++;]
			else [if(idade <= 60)]
				[faixa4++;]
			else
				faixa5++;
		}
		
		System.out.printf("\nPESSOAS NA FAIXA 1 = %d\n", faixa1);
		System.out.printf("PESSOAS NA FAIXA 2 = %d\n", faixa2);
		System.out.printf("PESSOAS NA FAIXA 3 = %d\n", faixa3);
		System.out.printf("PESSOAS NA FAIXA 4 = %d\n", faixa4);
		System.out.printf("PESSOAS NA FAIXA 5 = %d\n", faixa5);
	}
}
