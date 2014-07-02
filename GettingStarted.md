Given an array of values:

```
int[] values = new int[] { 1, 2, 3, 2, 1 };
```

You can find the equilibrium index like this:

```
EquilbriumIndex mEquilbriumIndex = new EquilbriumIndex();
int equilibriumIndex = mEquilbriumIndex.find(values);
System.out.println("Equilbrium Index == " + equilibriumIndex);
```

And get the expected result of 2.

If you supply an array with no equilibrium index, the function will return -1.