# backtrack
最適化手法での反復更新で利用される基本的な手法に「勾配降下法」がある。更新式は次のようになる。

<img src=
"https://render.githubusercontent.com/render/math?math=%5Clarge+%5Cdisplaystyle+%5Cbegin%7Bequation%2A%7D%0A%5Cmathbf%7Bx%7D_%7Bk%2B1%7D+%3D+%5Cmathbf%7Bx%7D_k+%2B+%5Calpha_k+%5Cmathbf%7Bd%7D_k%0A%5Cend%7Bequation%2A%7D%0A" 
alt="\begin{equation*}
\mathbf{x}_{k+1} = \mathbf{x}_k + \alpha_k \mathbf{d}_k
\end{equation*}
">

ここに出てくるベクトル d_k は目的関数 f が減少するように決定すればよいが、同時に係数 α_k も適当に選択することが求められる。
この係数 α_k を適切に決める手法に「バックトラック直線探索」があり、それを実装する問題がレポート課題として出された。

本Githubには、東京大学工学教程『最適化と変分法』にのっている例を実装した例を示す。
レポートを作成した当時と同じ手法を使いつつ、プログラミング演習や卒業研究、現在の研究で自然と身についたプログラミングスキルをもとに、スッキリしたコードを作成した。
