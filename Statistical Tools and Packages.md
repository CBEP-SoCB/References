# Citations To Statistical Tools and Packages

# Core Statistical Tools

**R** Statistical program.
R Core Team (2020). R: A language and environment for statistical computing. R
Foundation for Statistical Computing, Vienna, Austria. URL:
https://www.R-project.org/.

**RStudio** Integrated Development Environment for R. Provides enhanced access 
to many useful tools in R, especially R notebooks.

RStudio Team (2021). RStudio: Integrated Development Environment for R. RStudio,
PBC, Boston, MA URL http://www.rstudio.com/.

**tidyverse** Not one package, but a collection of interrelated packages that
support and extend R programming, data management and graphics. The collection
of packages supports efficient code development, and is a nearly essential tool.
Important component packages that we used in essentially every analysis
include: ggplot2, dplyr, tibble, and readr.

Wickham H, Averick M, Bryan J, Chang W, McGowan LD, François R, Grolemund G,
Hayes A, Henry L, Hester J, Kuhn M, Pedersen TL, Miller E, Bache SM, Müller K,
Ooms J, Robinson D, Seidel DP, Spinu V, Takahashi K, Vaughan D, Wilke C, Woo K,
Yutani H (2019). "Welcome to the tidyverse." Journal of Open Source
Software, 4(43), 1686. doi: 10.21105/joss.01686.

# Packages Supporting Core Workflows

**emmeans**
Supports work with "estimated marginal means" (EMMs). EMMs are the R equivalent
of the (misnamed) "Least Squares Means" from SAS. The package provide tools for
examining, comparing and plotting estimates of model results "adjusted" for
covariates. An essential tool for generating simple graphical output based on
complex statistical models (especially hierarchical models). Greatly facilitates
interpretation of results from data with uneven sampling histories and modeling
that includes ancillary variables of interest primarily to reduce model
residuals by incorporating known sources of variation.

Russell V. Lenth (2021). emmeans: Estimated Marginal Means, aka Least-Squares 
Means. R package version 1.5.4. https://CRAN.R-project.org/package=emmeans.


**ggplot2** The primary graphics engine used to generate graphics for State of
Casco Bay 2020. A part of the Tidyverse, but of sufficient importance to justify
an independent citation.

H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag 
New York, 2016.

**knitr**
Supports generation of dynamic reports from R notebooks. It facilitates
reproducible science by simplifying intermingling of data, code, graphics and
text. The output from R notebooks into HTML, GitHub markdown, word documents and
PDFs is an essential part of our statistical workflow, and generates the
versions of our analyses that are visible on GitHub.

Yihui Xie (2021). knitr: A General-Purpose Package for Dynamic Report Generation 
in R. R package version 1.31 

Yihui Xie (2015) Dynamic Documents with R and knitr. 2nd edition. Chapman and 
Hall/CRC. ISBN 978-1498716963

Yihui Xie (2014) knitr: A Comprehensive Tool for Reproducible Research in R. In
Victoria Stodden, Friedrich Leisch and Roger D. Peng, editors, Implementing 
Reproducible Computational Research. Chapman and Hall/CRC. ISBN 978-1466561595

**lme4**
One of two packages most frequently used in R that support linear mixed effects
("Hierarchical") models.

Douglas Bates, Martin Maechler, Ben Bolker, Steve Walker (2015). Fitting Linear 
Mixed-Effects Models Using lme4. Journal of Statistical Software,67(1), 1-48. 
doi:10.18637/jss.v067.i01.

**MASS**
"Recommended" package included with default installations of R, includes many
utilities, tools, and functions. Includes functions to support extensions of
linear model frameworks, including hierarchical models and robust methods.
Formally an R package to support the excellent book "Modern Applied Statistics
with S", but in practice a core part of man R workflows.

Venables, W. N. & Ripley, B. D. (2002) Modern Applied Statistics with S. Fourth 
Edition. Springer, New York. ISBN 0-387-95457-0

