## Sorting algorithms 


1. Bubble sort
2. Shaker sort


Bubble sort
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


### Bubble sort

```markdown
void BubbleSort(vector<int>& values) {
  for (size_t idx_i = 0; idx_i + 1 < values.size(); ++idx_i) {
    for (size_t idx_j = 0; idx_j + 1 < values.size() - idx_i; ++idx_j) {
      if (values[idx_j + 1] < values[idx_j]) {
        swap(values[idx_j], values[idx_j + 1]);
      }
    }
  }
}
```
