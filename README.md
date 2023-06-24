# IceCreamShop
This is a Java program that simulates an ice cream shop order system. It allows customers to place orders for various items, including ice cream, shakes, smoothies, and slushies.

Usage

Compile the code:
javac IceCreamShop.java

Run the program:
java IceCreamShop

Follow the instructions to place your order. Enter the item type and quantity when prompted. To exit the ordering process, enter 0.

Description
The program consists of two classes: ShopItems and IceCreamShop.

ShopItems Class
The ShopItems class is an inner class that keeps track of item counts. It contains two inner classes: NonVegan and Vegan, representing non-vegan and vegan items, respectively.

NonVegan Class
Attributes:

totalCount: Total count of all non-vegan items sold.
iceCreamCount: Count of ice cream items sold.
shakeCount: Count of shake items sold.

Method:

increaseCount(int type, int count): Updates the counts based on the item type and increases the total count.

Vegan Class
Attributes:

totalCount: Total count of all vegan items sold.
smoothieCount: Count of smoothie items sold.
slushieCount: Count of slushie items sold.

Method:

increaseCount(int type, int count): Updates the counts based on the item type and increases the total count.

IceCreamShop Class
The IceCreamShop class contains the main method, which handles the order process.

Method:
main(String[] args): The entry point of the program. It initializes the necessary objects and starts the order loop. It prompts the user for the item type and quantity, updates the counts accordingly, and displays the total counts. The loop continues until the user chooses to exit.
Limitations

The program assumes valid input from the user and does not include error handling or input validation.

There is no persistence of order data. Once the program is terminated, the order information is lost.

Pricing, payment, and other advanced features are not implemented. The program focuses on tracking item counts.

Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to submit a pull request.

License
This code is provided under the MIT License. You are free to use, modify, and distribute the code. See the LICENSE file for more details.
