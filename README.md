# DDMRP-Simulation

This simulation model aims to provide a tool for companies to examine the feasibility of implementing DDMRP (Demand Driven Material Requirements Planning) to their inventory planning policies. The model allows easy assembly for examination on multi-node and multi-layer supply chains. Each node takes demand data and calculates the recommended order quantity and buffer stock levels. Different layers communicate through the passing down orders and the backorder refill mechanism.

# Inputs:
* Demand data at Layer A (Other layers take in orders from the downstream layer as demand.)
* Constraints at each node: lead time, MOQ, desired order frequency, etc.

# Outputs:
* Visualization of inventory level, buffer stock levels (red/yellow/green) 
* Metrics including service level, inventory level, and order frequency
