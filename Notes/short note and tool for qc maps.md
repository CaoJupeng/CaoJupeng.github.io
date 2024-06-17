拟共形映射的定义.



1. **(C^1 qc-maps class )** A sense-persevering(i.e. $|f_z|>f_{\bar{z}},\forall z\in D$ ) $C^1$ diffeo $f:D \to \Omega$ is a K-qc map if the distortion 

$$
D_f(z):=\frac{\text{infitesimal maximal stretch}}{\text{infitesimal minimal stretch}}:=\frac{|f_{z}|+|f_\bar{z}|}{|f_{z}|+|f_\bar{z}|}(z)<K,\forall z\in D
$$

We define the the $\sup_{z\in D}D_{f}(z)=:K_{f}$, which is called the *maximal dilitation of $f$*.

Thus for any sense-persevering $C^1$ diffeo ,

$f$ is a $\infty-$ qc map $\iff$ $f$ is not a qc-map.

$f$ is a $K-qc$ map  $\iff$ $K_f\le K$.

**Ex1** Verify $K_{f^{-1}}=K_{f}$ and $K_{f\circ g}\le K_{f}K_{g}$. In particular, for conformal $f$ or $g$ ,we get $K_{f\circ g}=K_{g},etc.$ 

**Cor1** The best ambient spaces to talk about ($C^1$) qc maps are Riemann surfaces because the holo transition functions preserves the maximal dilatation of a given qc-map.

---

Since the above $C^1$ K-qc map is lack of **normality**, (for example.. the limit function is often not $C^1$ smooth.), we relax the "smoothness" of $f$, only with cts, but with a similar condtion defined by the action on  all quadrilaterals.

Let $M,N $ be Riemann surfaces. We will find the best ambient spaces to talk about qc maps are Riemann surfaces under the following definition of qc-maps.

2.**(geometric definition)**

A homeomorphism $f:D\to \Omega$ is a K-qc map if the action on every quadrilateral in D preserves quasi-invariant, i.e. for any quadrilateral $R(z_1,\dots,z_n)$ with $\bar{R}\sub D$  whose image is  $R'$ of $R$, there is 
$$
Mod(R')\le KMod(R).
$$
  From the sysmetry of $R$ , we get the def is equivalent to 
$$
\frac{1}{K}Mod(R)\le Mod(R')\le KMod(R).
$$
**Note** In fact, we define $K-qc$ by the action of $f$ on quadrilation space, so here K-qc is understanded as a good action on quadrilateral space.

**Notation** $C^{1}_{K}(D,\Omega):=\{C^1 K-qc \,maps:D\to \Omega\}$;

​				  $K(D,\Omega):=\{K-qc\,from \,D \,to\, \Omega\}$

​				  $Q(D):=\{\text{quadrilaterals in D\}}$ is called quadrilateral space  

​				$K_f:=\sup_{R\in Q(D)}{\frac{M(f(R)}{M(R)}}$, which is called the maximal dilatation of a homeo $f$ from $D$ to any space.

**eg1**  $C^{1}_{K}(D,\Omega)\sub K(D,\Omega)$.

**pf** Take 2 rectangles $R\to R'$ since we know the composite with holo maps preserves $C^1$ K-qc, and let $R,R'$ has widths and heights $(a,1),(a',1)$ resp. From the Grotszh's problem, we get the opimal maps has the minimal maximal dilatation $a'/a$, thus $K\ge a'/a=M'/M$, i.e. $M'\le KM$. This shows that the action of $f$ is $K-qc$. 

$\square$

The reader may ask whether the new infinimum of $K_{f}$ agree with the old one. At least we know the new is no larger than the old since the mapping space is larger. 

> 疑问? **Relation of the  2 defnitions** 



**eg2** A example not $C^1$ qc maps, which show the necessarity of relaxing smoothness. (Todo)

**lem** If $f$ is conformal, then the dilation of compostion of any $K-$qc map with $f$ is still $K-qc$ between correspoding domains. 

$A$ homeomorphism $f:M\to N$ is **K-qc** if on every local chart $f$ is represented as a $K-qc$ map (or action).The def is well-defined guaranteed by the lem.

When the action is $1-qc$, we infer it is a conformal map. The following lem is surprising because the 1-qc actions of quadrilateral space should correspond to conformal maps. The converse is more obvious.

**Thm** If $f:D\to \Omega$ is $1-qc$，then it is conformal.

**pf** <u>**length-area trick**</u>(app of schwar's inequality) and extremal metric.





---

The geomeric def has given many geometric interpretion especially the correspondence from the action on quadrilateral space to qcmaps-space(*imagine the different $K$ gives the stratification or the partion into slices*).

Geometric definition is useful but is difficult to answer whether there exists the optimal map and how  to solve,etc. Due to this, we emplogy the analysis method and firstly proposed a analytic defitnion which is equivalent to the geometric one, so that we know what we are looking for when we find some analytic objects.

3.**(analytic)** A homeo $f $  is a $K-q$c if $f$ is ACL(absolutely continuous on lines,i.e. abso.cts on almostly all horizontal lines and vertical lines in the sense of 1dimsional Lebesgue) and satisfies the Beltrami equaiton $f_{\bar{z}}=\mu(z)f_{z}$ a.e. and $||\mu||_{\infty}\le k<1$.

Recall the motivation why we introduce the analytic def, we later study qc map from the Beltami equation (cofficient $\mu$) for the existence and uniqueness,given any suitable $\mu$.





4.**(analytic)** A homeomorphism $f $  is a $K-q$c if $f$ has *distributional partial derivatives* in $L_{\text{loc}}^2$ satisfying BDE
$$
|f_\bar{z}|\le k|f_{z}|,
$$
a.e., where $k=\frac{K-1}{K+1}$.  

This is definition is espeically useful and avoid evaluating functions and the qc map is geometric good but has a bad property on evaluating at some poins.We study soft analysis and so avoid talking about a.e. such not precise words.

By Wely's lemma and this def of qc map,we get 

**Thm** 1-qc map is a synonym for a conformal map. 

Ex Compute the distributional der







---



## The solution of Beltrami equation

Given some measurable $\mu$ on $M$, $||\mu||_{\infty} \le k<1$, is there a solution $f:M\to N$ for some Riemann surface $N$?



As only for the BDE, there always exists many trival solutions, i.e. $f=const $ on $D$. But please we need a homeo with distributional derivative satisfying the above conditions.



smooth solution

It is difficult to understand and compute!











## Relation of 3 definitions

 We extend out mapping space from best conformal maps, to a little bigger $C^1$ qc-map, then geometrical ($\iff$ analytic) qc maps. Our aim of extending mapping space is to ensure the normality and we find  the lack of smoothness doesn't influence the action on quadrilaterals which is the unique geometric property we focus on.







## Todo 

application of extremal metic and write a toolkit

2024年5月26日

希望可以编个口诀总结一下拟共形映射解决问题的思路



简化参数区域,(sc变换)

微分调整映射，

对比长度模变



极限存在是关键，泰勒局部找极值。

加减运算看牛莱，加减换序是妙手。

级数通项比速度，中间抵消要留意。

变量替换算积分，斯托克斯看边界。

