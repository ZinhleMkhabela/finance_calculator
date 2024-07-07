# finance_calculator

# Finance Calculators

This repository contains a Python program that provides two financial calculators: an investment calculator and a home loan repayment (bond) calculator.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Formulas](#formulas)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The `finance_calculators.py` program allows users to choose between calculating the future value of an investment with either simple or compound interest, and calculating the monthly repayment amount for a home loan.

## Features

- **Investment Calculator**: Computes the future value of an investment using either simple or compound interest.
- **Bond Calculator**: Computes the monthly repayment amount for a home loan based on the present value of the house, the annual interest rate, and the number of months for repayment.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/finance_calculators.git
   ```

2. Navigate to the project directory:

   ```sh
   cd finance_calculators
   ```

3. Ensure you have Python installed on your machine. This program requires Python 3.x.

## Usage

1. Run the program:

   ```sh
   python finance_calculators.py
   ```

2. Follow the on-screen prompts to select either the investment or bond calculator and input the required data.

### Example

For the investment calculator:

```
Choose either 'investment' or 'bond' from the menu below to proceed:
investment - to calculate the amount of interest you'll earn on your investment
bond       - to calculate the amount you'll have to pay on a home loan
investment
Enter the amount of money you are depositing: 1000
Enter the interest rate (as a percentage): 5
Enter the number of years you plan on investing for: 10
Do you want 'simple' or 'compound' interest? compound
The total amount after 10 years is: 1628.89
```

For the bond calculator:

```
Choose either 'investment' or 'bond' from the menu below to proceed:
investment - to calculate the amount of interest you'll earn on your investment
bond       - to calculate the amount you'll have to pay on a home loan
bond
Enter the present value of the house: 200000
Enter the interest rate (as a percentage): 7
Enter the number of months you plan to take to repay the bond: 240
The monthly repayment amount is: 1550.60
```

## Formulas

### Investment Calculator

- **Simple Interest**: A = P * (1 + r * t)
- **Compound Interest**: A = P * math.pow((1 + r), t)

Where:
- `A` is the total amount after interest
- `P` is the principal amount (initial deposit)
- `r` is the annual interest rate (decimal)
- `t` is the number of years

### Bond Calculator

- **Monthly Repayment**: x = (i * P) / (1 - (1 + i)^-n)

Where:
- `x` is the monthly repayment amount
- `P` is the present value of the house
- `i` is the monthly interest rate (annual rate / 12)
- `n` is the number of months

## Contributing

Contributions are welcome! Please submit a pull request or open an issue to discuss any changes or enhancements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

