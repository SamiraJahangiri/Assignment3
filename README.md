# Assignment3
Matrix, Data Table, Data Frame.


#cbind function

Name<- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Berine")
ABC_political_poll_results<- c(4,62,51,21,2,14,15)
NBC_political_poll_results<- c(12, 75, 43, 19, 1, 21,19)
Results<- cbind(Name, ABC_political_poll_results, NBC_political_poll_results)
Results

#colMeans function

Name<- c("Jeb", "Donald", "Ted", "Marco", "Carly", "Hillary", "Berine")
ABC_political_poll_results<- c(4,62,51,21,2,14,15)
NBC_political_poll_results<- c(12, 75, 43, 19, 1, 21,19)
results.df<- data.frame(Name, ABC_political_poll_results, NBC_political_poll_results)
results.df
meansvec<- colMeans(results.df[,c(2:3)])
meansvec

