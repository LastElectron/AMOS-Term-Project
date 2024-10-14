# Stressses in Composite Cylinders with Shrink Fits | Course Project, Dr. Jeevanjyoti Chakraborty, IIT Kharagpur

## Description
• Derived expressions for radial and circumferential stresses in the inner cylinder of a composite system using axisymmetric formulation.
• Determined the shrink fit allowance for equal strength using maximum shear stress theory.

## Prerequisites
- Python 3.x
- Jupyter Notebook

 Contents
&bull; [Problem Statement](#Problem-Statement:)
1. [Initializing Neccesary Libraries and Functions](#Part-1:-Initializing-neccesary-libraries-and-functions)
2. [Deriving Expression for $\sigma_{rr}$ and $\sigma_{\theta\theta}$ for any general cylinder](#Part-2:-Deriving-expression-for-$\sigma_{rr}$-and-$\sigma_{\theta\theta}$)
3. [Analysis of Two Special Cases based on Internal and External Pressure Conditions](#Part-3:-Two-special-cases)
4. [Analysis of Shrink Fitted Composite Cylinder](#Part-4:-Shrink-fitted-composite-cylinder)
5. [Derivation of Radial Displacements of Inner and Outer Cylinder of Composite Cylinder](#Part-5:-Derivation-of-radial-displacements-of-inner-and-outer-cylinder)
6. [Analysis of Composite Cylinder under Internal Pressure and no External Pressure for Equal Strengths of Both Cylinders](#Part-6:-Composite-cylinder-under-internal-pressure,-no-external-pressure)
7. [Calculation of Optimum Shrink Fit Allowance $\Delta$ using Maximum Shear Stress Theory](#Part-7:-Using-Maximum-Shear-Stress-Theory-to-find-optimum-$\Delta$)
8. [Conclusion](#Part-8:-Conclusion)

&bull; [Individual Contributions by Each Group Member](#Individual-Contributions-by-Each-Group-Member:)<br>
&bull; [References](#References:)

## __Problem Statement:__

Consider a composite cylinder made of two cylinders made of two different materials and fitted one inside the other. Before assembling, the inner cylinder has an internal radius a and an external radius $c$. The internal radius of the outer cylinder is less than $c$ by $\Delta$, i.e. its internal radius is $c$ - $\Delta$. Its external radius is b. If the inner cylinder is cooled and the outer cylinder is heated, then the two cylinders can be assembled, one fitting inside the other. When the cylinders come to room temperature, a shrink fit is obtained.

__(1)__ Our primary objective is to determine expression for the radial stress σr and the circumferential stress σθ for the inner cylinder, employing an axisymmetric formulation.

__(2)__ The contact pressure pc acting on the outer surface of the inner cylinder reduces its outer radius by u1. On the other hand, the same contact pressure increases the inner radius of the outer cylinder by u2. The sum of these two quantities, i.e. (−u1 + u2) must be equal to delta, the difference in the radii of the cylinders. We have to express u1 and u2 in terms of pc.

__(3)__ Using relation between u1, u2 and Δ, we will find contact pressure pc.

__(4)__ Now we will apply internal pressure p to our composite cylinder. Our next aim is to calculate shrink fit allowance Δ such that strength of both cylinders will be equal. We will use maximum shear stress theory for this purpose.

## View the Notebook (nbviewer)
You can view the Jupyter Notebook online using nbviewer: [View Notebook](https://nbviewer.org/github/LastElectron/Stresses-in-Composite-Cylinders-with-Shrink-Fits/blob/b36340046e4bdb1731463d3e04bfdf30424cf4c6/Term%20Project%20Submission%20-%20Group%205.ipynb)
