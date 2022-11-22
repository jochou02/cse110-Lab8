# Lab 8 - Starter

John Chou A16410755

1) Within a Github action that runs whenever code is pushed. This makes more sense to automate this because manually running them may cause issues such as if someone forgets to do it. Running them after all developement is completed is obviously a terrible idea since it doesn't allow testing throughout the process. 

2) No, since end to end testing is focused more on higher level testing ("that involve emulating user actions from start to finish"), rather than individual functions. 

3) No, because messaging is not very simple and surely requires interaction with other components on the application level. 
   
4) Yes, because calculating max message length does not require any interaction with other parts of the application, so unit testing should work for this feature.