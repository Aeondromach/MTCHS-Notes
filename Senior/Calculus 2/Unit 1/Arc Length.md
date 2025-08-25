# Length of a Line
![[Arc Length Example 0 Picture 1]]
$$S=\sqrt{(x_1-x_2)^2+(y_1-y_2)^2}$$

$$S=\sqrt{(dx)^2+(f^1(x)*dx)^2}$$
$$S=\sqrt{(dx)^2+(1 + f^1(x))^2}$$
$$S=dx+\sqrt{1+(f^1(x))^2}$$
$$S=\sqrt{1+(f^1(x))^2}$$
## Arc Length
$$L=\int^{b}_{a}\sqrt{1+(f^1(x))^2}~dx=\int^{b}_{a}\sqrt{1+(\frac{dy}{dx})^2}~dx$$
![[Arc Length Example 0 Picture 2]]

![[Arc Length Example 1]]
## Discontinuities in $\frac{dy}{dx}$
At a point on a curve where $\frac{dy}{dx}$ DNE, $\frac{dy}{dx}$ *may* exist.
$$L=\int^d_c\sqrt{1+(\frac{dx}{dy})^2}~dy=\int^d_c\sqrt{1+(g^1(y))^2}~dy$$
![[Arc Length Example 2]]