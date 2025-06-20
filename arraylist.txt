import java.util.ArrayList;

public class ArrayListDemo {
    public static void main(String[] args) {
        ArrayList<String> languages = new ArrayList<>();
        languages.add("Java");
        languages.add("Python");
        languages.add("C++");
        System.out.println(languages.get(1));  
        languages.set(2, "C#");
        languages.remove("Java");
        System.out.println("Size: " + languages.size());
        System.out.println(languages);
    }
}