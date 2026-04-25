# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Least square dummy variable model (LSDV) Use Lsdv (lsdv) With (In) R Software
install.packages("remotes")
remotes::install_github("cran/lsdv")
library("lsdv")
# Estimation Least square dummy variable model (LSDV) Use Lsdv (lsdv) With (In) R Software
Lsdv = read.csv("https://raw.githubusercontent.com/timbulwidodostp/Lsdv/main/Lsdv/Lsdv.csv",sep = ";")
Lsdv <- Lsdv(Lsdv ~ Lsdv_1 + Lsdv_2 + Lsdv_3, Lsdv, n = 6, t = 3)
summary(Lsdv)
# Least square dummy variable model (LSDV) Use Lsdv (lsdv) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished