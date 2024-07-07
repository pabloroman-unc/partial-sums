# Maple Orthogonal Polynomials Examples

This repository contains examples of using Maple to work with various orthogonal polynomials, including Hermite, Charlier, and Lommel polynomials. Each example includes Maple code with detailed comments explaining the steps involved.

## Files in the Repository

1. `Hermite.mw`
2. `Charlier.mw`
3. `Lommel.mw`

### 1. Hermite Polynomials Example (`Hermite.mw`)

This file demonstrates how to work with Hermite polynomials in Maple. It includes the following steps:

- **Loading the Orthopoly Package**: `with(orthopoly):` This command loads the orthopoly package, which includes various orthogonal polynomials.

- **Defining the Function q**: `q := (n, x, t) -> sum(H(j, x)/factorial(j)*t^j, j = 0..n):` This function uses Hermite polynomials \( H(j, x) \) to define \( q \).

- **Recurrence Relation**: Definitions for the recurrence relation coefficients \( a, \alpha, b, c \).

- **Coefficients Computation**: Computation of coefficients \( d1, d2, d3, d4 \) based on the recurrence relation.

- **Simplifications and Verifications**: Simplifying and verifying expressions related to the recurrence relations.

- **Derivatives of \( q \)**: Computing and simplifying derivatives of the function \( q \).

- **Computation of \( t_c \)**: Using fsolve to find roots and compute the discriminant of \( q \).

### 2. Charlier Polynomials Example (`Charlier.mw`)

This file contains code for working with Charlier polynomials. The main steps include:

- **Loading Necessary Packages**: Importing required packages for Charlier polynomials.
- **Defining Charlier Polynomials**: Functions and procedures to define Charlier polynomials.
- **Recurrence Relations**: Definitions and computations of recurrence relations specific to Charlier polynomials.
- **Simplifications**: Simplifying expressions involving Charlier polynomials.
- **Derivatives**: Computing derivatives of Charlier polynomials.
- **Special Values and Roots**: Finding special values and roots for specific cases of Charlier polynomials.

### 3. Lommel Polynomials Example (`Lommel.mw`)

This file provides an example of working with Lommel polynomials in Maple. It includes:

- **Loading Packages**: Loading required packages for Lommel polynomials.
- **Defining Lommel Polynomials**: Functions and procedures to define Lommel polynomials.
- **Recurrence Relations**: Definitions and computations of recurrence relations specific to Lommel polynomials.
- **Simplifications**: Simplifying expressions involving Lommel polynomials.
- **Derivatives**: Computing derivatives of Lommel polynomials.
- **Special Values and Roots**: Finding special values and roots for specific cases of Lommel polynomials.

## How to Use

1. **Open Maple**: Ensure you have Maple installed on your system.
2. **Load the Files**: Open the `.mw` files in Maple.
3. **Run the Code**: Execute the code sections to see the results and understand the computations.

Each file contains comments explaining the steps, making it easy to follow and understand how to work with these orthogonal polynomials using Maple.

## Contributing

If you find any issues or have suggestions for improvements, feel free to create an issue.
