## Github Page

- Bulleted
- List

1. Numbered
2. List

### Sorting algorithms 
![Image](https://smylebifa.github.io/images/sorting_algorithms.png)


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

[Markdown](https://guides.github.com/features/mastering-markdown/)

[Jekyll Themes](https://jekyllrb.com/)
