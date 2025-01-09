![alt text](image-2.png)

Let \( f(x) = 3x - 1 \) and \( g(x) = \sqrt{x} \). We compute:

---

### 1. \( f(g(x)) \)
Substitute \( g(x) = \sqrt{x} \) into \( f(x) = 3x - 1 \):
$$
f(g(x)) = f(\sqrt{x}) = 3(\sqrt{x}) - 1 = 3\sqrt{x} - 1
$$

---

### 2. \( g(f(x)) \)
Substitute \( f(x) = 3x - 1 \) into \( g(x) = \sqrt{x} \):
$$
g(f(x)) = g(3x - 1) = \sqrt{3x - 1}
$$

**Domain Constraint**: For \( g(f(x)) \) to be valid, we require \( 3x - 1 \geq 0 \):
$$
3x \geq 1 \implies x \geq \frac{1}{3}
$$

---

### 3. \( f(f(x)) \)
Substitute \( f(x) = 3x - 1 \) into itself:
$$
f(f(x)) = f(3x - 1) = 3(3x - 1) - 1 = 9x - 3 - 1 = 9x - 4
$$

---

### 4. \( g(g(x)) \)
Substitute \( g(x) = \sqrt{x} \) into itself:
$$
g(g(x)) = g(\sqrt{x}) = \sqrt{\sqrt{x}} = \sqrt[4]{x}
$$

**Domain Constraint**: Since \( g(x) = \sqrt{x} \), the domain of \( g(g(x)) \) is \( x \geq 0 \).

---

### Final Results:
1. \( f(g(x)) = 3\sqrt{x} - 1 \)
2. \( g(f(x)) = \sqrt{3x - 1}, \text{ valid for } x \geq \frac{1}{3} \)
3. \( f(f(x)) = 9x - 4 \)
4. \( g(g(x)) = \sqrt[4]{x}, \text{ valid for } x \geq 0 \)
![alt text](image-3.png)

Let \( f(x) = e^x \) and \( g(x) = \ln(x) \). We compute the compositions \( f(g(x)) \) and \( g(f(x)) \):

---

### 1. \( f(g(x)) \)
Substitute \( g(x) = \ln(x) \) into \( f(x) = e^x \):
\[
f(g(x)) = f(\ln(x)) = e^{\ln(x)}
\]

Using the property of logarithms and exponentials (\( e^{\ln(x)} = x \), valid for \( x > 0 \)):
\[
f(g(x)) = x \quad \text{for } x > 0
\]

---

### 2. \( g(f(x)) \)
Substitute \( f(x) = e^x \) into \( g(x) = \ln(x) \):
\[
g(f(x)) = g(e^x) = \ln(e^x)
\]

Using the property of logarithms (\( \ln(e^x) = x \)):
\[
g(f(x)) = x \quad \text{for all } x
\]

---

### Observations
1. \( f(g(x)) = x \) is the **identity function**, valid for \( x > 0 \).
2. \( g(f(x)) = x \) is also the **identity function**, valid for all \( x \).

This shows that the functions \( f(x) = e^x \) and \( g(x) = \ln(x) \) are **inverses of each other**.
![alt text](image-4.png)

We are given the function:
\[
f = \{(1,7), (2,9), (3,11)\}
\]

### Definition of the Inverse Function:
The inverse function \(f^{-1}\) swaps the \(x\)- and \(y\)-coordinates of each pair in \(f\). That is:
\[
f^{-1} = \{(y, x) : (x, y) \in f\}
\]

---

### Compute \(f^{-1}\):
From the given function \(f = \{(1,7), (2,9), (3,11)\}\), we swap the pairs:
- Swap \((1, 7)\) to \((7, 1)\),
- Swap \((2, 9)\) to \((9, 2)\),
- Swap \((3, 11)\) to \((11, 3)\).

Thus, the inverse function is:
\[
f^{-1} = \{(7, 1), (9, 2), (11, 3)\}
\]

---

### Final Answer:
\[
f^{-1} = \{(7, 1), (9, 2), (11, 3)\}
\]
![alt text](image-5.png)

We are given the function:
\[
f = \{(1,7), (2,7), (3,11)\}
\]

### Definition of the Inverse Function:
The inverse function \(f^{-1}\) swaps the \(x\)- and \(y\)-coordinates of each pair in \(f\). That is:
\[
f^{-1} = \{(y, x) : (x, y) \in f\}
\]

---

### Compute \(f^{-1}\):
From the given function \(f = \{(1,7), (2,7), (3,11)\}\), we swap the pairs:
- Swap \((1, 7)\) to \((7, 1)\),
- Swap \((2, 7)\) to \((7, 2)\),
- Swap \((3, 11)\) to \((11, 3)\).

Thus, the inverse function is:
\[
f^{-1} = \{(7, 1), (7, 2), (11, 3)\}
\]

---

### Observations:
1. The value \(7\) in \(f\) maps to two different \(x\)-values (\(1\) and \(2\)) in \(f^{-1}\).
2. Hence, \(f^{-1}\) is not a function because a single input (\(7\)) maps to multiple outputs (\(1\) and \(2\)).

---

### Final Answer:
\[
f^{-1} = \{(7, 1), (7, 2), (11, 3)\}
\]
![alt text](image-6.png)

We are given the function:
\[
f(x) = x - 1
\]

### Definition of the Inverse Function:
The inverse function \(f^{-1}(x)\) satisfies the condition:
\[
f(f^{-1}(x)) = x \quad \text{and} \quad f^{-1}(f(x)) = x
\]

---

### Solve for \(f^{-1}(x)\):
To find the inverse, start with the equation:
\[
y = f(x) = x - 1
\]

1. Replace \(f(x)\) with \(y\):
   \[
   y = x - 1
   \]

2. Solve for \(x\) in terms of \(y\):
   \[
   x = y + 1
   \]

3. Replace \(y\) with \(x\) to get the inverse function:
   \[
   f^{-1}(x) = x + 1
   \]

---

### Final Answer:
The inverse function is:
\[
f^{-1}(x) = x + 1
\]
![alt text](image-7.png)



