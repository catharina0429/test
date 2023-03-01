# Ch6. Database Design Using the E-R Model 
  - conceptual design: the creation of an entity-relationship diagram that provides a graphic representation of the schema. 
  - entity-relationship: used to represent the conceptual design
    
## 6.1.2 Design Alternatives
  - Redundancy: repeat information copies of a piece of information can beco **inconsistent** if the information is updated without taking precautions to update all copies of the information.
  - Incompleteness: having a relationship between two entities, but one is removed from the database. there is still remained the relationship

## 6.2 The Entity-Relationship (ER) Model
  - ER diagram can express the overall logical structure of a database graphically
  - `entity`: distinguishable from all other objects (must uniquely identify an entity)
    - Each entity has a `value` for each of its attributes
  - `entity set`: a set of entities of the same type that share the same properties or `attributes` (a.k.a column name). 
    - don't need to be disjoint.
    - represented in an ER diagram by a rectangle
  - Relationship sets: a set of relationships of the same type
    - relationship instance in an ER schema represents an association between the named entities 
    - represented in an ER diagram by a diamond
        - $$R = {(e_1, e_2, \cdots, e_n) | e_1 \in E_1, e_2 \in E_2, \dots, e_n \in E_n} $$
        - where   $$(e_1, e_2, \cdots, e_n)$$ : relathionship instance, $$E_1, E_2, \cdots, E_n $$: entity sets
    - role: the function that an entitiy plays in a relationship
