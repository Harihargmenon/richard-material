---
title: "C Arrays"
---

# Arrays

## Introduction

An array is a collection of items stored at contiguous memory locations. The idea is to store multiple items of the same type together. This makes it easier to calculate the position of each element by simply adding an offset to a base value, i.e., the memory location of the first element of the array (generally denoted by the name of the array).

```cpp
// An array of 10 integers
int arr[10];
```

## Accessing Array Elements

An element in an array can be accessed by using the index of the element. The following example accesses the third element in the array `arr`:

```cpp
// accessing array elements
arr[2] = 10;
```
