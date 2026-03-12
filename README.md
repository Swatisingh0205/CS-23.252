# CS-23.252
[program1 wap to reverse the array](#assignment1)
##assignment1
```
import java.util.Scanner;
public class Revarray {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Arraytest t1=new Arraytest();
        t1.input();
       
        t1.outarrorg();
         t1.rev();
        t1.outarrrev();
    }
    
}
class Arraytest{
    int x[];
    int rev[];
    
void input(){
    x=new int [5];
    Scanner sc = new Scanner(System.in);
    for(int i=0;i<5;i++){
        System.out.println("Enter array elements");
         x[i]=sc.nextInt();
    }
}
void outarrorg(){
    for(int i=0;i<5;i++)
    {
        System.out.println("The array is"+x[i]);
    }
}
void rev(){
    rev=new int[5];
    for(int i=4;i>=0;i--){
        
        
    }
}
void outarrrev(){
    for(int i=4;i>=0;i--){
        System.out.println("the reverse array is"+x[i]);
        
      
    
    }
        
}

}
```
<img width="557" height="448" alt="image" src="https://github.com/user-attachments/assets/afcdb4f5-0d02-496c-a104-44c604e2ecfb" />







