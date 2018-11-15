## Overview of the Problem

Viasat is a global communications company that believes everyone and everything in the world can be connected. For more than 30 years, Viasat has helped shape how consumers, businesses, governments and militaries around the world communicate.

Viasat designs all of the hardware necessary to provide internet services, but outsources most of its manufacturing to other companies in a process known as contract manufacturing.  Although other companies are responsible for manufacturing the products, Viasat is still responsible for managing the supply chain.  This can become very complex as the number of suppliers grows and the complexity of products increases.

This project will focus on optimizing the supply chain of a single product, which will be referred to as "Product A".  This involves determining which suppliers should be used to manufacture product A in order to minimize cost.  Product A has hundreds of components, but for the purpose of this simulation, we will only look at product A's largest subassembly, referred to as "Product B", and product B's largest components, "Product X" and "Product Y".  The product structure of product A is shown in the diagram below.

![Product Structure of A](http://ryankohls.github.io/simulation-final-project/images/product_structure.PNG)

The supply chain for product A is split into three tiers based on the stage of assembly.  Each tier has between 2 and 4 suppliers.  The assembly flowchart is summarized below.

![Supplier Flowchart of A](http://ryankohls.github.io/simulation-final-project/images/product_flowchart.PNG)

Each supplier has a separate capacity, yield, cost, and lead time.

## High Level Objectives

1. Minimize the Total Cost to Manufacture Product A
2. Determine optimal inventory levels to minimize product stockouts

```
Metrics
1. Total Cost
  - Based on Manufacturing and inventory holding cost
2. Inventory Stockouts
  - Measured in the percentage of time that the warehouse has zero units of Product A in stock

Model Parameters
- Capacity
- Yield
- Cost
- Lead Time
- 


```

## Functional Specification

## Logical Model
