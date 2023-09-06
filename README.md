# Ch1998
# First try
# Αποθετηριο ενος απλού κωδικα
*dat <- mtcars
*pmatrix=scale(dat)
*d=dist(pmatrix)
*c=hclust(d,method="ward.D2")
*plot(c)
*rect.hclust(c,k=3) 
*groups<-cutree(c,k=3)
*table(mtcars,groups)
*table(groups)
