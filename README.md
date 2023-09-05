import java.util.*;

public class Main {
    public static void main(String[] args) {
        // Set Example
        Set<String> fruitSet = new HashSet<>();
        fruitSet.add("Grape");
        fruitSet.add("Kiwi");
        fruitSet.add("Orange");
        fruitSet.add("Mango");

        System.out.println("Set Example:");
        for (String fruit : fruitSet) {
            System.out.println(fruit);
        }
        System.out.println();

        // List Example
        List<Integer> numberList = new ArrayList<>();
        numberList.add(1);
        numberList.add(2);
        numberList.add(3);
        numberList.add(4);

        System.out.println("List Example:");
        for (int number : numberList) {
            System.out.println(number);
        }
        System.out.println();

        // Map Example
        Map<String, Integer> studentScores = new HashMap<>();
        studentScores.put("Alice", 8);
        studentScores.put("Bob", 9);
        studentScores.put("Charlie", 7);
        studentScores.put("David", 4);

        System.out.println("Map Example:");
        for (Map.Entry<String, Integer> entry : studentScores.entrySet()) {
            System.out.println(entry.getKey() + ": " + entry.getValue());
        }
    }
}
