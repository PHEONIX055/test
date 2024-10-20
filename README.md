# test
public class Add {

    public static void main(String[] args) {
        // Check if two arguments are passed
        if (args.length != 2) {
            System.out.println("Please provide two integer arguments.");
            return;
        }

        // Parse the command-line arguments
        int first = Integer.parseInt(args[0]);
        int second = Integer.parseInt(args[1]);

        // Add the two numbers
        int sum = first + second;

        // Print the result
        System.out.println(first + " + " + second + " = " + sum);
    }
}

_____________________________________________________________________________
public class Main {

    public static void main(String[] args) {
      
      int first = 10;
      int second = 20;
  
      // add two numbers
      int sum = first + second;
      System.out.println(first + " + " + second + " = "  + sum);
    }
}

____________________________________________________________________



# sum_fixed_numbers.py

def main():
    first = 10
    second = 20

    # Add the two numbers
    sum_ = first + second

    # Print the result
    print(f"{first} + {second} = {sum_}")

if __name__ == "__main__":
    main()
_________________________________________________________________________--


# sum_numbers.py

import sys

def main():
    if len(sys.argv) != 3:
        print("Please provide two numbers.")
        return

    first = int(sys.argv[1])
    second = int(sys.argv[2])
    sum_ = first + second
    print(f"{first} + {second} = {sum_}")

if __name__ == "__main__":
    main()
