  Engiish Version:
  This paper presents a novel adaptive super-twisting control framework for achieving bipartite consensus of multiple autonomous underwater vehicles (MAUVs) over signed networks. Unlike the conventional super-twisting algorithm (STA), which typically relies on conservative a priori gain selection, the proposed method incorporates barrier functions (BF) into the STA framework. This guarantees safety constraint satisfaction by strictly confining the consensus errors within a predefined neighborhood of $\pm 0.1$  m, while demonstrating strong robustness against uncertainties and reducing control effort without prior knowledge of disturbance bounds. To further improve communication efficiency, an event-triggered mechanism is introduced, which guarantees Zeno-free behavior. By integrating adaptive STA, BF-based constraint handling, and event-triggered communication, an event-triggered barrier-function-based adaptive super-twisting control (ETBFASTC) protocol is developed. Rigorous Lyapunov-based analysis establishes the finite-time stability of the closed-loop system, proving that bipartite consensus is achieved within a theoretical upper bound of $T$. Finally, numerical simulations validate the superiority of the proposed approach. The results demonstrate that the MAUVs achieve precise bipartite formation within 2 s, while the event-triggered mechanism yields about  50\% reduction in communication and control update frequency compared to traditional time-triggered continuous schemes.


中文版本：
本文提出了一种新颖的自适应超级扭转控制框架，用于在有向网络中实现多辆自主水下航行器（MAUVs）的二分子一致性。与传统超螺旋算法（STA）通常依赖保守的先验增益选择不同，
本文方法将障碍函数（BF）引入STA框架中。该方法通过严格将一致性误差限制在预设的±0.1米邻域内，确保安全约束满足，同时表现出对不确定性的强鲁棒性，并在无需预先知道扰动范围的情况下降低了控制努力。为
进一步提高通信效率，文中引入了事件触发机制，以保证系统行为无泽诺现象。通过结合自适应STA、基于障碍函数的约束处理以及事件触发通信，开发出一种事件触发型障碍函数自适应超螺旋转控制协议（ETBFASTC）。
严格的Lyapunov分析证明了闭环系统的有限时间稳定性，表明在理论上限时间内可实现二分一致性。最后，数值仿真验证了所提方法的优势。结果表明，MAUVs可在2秒内实现精确的二分图形成，
而事件触发机制相比传统的定时连续方案，可将通信和控制更新频率降低约50%。
