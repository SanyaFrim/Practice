import numpy as np
x = np.array([1, 2, 3, 4, 5])
y = np.array([2.5, 3.5, 4.5, 5.5, 6.5])
A = np.vstack([x, np.ones(len(x))]).T
m, c = np.linalg.lstsq(A, y, rcond=None)[0]
print("Уравнение линейной аппроксимации: y = {}x + {}".format(m, c))
