This is where I will dump all my notebooks for learning scala...

# What is Scala

Scala is a modern multi-paradigm programming language designed to express common programming patterns in a concise, elegant, and type-safe way. It seamlessly integrates features of object-oriented and functional languages.

# Scala is object-oriented

Scala is a pure object-oriented language in the sense that [every value is an object](https://docs.scala-lang.org/tour/unified-types.html). Types and behaviors of objects are described by [classes](https://docs.scala-lang.org/tour/classes.html) and [traits](https://docs.scala-lang.org/tour/traits.html). Classes can be extended by subclassing, and by using a flexible [mixin-based composition](https://docs.scala-lang.org/tour/mixin-class-composition.html) mechanism as a clean replacement for multiple inheritance.

# Scala is functional

Scala is also a functional language in the sense that [every function is a value](https://docs.scala-lang.org/tour/unified-types.html). Scala provides a [lightweight syntax](https://docs.scala-lang.org/tour/basics.html#functions) for defining anonymous functions, it supports [higher-order functions](https://docs.scala-lang.org/tour/higher-order-functions.html), it allows functions to be [nested](https://docs.scala-lang.org/tour/nested-functions.html), and it supports [currying](https://docs.scala-lang.org/tour/multiple-parameter-lists.html). Scala's [case classes](https://docs.scala-lang.org/tour/case-classes.html) and its built-in support for [pattern matching](https://docs.scala-lang.org/tour/pattern-matching.html) provide the functionality of algebraic types, which are used in many functional languages. [Singleton objects](https://docs.scala-lang.org/tour/singleton-objects.html) provide a convenient way to group functions that aren't members of a class.

Furthermore, Scala's notion of pattern matching naturally extends to the [processing of XML data](https://github.com/scala/scala-xml/wiki/XML-Processing) with the help of [right-ignoring sequence patterns](https://docs.scala-lang.org/tour/regular-expression-patterns.html), by way of general extension via [extractor objects](https://docs.scala-lang.org/tour/extractor-objects.html). In this context, [for comprehensions](https://docs.scala-lang.org/tour/for-comprehensions.html) are useful for formulating queries. These features make Scala ideal for developing applications like web services.

# Scala is statically typed

Scala's expressive type system enforces, at compile-time, that abstractions are used in a safe and coherent manner. In particular, the type system supports:

-   [Generic classes](https://docs.scala-lang.org/tour/generic-classes.html)
-   [Variance annotations](https://docs.scala-lang.org/tour/variances.html)
-   [Upper](https://docs.scala-lang.org/tour/upper-type-bounds.html) and [lower](https://docs.scala-lang.org/tour/lower-type-bounds.html) type bounds
-   [Inner classes](https://docs.scala-lang.org/tour/inner-classes.html) and [abstract type members](https://docs.scala-lang.org/tour/abstract-type-members.html) as object members
-   [Compound types](https://docs.scala-lang.org/tour/compound-types.html)
-   [Explicitly typed self references](https://docs.scala-lang.org/tour/self-types.html)
-   [Implicit parameters](https://docs.scala-lang.org/tour/implicit-parameters.html) and [conversions](https://docs.scala-lang.org/tour/implicit-conversions.html)
-   [Polymorphic methods](https://docs.scala-lang.org/tour/polymorphic-methods.html)

[Type inference](https://docs.scala-lang.org/tour/type-inference.html) means the user is not required to annotate code with redundant type information. In combination, these features provide a powerful basis for the safe reuse of programming abstractions and for the type-safe extension of software.

# Scala is extensible

In practice, the development of domain-specific applications often requires domain-specific language extensions. Scala provides a unique combination of language mechanisms that make it straightforward to add new language constructs in the form of libraries.

In many cases, this can be done without using meta-programming facilities such as macros. For example:

-   [Implicit classes](https://docs.scala-lang.org/overviews/core/implicit-classes.html) allow adding extension methods to existing types.
-   [String interpolation](https://docs.scala-lang.org/overviews/core/string-interpolation.html) is user-extensible with custom interpolators.

# Scala interoperates

Scala is designed to interoperate well with the popular Java Runtime Environment (JRE). In particular, the interaction with the mainstream object-oriented Java programming language is as seamless as possible. Newer Java features like SAMs, [lambdas](https://docs.scala-lang.org/tour/higher-order-functions.html), [annotations](https://docs.scala-lang.org/tour/annotations.html), and [generics](https://docs.scala-lang.org/tour/generic-classes.html) have direct analogues in Scala.

Those Scala features without Java analogues, such as [default](https://docs.scala-lang.org/tour/default-parameter-values.html) and [named parameters](https://docs.scala-lang.org/tour/named-arguments.html), compile as closely to Java as reasonably possible. Scala has the same compilation model (separate compilation, dynamic class loading) as Java and allows access to thousands of existing high-quality libraries.

--