**mblm**
"Median based linear models" implements Theil-Sens single median and Siegel 
repeated medians linear models, which are robust alternatives to simple linear
regression.

Lukasz Komsta (2019). mblm: Median-Based Linear Models. R package version 
0.12.1. https://CRAN.R-project.org/package=mblm.

**mgcv**
Used for generalized additive models (GAMs). GAMs allow flexible fitting of 
non-linear relationships. We use GAMs principally to model seasonal and diurnal 
patterns, but also to model dependence of water quality conditions on river 
flow, rainfall, temperature etc. The package also provides two alternative 
approaches to hierarchical models. The function `gamm()` allows fitting models 
with temporal autocorrelation.

Wood, S.N. (2017) Generalized Additive Models: An Introduction with R (2nd 
edition). Chapman and Hall/CRC.

**nlme**
One of two packages most frequently used in R that support linear mixed effects ("Hierarchical") models.

Pinheiro J, Bates D,  DebRoy S, Sarkar D, R Core Team (2020). nlme: _Linear and 
Nonlinear Mixed Effects Models_. R package version 3.1-148. 
URL:https://CRAN.R-project.org/package=nlme.


# Additional Packages Used

**readxl**
Hadley Wickham and Jennifer Bryan (2019). readxl: Read Excel Files. R package
version 1.3.1. https://CRAN.R-project.org/package=readxl.

**actuar**
Provides access to a variety of heavy tailed probability distributions,
especially convenient parameterizations of the Pareto distribution.

Dutang C, Goulet V, Pigeon M (2008). "actuar: An R Package for Actuarial 
Science." Journal of Statistical Software, 25(7), 38. 
https://www.jstatsoft.org/v25/i07.

