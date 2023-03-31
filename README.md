## Hi there! 👋

### I'm currently enrolled in Digital Crafts for Full-Stack Web Development. 

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ETH1Elohim&theme=tokyonight)

## Big O Notation
### The longest amount any function is going to take given the worst case scenario of input

### Big O Table:
| Notation   | Name(time)  | Speed      |
|------------|-------------|------------|
| O(1)       | constant    | Instant    |
| O(logn)    | logarithmic | Fast       |
| O(n)       | linear      | Average    |
| O(nlogn)   | nlogn       | Ok         |
| O(n2)      | quadratic   | Slow       |
| O(kn)      | exponential | Get Out... |

<img src="https://miro.medium.com/v2/resize:fit:1650/1*iQkFjNn02oogc2Yv27-pyQ.png" alt="" title="BigO Visual">

### Constant - O(1):
Accessing elements in an array (by index) or object (by key) is constant
.push() & .pop()
Saving data to a variable
Accessing data in an array
Accessing key information
Math equations & comparisons

### Logarithmic - O(logn):
With each iteration, the input size decreases by a constant multiple factor
^every time, you're cutting down the amount you have to search through by 1/2
Example is binary search algorithm to find a particular element in a one-dimensional data-structure.

### Linear - O(n):
Execution time is directly proportional to the size of the input
Searching an element or finding the min/max value of an array
.shift() & .unshift()

### nlogn - O(nlogn):


### Quadratic - O(n2):
for (let i = 0; i < 10; i++){ //* n^2
     * performs 10x
    for(let j = 0; j < 10; j++){
     * performs 100x
    }
}

Exponential:
2^8

-------------------------------------------------------------------------------------------------------

### All of the Bigs
#### Big Omega - Best case
Operational complexity of your ideal input (if all things go well, it's going to run quickly. Best case).
#### Big Theta - Average case
#### Big O - Worst Case
generally care about Big O. Want to know the slowest possible time if I run this function.
