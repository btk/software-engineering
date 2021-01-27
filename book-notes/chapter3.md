# Traditional Software Development

## Design

Design is a fundamental activity - if not the most important – a good engineer must master.

Modularity parameters;
- Hierarchy
- Cohesion: the degree to which a module does only one task. (High better)
- Coupling: the degree of dependence to other modules. (low better)

Modularization is the decomposition of a system into its components.

- when system is decomposed, the top-level modules should be defined first, containing high-level decisions.

## Coding and Debugging

- Diciplined coding is important for the lifecycle of the software.
- Team should decide on a standard or rules before starting the coding; these rules might include;
  * comment lines
  * code writing structure
  * meaniningful naming
  * structured programming elements

## Testing and Integration

Testing is conducted for finding errors.
- Testing is a costy procedure.
- before development, a test plan is prepared

White/Black Box testing.

*Basis path testing* visit every possible path or sequence.

* Cyclomatic complexity = E - N + 2

E: Edges, N: Nodes

## Integration

Prevention measures to less complicate this problem;
- Specify the interfaces even during the earliest decomposition activity
- Obey the less coupling / more cohesion laws
- Avoid side-effect causes such as global variables, uncontrolled access to data structures, while creating interfaces whenever different layers are present.
