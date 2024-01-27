# Algorithm
# Create an array that starts from the integer 1, ends at 20, incremented by 3.
import numpy as np
c = np.arange(1, 20, 3)
print(c)

#Create a new array of shape 3 with random numbers between 0 and 1.
import numpy as np
randarr = np.random.rand(3)
print(randarr)

# Create a 2 dimensional array (2-D)
import numpy as np
twodimarr = np.array([[10, 20, 45], [30, 12, 16], [42, 17, 56]])
print(twodimarr)

# Slice the twoD array to get the first two rows
slicedarr = twodimarr[0:2]
print("\n", slicedarr)

# Similarily, slice the twoD array to get the last two rows
slicedtwoDrows = twodimarr[1:3]
print("\n", slicedtwoDrows)

import numpy as np
a1 = np.array([[10, 20, 45], [30, 12, 16], [42, 17, 56]])
a2 = np.array([[15, 25, 45], [35, 11, 26], [12, 27, 26]])
print(f'a1:\n{a1}')
print(f'a2:\n{a2}')

# Stack the arrays vertically
vertstack = np.vstack((a1, a2))
print("\n", vertstack)

# Stack the arrays horizontally
horzstack = np.hstack((a1, a2))
print("\n", horzstack)

# Spilt  the arrays
spiltarr = np.array_split(a1, 4)
print("\n", spiltarr)

import numpy as np
X = np.array([[5, 7, 2], [4, 5,6], [7, 4, 2]])
Y = np.array([[4, 2], [6, 2], [4, 2]])
print(f'X:\n{X}')
print(f'Y:\n{Y}')
print("\n", np.matmul(X,Y))

import numpy as np
x = np.array([2, -1, -8])
y = np.array([3, 1, -2])
print(f'x:\n{x}')
print(f'y:\n{y}')

array_shape = x.shape
print("\n Array shape x:\n", array_shape)
print("\n Array Dimensions x:\n", x.ndim)

print( "\n Array Reshape x:\n", np.reshape(x, (3, 1)))
print( "\n Array Reshape y:\n", np.reshape(y, (3, 1)))
print("\n Array Dimensions y :\n", x.ndim)