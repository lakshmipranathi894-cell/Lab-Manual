import java.util.Scanner;

public class CharCount {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter text: ");
        String str = sc.nextLine().toLowerCase();

        int v = 0, c = 0, d = 0, s = 0;

        for (char ch : str.toCharArray()) {
            if ("aeiou".indexOf(ch) >= 0) v++;
            else if (ch >= 'a' && ch <= 'z') c++;
            else if (ch >= '0' && ch <= '9') d++;
            else if (ch != ' ') s++;
        }

        System.out.println("Vowels: " + v + "\nConsonants: " + c + "\nDigits: " + d + "\nSpecial: " + s);
    }
}
