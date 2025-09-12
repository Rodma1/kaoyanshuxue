

## 方法一：降幂公式（推荐）
已知：
$$
\sin^2 t = \frac{1 - \cos(2t)}{2}
$$

因此：
$$
\int \sin^2 t \, dt
= \int \frac{1 - \cos(2t)}{2} \, dt
= \frac{t}{2} - \frac{\sin(2t)}{4} + C
$$

---

## 方法二：分部积分
设：
- \( u = \sin t \)
- \( dv = \sin t \, dt \)

则：
$$
\int \sin^2 t \, dt
= -\sin t \cos t + \int \cos^2 t \, dt
= -\sin t \cos t + \int (1 - \sin^2 t)\, dt
$$

解得与方法一相同：
$$
\int \sin^2 t \, dt = \frac{t}{2} - \frac{\sin(2t)}{4} + C
$$

---

## 常用结果
- 不定积分：
$$
\int \sin^2 t \, dt = \frac{t}{2} - \frac{\sin(2t)}{4} + C
$$

- 定积分：
$$
\int_0^{2\pi} \sin^2 t \, dt = \pi
$$

$$
\int_0^{\pi} \sin^2 t \, dt = \frac{\pi}{2}
$$
