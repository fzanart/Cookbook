# Working with Matplotlib

### 1. Import Library:

```python
import matplotlib.pyplot as plt
```

### 2. Create figure, axes:
```python
fig, ax1 = plt.subplots()
```
   2.1 Create secondary axis 
```python
ax2 = ax1.twinx()
```
### 3. Type of plots

   3.1 Line: ```ax.plot(x, y)```  
   3.2 Scatter  
   3.3 Histogram ...   

### 4. Basic colors:

### 5. Set title, axes names:
   ```python
   ax.set_title('Title')
   ax.set_xlabel('X data')
   ax.set_ylabel('Y1 data', color='g')
   ```
### 6. Plot

```
plt.show()
```