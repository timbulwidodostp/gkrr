# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Gaussian Kernel Robust Regression (GKRReg) Use gkrr (gkrreg) With (In) R Software
install.packages("gkrreg")
library("gkrreg")
# Estimate Gaussian Kernel Robust Regression (GKRReg) Use gkrr (gkrreg) With (In) R Software
gkrr = read.csv("https://raw.githubusercontent.com/timbulwidodostp/gkrr/main/gkrr/gkrr.csv",sep = ";")
gkrr <- gkrr(gkrr ~ gkrr_, data = gkrr, sigma_method = "s3")
summary(gkrr)
# Gaussian Kernel Robust Regression (GKRReg) Use gkrr (gkrreg) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished