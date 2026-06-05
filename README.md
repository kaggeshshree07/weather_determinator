# weather_deteimport java.util.Scanner;
public class MocktestQ2 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
         double temp;
        System.out.print("Enter temperature in Celsius: ");
        temp= sc.nextDouble();
        if (temp < 20) {
            System.out.println("Cold");
        } else if (temp >= 20 && temp<= 30) {
            System.out.println("Warm");
        } else {
            System.out.println("Hot");
        }
       
    }
}rminator
