MANET_Dissipativity/
├── model/
│   ├── state.py          # 状态定义（I, W, A, E, S, M）
│   ├── events.py         # 事件定义（BR, FR, RR, ...）
│   ├── transition.py     # 转移函数 δ(q, e)
│   ├── storage.py        # 存储函数 V(q)
│   └── supply.py         # 供给率 ω(e, q)
├── analysis/
│   ├── dissipativity.py  # 耗散不等式验证
│   ├── efficiency.py     # 耗散效率计算
│   └── reachability.py   # 可达状态遍历
├── control/
│   ├── supervisor.py     # Algorithm 1
│   └── adaptive.py       # Algorithm 2
├── experiment/
│   ├── run_case_study.py # 主实验脚本
│   └── plot.py           # 结果可视化
└── results/
    └── figures/
	
	
只关注 A→F 单条路由的案例
