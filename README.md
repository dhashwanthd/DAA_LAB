# Search Algorithm Performance Analysis

## Overview

This project compares the performance of two searching algorithms:

- Interpolation Search
- Binary Search

The program searches for a target element in a sorted array and measures:

- Execution time
- Number of comparisons
- Search efficiency for different input sizes

The project demonstrates how both algorithms perform under varying dataset sizes.

---

## Features

- Implementation of Interpolation Search
- Implementation of Binary Search
- Performance analysis using execution time
- Comparison of the number of comparisons
- Works with randomly generated sorted arrays

---

## Algorithms Used

### Binary Search
- Works on sorted arrays.
- Divides the search space into two halves repeatedly.
- Time Complexity:
  - Best Case: **O(1)**
  - Average Case: **O(log n)**
  - Worst Case: **O(log n)**

### Interpolation Search
- Works on sorted and uniformly distributed data.
- Estimates the probable position of the target before searching.
- Time Complexity:
  - Best Case: **O(1)**
  - Average Case: **O(log log n)**
  - Worst Case: **O(n)**

---

## Project Structure

```
Search-Algorithm-Performance-Analysis/
│
├── main.py
├── README.md
├── requirements.txt
├── LICENSE
└── images/
```

---

## Requirements

- Python 3.x

No external libraries are required.

---

## How to Run

1. Clone the repository

```bash
git clone https://github.com/yourusername/Search-Algorithm-Performance-Analysis.git
```

2. Navigate to the project folder

```bash
cd Search-Algorithm-Performance-Analysis
```

3. Run the program

```bash
python main.py
```

---

## Sample Output

```
Array: [2, 5, 10, 15, 23, 35, 48, 60, 75, 90, 105, 120]
Searching for: 35
Found at index: 5
Comparisons: 1

Size      IS Time(ms)   BS Time(ms)   IS Comparisons   BS Comparisons
---------------------------------------------------------------------
1000      0.0021        0.0038               2                9
5000      0.0024        0.0042               3               12
10000     0.0026        0.0046               3               13
```

---

## Future Improvements

- Add graphical performance comparison using Matplotlib.
- Compare additional search algorithms such as Linear Search and Jump Search.
- Export benchmark results to CSV.
- Create an interactive user interface.

---

## Author

**Your Name**

---

## License

This project is licensed under the MIT License.