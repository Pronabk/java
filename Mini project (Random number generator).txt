import java.util.*;
public class miniproject {
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        //mini project(random number generator)
        int myNumber=(int)(Math.random()*100);
        do{
            System.out.println("Guess Any Number(1-100):");
            int userNumber=sc.nextInt();
            if(userNumber==myNumber){
                System.out.println("CORRECT NUMBER");
                break;
            } else if (userNumber > myNumber) {
                System.out.println("UR number too large");
            }
            else {
                System.out.println("UR number too small");
            }
        } while (myNumber>=0);
        System.out.println("my NUMBER was...");
        System.out.println("my NUMBER");

    }
}
