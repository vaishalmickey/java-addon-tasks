# java-addon-tasks



	package task;

	import java.util.Scanner;

	public class task1 {
	    public static void main(String[] args) {
	        Scanner scanner = new Scanner(System.in);

	        System.out.print("Input: ");
	        String inputString = scanner.nextLine(); 
	      
	        String vowels = "aeiouAEIOU";  

	        int a = 0;
	        for (char b : inputString.toCharArray()) {  
	            if (vowels.indexOf(b) != -1) { 
	                a++;   
	            }
	        }

	        System.out.println("Output: " +a);
	        
	        
	    }
	}


	
