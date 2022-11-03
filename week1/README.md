The `*-sol.ipynb` files contain "solutions" mainly for the coding part. Most of the "comment on your finding" or textual answer part is empty. 

The code snippets provided are not **the** solution, they are just one possible way to achive the goal. If your time permits explore <!--the `statsmodels.graphics` module, and--> the `pandas`, `statsmodels`, and `seaborn` packages. 
<!--If you are familiar with `ggplot2` from `R`, then `plotnine` might be your favorite choice. -->

You can fit linear regression multiple way. We have seen a few: `np.linalg.lstsq`, or with a somewhat longer code using `np.linalg.qr`. 

`statsmodels.api.formula.ols` provides a convinient way with summaries of the result.

The `sklearn` library also has an implementation in the `sklearn.linear_model` submodule, this estimator is called `LinearRegression`. Its purpuse and interface are somewhat different from the `statsmodels` implementation, e.g. you can't get the statistical summary of the fit. However, the `yellowbrick` package can help to visualize the fit, it can produce diagnostic plots easily.
