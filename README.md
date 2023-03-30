# projekt-
projekt.java
import java.util.*;
import javax.swing.*;
public class DetyreShtepie 
{
	public static void main (String []args) {
	{
		for (int i=2; i<=10; i++)
		{
			boolean isPrimeNumber=true;
		for(int j=2;j<i;j++)
		{
			if(i%j==0)
			
		 { 
				isPrimeNumber=false;
		break;
		 }
		}
		if(isPrimeNumber)
		{
			/**int diveds;
			Scanner diveds1= new Scanner(System.in);
			System.out.print(i +" divides");
			int num=diveds1.nextInt();
			System.out.print(num +"? ");
			float d= num%i;
			System.out.println( d==0 );
			//menyra tjeter e perdorur me scanner//
			 **/
			 
			String input=
			JOptionPane.showInputDialog("Shkruani numrin qe deshironi te plotepjestoni:");
		    int number = new Integer(input).intValue();
		    System.out.print(i + " diveds " + number+"? ");
		    System.out.println( number%i==0 );
		    
		}
		}

	}
}
}