**colorspace**
Zeileis A, Fisher JC, Hornik K, Ihaka R, McWhite CD, Murrell P, Stauffer R,
Wilke CO (2020). "colorspace: A Toolbox for Manipulating and Assessing Colors
and Palettes." Journal of Statistical Software 96(1), 1-49. doi:
10.18637/jss.v096.i01 (URL: https://doi.org/10.18637/jss.v096.i01).

Zeileis A, Hornik K, Murrell P (2009). "Escaping RGBland: Selecting Colors for
Statistical Graphics." Computational Statistics \& Data Analysis, 53(9),
3259-3270. doi: 10.1016/j.csda.2008.11.033 (URL:
https://doi.org/10.1016/j.csda.2008.11.033).

**corrplot**
Taiyun Wei and Viliam Simko (2017). R package "corrplot": Visualization of a 
Correlation Matrix (Version 0.84). Available from 
https://github.com/taiyun/corrplot.

**corrr**
Max Kuhn, Simon Jackson and Jorge Cimentada (2020). corrr: Correlations in R. 
R package version 0.4.3.https://CRAN.R-project.org/package=corrr.

**extrafont**
Winston Chang, (2014). extrafont: Tools for using fonts. R package version 
0.17. https://CRAN.R-project.org/package=extrafont

**fitdistrplus**
Tools for evaluating suitability of distributions for representing data and 
fitting distributions to data.

Delignette-Muller ML, Dutang C (2015). "fitdistrplus: An R Package for Fitting 
Distributions." Journal of Statistical Software, 64(4), 1–34. 
https://www.jstatsoft.org/v64/i04/.

**GGally**
Includes a nice interface to ggplot2 based pairs plots, with fine control of 
output.

Barret Schloerke, Di Cook, Joseph Larmarange, Francois Briatte, Moritz Marbach,
Edwin Thoen, Amos Elberg and Jason Crowley (2021). GGally: Extension to
"ggplot2". R package version 2.1.1. https://CRAN.R-project.org/package=GGally.

**ggpmisc**
Includes tools to allow positioning of annotations using absolute coordinates 
rather than "user" coordinates.

Pedro J. Aphalo (2021). ggpmisc: Miscellaneous Extensions to "ggplot2". R 
package version 0.3.9. https://CRAN.R-project.org/package=ggpmisc.

**ggthemes**
Jeffrey B. Arnold (2019). ggthemes: Extra Themes, Scales and Geoms for 'ggplot2'. R package version 4.2.0. https://CRAN.R-project.org/package=ggthemes

**Hmisc**
Frank E Harrell Jr, with contributions from Charles Dupont and many others. 
(2020). Hmisc: Harrell Miscellaneous. R package version 4.4-2. 
https://CRAN.R-project.org/package=Hmisc.

**lmerTest**
Kuznetsova A, Brockhoff PB, Christensen RHB (2017). "lmerTest Package: Tests 
in Linear Mixed Effects Models." Journal of Statistical Software, 82(13), 1–26.
doi: 10.18637/jss.v082.i13.

**lubridate**
Garrett Grolemund, Hadley Wickham (2011). Dates and Times Made Easy with 
lubridate. Journal of Statistical Software, 40(3), 1-25.
URL https://www.jstatsoft.org/v40/i03/.

**maxLik**
Provides tools for maximum likelihood estimation based on user-supplied
likelihoods. Our "LCensMeans" package depends on this package.

Henningsen A, Toomet O (2011). "maxLik: A package for maximum likelihood 
estimation in R." Computational Statistics, 26(3), 443-458. 
doi: 10.1007/s00180-010-0217-1, http://dx.doi.org/10.1007/s00180-010-0217-1.

**RColorBrewer**
Erich Neuwirth (2014). RColorBrewer: ColorBrewer Palettes. R package version 1.1-2. https://CRAN.R-project.org/package=RColorBrewer.

**readxl**
Hadley Wickham and Jennifer Bryan (2019). readxl: Read Excel Files. R package version 1.3.1. https://CRAN.R-project.org/package=readxl

**seacarb**
A partial R port of the standard seawater carbonate chemistry analytic package, 
`CO2SYS`, originally from Matlab, but since ported to other languages, including
R and Python. Because of it's non-R heritage, the user interface does not follow
common R conventions.

Jean-Pierre Gattuso, Jean-Marie Epitalon, Heloise Lavigne and James Orr (2021). 
seacarb: Seawater Carbonate Chemistry. R package version 3.2.16. 
https://CRAN.R-project.org/package=seacarb.

**Svglite**
Improved SVG and PDF output frrom R and (especially) ggplot.

Hadley Wickham, Lionel Henry, Thomas Lin Pedersen, T Jake Luciani, Matthieu 
Decorde and Vaudor Lise (2021). svglite: An "SVG" GraphicsDevice. R package 
version 2.0.0. https://CRAN.R-project.org/package=svglite.

**viridis**
Simon Garnier (2018). viridis: Default Color Maps from "matplotlib". R package
version 0.5.1. https://CRAN.R-project.org/package=viridis.

**zoo**
Zeileis A, Grothendieck G (2005). "zoo: S3 Infrastructure for Regular and 
Irregular Time Series." Journal of Statistical Software, 14(6), 1–27. 
doi: 10.18637/jss.v014.i06.

**VGAM**
Sophisticated package for vector generalized linear models. We used it 
principally to address model development in the context of heavy tailed 
distributions.

Yee TW (2021). VGAM: Vector Generalized Linear and Additive Models. R package 
version 1.1-5, 
[https://CRAN.R-project.org/package=VGAM](https://CRAN.R-project.org/package=VGAM).

Yee TW (2015). Vector Generalized Linear and Additive Models: With an
Implementation in R. Springer, New York, USA.

Yee TW (2010). "The VGAM Package for Categorical Data Analysis." Journal of 
Statistical Software, 32(10), 1–34. https://www.jstatsoft.org/v32/i10/.
