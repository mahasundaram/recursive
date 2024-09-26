# using recursive function
import java.util.*;
public class Main
{
    public static void recursive(int n){
        if(n<1){
            return;
        }
        else{
             System.out.println(n);
            recursive(n-1);
           
        }
    
    }
	public static void main(String[] args) {
	    int num=5;
	    recursive(num);
		//System.out.println(num);
	}
}

