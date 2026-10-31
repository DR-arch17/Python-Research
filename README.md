# Python-Research
My scientific computing projects
import numpy as np
import matplotlib.pyplot as plt
import scipy
import pandas as pd

print("我的第一个 GitHub 项目！")

x = np.linspace(0, 10, 100)
y = np.sin(x)

plt.plot(x, y)
plt.xlabel("Time")
plt.ylabel("Amplitude")
plt.title("My First Scientific Plot")
plt.grid()
plt.show()