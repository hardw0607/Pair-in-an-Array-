# Pair-in-an-Array-
Pair in an Array?

public class pairarrays {
    public static void main(String[] args) {
        int[] numbers = { 65, 75, 33, 99,23};
        for(int i = 0; i < numbers.length; i++){
            for(int j = i + 1; j < numbers.length; j++){
                System.out.println("("+ numbers[i] + "," + numbers[j] +")");

            }
        }
    }
    
}
// this is output check the pair of arrrays 
(65,75)
(65,33)
(65,99)
(65,23)
(75,33)
(75,99)
(75,23)
(33,99)
(33,23)
(99,23)\\
