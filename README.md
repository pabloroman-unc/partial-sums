# Maple Orthogonal Polynomials Examples

This repository contains examples of partial sums of orthogonal polynomials, including Hermite, Charlier, and Lommel polynomials. Each example includes Maple code with detailed comments explaining the steps involved. The plots are done with a Python script.

## Trajectories of the zeros of partial sums

### Trajectories of partial sums of Hermite polynomials
Let $H_n(x)$ be the classical Hermite polynomials. The following video exhibits the trajectories of the zeros of the partial sums

$$q_m(x;t) = \sum_{n=0}^m \frac{H_{n}(x) t^n}{n!},$$

as the parameter $t$ approaches zero. Initially, the zeros of $q_m(x;t)$ are close to a zero of $H_m(x)$. The first
collission occurs at a critical time $t_c$. For $t &lt; t_c$, the zeros move into the complex plane.

https://github.com/pabloroman-unc/partial-sums/assets/101678587/9bd53dd2-8545-4c2f-93b1-2b39e1a57c05

### Trajectories of partial sums of Charlier polynomials
Let $C_n^{(a)}(x)$ be the Charlier polynomials. The following video exhibits the trajectories of the zeros of the partial sums

$$q_m^{(3)}(x;t) = \sum_{n=0}^m \frac{C^{(3)}_{n}(x) t^n}{n!},$$

as the parameter $t$ approaches zero. Initially, the zeros of $q_m(x;t)$ are close to a zero of $C^{(3)}_m(x)$. The first
collission occurs at a critical time $t_c$. For $t &lt; t_c$, the zeros move into the complex plane.



https://github.com/user-attachments/assets/00d90d06-f9e4-4363-a4c9-b81403709c8e




### Trajectories of partial sums of Lommel polynomials
Let $h_{m,\nu}(x)$ be the Charlier polynomials. The following video exhibits the trajectories of the zeros of the partial sums

$$q_m^{(\nu)}(x;t) = \sum_{n=0}^m h_{m,\nu}(x) t^n,$$

as the parameter $t$ approaches zero. Initially, the zeros of $q_m(x;t)$ are close to a zero of $h_{m,\nu}(x)$.

https://github.com/user-attachments/assets/0e5f2a7c-d807-4e64-8c76-6c4c004d7c77

## Plots of zeros of partial sums

The file 'Plots.ipynb' provides the plots for zeros and trajectories of the partial sums of Hermite, Charlier and Lommel polynomials.

## Three main Examples:

1. `Hermite.mw`
2. `Charlier.mw`
3. `Lommel.mw`

### 1. Hermite Polynomials Example (`Hermite.mw`)

This file provides verifications of formulas of partial sums of Hermite polynomials in Maple. It includes:

- **Defining the partial sums $q_m(x;t)$**:

- **Simplifications and Verifications**: Simplifying and verifying expressions related to the recurrence relations.

- **Derivatives of $q_m(x;t)$**: Computing and simplifying derivatives of the function $q_m(x;t)$.

- **Computation of the critical time $t_c$**: Using fsolve to find roots and compute the discriminant of $q_m(x;t)$.

### 2. Charlier Polynomials Example (`Charlier.mw`)

This file provides verifications of formulas for partial sums of Charlier polynomials. It includes:

- **Defining the partial sums $q^{(a)}_m(x;t)$**:

- **Simplifications and Verifications**: Simplifying and verifying expressions related to the recurrence relations.

- **Derivatives of $q^{(a)}_m(x;t)$**: Computing and simplifying differences of the function $q^{(a)}_m(x;t)$.

### 3. Lommel Polynomials Example (`Lommel.mw`)

This file provides verifications of formulas for partial sums of Lommel polynomials in Maple. It includes:

- **Defining the partial sums $q$**:

- **Simplifications and Verifications**: Simplifying and verifying expressions related to the recurrence relations.


