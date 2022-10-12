# Master_Thesis

Topic: Dimension selection in high dimensional data sets



\textbf{Background:} Factor analysis has been an essential workhorse in analyzing high dimensional data sets, especially when the number of observed dimensions exceeds sample sizes. Determining the number of latent dimensions has an imperative impact on the quality and accuracy of factor models. Some existing methods of selecting the optimal number of latent factors, for instance, Kaiser's eigenvalue greater than one rule, maximum log likelihood ratio test, information criterion, scree plot test, and parallel analysis, mostly suffer from over identification of latent dimensions, which inevitably causes problems of inaccuracies in factor analysis. 

\textbf{Proposed method:} We propose a method on the basis of Marchenko-Pastur law, which originates from random matrix theory. This law states that for a $n \times p$ random matrix following Wishart distribution,the limiting behaviour of its eigenvalues is generally bound by a constant ration $n/p \to c \in (0,\infty)$ as $p$ approaches to $\infty$. The latent factors are selected as its respective eigenvalues greater that the value of bounding ratio of $c_{+} = \left( 1 + \sqrt{\frac{1}{c}} \right)^2$.

\textbf{Results:} In a simulation study, comparing with methods of Kaiser's rule, Empirical Kaiser Criterion, Eigenvalue ratio and Growth ratio, Marchenko-Pastur law performs the best in most of cases, particularly when the number of observed variables exceeds the sample sizes.

\textit{Keywords:} Factor analysis; High dimensional data; Latent factors/dimensions; Marchenko-Pastur law
