# Python Mastery Plan – Weekly Checklist

---

## Month 1: Foundations & Data Structures

### Week 1: Python Data Model
- [ ] Read Fluent Python Ch. 1–3 (Data Model & Special Methods)
- [ ] Read source code:
  - [`collections.Counter`](https://github.com/python/cpython/blob/main/Lib/collections/__init__.py#L538)
  - [`collections.defaultdict`](https://github.com/python/cpython/blob/main/Lib/collections/__init__.py#L688)
- [ ] Task: Reimplement a mini-`Counter` class
- [ ] Take notes & summarize patterns learned

### Week 2: Sequences & Iterables
- [ ] Read Ch. 4–6 (Sequences, Slicing, Iterables)
- [ ] Read source code:
  - [`pandas.Series`](https://github.com/pandas-dev/pandas/blob/main/pandas/core/series.py#L128)
- [ ] Task: Implement a class that mimics `Series` slicing
- [ ] Take notes & summarize patterns learned

### Week 3: Dictionaries & Sets
- [ ] Read Ch. 7–9 (Mapping Types & Hash Tables)
- [ ] Read source code:
  - [`json.loads`](https://github.com/python/cpython/blob/main/Lib/json/__init__.py#L293)
  - [`dict` implementation](https://github.com/python/cpython/blob/main/Objects/dictobject.c)
- [ ] Task: Build a dict-like object with custom rules
- [ ] Take notes & summarize patterns learned

### Week 4: Functions as Objects
- [ ] Read Ch. 10–12 (First-class Functions, Decorators)
- [ ] Read source code:
  - [`torch.nn.Module`](https://github.com/pytorch/pytorch/blob/main/torch/nn/modules/module.py)
- [ ] Task: Write a custom decorator for logging training steps
- [ ] Take notes & summarize patterns learned

---

## Month 2: Objects, Idioms & Control Flow

### Week 5: Object-Oriented Python
- [ ] Read Ch. 13–15 (Closures, Objects, Classes)
- [ ] Read source code:
  - [`sklearn.base.BaseEstimator`](https://github.com/scikit-learn/scikit-learn/blob/main/sklearn/base.py)
- [ ] Task: Create a base class for your ML models
- [ ] Take notes & summarize patterns learned

### Week 6: Operator Overloading
- [ ] Read Ch. 16–18 (Special Methods & Protocols)
- [ ] Read source code:
  - [`torch.Tensor` dunder methods](https://github.com/pytorch/pytorch/blob/main/torch/_tensor.py)
- [ ] Task: Implement a `Vector` class with `+` and `*`
- [ ] Take notes & summarize patterns learned

### Week 7: Iterators & Generators
- [ ] Read Ch. 19–20 (Iterables, Generators, Coroutines)
- [ ] Read source code:
  - [`itertools`](https://github.com/python/cpython/blob/main/Lib/itertools.py)
- [ ] Task: Implement `take(n, iterable)` like `itertools.islice`
- [ ] Take notes & summarize patterns learned

### Week 8: Context Managers
- [ ] Read Ch. 21 (Context Managers & `with` statement)
- [ ] Read source code:
  - [`open()` implementation](https://github.com/python/cpython/blob/main/Lib/_pyio.py#L132)
  - [`torch.no_grad`](https://github.com/pytorch/pytorch/blob/main/torch/autograd/grad_mode.py#L75)
- [ ] Task: Write your own `with timer():` context manager
- [ ] Take notes & summarize patterns learned

---

## Month 3: Concurrency & Advanced Topics

### Week 9: Concurrency (Threads, Futures)
- [ ] Read Ch. 22 (Concurrent Futures)
- [ ] Read source code:
  - [`ThreadPoolExecutor`](https://github.com/python/cpython/blob/main/Lib/concurrent/futures/thread.py)
- [ ] Task: Implement a mini thread pool
- [ ] Take notes & summarize patterns learned

### Week 10: Async & Multiprocessing
- [ ] Read Ch. 23 (Asyncio)
- [ ] Read source code:
  - [`asyncio.gather`](https://github.com/python/cpython/blob/main/Lib/asyncio/tasks.py#L391)
- [ ] Task: Build async coroutines for reading large datasets
- [ ] Take notes & summarize patterns learned

### Week 11: Metaprogramming
- [ ] Read Ch. 24 (Descriptors & Metaclasses)
- [ ] Read source code:
  - [`torch.nn.Parameter`](https://github.com/pytorch/pytorch/blob/main/torch/nn/parameter.py)
- [ ] Task: Build a descriptor for validated attributes
- [ ] Take notes & summarize patterns learned

### Week 12: Wrapping Up
- [ ] Read Ch. 25–26 (Summary & Beyond)
- [ ] Read source code:
  - Any advanced PyTorch or NumPy class (e.g., [`numpy.ndarray`](https://github.com/numpy/numpy/blob/main/numpy/core/src/multiarray/ndarrayobject.c))
- [ ] Task: Write a mini-library combining learned concepts
- [ ] Take notes & summarize patterns learned
