# Estrutura-de-Repeti-oimport java.util.Scanner;

    public class EstruturadeRepeti��oexer01 {

	public static void main(String[] args) {
		
    Scanner leitor = new Scanner (System.in);
		
	float num;
		
	System.out.println("Digite um numero e descubra se ele � positivo ou negativo");
	num=leitor.nextFloat();
		
	if (num<0)
	System.out.println("Ele � negativo.");
	if (num>0)
	System.out.println("Ele � positivo.");
		
	if (num==0)
	System.out.println("Ele � neutro, � o n�mero ZERO.");
		}
}
