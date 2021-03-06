# Scientific Computing with C++20 and Beyond

A three part technical talk I delivered in the spring of 2020 for the Numerical Algorithms Group, discussing emerging modern C++ design patterns, new language and library extensions for C++20, and experimental library extensions under consideration for C++23.

## Order of Topics

### Part One
* Generic programming
* concepts (C++20)
* Reference types
* span (C++20)

### Part Two
* mdspan (C++23*)
* mdarray (C++23*)

### Part Three
* blas (C++23*)
* linear_algebra (C++23*)


## References (updated: 6 March 2021)

### Language and Library Extensions

#### concepts
* Stroustrup, B., Sutton, A. (editors). [A Concepts Design for the STL](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2012/n3351.pdf). WG21 N3351. January 2012.
* *A final draft of the [Concepts Technical Specification](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2015/n4549.pdf)*. WG21 N4549. ISO/IEC TS 19217. July 2015.
* Sutton, A. [Introducing Concepts](http://accu.org/index.php/journals/2157). ACCU Overload, October 2015.
* Sutton, A. [Defining Concepts](http://accu.org/index.php/journals/2198). ACCU Overload, February 2016.
* Sutton, A. [Overloading with Concepts](https://accu.org/index.php/journals/2316). ACCU Overload, December 2016.
* Stroustrup, B. [Concepts: The Future of Generic Programming](https://www.stroustrup.com/good_concepts.pdf). WG21 P0557R1. January 2017.
* Stroustrup, B. [CppCon]. (2018, September 24). *Concepts: The Future of Generic Programming (the future is here)*. [Video]. [www.youtube.com/watch?v=HddFGPTAmtU](https://www.youtube.com/watch?v=HddFGPTAmtU)
* Sutton, A. [CppCon]. (2018, September 27). *Concepts in 60: Everything You Need to Know and Nothing You Don't*. [Video]. [www.youtube.com/watch?v=ZeU6OPaGxwM](https://www.youtube.com/watch?v=ZeU6OPaGxwM)

#### span
* MacIntosh, N., Lavavej, S. [span: Bounds-Safe Views for Sequences of Objects](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2018/p0122r7.pdf). WG21 P0122R7. March 2018.
* Corentin, J. "A Can of span". *cor3ntin*, 14 May 2018. [www.cor3ntin.github.io/posts/span](https://cor3ntin.github.io/posts/span/)
* Brindle, T. [Usability Enhancements for std::span](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1024r3.pdf). WG21 P1024R3. February 2019.
* Corentin, J., Carter, C. [Range Constructor for std::span](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1394r3.pdf). WG21 P1394R3. August 2019.

#### mdspan
* Mendakiewicz, L., Sutter, H. [Multidimensional Bounds, Index and array_view](http://www.open-std.org/Jtc1/sc22/wg21/docs/papers/2014/n3851.pdf). WG21 N3851. January 2014.
* Hollman, D., et al. [mdspan in C++: A Case Study in the Integration of Performance Portable Features into International Language Standards](https://sc19.supercomputing.org/proceedings/workshops/workshop_files/ws_p3hpc114s2-file1.pdf). *White Paper*. ACM/IEEE Supercomputing Conference, November 2019.
* Hollman, D., et al. *Modern C++ in Computational Science*. Sandia National Laboratories, 2019. [www.osti.gov/servlets/purl/1602625](https://www.osti.gov/servlets/purl/1602625). Accessed February 2020.
* Trott, C., et al. [mdspan: A Non-Owning Multidimensional Array Reference](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2020/p0009r10.html). WG21 P0009R10. February 2020.
* Reference implementation: [www.github.com/kokkos/mdspan](https://github.com/kokkos/mdspan)

#### mdarray
* Hollman, D., et al. [mdarray: An Owning Multididmensional Array Analog of mdspan](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1684r0.pdf). WG21 P1684R0. May 2019.
* Reference implementation: [www.github.com/kokkos/mdarray](https://github.com/kokkos/mdarray)

#### blas
* Hoberock, J. [Integrating Executors with Parallel Algorithms](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1019r2.pdf). WG21 P1019R2. January 2019.
* Hoemmen, M., et al. [Historical Lessons for C++ Linear Algebra Library Standardization](https://isocpp.org/files/papers/p1417r0.pdf). WG21 P1417R0. January 2019.
* Hoemmen, M., et al. [A Free Function Linear Algebra Interface Based on the BLAS](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1673r1.html). WG21 P1673R1. June 2019.
* Hoemmen, M., et al. [Evolving a Standard C++ Linear Algebra Library from the BLAS](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1674r0.md). WG21 P1674R0. June 2019.
* Reference implementation: [www.github.com/kokkos/stdBLAS](https://github.com/kokkos/stdBLAS)

#### linear_algebra
* Davidson, G. [Meeting Cpp]. (2018, November 15). *Standardizing a Linear Algebra Library*. [Video]. [www.youtube.com/watch?v=cIPmhIiY68U](https://www.youtube.com/watch?v=cIPmhIiY68U)
* Davidson, G., Steagall, B. [What Do We Need from a Linear Algebra Library?](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p1166r0.pdf) WG21 P1166R0. January 2019.
* Steagall, B. [CppNow]. (2019, May 7). *Linear Algebra for the Standard C++ Library*. [Video]. [www.youtube.com/watch?v=CslK9tu9ssA](https://www.youtube.com/watch?v=CslK9tu9ssA)
* Davidson, G., Steagall, B. [A Proposal to Add Linear Algebra Support to the C++ Standard Library](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2020/p1385r6.pdf). WG21 P1385R6. March 2020.
* Reference implementation: [www.github.com/BobSteagall/wg21](https://github.com/BobSteagall/wg21)

### General Topics

#### Structure and Operations of ISO C++
* Van Winkel, JC., et al. [Operating Principles for Evolving C++](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2017/p0559r0.pdf). WG21 P0559R0. January 2017.
* Hinnant, H. [Direction for ISO C++](http://www.open-std.org/jtc1/sc22/wg21/docs/papers/2019/p0939r4.pdf). WG21 P0939R4. October 2019.

#### Interface Design
* Meyers, S. [The Most Important Design Guideline?](https://www.aristeia.com/Papers/IEEE_Software_JulAug_2004.pdf) IEEE Software, July-August, 2004.
* Meyers, S. [ConFu] (2014, November 13). *The Most Important Design Guideline*. [Video]. [www.aristeia.com/videos](https://www.aristeia.com/videos/confu-themostkimportantdesignguideline.mp4)
* Winters, T. "Revisiting Regular Types." *Abseil Blog*, 31 May 2018. [www.abseil.io/blog/20180531-regular-types](https://abseil.io/blog/20180531-regular-types)
* Winters, T. [CppCon]. (2018, September 24). *Modern C++ API Design (part 1 of 2)*. [Video]. [www.youtube.com/watch?v=xTdeZ4MxbKo](https://www.youtube.com/watch?v=xTdeZ4MxbKo)
* Winters, T. [CppCon]. (2018, September 24). *Modern C++ API Design (part 2 of 2)*. [Video]. [www.youtube.com/watch?v=tn7oVNrPM8I](https://www.youtube.com/watch?v=tn7oVNrPM8I)

#### Generic Programming
* *Online collection of books, papers, class notes, and source code from Alexander Stepanov:* [www.stepanovpapers.com](http://www.stepanovpapers.com/)
* Musser, D., Stepanov, A. [Generic Programming](http://stepanovpapers.com/genprog.pdf). *White Paper*. ISSAC, July 1988.
* Dehnert, J., Stepanov, A. [Fundamentals of Generic Programming](http://stepanovpapers.com/DeSt98.pdf). *White Paper*. Report of the Dagstuhl Seminar on Generic Programming, April 1998.
* Stepanov, A. [Aaron Gray]. (2002, January 30). *STL and Its Design Principles*. [Video]. [www.youtube.com/watch?v=1-CmNNp5eag](https://www.youtube.com/watch?v=1-CmNNp5eag)
* Stepanov, A., McJones, P. *[Elements of Programming](https://www.amazon.com/Elements-Programming-Stepanov-Alexander-McJones-dp-B00BUFKPJK/dp/B00BUFKPJK/)*. Addison-Wesley, June 2009.
* Stepanov, A., Rose, D. *[From Mathematics to Generic Programming](https://www.amazon.com/Mathematics-Generic-Programming-Alexander-Stepanov/dp/0321942043/)*. Addison-Wesley, November 2014.
* Parent, S. [Pacific++]. (2018, October 18). *Generic Programming*. [Video]. [www.youtube.com/watch?v=iwJpxWHuZQY](https://www.youtube.com/watch?v=iwJpxWHuZQY)
* Website for "Elements of Programming": [www.elementsofprogramming.com](http://elementsofprogramming.com/)
* Website for "From Mathematics to Generic Programming": [www.fm2gp.com](http://fm2gp.com/)
