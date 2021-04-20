# task_2.11

public class Main {

    public static void main(String[] args) {

        int numbers[] = {1, 2, 2, 3, 4, 5, 4, 6};
        int sum = 0;
        int counter = 0;

        for (int i = 0; i < numbers.length; i++) {
           sum += numbers[i];
           counter++;
           if (sum > 10) {
             System.out.println("Сумма равна: " + sum);
             System.out.println("Число элементов в сумме: " + counter);
             break;
            }
        }
    }
}
