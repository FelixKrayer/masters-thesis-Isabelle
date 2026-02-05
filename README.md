# Constructing Linear Types in Isabelle/HOL
## Konstruktion linearer Typen in Isabelle/HOL
### Abstract
In this thesis, we address the problem of constructing linear Map-Restricted Bounded Natural Functors (MRBNFs) in the Isabelle/HOL proof assistant. We formalize the process of linearization as taking a linear subtype from a non-linear MRBNF and show that the resulting type is also a MRBNF. Furthermore, we automate this process in a new **linearize_mrbnf** command, which generates the linearized type, derives the typical MRBNF constants, and proves the necessary properties.

We demonstrate the utility of our approach with an example based on the POPLmark Challenge, showing how a manual linearization can be streamlined with our new command.

Our work extends Isabelle/HOL to simplify the generation of complex, non-repetitive datatypes, supporting further reasoning about syntaxes with bindings.


[full document](https://github.com/FelixKrayer/masters-thesis-Isabelle/blob/main/Thesis_2025_11_13.pdf)

## License

[![Creative Commons License][license-image]][license]

This template is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][license], meaning that:

 * You can share (copy, redistribute) and adapt (remix, transform, build upon) this template for any purpose, even commercially.
 * If you share the template or a modified (derived) version of it, you must attribute the template to the original authors ([Florian Walch and contributors][template-authors]) by providing a [link to the original template][template-url] and indicate if changes were made.
 * Any derived template has to use the [same][license] or a [compatible license][license-compatible].

The license **applies only to the template**; there are no restrictions on the resulting PDF file or the contents of your thesis.

[license-compatible]: https://creativecommons.org/compatiblelicenses
[license-image]: https://i.creativecommons.org/l/by-sa/4.0/88x31.png
[license]: https://creativecommons.org/licenses/by-sa/4.0/
[template-authors]: https://github.com/TUM-Dev/tum-thesis-latex/graphs/contributors
[template-url]: https://github.com/TUM-Dev/tum-thesis-latex