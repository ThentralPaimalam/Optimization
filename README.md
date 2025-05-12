# Optimization 

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: THENTRAL S

*INTERN ID*: CT08WN69

*DOMAIN*: DATA SCIENCE

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

# Chocolate Production Optimization Model using PuLP

**Overview:**

This project focuses on solving a linear programming (LP) problem using the PuLP library in Python to maximize profit in a chocolate manufacturing business. The model was designed to help a chocolate company determine the optimal number of different chocolate products to produce, given certain constraints like labor hours, material availability, and machine time.

The objective was to maximize the total profit by finding the best possible combination of product quantities that the company should manufacture without exceeding available resources. This type of optimization is crucial in real-world production planning to improve efficiency and reduce waste.

**About the Dataset and Problem Statement:**

The dataset or input data for this model included:

The types of chocolate products (e.g., milk chocolate, dark chocolate, white chocolate).

The profit earned per unit of each type of chocolate.

The resource constraints, including:

Available labor hours per day.

Raw materials (e.g., cocoa, milk powder, sugar).

Machine or production line capacity.

For each type of chocolate, the model considered the amount of each resource it consumes and then built constraints around these resources.

**Environment:**

The project was developed in Jupyter Notebook using Python, with the PuLP library as the core tool for building and solving the linear programming model. The environment allowed for interactive experimentation and visualization of outputs.

Steps Involved:

**Step 1:** Defining the Decision Variables

Each decision variable represented the number of units to produce for each chocolate type.

These were defined as non-negative integers, since producing a fraction of a chocolate bar isn’t practical.

**Step 2:** Setting the Objective Function

The goal was to maximize profit.

The objective function was defined as the sum of the profit per unit multiplied by the number of units produced for each chocolate type.

**Step 3:** Adding Constraints

Multiple constraints were included:

Labor hours: Total hours used must not exceed the available hours.

Raw materials: Each material had a limit, and usage across all products couldn’t exceed that limit.

Machine capacity: Total machine time used per day had to stay within operational limits.

**Step 4:** Model Building and Solving

The model was built using LpProblem from PuLP and solved using the default solver.

The solution included the optimal quantity of each chocolate product to produce and the maximum achievable profit.

**Step 5:** Results Interpretation and Analysis

The output displayed which products to focus on and how many units of each to manufacture.

This helped identify resource bottlenecks and adjust production plans to maximize efficiency.

**Applications and Impact:**

This project demonstrates how operations research and optimization techniques can significantly enhance decision-making in a manufacturing setting. Businesses can apply such models to:

Maximize profits

Utilize resources more effectively

Reduce waste and costs

Improve strategic planning

The approach is scalable and can be adapted to any manufacturing or supply chain scenario where resource allocation plays a key role.

**Conclusion:**
Using PuLP for linear programming, this project successfully built a mathematical model that provides actionable insights for maximizing profit in chocolate production. The experience showcased the power of optimization in real-world business applications and strengthened skills in problem formulation, constraint handling, and model interpretation.

