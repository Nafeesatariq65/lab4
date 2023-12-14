# lab4
    int evenCount = 0;
    int oddCount = 0;

    System.out.println("Enter 10 values:");

    for (int i = 0; i < 10; i++) {
        System.out.print("Value " + (i + 1) + ": ");
        int inputValue = scanner.nextInt();

        if (inputValue % 2 == 0) {
            evenCount++;
        } else if (inputValue %2==0) {
            oddCount++;
        }
        
    }

    System.out.println("Even Count: " + evenCount);
    System.out.println("Odd Count: " + oddCount);
}
