package switchcase
import java.util.scanner;
public class Switchcase
{
  public static void main(String[] args)
  {
    int choice;
    System.out.println("Pick one 1. hi/t1, hey/t2, hello/t3")
    Scanner a = new scanner(System.in)
    choice=s.nextInt()
    switch(choice)
    {
     case 1: System.out.println("You said 'Hi'");
             break;
     case 2: System.out.println("You said 'Hey'");
             break;
     case 3: System.out.println("You said 'Hello'");
             break;       
     default: System.out.println("invalid choice")        
    }
  }
}
