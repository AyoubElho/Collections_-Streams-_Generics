import java.util.HashSet;
import java.util.Set;
import java.util.TreeSet;

public class StudentsSets {

    public static void main(String[] args) {

        // 1. Create and populate two HashSets
        Set<String> groupA = new HashSet<>();
        Set<String> groupB = new HashSet<>();

        // Adding students to group A
        groupA.add("Oussama");
        groupA.add("Amina");
        groupA.add("Youssef");
        groupA.add("Fatima");
        groupA.add("Ibrahim");

        // Adding students to group B
        groupB.add("Youssef");
        groupB.add("Fatima");
        groupB.add("Khadija");
        groupB.add("Mehdi");
        groupB.add("Sara");
        groupB.add("Oussama");

        // Display initial groups
        System.out.println("=== Student Groups ===");
        System.out.println("Group A: " + groupA);
        System.out.println("Group B: " + groupB);
        System.out.println();

        // 2. Intersection
        Set<String> intersection = new HashSet<>(groupA);
        intersection.retainAll(groupB);
        System.out.println("Students in BOTH groups:");
        System.out.println(intersection);
        System.out.println();

        // 3. Union
        Set<String> union = new HashSet<>(groupA);
        union.addAll(groupB);
        System.out.println("All students (Union):");
        System.out.println(union);
        System.out.println("Total students: " + union.size());
        System.out.println();

        // 4. Difference A - B
        Set<String> onlyInA = new HashSet<>(groupA);
        onlyInA.removeAll(groupB);
        System.out.println("Students only in Group A:");
        System.out.println(onlyInA);
        System.out.println();

        // 5. Difference B - A
        Set<String> onlyInB = new HashSet<>(groupB);
        onlyInB.removeAll(groupA);
        System.out.println("Students only in Group B:");
        System.out.println(onlyInB);
        System.out.println();

        // 6. Check if a student exists
        String student = "Amina";
        System.out.println("Is " + student + " in Group A? " + groupA.contains(student));
        System.out.println();

        // 7. Sorted display
        Set<String> sortedStudents = new TreeSet<>(union);
        System.out.println("All students (Sorted):");
        System.out.println(sortedStudents);
    }
}
