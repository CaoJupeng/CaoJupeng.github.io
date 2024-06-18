From a transitive group action  $\rho:\pi_1(S,q)\to S_d$ ,we can construct a covering such that image of the fundamental group of the covering space is exactly $H:=Stab(1)$. 

The difficult is only to show that the induced monodromy representation $\sigma:\pi_1(S,q)\to S_d$ is equal to $\rho$ up to a conjugacy.

We now forget the backgroud and turn down to the pure algebra.
$$
\begin{CD} 
\{1,2,\dots,d\} @>{\rho_{\beta}}>> \{1,2,\dots,d\}\\ 
@V{f}VV @V{f}VV @. \\ 
\pi_1(S,q)/H @>{}>> \pi_1(S,q)/H \\ 
@V{g}VV @V{g}VV @. \\ 
\{1,2,\dots,d\} @>{\sigma_{\beta}}>> \{1,2,\dots,d\}\\ 
\end{CD}

\begin{CD} 
i @>{\rho_{\beta}}>> \rho_{\beta}(i)\\ 
@V{f}VV @V{f}VV @. \\ 
\alpha @>{\beta}>> \beta\cdot\alpha H  \\ 
@V{g}VV @V{g}VV @. \\ 
\sigma_{\alpha}(1) @>{\sigma_{\beta}}>> \sigma_{\beta}(\sigma_{\alpha}(1))=\sigma_{\beta\alpha}(1)\\ 
\end{CD}
$$


where  $H:Stab(1)$， $f:i\mapsto \alpha$ is a bijection if $\rho_\alpha(1)=i$ . It is well-defined and $g:\alpha H\to \sigma_{\alpha}(1) $ is also a bijection. You will find that the 2 diagrams are commutative and hence the group actions  are isomorphic under a bijection between $\{1,2,\cdots,d\}$.  Therefore, $\rho_{\beta}=(fg)^{-1}\sigma_{\beta}(fg),\forall \beta\in \pi_1(S,q)$ . As mentioned above, the high-level explaination is they are essentially the same representaion on the coset $H$. 

Hope the diagram is useful for your understanding.

