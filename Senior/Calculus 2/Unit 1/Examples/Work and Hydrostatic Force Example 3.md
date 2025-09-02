Given a tank that is shaped like an inverted cone with a height of $10ft$ and base radius of $5$. If the tank is filled with olive oil (weighing $57\frac{lbs}{ft^3}$) to $2$ feet from the top, how much work is required to pump the oil to the rim of the tank (empty the tank)?
> height: $10ft$
> radius: $5$
> tank weight: $57\frac{lbs}{ft^3}$
> height top top: $2ft$
![[Work and Hydrostatic Force Example 3 Picture 1.excalidraw]]
$$\frac{5}{10}=\frac{r}{x}=>\frac{x}{2}=r$$
$$V=\pi(\frac{x}{2})^2\delta x$$
$$F(x)~\text{(weight)}=V*\rho~\text{(density)}=$$
$$F(x)=\pi\frac{x^2}{4}*57=\frac{57\pi x^2}{4}$$
$$d(x)=(10-x)$$
$$W=\int (\frac{57\pi x^2}{4})(10-x)~dx$$
$$W=\frac{57\pi}{4}\int^8_0 10x^2-x^3~dx$$
$$W=\frac{57\pi}{4}[\frac{10x^3}{3}-\frac{x^4}{4}|^8_0]$$
$$W=30,561ft-lbs$$