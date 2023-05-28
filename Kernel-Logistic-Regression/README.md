# Kernel Logistic Regression

### Goal
Mathematical formalisation. Implementation with R libraries. Implementation from scratch.

### Language
```R```

### Contents
1. Mathematical formalisation - Multiple binary logistic regression
2. Solving with glmnet
3. Solving with Newton-Raphson

### Libraries
* ```glmnet```
* ```dplyr```
* ```pracma```
* ```pROC```
* ```caret```

### Conclusion
In this study, we were able to apply the Newton-Raphson aglorithm and compare its results with functions already defined on R such as glmnet. We were able to see that we obtained values in the same orders of magnitude, and very good classification results. Above all, we were able to see the importance of working with α's rather than β's in the algorithm, because we have much less complex calculations to perform, and some can even be performed only once. So we gain enormously in performance.
