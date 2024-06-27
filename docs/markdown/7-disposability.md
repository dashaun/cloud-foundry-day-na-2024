### 7. Disposability

| Then | Now |
|:----:|:----:|
| Assume reliable infrastructure | Assume fragile infrastructure |
| Minutes to get to steady state | Scale up and down in seconds |

```bash
cf scale hello-world -i 3

cf scale hello-world -i 1
```