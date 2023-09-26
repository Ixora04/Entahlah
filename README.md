import java.util.Scanner;
public class Entahlah {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        System.out.println("Silahkan masukan bilangan = " ); int bilangan=input.nextInt();
        
        if(bilangan%5==0 && bilangan%2!=0){
        System.out.println("Program Started.");
        } else {
        System.out.println("Program Halted.");
        }
    }
    
}
