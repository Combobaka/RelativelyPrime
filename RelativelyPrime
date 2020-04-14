import java.util.Scanner;

public class RelativelyPrime {
		
	public static int Low(int a, int b) {
			if(a<b) {
				return a;
			}else {
				return b;
			}		
	}
  
	public static void IsRelativelyPrime(int a, int b) {
		int divider = 2;		
		while(divider <= Low(a,b)) {
			if(a % divider == 0 && b % divider == 0) {
				System.out.println(a + " and " + b +" is not relatively prime.");
				System.out.println(a + " and " + b +" can both dividable by " + divider);
				break;
			}else if(divider == Low(a,b)) {
				System.out.println(a + " and " + b +" is relatively prime.");
				break;
			}else {
				divider++;
			}
		}
	}

	public static void main(String[] args) {
		
		Scanner scan = new Scanner(System.in);
		System.out.println("Number A:");
		int a = scan.nextInt();
		System.out.println("Number B:");
		int b = scan.nextInt();
		
		IsRelativelyPrime(a,b);
	}
}
