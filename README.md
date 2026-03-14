public class NumberPattern {
    public static void main(String[] args) {
        int rows = 5;

        for (int i = 1; i <= rows; i++) {
            // 1. Loop for the ascending part
            for (int j = 1; j <= i; j++) {
                System.out.print(j);
            }

            // 2. Loop for the descending part
            for (int j = i - 1; j >= 1; j--) {
                System.out.print(j);
            }

            // 3. Move to the next line
            System.out.println();
        }
    }
}
