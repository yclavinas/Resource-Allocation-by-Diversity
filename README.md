# Resource-Allocation-by-Diversity

Author Yuri Lavinas - University of Tsukuba
Co-Author Claus Aranha - University of Tsukuba
Co-Author Tetsuya Sakurai - University of Tsukuba

Working title: Resource-Allocation-by-Diversity

Target Journal: IEEE Transactions on Evolutionary Computation

Topic of Study: Multiobjective problems - benchmark functions


1. The specific objective of this study was to propose a variation of one popular multiobjective problem algorithm, MOEA/D, by the usage of evaluations during its iteractions leading to better approximations sets of the Pareto Front. The purpose of this investigation is to explore the relationship of subproblems and evalutions needed. 

2. There are a few already proposed algorithms. Generally a utility function is used to prioritize this usage of evaluations, but it is not clear hy this function was proposed and if it has mathematical justification. I want to integrate a diversity metric based on a geometrical perspective as the utility function.

3. I need to focus on the Methology and results, since describing the proposed method clearly has a plays a major role here. The results section is also important to show in practice that the geometrical proposition is useful. The most important aspect of the methology is to show how the diversity metric works. Then, it is crucial to demonstrate how this metric is going to be integrate into MOEA/D.

4. Most of the background needed to understand this study are:

  1. what are multiobjective problems and why are they important
  2. how are the addressed, show evolutionary algorithms that are used for MOP
  3. place MOEA/D among them
  4. describe MOEA/D variants that deal with resource allocation
  5. describe their limits
  6. demonstrate why this study is of relevance.

5. Results will be mainly some applications of the proposed method, compared with a traditional version - MOEA/D-DE - and MOEA/D-GRA, another proposal to address resource allocation.

6. If the results indicate that the proposed method, in many cases, find better approximations to the Pareto Front, then I will apply it to real-world problems.

7. The diversity metric considered here may be very computation intensive, therefore it can be impratical to use it for real-world problems. Only one metric is considered in this other, which could be extended.

8. Mainly there are three future works considered:

  1. Use this metric as a measure for adaptive techniques. 
  2. Consider other diversity metrics - expecially those with mathematical justification and with low computational cost.
  3. Consider reference-based strategy to approximate regions of interested of the Pareto Fronts.
  

Outline of the paper

1. Introduction
  1.1 Topic and importance of it
  1.2 related works
  1.3 reseach addressing the problem

2. Methods
  2.1 how to answer the research question
  2.2 why this method

3. Results 
  3.1 Figures
  3.2 Statistical analysis
  3.3 Explanation

4. Discussion
  4.1 impacts
  4.2 advantagens
  4.3 disadvantagens

5. Conclusion
  5.1 main results
  5.2 Wider implications
  5.3 limitations
  5.4 future works
