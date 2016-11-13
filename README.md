# class-tamirinta3
public class tamirinta3 {

    public static void main(String[] args) {
        int n = 12;
        for (int i = 1; i < n + 1; i++) {
            System.out.print(fib(i)+"\t");
        }

    }

    public static long fib(int n) {
        if (n <= 1) {
            return n;
        } else {
            return fib(n - 1) + fib(n - 2);
        }

    }

}
