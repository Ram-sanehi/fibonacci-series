# fibonacci-series
<br>
def fibonacci(n):
<br>
    fib_series = []
    <br>
    a, b = 0, 1
    <br>
    for _ in range(n):
      <br>
      </br>  fib_series.append(a)
        <br>
        a, b = b, a + b
    <br>
    return fib_series

<br>
# Get user input for the number of terms in the series
num_terms = int(input("Enter the number of terms for the Fibonacci series: "))

<br>
# Call the function and print the Fibonacc
