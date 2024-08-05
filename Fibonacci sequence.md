
```
{x,sum -2#x}/[19; 1 1]
```

Here, the first 19 elements of the fibonacci sequence are printed. The logic is simple,

for the parameter `x` (list in tihs case) sum it's last two indices `sum -2#x` and append the sum to the end of x as shown by the `,` operator, the final function becomes `{x,sum -2#x}`

we do this a running `19` number of times using the `/` operator.

`[1 1]` is the starting list to begin our fibonacci sequence with.

neat! isn't it?
