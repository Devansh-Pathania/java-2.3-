import java.util.*;
import java.util.stream.*;

class Employee {
    int id;
    String name;
    double salary;

    Employee(int id, String name, double salary) {
        this.id = id;
        this.name = name;
        this.salary = salary;
    }

    public String toString() {
        return id + " - " + name + " - " + salary;
    }
}

class Student {
    int id;
    String name;
    double marks;

    Student(int id, String name, double marks) {
        this.id = id;
        this.name = name;
        this.marks = marks;
    }

    public String toString() {
        return id + " - " + name + " - " + marks;
    }
}

class Product {
    int id;
    String name;
    double price;
    String category;

    Product(int id, String name, double price, String category) {
        this.id = id;
        this.name = name;
        this.price = price;
        this.category = category;
    }

    public String toString() {
        return id + " - " + name + " - " + price + " - " + category;
    }
}

public class Main {
    public static void main(String[] args) {

        // ------------------- Part A: Sorting Employee Objects Using Lambda -------------------
        System.out.println("=== Part A: Sorting Employees Using Lambda ===");
        List<Employee> employees = Arrays.asList(
            new Employee(101, "John", 50000),
            new Employee(102, "Alice", 70000),
            new Employee(103, "Bob", 60000)
        );

        // Sort employees by salary using lambda expression
        employees.sort((e1, e2) -> Double.compare(e1.salary, e2.salary));
        System.out.println("Sorted by Salary:");
        employees.forEach(System.out::println);

        // Sort by name
        employees.sort((e1, e2) -> e1.name.compareTo(e2.name));
        System.out.println("\nSorted by Name:");
        employees.forEach(System.out::println);


        // ------------------- Part B: Filtering and Sorting Students Using Streams -------------------
        System.out.println("\n=== Part B: Filtering and Sorting Students Using Streams ===");
        List<Student> students = Arrays.asList(
            new Student(1, "Ankit", 85.5),
            new Student(2, "Riya", 92.0),
            new Student(3, "Karan", 76.3),
            new Student(4, "Sneha", 89.2)
        );

        System.out.println("Students with marks > 80, sorted by marks descending:");
        students.stream()
                .filter(s -> s.marks > 80)
                .sorted((s1, s2) -> Double.compare(s2.marks, s1.marks))
                .forEach(System.out::println);


        // ------------------- Part C: Stream Operations on Product Dataset -------------------
        System.out.println("\n=== Part C: Stream Operations on Product Dataset ===");
        List<Product> products = Arrays.asList(
            new Product(201, "Laptop", 85000, "Electronics"),
            new Product(202, "Phone", 55000, "Electronics"),
            new Product(203, "Shoes", 4000, "Fashion"),
            new Product(204, "Watch", 7000, "Fashion"),
            new Product(205, "TV", 45000, "Electronics")
        );

        // Filter products by category
        System.out.println("Electronics products:");
        products.stream()
                .filter(p -> p.category.equalsIgnoreCase("Electronics"))
                .forEach(System.out::println);

        // Find the most expensive product
        Product maxProduct = products.stream()
                .max(Comparator.comparingDouble(p -> p.price))
                .orElse(null);
        System.out.println("\nMost expensive product: " + maxProduct);

        // Calculate average price of all products
        double avgPrice = products.stream()
                .mapToDouble(p -> p.price)
                .average()
                .orElse(0.0);
        System.out.println("\nAverage price of all products: " + avgPrice);
    }
}
