# App
public class App {
    public String str_1 = " I am a public  constructor";

    public App() {
    }

    void printfromClass() {
        System.out.println("Within Class" + this.str_1);
    }

    public static void main(String[] args) {
        App obj = new App();
        obj.printfromClass();
        System.out.println(obj.str_1);
    }
}
