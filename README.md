Most nature-inspired algorithms exhibit certain limitations compared to evolutionary algorithms. This study proposes an improved Aptenodytes Forsteri Optimization (AFO) algorithm, which can rival advanced evolutionary algorithms in solving the CEC benchmarks and real-world problems. The study addresses key limitations of the original AFO algorithm. The Artificial Potential Field (APF) method is integrated into a nature-inspired algorithm for the first time, replacing the gradient-based mechanism and reducing computational overhead. An adaptive parameter tuning mechanism and a multi-population framework, including a local search inspired by CMA-ES, are incorporated. These advances balance exploration and exploitation.
The algorithm has been commercialized and integrated into an industrial optimization system at Shuyou Technologies. During the development of an Advanced Planning and Scheduling (APS) system, we found that many existing metaheuristic algorithms require extensive modifications to solve discrete optimization problems, limiting their applicability in scheduling and routing.
To overcome this, a universal encoding–decoding framework is proposed, enabling metaheuristic algorithms designed for continuous domains to be directly applied to combinatorial tasks, such as the Traveling Salesman Problem, without altering their core mechanisms. By transferring part of the constraint handling to the decoding phase and incorporating heuristic factors, solution quality improves while preserving the inherent generality of metaheuristic algorithms.
The main contributions of this study are summarized as follows:
(1) The APF method is applied to a nature-inspired algorithm for the first time, supplanting high-cost gradient estimation.
(2) A multi-population mechanism with learning-based parameter control is developed.
(3) A priority-based encoding approach enables continuous metaheuristics to tackle discrete problems without major revisions.
The code for the algorithm and encoding-decoding framework has been open-sourced (https://github.com/TwilightArchonYz/APF-AFO).



大多数自然启发式算法相比于进化算法存在一定的局限性。本研究提出了一种改进的帝企鹅优化（Aptenodytes Forsteri Optimization，AFO）算法，该算法能够在解决CEC基准问题和实际问题时，与先进的进化算法相媲美。研究解决了原始AFO算法的关键局限性。首次将人工势场（Artificial Potential Field，APF）方法集成到自然启发式算法中，替代了基于梯度的机制，减少了计算开销。还引入了一种自适应参数调节机制和一个多种群框架，包括受CMA-ES启发的局部搜索。这些进展平衡了探索与利用之间的关系。

该算法已在Shuyou Technologies公司实现商业化，并集成到工业优化系统中。在开发高级规划与调度（APS）系统过程中，我们发现许多现有的元启发式算法需要对离散优化问题进行大量修改，限制了它们在调度和路径规划中的应用。

为了解决这一问题，提出了一种通用的编码-解码框架，使得针对连续领域设计的元启发式算法可以直接应用于组合任务（如旅行商问题），而无需改变其核心机制。通过将部分约束处理转移到解码阶段，并结合启发式因素，解决方案的质量得到了改善，同时保留了元启发式算法固有的通用性。

本研究的主要贡献总结如下： 
(1) 首次将APF方法应用于自然启发式算法，取代了高成本的梯度估计。 
(2) 开发了一种具有基于学习的参数控制的多种群机制。 
(3) 提出了基于优先级的编码方法，使得连续元启发式算法能够解决离散问题，而无需进行重大修改。

