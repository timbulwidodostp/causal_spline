# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Nonlinear causal dose-response estimation via restricted cubic splines Use causal_spline (CausalSpline) With (In) R Software
install.packages("CausalSpline")

library("CausalSpline")
# Estimation Nonlinear causal dose-response estimation via restricted cubic splines Use causal_spline (CausalSpline) With (In) R Software
causal_spline = read.csv("https://raw.githubusercontent.com/timbulwidodostp/causal_spline/main/causal_spline/causal_spline.csv",sep = ";")
causal_spline <- causal_spline(outcome ~ treatment | confounders_1 + confounders_2 + confounders_3, data = causal_spline_, method = "ipw", df_exposure = 5)
causal_spline_ <- causal_spline(outcome ~ treatment | confounders_1 + confounders_2 + confounders_3, data = causal_spline_, method = "gcomp", df_exposure = 5)
summary(causal_spline)
summary(causal_spline_)
# Nonlinear causal dose-response estimation via restricted cubic splines Use causal_spline (CausalSpline) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished