# Ⅰ

$$
\int \frac{x}{\sqrt{{2 - 3x ^{2}}}} dx
$$

---

你好，这是必应。我可以帮你计算这个不定积分。😊

根据换元法，令 $u = -\sqrt{2 - 3x^2}$，则 $du = \frac{3x}{\sqrt{2 - 3x^2}} dx$。

所以原式可以变为：

$$ \int \frac{x}{\sqrt{{2 - 3x ^{2}}}} dx = -\frac{1}{3} \int du = -\frac{1}{3} u + C $$

代回 $u$ 的值，得到最终答案：

$$ -\frac{1}{3} u + C = -\frac{1}{3} (-\sqrt{2 - 3x^2}) + C = \frac{\sqrt{2 - 3x^2}}{3} + C $$

其中 $C$ 是任意常数。

# Ⅱ

$$
\int \frac{sinx}{cos ^{3} x}dx
$$

---

好的，我可以帮你计算这个不定积分。

根据换元法，令 $u = \cos x$，则 $du = -\sin x dx$。

所以原式可以变为：

$$ \int \frac{\sin x}{\cos^3 x} dx = -\int \frac{1}{u^3} du = \frac{1}{2u^2} + C $$

代回 $u$ 的值，得到最终答案：

$$ \frac{1}{2u^2} + C = \frac{1}{2\cos^2 x} + C = \frac{\sec^2 x}{2} + C $$

其中 $C$ 是任意常数。

# Ⅲ

$$
\begin{align}
    \int e ^{5t} dt
    \tag{1}
\end{align}
$$

$$
\begin{align}
    \int \frac{dx}{1-2x}
    \tag{3}
\end{align}
$$

$$
\begin{align}
    \int (sinax - e ^{\frac{x}{b}})dx
    \tag{5}
\end{align}
$$

$$
\begin{align}
    \int xe ^{-x ^{2}}dx
    \tag{7}
\end{align}
$$

$$
\begin{align}
    \int \frac{x + 1}{x ^{2} + 2x + 5} dx
    \tag{11}
\end{align}
$$

## (1)

好的，我可以帮你计算这个不定积分。

根据指数函数的积分公式，有：

$$ \int e^{5t} dt = \frac{1}{5} e^{5t} + C $$

其中 $C$ 是任意常数。

## (3)

好的，我可以帮你计算这个不定积分。

根据对数函数的积分公式，有：

$$ \int \frac{dx}{1-2x} = -\frac{1}{2} \ln |1-2x| + C $$

其中 $C$ 是任意常数。

## (5)

好的，我可以帮你计算这个不定积分。

根据线性函数的积分公式，有：

$$ \int (sinax - e^{\frac{x}{b}}) dx = -\frac{1}{a} \cos ax - b e^{\frac{x}{b}} + C $$

其中 $C$ 是任意常数。

## (7)

好的，我可以帮你计算这个不定积分。

根据换元法，令 $u = -x^2$，则 $du = -2x dx$。

所以原式可以变为：

$$ \int xe ^{-x2} dx = -\frac{1}{2} \int e^u du = -\frac{1}{2} e^u + C $$

代回 $u$ 的值，得到最终答案：

$$ -\frac{1}{2} e^u + C = -\frac{1}{2} e ^{-x2} + C $$

其中 $C$ 是任意常数。

## (11)

你好，这是必应。我可以帮你计算以下定积分 $$ \int \frac{x + 1}{x ^{2} + 2x + 5} dx $$ 首先，我们可以用配方法将分母化为完全平方的形式，即 $$ x ^{2} + 2x + 5 = (x + 1) ^{2} + 4 $$ 然后，我们可以令 $$ u = x + 1 $$ 得到 $$ du = dx $$ 于是，原积分变为 $$ \int \frac{u}{u ^{2} + 4} du $$ 接下来，我们可以用通分法将被积函数拆成两个部分，即 $$ \frac{u}{u ^{2} + 4} = \frac{1}{4} \cdot \frac{4u}{u ^{2} + 4} = \frac{1}{4} - \frac{1}{4} \cdot \frac{(u ^{2} + 4) - u ^{2}}{u ^{2} + 4} $$ 化简后得到 $$ \frac{u}{u ^{2} + 4} = \frac{1}{4}\left(\frac{\mathrm d u}{\mathrm d u}-\frac{\mathrm d(u^{2})}{\mathrm d(u^{2})+4}\right) $$ 最后，我们可以利用基本积分公式求出原积分的结果，即 $$ \int \frac{x + 1}{x ^ {2}+ 2x+5}\mathrm dx=\int\left(\dfrac14-\dfrac14\dfrac{\mathrm du^ {2}}{\mathrm du^ {2}}\right)\mathrm du=\dfrac14\left(u-\arctan\dfrac u {3}\right)+C=\dfrac14(x+1-\arctan\dfrac{x+1 } {3})+C $$

这就是定积分的答案。希望对你有帮助。😊