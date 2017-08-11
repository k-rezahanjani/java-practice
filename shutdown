import java.io.IOException;
import java.util.*;
import sun.management.snmp.jvminstr.JvmThreadInstanceEntryImpl;

public class Shutdown {
    
    public static void main(String[] args) {
        
        Scanner input = new Scanner(System.in);
        
        System.out.println("Enter your name : ");
        String name = input.nextLine();
        
        System.out.println("Hey " + name);
        
        System.out.println("Press Enter to Continue...");
        String pressEnter = input.nextLine();
        
        
        System.out.println("System SHUT DOWN");
        System.out.println("Press Enter to FUCK UP");
        input.nextLine();
        
        Runtime runtime = Runtime.getRuntime();
        
        try
        {
           
           Process p = runtime.exec("shutdown -s -t 1");
        }
        catch(Exception ex)
        {
            System.out.println("Shutdown Error !");
        }
     
    }
    
}
