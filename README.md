# freestl
Post-modern C++23+ Free standing STL reimplementation

## Roadmap for ```std::vector```

1. Major pre-C++11 functionalities
2. Perfect forwarding
3. Concepts as contraints
4. constexpr support
5. Support rvalue vector itself
6. Support move in re-allocation
7. Offer strong exception safety guarantee


## Considerations of ```std::vector```

1. How to make lock step progresses between container and algorithms
2. How many utilities, but std and details would be needed along each milestone
3. Maybe start with something simpler first, like pair, tuple, array, etc.

## Considerations for modern C++ style

1. Use consteval instead of constexpr wherever it is applicable (https://github.com/microsoft/STL/discussions/3604)
2. No more legacy iterator_traits, (https://quuxplusone.github.io/blog/2023/01/27/sinkerator/)

## Why post-modern C++ implemenation of STL (partial)

1. Experiment new post-modern C++ programming style. 
2. Design library the right way
3. 
