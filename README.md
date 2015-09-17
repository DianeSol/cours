# cours
#comprendre le fonctionnement de a.means 


import numpy as np
a = np.array([3,2])
a.mean 
print a.mean()


#np.median

import numpy as np
print np.median([3,2])

#test d'une np.inner

import numpy as np
v1 = np.arange(6)
v2 = np.arange(6)*2

np.inner(v1,v2)
print np.inner(v1,v2)
