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
