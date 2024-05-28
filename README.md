# graphs

このフォルダは
https://github.com/hu-ids-exercise-algorithm-II/graphs.git
のクローンでnetworkxのグラフが置いてある．

次のリポジトリにあるColabノートブックからこのフォルダを使う．
https://github.com/hu-ids-exercise-algorithm-II/notebooks.git

ノートブックでグラフのフォルダを仮想マシンにクローンするには次のコード．
```
!git clone https://github.com/hu-ids-exercise-algorithm-II/graphs.git
import networkx as nx

G = nx.read_edgelist('graphs/Delaunary-10-exp-10.edgelist', nodetype=int)
```
