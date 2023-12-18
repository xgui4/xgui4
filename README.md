- 👋 Hi, I’m @xgui4
- 👀 I’m interested in programming and gaming in game like Fortnite and Minecraft
- 🌱 I’m currently learning Python, C#, JS, HTML5, CSS3.

import java.util.Scanner;

public class Console {
    public static String ReadLine(String txt)
    {
        Scanner scanner  = new Scanner(System.in);
        System.out.println(txt);
        String name = scanner.nextLine();
        return name;
    }
    public static void WriteLine(String txt)
    {
        System.out.println(txt);
    }
        public static void Write(String txt)
    {
        System.out.print(txt);
    }
}
