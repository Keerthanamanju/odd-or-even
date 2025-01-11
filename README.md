public class OddOrEven {
    public static void main(Strimport java.util.Scanner;

ing[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter a number
        System.out.print("Enter a number: ");
        int number = scanner.nextInt();

        // Check if the number is odd or even
        if (number % 2 == 0) {
            System.out.println("The number " + number + " is even.");
        } else {
            System.out.println("The number " + number + " is odd.");
        }

        scanner.close();

    }
}

OUTPUT::


PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1>  'C:\Users\MY\AppData\Roaming\Code\User\workspaceStorage\09ba20b68fc885bcf32d210e84cb47ec\redhat.java\jdt_ws\java emc 1_2ecfe798\bin' 'OddOrEven' 
Enter a number: 19
The number 19 is odd.
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1> 


