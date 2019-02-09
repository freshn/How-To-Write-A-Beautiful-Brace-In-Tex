Today I see a beautiful equation:  
![How Pretty This Equation Is](/prettybrace.png)  
I don't know how to write it in Tex.
I try my best to write like following:
```
\begin{equation}
\begin{aligned}
r_{t}=\left\{
\begin{array}{crl}
1+\dfrac{\bar{R}_{Q}(t+\Delta t)-R_{Q}(t)}{2\Delta t/T_{single}}\; &+0\qquad &if\,\bar{R}_{Q}(t+\Delta t)>0,\\
0 \; &-P\qquad &if\,R_{Q}(t)\neq 0\wedge R_{Q}(t+\Delta  t)=0,\\
0\; &+0\qquad &if\,R_{Q}(t)=0
\label{rforProtRwd}
\end{array}
\right.
\\
\underbrace{\hspace{10em}}_{=:r_{t}^{(1)}}\hspace{1em}\underbrace{\hspace{2em}}_{=:r_{t}^{(2)}}\hspace{17em}
\end{aligned}
\end{equation}
```
![My Ugle Brace](https://github.com/freshn/How-To-Write-A-Beautiful-Brace-In-Tex/blob/master/mybrace.png?raw=true)  
It is obviously that the underbrace is a little far from the main part of the equation. And actually both the method I write and the result are ugle.  
So I wonder if there are some better ways to write it.  
Hoping someone can help.[Pull Request](https://github.com/freshn/How-To-Write-A-Beautiful-Brace-In-Tex/compare) :octocat:
