# Method in java 
This program is simply based on concept, logic and syntax of method  
class method{
    public int sum(int a,int b){
        int sum=a+b;
        return sum;
    
    }
    public int sum(int a,int b,int c){
        int sum=a+b+c;
        return sum;
    }

}
public class p2 {
    public static void main(String argus[]){
        method obj=new method();
        obj.sum(25,5);
        System.out.println("your result is "+obj.sum(15,5));
    }
}
