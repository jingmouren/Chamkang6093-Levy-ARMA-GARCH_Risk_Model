# Lévy - ARMA - GARCH Risk Model Implement and its Evaluation

## Descriptions
* <font face='Times New Roman'>Modeled assets’ return series with ARMA-GARCH model and convolution-closed distributions, e.g., Generalized Hyperbolic or Normal Inverse Gaussian, to get 1-step forecasted p.d.f.s of returns.</font>
* <font face='Times New Roman'>Evaluated the effectiveness of this model by some risk measures like CVaR and coverage tests.</font>

## Notes
* <em>_snp_tickers_sectors.csv</em>&nbsp;&nbsp;is found at https://en.wikipedia.org/wiki/List_of_S%26P_500_companies (In this project, last change was on April 21, 2021).
* In the part of tests, the code about coverage tests is mainly from the library named "vartests" (Link: https://github.com/rafa-rod/vartests) with some small minor modifications.
* In the part of fitting Lévy - ARMA - GARCH model, Some lines of the code are omitted due to potential copyright issue, where some of them are from private code of our professor and his assistant. You can try to incorporate NIG and GH distributions into some other open-source ARMA - GARCH code as an alternative if you are interested in this part. Sorry for the incovenience.

## Main Reference
* <a style='color: black;' href='https://econpapers.repec.org/article/taflstaxx/v_3a47_3ay_3a2018_3ai_3a15_3ap_3a3616-3639.htm' target='_blank'>https://econpapers.repec.org/article/taflstaxx/v_3a47_3ay_3a2018_3ai_3a15_3ap_3a3616-3639.htm</a>
* <a style='color: black;' href='https://www.semanticscholar.org/paper/Backtesting-Value-at-Risk-Models-Nieppola/5fbbf20d7f3e03c4da3a9d33aa618fdfe5d0a9d4' target='_blank'>https://www.semanticscholar.org/paper/Backtesting-Value-at-Risk-Models-Nieppola/5fbbf20d7f3e03c4da3a9d33aa618fdfe5d0a9d4</a>
* <a style='color: black;' href='https://link.springer.com/book/10.1007/978-0-387-77827-3' target='_blank'>https://link.springer.com/book/10.1007/978-0-387-77827-3</a>
