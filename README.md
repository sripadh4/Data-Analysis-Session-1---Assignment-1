# Data-Analysis-Session-1---Assignment-1

Calculate the moving average of an array over a window size

import numpy as np
a = [3, 5, 7, 2, 8, 10, 11, 65, 72, 81, 99, 100, 150]
a = np.array(a)
b = int(input("Window Size = "))

print (np.convolve(a, np.ones((b,))/b, 'valid'))
