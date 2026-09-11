# micrograd — typed from scratch

Karpathy's micrograd (Zero to Hero, video 1), typed by hand from the video — no copy-paste. Scalar autograd engine (`Value`), operator overloads, topological-sort `backward()`, and a small MLP trained with it.

Result: 3-input MLP [4,4,1] on the toy dataset, loss 3.89 -> 0.06 in 20 steps, lr 0.05.

Part of my ML systems worklog (Phase 1, item 1).
