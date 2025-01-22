
public class Main {
    public static void main(String[] args) {
        int[] array = {1, 2, 3, 4, 5};
        int sum = 0;

        for (int i = 0; i < array.length; i++) {
            sum += array[i];
        }

        System.out.println("Sum of array: " + sum);
    }
}


Output:

Sum of array: 15

Alternatively, you can use the `Arrays.stream()` method to calculate the sum of the array:


import java.util.Arrays;

public class Main {
    public static void main(String[] args) {
        int[] array = {1, 2, 3, 4, 5};
        int sum = Arrays.stream(array).sum();

        System.out.println("Sum of array: " + sum);
    }
}

Output:

Sum of array: 15# Sum-of-array-
