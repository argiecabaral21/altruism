/**
* Name: Argie G. Cabaral
* Section: Altruism
* Year: 4th Year
*/

import java.util.Scanner;

public class Main{
  
  public static void main(String[]args){
  Scanner sc = new Scanner(System.in);

  int i, grades=0, sum=0;
  double avg;
  char choosen;
  
  System.out.print("----Do You Want To Enter Your Grade----\n\n"); 

  do{
     
     System.out.print("Please choose Y for Yes\n");
     System.out.print("Please choose N for No\n");
     System.out.print("Enter Here: ");
     choosen = sc.next().charAt(0);
   
     if((choosen == 'y') || (choosen == 'Y')){
         
     for(i=0; i<5; i++){
       System.out.print("Enter Your Grade: ");   
       grades = sc.nextInt();
       sum +=grades;
       }
      
     }

  }while((choosen == 'y') || (choosen == 'Y'));
     avg = sum/5;
     System.out.printf("The Average is: %.2f" ,avg);  
  }
}
