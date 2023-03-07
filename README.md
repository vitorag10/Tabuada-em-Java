# Tabuada-em-Java

import java.util.Scanner;

public class tabuada {
	public static void main(String[] args) {
		Scanner scan = new Scanner(System.in);
		
		System.out.println("Tabuada: ");
		int tabuada = scan.nextInt();
		
		System.out.println("Tabuada do " + tabuada);
		for(int x = 0; x <= 10; x++) {
			System.out.println(tabuada + " X " + x + " = " + (x*tabuada));
		}
	}
}

