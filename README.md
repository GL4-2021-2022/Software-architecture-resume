# Software-architecture-resume

## Good design rules

### Architecture risks

#### Software rigidity

- Hard to modify
- Little changes cascade into lot more changes

#### Fragility

- software breaks in multiple unrelated places when a small change is introduced

#### Immobility

- modules cant be easily ported outside the project

#### Viscosity

- software is flexible to a fault
- multiple ways exist to achieve the same goal
- hacks are easier than proper implementation

#### Useless Repetition

- Lack of useful abstractions

#### Opacity

- software modules are hard to understand

#### Useless Complexity

- Introducing not needed complexity trying to avoid other pitfalls

### SOLID principles

#### Open/Closed principle OCP

- Classes should be open for open for extension and closed for modification

#### The Liskov Substitution Principle LSP

- Sub class should be able to replace its parent class without the module knowing

#### Dependency inversion principle DIP

- Classes should depend on abstractions ( Interfaces ) not concrete implementations

#### Interface Segregation Principle ISP

- Interfaces should serve a single purpose and be decomposable
