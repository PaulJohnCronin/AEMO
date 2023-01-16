# AEMO Original
[Australian Energy Market Operator](https://aemo.com.au/en) power prediction project.

My [contribution](https://github.com/the-rahul-kumar/UNSW-Group-C-Project/tree/main/src/Paul) to this project.

# AEMO Redux
During the original AEMO project, I was tasked with the linear model analysis, which worked well, but did not have better forecast accuracy than AEMO.  I wished to see if I could "beat AEMO", so went back and implement an LSTM + Dense neural network, that was aware of each state's instantaneous photovoltaic production, and incorporated that.  The result was that the two models developed beat the AEMO predictions in 3 Australian states out of 4.

This code calls for a dataset too large to store in GitHub.  It is accessible at: https://drive.google.com/file/d/1N5TstubZmZhPW5k9N-ZdCScoit_O9F5G/view?usp=sharing.
