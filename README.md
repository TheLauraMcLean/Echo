public class Echo {

    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        String message;
        String message1;

        System.out.println("Enter a line:");
        message = scan.nextLine();

        System.out.println("Enter another line:");
        message1 = scan.nextLine();

        System.out.println(message1 + ", " + message);

    }
}
