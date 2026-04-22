Hey guys! So, for this project I had to do a bunch of changes to the dataset simply because I don't have the computational power necessary to even open the files.
As I explain in the Preprocessing document, I had to do chunk by chunk for the bigger dataset, otherwise colab would crash for me.
I chose to keep the numerical variables (even though I'm not sure if there were many or if any categorical ones) and remove the id variable since it wouldn't make any
difference to do the correlation. I replaced missing values with the median, and used correlation to pick just the 50 "best" variables. Once again, I'm not sure
if this is the best aproach, but this is what I was able to do giving my computational power. I think that either way, these 50 variables could be used for modeling,
and with Lasso and Ridge we could reduce even more the number of variables, so it's easier for us to explain what is going on. I also added on the document, how we can
get to that table he is expecting from us with 2 columns id and loss. I saved the test ids in a different file so aster finding the loss for each row we can just
concatenate everything since they are in the same order.
