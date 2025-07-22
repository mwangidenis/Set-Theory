# Set Theory
In this project we practice knowledge on sets, such as common set operations, the use of Venn Diagrams, the inclusion exclusion principle, and how to use sets in Python!

### Set Membership
We have a Universal set of Positive Intergers[1,12], sets:
U = {1,2,3,4,5,6,7,8,9,10,11,12}
A = {2,4,6,8,10}
B = {3,8,11,12}
C = {2,3,6,8,9,11}

We use the above sets to get the following set membership operations;
1. Intersection (.intersection or &): A&B
2. Union        (.union or |):A|B
3. Absolute Complement  : A', B' , (AuB)', BnC' 
4. Relative Complement  : A\B, C\(B\A), (CnA)u(C\B)

### Inclusion-Exclusion Principle
This is about cardinality of sets and to avoid double counting we use the inclusion principle
Here we find out the number of distinct elements in (A U B U C). 

## Set-Operations
In this exercise we use the following operations on dataset of the animal species between three friends and different directions of cars in a highway;

| Operation                        | Shorthand      | Result                                                      |
|----------------------------------|----------------|-------------------------------------------------------------|
| `s.update(t)`                   | `s |= t`       | Add elements from set `t` into set `s`                      |
| `s.intersection_update(t)`      | `s &= t`       | Keep only elements found in both `s` and `t`                |
| `s.difference_update(t)`        | `s -= t`       | Remove elements in `t` from set `s`                         |
| `s.symmetric_difference_update(t)` | `s ^= t`    | Keep elements in `s` or `t` but not both                    |
| `s.add(x)`                      |                | Add element `x` to set `s`                                  |
| `s.remove(x)`                   |                | Remove `x` from `s`; throws error if not present            |
| `s.discard(x)`                  |                | Remove `x` from `s` if present; no error if not             |
| `s.pop()`                       |                | Remove and return an arbitrary element from `s`             |
| `s.clear()`                     |                | Remove all elements from set `s`                            |

### European Countries
We have a 2018 data set about EU countries and EU membership
In this exercise get to import library such as pandas so as to read excel files in python,view the table in excel, 
We use set operations such as getting subsets for example getting to know if eu members are countries in europe or relative complement to get to know which countries in Europe are not members of the EU.
