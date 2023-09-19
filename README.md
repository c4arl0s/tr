# tr

Snippets to use tr command 

# How to strip multiple spaces to one using sed?

First output:

```bash
ls /bin | grep kill
```
```bash
-rwxr-xr-x  1 root  wheel   134352 Dec  2  2022 kill
```

Solution:

```bash
ls /bin | grep kill | tr -s " "
```

Output:

```bash
-rwxr-xr-x 1 root wheel 134352 Dec 2 2022 kill
```
