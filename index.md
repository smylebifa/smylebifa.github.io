## Sorting algorithms 

| № |  Algorithm  | Time complexity (Worst) | Time complexity (Average) | Time complexity (Best) | Space compexity |
|:-:|:-----------:|:-----------------------:|:-------------------------:|:----------------------:|:---------------:|
| 1 | Bubble sort |          O(n2)          |            O(n2)          |           O(n)         |      O(1)       |
| 2 | Shaker sort |          O(n2)          |            O(n2)          |           O(n)         |      O(1)       |

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

### Shaker sort

```markdown
void ShakerSort(vector<int>& values) {
  if (values.empty()) {
    return;
  }
  int left = 0;
  int right = values.size() - 1;
  while (left <= right) {
    for (int i = right; i > left; --i) {
      if (values[i - 1] > values[i]) {
        swap(values[i - 1], values[i]);
      }
    }
    ++left;
    for (int i = left; i < right; ++i) {
      if (values[i] > values[i + 1]) {
        swap(values[i], values[i + 1]);
      }
    }
    --right;
  }
}
```
