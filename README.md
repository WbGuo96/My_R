# My_R
library(ggplot2)
plot(1:5)
plot(c(0:5), col = 'white')
text(2,4, labels = 'font=1:正常字体（默认）', font = 1)
text(3,3, labels = 'font=2:粗体字体',font = 2)
text(4,2,labels = 'font=3:斜体字体',font = 3)
text(5,1,labels = 'font=4:粗斜体字体',font=4)
