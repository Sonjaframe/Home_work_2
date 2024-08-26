# Home_work_2
#задача1
 def task_func():
    a: int = 5
    b: float = 3.14
    c: str = 'Hello'
    d: list = [1,2,3,4,5]
    f: bool = True

    return a,b,c,d,f
print(task_func())

#задача2
def task_func(a=(1,2,3,4,5,8,13,21)):
    return a[:3]
print(task_func())

#задача3
def task_func(x):
    return x*x
print(task_func(5))
