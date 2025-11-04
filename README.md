import java.util.Scanner;
public class array {

	public static void main(String[]args) {
		Scanner sc=new Scanner(System.in);
	    System.out.print("Enter No data");
	    int array_size=sc.nextInt();
	    int[]numbers=new int [array_size];
	     System.out.print("enter the number");
	    for(int i=0;i<numbers.length;i++) {
	    	numbers[i]=sc.nextInt();
	    	for (int temp :numbers) {
	    		if(temp%2==0) {
	    System.out.print(temp+"");
	    		}
	    	}
	  
	    }
	    
	
	}
ques 2
import java.util.Scanner;

public class Multiples {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int[] arr = new int[10];
        int[] multiples = new int[10];
        int j = 0;

        System.out.println("Enter 10 numbers:");
        for (int i = 0; i < 10; i++) {
            arr[i] = sc.nextInt();
        }

        for (int i = 0; i < 10; i++) {
            if (arr[i] % 9 == 0 && arr[i] % 3 == 0) {
                multiples[j] = arr[i];
                j++;
            }
        }

        System.out.print("The numbers that are multiples of both 9 and 3: ");
        for (int i = 0; i < j; i++) {
            System.out.print(multiples[i]);
            if (i < j - 1)
                System.out.print(",");
        }
        sc.close();
    }
}



