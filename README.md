# Multithreaded Sorting using POSIX Threads (C)

## 📖 Overview
This project implements a **multithreaded sorting algorithm** in C using **POSIX threads (pthreads)**.  
The array is divided into multiple parts, each sorted concurrently by a thread, and finally merged.

## ✨ Features
- Parallel sorting using **QuickSort**.
- Demonstrates **multithreading, synchronization, and merging**.
- Configurable number of threads (`THREAD_MAX`).
- Works on large datasets efficiently.

## ⚙️ How It Works
1. Array is divided into equal parts.
2. Each thread sorts a part independently.
3. Sorted parts are merged to form the final sorted array.

## 🚀 Run the Project
```bash
# Compile
gcc src/multithreaded_sort.c -o multithreaded_sort -lpthread

# Run
./multithreaded_sort
