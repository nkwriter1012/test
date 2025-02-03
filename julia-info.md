# Information about the Julia Language 

[Julia Homepage](https://julialang.org/)

# Julia Language Overview

Julia was created at MIT and first released in 2012. It was designed specifically for high-performance numerical and scientific computing, aiming to combine the ease of use of Python with the speed of C.

Key Features:
- Just-in-time (JIT) compilation for high performance
- Dynamic typing with optional type declarations
- Multiple dispatch (functions choose behavior based on argument types)
- Excellent support for linear algebra and scientific computing
- Native support for parallel and distributed computing
- Easy integration with C, Python, and other languages
- Interactive REPL with rich features and modes
- Free, open source (MIT licensed)
- Strong package ecosystem for scientific computing

Julia solves the "two-language problem" where researchers prototype in a slow language (like Python) then rewrite in a fast language (like C++) for production. With Julia, the same code can be used for both prototyping and production.

Version 1.0 was released in 2018, marking API stability. As of 2024, Julia is used extensively in scientific computing, data science, machine learning, and numerical analysis.

## Julia Naming Conventions

- Variables/Functions: lowercase, optionally with underscores (`mass`, `particle_count`)
- Types/Modules/Packages: CamelCase (`Float64`, `LinearAlgebra`)
- Constants: UPPERCASE with underscores (`PLANCK_CONSTANT`)
- Unicode symbols allowed (α, β, γ)

Common Restrictions:
- Cannot start with a number (`2mass` invalid, use `mass2`)
- No hyphens/dashes (`particle-mass` invalid, use `particle_mass`)
- No spaces (`particle mass` invalid, use `particle_mass`)
- No special characters except underscore (`mass$` invalid)

Note: Julia is case-sensitive, so `mass` and `Mass` are different variables.

## Learning Resources 
This course is intended to be self-contained but here are some resources you might find helpful.  You can also ask LLMs (aka chatbots) about Julia.  

- [Julia 1.11 Documentation](https://docs.julialang.org/en/v1/)
- [Get Started with Julia](https://julialang.org/learning/)
- [Julia for Talented Amateurs](https://www.youtube.com/c/juliafortalentedamateurs/videos)
- [Introduction to Computational Thinking](https://ocw.mit.edu/courses/18-s191-introduction-to-computational-thinking-fall-2020/)
- [Julia Programming Tutorial](https://www.matecdev.com/posts/julia-tutorial-science-engineering.html)
- [YouTube: The Julia Programming Language](https://www.youtube.com/user/JuliaLanguage)
- [Julia Discourse](https://discourse.julialang.org/)

## Propoganda
- [A programming language to heal the planet together: Julia | Alan Edelman | TEDxMIT](https://www.youtube.com/watch?v=qGW0GT1rCvs)
- [The Unreasonable Effectiveness of Multiple Dispatch | Stefan Karpinski | JuliaCon 2019](https://www.youtube.com/watch?v=kc9HwsxE1OY)

