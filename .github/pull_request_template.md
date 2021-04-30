**Internal Quality Bar (IQB v1.0)**
**For Configuration change**
    
- [ ] IQB.C.1: I have tested my changes locally or on DEV when necessary

**For code changes (otherwise remove)**

1. Documentation:
    - [ ] IQB.D.1: There is a task in JIRA for the work delivered and it has a proper description of the requirement

1. Functional:
    - [ ] IQB.F.2: I verified that the code implements the requirement specified by the task

1. Testing:
    - [ ] IQB.T.1: Code is covered by unit tests (This promotes: separation of concern and DI)
    - [ ] IQB.T.2: Tests follow the Test Pyramid

1. Structure:
    - [ ] IQB.S.1: The code structure makes sense to me
    - [ ] IQB.S.2: Variable/Method/Class names clearly define what they do
    - [ ] IQB.S.3: Class responsibilities are minimal and clearly defined -> "S.O.L.I.D."
    - [ ] IQB.S.4: The code does not contain redundant logic or abstractions for unknown future use-cases beyond what is necessary to achieve in the near future (KISS)
    - [ ] IQB.S.5: The code does not contain repeating logic
 
1. Logging:
    - [ ] IQB.L.1: Log statements are on the correct level
    - [ ] IQB.L.2: Error log statements express context (entity type, id, operation, error message)
