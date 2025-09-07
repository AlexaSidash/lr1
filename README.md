# lr1
різні типи даних java
public class Main {
    public static void main(String[] args) {
        // 1) Оголошення змінних
        long l = 123456L;     // цілого типу 8 байт
        double d1, d2;        // дійсного типу 8 байт
        float f = 14.75f;     // дійсного типу 4 байти
        char c1 = '0';        // символьного типу

        // Виведення початкових значень
        System.out.println("Початкові значення:");
        System.out.println("l = " + l);
        System.out.println("f = " + f);
        System.out.println("c1 = " + c1);

        // 2) Виконання дій

        // Присвоєння float -> long (втрачається дробова частина)
        l = (long) f;
        System.out.println("\nПісля присвоєння l = f:");
        System.out.println("l = " + l + " (було f = " + f + ")");

        // Присвоєння конкретного значення змінній d1
        d1 = 250.5;
        System.out.println("\nd1 = " + d1);

        // Присвоєння конкретного значення змінній v2
        int v2 = 42;
        System.out.println("v2 = " + v2);



    }
}
