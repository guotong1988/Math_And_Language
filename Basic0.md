P(A ∪ B) 用编程语言表示为
```python
def function_P(generated_random_int_1to100__A, generated_random_int_1to100__B):
    if generated_random_int_1to100__A > 40 or generated_random_int_1to100__B > 40: #两个事件有一个发生
        return 0.84
```
P(A ∩ B) 用编程语言表示为
```python
def function_P(generated_random_int_1to100__A, generated_random_int_1to100__B):
    if generated_random_int_1to100__A > 40 and generated_random_int_1to100__B > 40: #两个事件都发生
        return 0.36
```        
P(A) 用编程语言表示为
```python
def function_P(generated_random_int_1to100__A):
    if generated_random_int_1to100__A > 40: # A事件发生
        return 0.6    
```       
P(B) 用编程语言表示为
```python
def function_P(generated_random_int_1to100__B):
    if generated_random_int_1to100__B > 40: # B事件发生
        return 0.6   
```        
所以，有

P(A ∪ B) = P(A) + P(B) - P(A ∩ B)