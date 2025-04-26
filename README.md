import time 
def sum_of_squares(numbers):
built-in sum function
return sum([x**2 for x in numbers])

# Example Usage
numbers = [1,2,3,4]
start_time = time.time()
result=sum_of_squares(numbers)
end_time=time.time()
print(f"Result:{result}")
print(f"Execution time:{end_time-start_time}seconds")

