# OSA_multivariate_dists
Additional multivariate distributions with estimation of one-step-ahead (OSA) residuals.



This installs the contributed code:
```R
TMB:::install.contrib("https://github.com/vtrijoulet/OSA_multivariate_dists/archive/main.zip")
```

After that you can use it in a TMB model with:
```C++
#include <TMB.hpp>
#include <OSA_multivariate_dists/dists.hpp>
using contrib::dists::;
```
