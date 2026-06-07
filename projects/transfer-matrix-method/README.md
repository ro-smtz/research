# Transfer matrix method

Implementation of the transfer matrix formalism for computing the optical response of layered systems and coupled microcavities.

**Language:** MATLAB  
**Status:** In progress

## Physics

The transfer matrix method (TMM) propagates the electromagnetic field through a stack of planar layers by composing 2×2 matrices of the form:

$$M_j = \begin{pmatrix} \cos\delta_j & -\frac{i}{\eta_j}\sin\delta_j \\ -i\eta_j\sin\delta_j & \cos\delta_j \end{pmatrix}$$

where $\delta_j = k_0 n_j d_j \cos\theta_j$ is the phase accumulated across layer $j$. Reflectance and transmittance follow from the total system matrix.

## Contents

*(Add MATLAB scripts here.)*

## Related

Used in: [`papers/2025-intercavity-polaritons/`](../../papers/2025-intercavity-polaritons/)
