# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# computing standardized mean differences (SMD) Use smd With (In) R Software
install.packages("smd")
library("smd")
smd = read.csv("https://raw.githubusercontent.com/timbulwidodostp/smd/main/smd/smd.csv",sep = ";")
# Estimation computing standardized mean differences (SMD) Use smd With (In) R Software
smd_1 <- smd$smd_1
smd_2 <- smd$smd_2
smd_3 <- smd$smd_3
smd_4 <- smd$smd_4
smd_5 <- smd$smd_5
smd <- smd$smd
smd(smd_1, smd, std.error = TRUE)
smd(smd_2, smd, std.error = TRUE)
smd(smd_3, smd, std.error = TRUE)
smd(smd_4, smd, std.error = TRUE)
smd(smd_5, smd, std.error = TRUE)
# computing standardized mean differences (SMD) Use smd With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished