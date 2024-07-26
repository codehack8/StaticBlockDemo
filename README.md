# StaticBlockDemo
public class StaticBlockDemo {
    static {
        System.out.println("Static Block");
        }
        public void display() {
            System.out.printin("Display method");
            
            
        }
    public static void main(String[] args){
        StaticBlockDemo sd=new StaticBlockDemo();
        sd.display();
    }}
