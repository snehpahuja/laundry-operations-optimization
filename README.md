# Laundry Operations Optimization (Goal Programming)

## Overview
This project optimizes FLAME University’s paid and free laundry services using integer goal programming. The objective is to meet daily demand while minimizing spillovers and operating within budget and resource constraints.

Spillovers refer to clothes that cannot be processed within the planned timeframe and must be carried forward, leading to delays.

## Problem Context
FLAME University operates two laundry systems with different service levels and constraints.

### Paid Laundry
- Same or next-day delivery  
- Limited by machine capacity and cost ceilings  

### Free Laundry
- Bulk processing with washing, ironing, and sorting  
- Limited by manpower availability and budget  

Both systems require careful coordination to avoid delays while controlling costs.

## Objectives
The optimization model was designed to:
- Meet daily laundry demand  
- Eliminate spillovers and delays  
- Operate within budget limits  
- Optimize machine allocation and workforce planning  

These goals were modeled using goal programming with integer constraints.

## Methodology
- Built an integer goal programming model  
- Defined deviation variables for unmet demand, spillovers, and budget overruns  
- Prioritized objectives based on operational importance  
- Solved using linear optimization techniques  

## Key Results

### Paid Laundry
- Optimal configuration of 23 machines  
- 100 percent demand met with zero spillovers  
- Operated within budget with a ₹5,000 underspend  

### Free Laundry
- 2 large machines and 6 small machines allocated optimally  
- 3 ironing workers and 2 sorting workers met full demand  
- Achieved ₹3.28 lakh in cost savings under the allocated budget  
- No unmet demand or processing delays  

## Impact
The model demonstrates how structured optimization can:
- Remove operational bottlenecks  
- Reduce costs without compromising service levels  
- Support data-driven decisions in capacity and workforce planning  

This approach is applicable to real-world operations and supply chain problems involving shared resources and capacity limits.

## Limitations
- Does not account for electricity, water usage, machine downtime, or staff breaks  
- Assumes full efficiency of machines and workers  
- Solver tolerance may lead to near-optimal solutions rather than exact optima  

## Tools and Concepts
- Goal Programming with Integer Constraints  
- Operations Research  
- Capacity Planning  
- Workforce Optimization  
- Cost Minimization  

