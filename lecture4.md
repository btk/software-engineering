### Software Quality Assurance Cont.

- A quality management approach
- Effective software eng. technology
- Formal technical reviews throughout
- Multi-tiered testing strategy
- Control of documentation and its changes
- Standarts compliance procedure
- Measurement and reporting mechanisms

> Quality is the variation between produced products.
> Engineer does optimization.

*3 Foundations for SQA*
- Requirements, how we measure it
- Standards, setting the development criteria
- Unmentioned implicit requirements, things costumer doesn't define, but important

**Formal Technical Review**
- Stick to agenda
- Not the place to introduce new ideas
- find problems not solutions
- producer, reviewers and recorders.

#### Statistical Quality Assurance

- *Pareto principle*, 80% of the defects relate to 20% of causes.

> End of Quality Topic

## Software Configuration Management

- Preserving the variation of intermediate products
- Change management
- Version management
- Baseline, decisions management

Software Config Items
- documents
- code
- data
- test code etc.

**Config Item Pool**

In order to make changes, create new config items, you need to create a new version

# Metrics, Estimation

- Metrics
- Size & Function oriented Metrics
- Empirical Estimation
- Metrics for quality
- Make/Buy decision

**Measure:** How big are you
**Metric:** quantifiable measure

## LOC Method, Estimation

LOC: Lines of Codes.
pm: person month

Labor Cost: $/pm
Productivity: LOC/pm

How many loc in avg people can write in one day in 1990's? **3 lines LOL**

> Estimation: use the common sense and scale it up.

## Function Method

Size oriented.

- Depending on the pointing system for functions, measure functions by size.
- Extentions, 3D Function points;
  - Data, same as *mentioned* function points
  - Function, nof transformations
  - Control, nof states

## Empirical Estimation Methods

Based on klocs;
Boehm: simple: 3.2 (KLOC)^1.05 > Winner

Based on Function Points;
Albrecht - Gaffney: -13.39 + 0.045 FP

## COCOMO

Constructive Costing Models
  1) Basic, effort and time as a function of size
  2) Intermadiate, basic with some cost drivers
  3) Advanced, intermadiate but also dynamic

> Choose a model and find out how embeded it is.
