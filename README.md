# Mortgage Calculator

## Overview

The Mortgage Calculator is an interactive web application designed to assist users in determining their monthly mortgage payments. Whether you're a first-time homebuyer, refinancing an existing mortgage, or just curious about how different variables affect your monthly payments, this calculator provides a straightforward and visually appealing way to estimate your mortgage costs.

![Mortgage Calculator Image 1](src/assets/images/01.png)
![Mortgage Calculator Image 2](src/assets/02.png)
![Mortgage Calculator Image 3](src/assets/images/03.png)

## Purpose

The primary purpose of the Mortgage Calculator is to simplify the complex process of mortgage calculation. By allowing users to input essential variables such as the loan amount, interest rate, and loan term, the calculator provides instant feedback on monthly payments. This tool empowers users to make informed financial decisions by understanding how varying factors influence their mortgage obligations.

## Key Features

1. **User-Friendly Interface**: The calculator is designed with a clean, intuitive layout that guides users through the input process. It employs a modern aesthetic that enhances usability, making it accessible for users of all ages.

2. **Input Fields**:
   - **Loan Amount**: Users can enter the total amount of money they wish to borrow for their mortgage.
   - **Interest Rate**: A field for users to specify the annual interest rate of the loan.
   - **Loan Term**: Users can select the duration of the loan, typically in years (e.g., 15, 20, or 30 years).

3. **Calculation Logic**: Upon entering the required values and clicking the "Calculate" button, the application performs the necessary calculations using the formula for monthly mortgage payments:
   \[
   M = P \frac{r(1 + r)^n}{(1 + r)^n - 1}
   \]
   where:
   - \( M \) is the total monthly mortgage payment.
   - \( P \) is the principal loan amount.
   - \( r \) is the monthly interest rate (annual interest rate divided by 12).
   - \( n \) is the number of payments (loan term in months).

4. **Results Display**: The calculated monthly payment is presented clearly, along with additional breakdowns if applicable, such as total interest paid over the loan term.

5. **Responsive Design**: The application is fully responsive, ensuring a seamless experience on devices of all sizes, from desktops to tablets and smartphones.

6. **Attractive Visuals**: The design incorporates visually appealing elements such as images, icons, and color schemes that enhance user engagement. The use of CSS for styling ensures a polished and professional look.

7. **Accessibility**: The calculator is built with accessibility in mind, allowing users with different needs to navigate and interact with the tool effortlessly.

## Technologies Used

- HTML
- CSS
- JavaScript

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mortgage-calculator.git
