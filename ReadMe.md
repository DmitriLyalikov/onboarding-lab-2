# Week 2 Lab: System Verilog
## Dmitri Lyalikov Lab 2 Completion + Answers

### Q1: 
Why do you think the reason for these different testing approaches are? What are their advantages and disadvantages?

* Exercise 1 uses the method of exhaustive testing, which implies testing behavior of the module over every possible case. This is the most thorough and can be done for modules with a reasonably small input range. However, it's application does not work and is limited by time/complexity as input ranges grow.

* Exercise 2 uses sampled testing which is an informed selection of initial values to test over. This is advantageous as it reduces test computation, and if done correctly focuses on important corners/cases.

* Exercise 3 uses randomized testing where input values are randomly generated, this can be helpful for large input spaces and is easy to implement, however there is obviously no guarantee of complete coverage.


