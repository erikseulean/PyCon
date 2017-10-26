#### Performance vs Pythonic code

##### Perforamance aspects
- CPU time
- Memory
- I/O 

##### What to do?
- Plan
- Measure
- Monitor
- Identify bottlenecks and quick wins

##### Profiling tools:
- cProfile
- memory_profiler
- psutil
- dis

Profiling different ways to create lists, different data structures, copying elements, checking `in`, getting elements by index or using zip. 

##### Takeaways
- Defining slots on objects increase performance
- List comprehension in average runs faster

Copy vs deepcopy
- Copy - just the top level elements are being referenced
- Deepcopy - goes recursively and copies everything

Obviously deepcopy is slower but it also does more than copy. 

- Don'y predict, don't trust presumption and profile everything. It's easy to profile @method_level.\
Presentation: lukkol.pl/pyconuk2017-performance 