# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Comparing Two-Sample (Mean Cumulative Function) MCFs (Two-Sample Pseudo-Score Tests) Use mcfDiff (reda) With (In) R Software
install.packages("reda")
install.packages("ggplot2")
library("ggplot2")
library("reda")
mcfDiff = read.csv("https://raw.githubusercontent.com/timbulwidodostp/mcfDiff/main/mcfDiff/mcfDiff.csv",sep = ";")
# Estimation Comparing Two-Sample (Mean Cumulative Function) MCFs (Two-Sample Pseudo-Score Tests) Use mcfDiff (reda) With (In) R Software
mcf <- mcf(Recur(time, ID, event) ~ group, data = mcfDiff)
mcfDiff <- mcfDiff(mcf)
mcfDiff
# Comparing Two-Sample (Mean Cumulative Function) MCFs (Two-Sample Pseudo-Score Tests) Use mcfDiff (reda) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
