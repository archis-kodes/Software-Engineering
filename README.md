# Overview
1. Introduction
2. Software Development Life Cycle (SDLC)
3. Requirement Analysis
4. Software project management
6. Codng and Testing
7. Maintainance
8. Quality Management and Reuse

# Software Engineering Definition and Evolution
- It is a Systematic, desciplined, cost-effective techniques for Software Development.
- Engineering approach to develop a Software

# Software Development Life Cycle (SDLC)
- Planning
- Defining/Analysis
- Designing
- Coding/Implementation
- Testing
- Deploy/Maintainance

# Classical Waterfall Model
![Classical waterfall Model](https://media.geeksforgeeks.org/wp-content/uploads/20200330182523/Untitled-Diagram83.png)
<!--```
Feasibility Study
    ↳ Requirement Analysis and Specification
        ↳ Design
            ↳ Coding and Unit Testing
                ↳ System Testing and Integration
                    ↳ Maintainance
```-->
### Advantages
- Base Model
- Simple and Easy
- Small projects

### Disadvantages
- No Feedback
- No Experiment
- No Parallelism
- High Risk
- 60% Effort Maintainance

# Iterative Waterfall Model
![Iterative Waterfall Model](https://media.geeksforgeeks.org/wp-content/uploads/20240314155656/Example-of-Interative-Waterfall-Model.webp)
<!--```
Feasibility Study
   ↳ Requirement Analysis and Specification
        ↑ Design
        |    ↑  Coding and Unit Testing
        |    |   ↑ System testing and Integration
        |━━|━━|━━↑━ Maintainance
```-->

### Advantages
- Base Model
- Simple and Easy
- Small projects
- Feedbacks [NEW!]

### Disadvantages
- No Feedback
- No Experiment
- No Parallelism
- High Risk
- 60% Effort Maintainance

# V-Shaped Model
![V shaped Model](https://media.geeksforgeeks.org/wp-content/uploads/20231030123258/software-Testing-SDLC-V-model.webp)
- Also known as Verification and Validation Model
- Extension of Waterfall model
- Testing is associated with every phase of lifecycle
- Verification Phase (Requirement Analysis, System Design, Architecture Design, Module Design)
- Validation Phase (Unit testing, Integration, System, Acceptance testing)

### Advantages
- Time saving
- Understanding of project at beginning
- Every component must be testable
- Progress can be tracked easily
- Proactive defect tracking

### Disadvantages
- No feedback so less scope of changes
- Risk analysis not done
- Not good for object-oriented projects

# Prototyping Model
![Prototyping Model](https://media.geeksforgeeks.org/wp-content/uploads/Prototyping-model.png)
- Customer not clear with idea
- Throw away model
- Good for technical and requirement risks
- Increase in Cost of Development

# Incremental Model
![Incremental Model](https://media.geeksforgeeks.org/wp-content/uploads/20240530140654/incremental.jpg)
- Module by module working
- Large Projects
- Early release product demands
- Flexible to changes

# Evolutionary Model
![Evolutionary Model](https://media.geeksforgeeks.org/wp-content/uploads/20190430124930/33331.jpg)
- Evolutionary model is a combination of Iterative and Incremental model of software development life cycle.
- Incremental model first implements a few basic features and delivber to the customer. Then build the next part and deliver it again and repeat this step until the desired system is fully realized. No long-term plans are made.
- Iterative model main advantage is its feedback process in every phase.

# Spiral Model
![Spiral Model](https://media.geeksforgeeks.org/wp-content/uploads/20240530140428/spiral-1-1024x945-660.webp)
1. Objective Determination and Identify alternative solutions
2. Itentify and resolve risks
3. Develop next version of product
4. Review and plan for next phase

- Risk Handling
- Radius of Spiral = Cost
- Angular Dimension = Progress
- Meta model

### Advantages
- Risk Handling
- Large projects
- Flexible
- Customer Satisfaction

### Disadvantages
- Complex
- Expensive
- Too much Risk Analysis
- Time

# Agile Model
![Agile Model](https://media.geeksforgeeks.org/wp-content/uploads/20240529165415/agile.jpg)
### Advantages
- Face to face communication client
- Changes
- Time

### Disadvantages
- Less documentation
- Maintainance Problem

# SCRUM Model (Agile Model)
![SCRUM Model](https://media.geeksforgeeks.org/wp-content/uploads/20240529122458/What-is-Scrum.webp)
- SCRUM is lightweight, iterative, incremental framework

### Advantages
- Freedom and Adaptation
- High quality, low risk product
- Reduce the development time up to 40%
- Scrum curtomer satisfaction is very important
- Reviewing the current sprint before moving to new one

### Disadvantages
- More efficient for small team size
- No changes in the sprint

# Comparison🔥
| Classical Waterfall | Iterative Waterfall | Prototype Model | Incremental Model |Evolutionary Model | RAD Model | Spiral Model | Agile Model
| -------- | ------- | -------- | ------- | -------- | ------- | -------- | -------- |
| Basic | Basic | User Requirement not clear | Module by Module delivery | Large projects | Time and cost constraints | Risk management | Flexible
| Rigid | Problem is well understood | Costly | Easy to test and debug | | User at all levels | Not for small projects | Advanced 
| Inflexible | | No early lock on requirements | | | Reusability | No early lock on requirements | Parallel
| Not for Real Project | | High User involvement | | | | Less Experience can work | Process divided into sprints

