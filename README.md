# Starburst Pattern

A simple Python script to generate a colorful starburst visualization using **matplotlib** and **numpy**.

How It Works

We use parametric equations:

𝑥
=
cos
⁡
(
𝑡
)
×
(
1
+
0.6
cos
⁡
(
20
𝑡
)
)
x=cos(t)×(1+0.6cos(20t))
𝑦
=
sin
⁡
(
𝑡
)
×
(
1
+
0.6
cos
⁡
(
20
𝑡
)
)
y=sin(t)×(1+0.6cos(20t))

This produces a circle with oscillating distortions that create the starburst effect.
Colors are mapped to the parameter "t" using matplotlib’s spring colormap.
