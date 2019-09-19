## Van Dyke, M. C. C., Teixeira, M. M., & Barker, B. M. (2019). 
## Fantastic yeasts and where to find them: the hidden diversity of dimorphic fungal pathogens. 
## Current opinion in microbiology, 52, 55-63.


## Harvey, J. T., Culvenor, J., Payne, W., Cowley, S., Lawrance, M., Stuart, D., & Williams, R. (2002). 
## An analysis of the forces required to drag sheep over various surfaces. 
## Applied Ergonomics, 33(6), 523-531.




## Bao, X., Mills, P. J., Rana, B. K., Dimsdale, J. E., Schork, N. J., Smith, D. W., ... & Ziegler, M. G. (2005). 
## Interactive effects of common β2-adrenoceptor haplotypes and age on susceptibility to hypertension and receptor function. 
## Hypertension, 46(2), 301-307.



## Using the istherecorrelation.csv 

import matplotlib.pyplot as plt
import pandas as pd


data=pd.read_csv(".../CS_Assignment-1-master/istherecorrelation.csv",sep=';')

plt.rcParams['figure.figsize'] = [10,10]

new_fig=plt.figure()


plt.subplot(2,1,1)
plt.plot(data.iloc[:,0],data.iloc[:,2])
plt.title('Beer consumption in the Nehterlands')
plt.xlabel('Year')
plt.ylabel('Beer (hectoliter)')


plt.subplot(2,1,2)
plt.plot(data.iloc[:,0],data.iloc[:,1])
plt.title('Beer consumption in the Nehterlands')
plt.xlabel('Year')
plt.ylabel('Wo')




![Drag Racing](/Users/Louis/Desktop/Seminars/CS_Assignment-1-master/Beer_consumption_NL.png)


