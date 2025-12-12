# RESTAURANT_BILL_SYSTEM

*Project Title
Restaurant Billing System in C

*Objective
The primary objective of this project is to create a simple console-based restaurant billing system using the C programming language. The system allows a user (e.g., a cashier) to:

Take a customer's name.

Display a fixed menu with item prices.

Allow the user to select items and quantities repeatedly.

Calculate the subtotal (Total Amount) of the selected items.

Calculate the Goods and Services Tax (GST) at a fixed rate of 5% on the subtotal.

Calculate the final bill amount (Final Amount).

Display a summary of the bill on the console.

Save the detailed bill, including a list of items and the final summary, to a text file named after the customer (e.g., CustomerName.txt).

* How to Compile and Run the Program
The program is written in standard C and can be compiled and run using a C compiler like GCC.

Save the Code: Save the provided C code in a file named restaurant_billing.c.

Compile: Open a terminal or command prompt and use the GCC compiler to compile the source( file.gcc restaurant_bill_management.c -o restaurant_bill_management)

Run: Execute the compiled program from the terminal. (./restaurant_bill_management)
(Note: On Windows, you might run it as restaurant_billing_management.exe)

* SAMPLE OUTPUT

  ![WhatsApp Image 2025-12-12 at 09 11 43_8406888f](https://github.com/user-attachments/assets/75a8e35a-0e27-41c7-8397-b4a4e5403af3)
  ![WhatsApp Image 2025-12-12 at 09 11 44_410a9272](https://github.com/user-attachments/assets/7d3c8f6e-e8b5-4716-948d-6ead6bebd8e9)
  ![WhatsApp Image 2025-12-12 at 09 11 44_77760acf](https://github.com/user-attachments/assets/531329d8-14ab-4b33-8e92-2f524d2580c0)

* Important Notes or Assumptions
Customer Name Input: The program only reads the first word of the customer name (due to scanf("%49s", customerName);). Spaces in the name will terminate the input.

Menu and Pricing: The menu items and their prices are fixed and hardcoded within the source file. Any change requires recompilation.

GST Rate: The GST is fixed at 5% (0.05) for all items.

Error Handling: Basic error handling is present for file opening failures and invalid menu choices. Invalid choices are skipped, and the user is prompted to continue ordering.

File Output: The program saves the bill detail and summary to a text file in the same directory as the executable, named after the customer.



