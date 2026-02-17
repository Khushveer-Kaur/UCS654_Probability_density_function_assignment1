# UCS654_Probability_density_function_assignment1

### Name- Khushveer Kaur
### Roll no. -102303327

This repository contains the solution for Assignment-1, which focuses on
learning the parameters of a probability density function using a
roll-number-parameterized non-linear transformation.

## Dataset
India Air Quality Dataset  
Feature used: NO₂ concentration

## Transformation
Each NO₂ value (x) is transformed into z using a non-linear function:

z = x + a_r sin(b_r x)

where:
- a_r = 0.05 × (r mod 7)
- b_r = 0.3 × (r mod 5 + 1)
- r is the university roll number

## Probability Density Function
The transformed variable z is modeled using:

p̂(z) = c · exp(−λ (z − μ)²)

## Parameter Estimation
The parameters μ, λ, and c are estimated using the **Method of Moments**.

## Output Values
<img width="590" height="150" alt="results" src="https://github.com/user-attachments/assets/399179c5-10e7-4796-be27-6e9a40c40221" />


## Estimated PDF Plot
<img width="697" height="530" alt="pdf_plot" src="https://github.com/user-attachments/assets/a1fa05f9-8fe9-4862-b4f4-41acbfc720ac" />


## Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
