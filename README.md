## Test task

Here are 2 problems. Feel free to solve any of them or both of them. The more, the better

## First problem

Your task is to write a **method that calculates the max possible quality of the computer cluster**. Cluster consists of one or more machines. Your method will take the following params

- array of the computers' `speeds`, e.g. [10, 5, 7, 12, 130]
- array of the computers' `reliabilities`, e.g. [3, 6, 8, 9, 10]
- and the maximum of the machines number that can be included into the cluster, e.g. 3

So, you are expected to write a method like this

```Ruby
def your_method_name(speeds, reliabilities, max_machines_number)
  # your code
end
```
Feel free to add any number of methods if you want to make the program more readable.

The quality for chosen set of machines is calculated the following way:

`quality = (sum of the speeds of the chosen machines) * (minimum reliabilities of the chosen machines)`


For example, you have the following input params:

```Ruby
speeds = [10, 5, 7, 12, 130]
reliabilities = [3, 6, 8, 9, 10]
max_number = 3
```

And you've chosen 1st (index 0), 3rd (index 2) and 4th (index 3) machines. Their characteristics are the corresponding values at arrays

The quality for that cluster will be (10 + 7 + 12) * (min(3, 8, 9)) = 29 * 3 = 87

NB:

- the sizes of `speeds` and `reliabilities` arrays are expected to have equal size
- the sizes are dynamic (don't assume that theay are always equal to 5, there can be more machines for chose)
- the `max_machines_number` might differ from one test case to another
- pay attention to word "maximum" in the `max_machine_number` parameter.

## Second problem

Create a ruby file so that the instructions at the bottom of the file give the specified result

```Ruby
# your code here

puts one.plus.one.equals              # => 2
puts two.plus.two.minus.three.equals  # => 1
```
