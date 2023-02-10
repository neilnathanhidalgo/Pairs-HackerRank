
package pairs;

import java.math.*;
import java.util.*;

public class Pairs {

    public static void main(String[] args) {
        List<Integer> arr = new ArrayList<>();
        
        arr.add(1);
        arr.add(2);
        arr.add(3);
        arr.add(4);
        
        int k = 1;
        
        Result.pairs(k, arr);
    }
    
}
class Result {

    public static int pairs(int k, List<Integer> arr) {
    // Write your code here
    int pair = 0;
    int size = arr.size();
    for (int i = 0; i < size - 1; i++) {
        for (int j = 1 + i; j < size; j++) {
            if(Math.abs(arr.get(i) - arr.get(j)) == k) {
                pair++;
            }
        }
    }
        System.out.println(pair);
        return pair;
    }

}
