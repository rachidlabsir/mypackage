# Top N Items

This function returns the top N items from a list in descending order.

## Usage

```python
from top_n import top_n

items = [8, 3, 2, 7, 4]
n = 3
result = top_n(items, n)
print(result)  # Output: [8, 7, 3]

Arguments

    items (array): A list or array-like object containing numerical values.
    n (int): The number of top items to return.

Returns

    array: A list containing the top N items from the input list, sorted in descending order.

Details

The function first sorts the input list in ascending order using a bubble sort algorithm. It then selects the last N items from the sorted list and reverses them to obtain the top N items in descending order.
Example

python

print(top_n([8, 3, 2, 7, 4], 3))  # Output: [8, 7, 3]

kotlin


Replace `your_package_name` with the actual name of your package when you add this content to your `README.md` file.