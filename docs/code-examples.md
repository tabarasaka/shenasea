An example of a code block for Python:

```py
# Function to add two numbers
def add_two_numbers(num1, num2):
    return num1 + num2

# Example usage
result = add_two_numbers(5, 3)
print('The sum is:', result)
```

An example for Praat:

```c++
   To Intensity: 100, 0
   n = Get number of frames
   for i to n
      intensity = Get value in frame: i
      if intensity > 40
         time = Get time from frame: i
         writeInfoLine: "Onset of sound at: ", fixed$ (time, 3), " seconds."
         exit
      endif
   endfor
```