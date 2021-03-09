# OptNSDP
Exact approaches to the Network Slice Design Problem.

In this work, we address the Network Slice Design problem. This is an original problem arising from the optimization of end-to-end communication networks using fifth-generation (5G) radio access technology. We propose a Mixed-Integer Linear Programming (MILP) formulation for the problem including novel splitting, mapping and provisioning constraints described in the published 5G standards documents. We propose several classes of valid inequalities in order to strengthen the linear relaxation of the proposed MILP and integrate them in a Branch-and-Cut algorithm for the problem. We further present several strategies to reduce the symmetries on the one hand and the size of the model on the other hand.  

The code-source is written in Julia-JuMP language for Jupyter environment. You will find below the version of each library used in this work.


  [a076750e] CPLEX v0.7.3
  
  [aa1b3936] GraphIO v0.5.0
  
  [86223c79] Graphs v0.10.3
  
  [7073ff75] IJulia v1.21.3
  
  [4076af6c] JuMP v0.21.1
  
  [093fc24a] LightGraphs v1.3.3
  
  [2f5eb75a] LightGraphsFlows v0.3.1
  
  [b8f27783] MathOptInterface v0.9.14
  
  [fdba3010] MathProgBase v0.7.8
  
  [626554b9] MetaGraphs v0.6.5
  
  [0db19996] NBInclude v2.2.0
  
  [fae87a5f] ParserCombinator v2.0.0
  
  [47aef6b3] SimpleWeightedGraphs v1.1.1
  
  [9a3f8284] Random
