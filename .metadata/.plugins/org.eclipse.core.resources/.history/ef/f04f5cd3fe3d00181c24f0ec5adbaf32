import java.util.Scanner;

public class SnilsValid {
	
	public static void main (String args[]){ 
		
		int number [] = new int[9];
		int checkSum = 0;
		Scanner in = new Scanner(System.in);
		Scanner sc = new Scanner(System.in);
		System.out.println ("Введите первые 9 цифр снилс");
		for (int i = 0; i < 9; i++)	{
		number[i] = in.nextInt();
		}
		System.out.println ("Введите последнее двузначное число снилс");
		checkSum = sc.nextInt();
		
	    int sum = 0;
	    sum = (number[0]*9 + number[1]*8 + number[2]*7 + number[3]*6 + number[4]*5 + number[5]*4 + number[6]*3 + number[7]*2 + number[8]*1);
	    
	    if(sum < 100 && sum == checkSum){
	    	System.out.println ("Снилс правильный");
	    }else if((sum == 100 || sum == 101) && checkSum == 0){
	    	System.out.println ("Снилс правильный");
	    }else if(sum > 101 && (sum%101 == checkSum || (sum%101 == 100 && checkSum == 0))){
	    	System.out.println ("Снилс правильный");
	    }else{
	    	System.out.println ("Снилс неправильный");
	    }
	}
}
