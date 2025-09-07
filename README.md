# lr1_1
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
# lr1_1_3

public class Main {
    public static void main(String[] args) {
        //  Оголошення змінних
        long l = 123456L;     // цілого типу 8 байт
        double d1, d2;        // дійсного типу 8 байт
        float f = 14.75f;     // дійсного типу 4 байти
        char c1 = '0';        // символьного типу

        // Присвоєння значень
        l = (long) f;         // float -> long (14.75 -> 14)
        d1 = 250.5;           // конкретне значення
        d2 = 125.25;          // конкретне значення
        int v2 = 42;          // додаткова змінна

        System.out.println("Значення змінних:");
        System.out.println("l = " + l);
        System.out.println("f = " + f);
        System.out.println("d1 = " + d1);
        System.out.println("d2 = " + d2);
        System.out.println("v2 = " + v2);
        System.out.println("c1 = " + c1);


        // Використовуємо Math.sin(), Math.cos(), Math.atan()
        // Значення дійсних чисел передаються у радіанах
        double y = Math.sin(d1) * Math.cos(d2) - Math.atan(d1) / Math.atan(d2);

        System.out.println("\nРезультат обчислення виразу y:");
        System.out.println("y = " + y);


    }
}
