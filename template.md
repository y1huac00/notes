# 数学笔记

## 1. 基础概念

> **Definition 1.1 (Group).**  
> A *group* is a set $G$ with a binary operation $\cdot : G \times G \to G$  
> such that for all $a, b, c \in G$:  
> 1. (Associativity) $(a \cdot b) \cdot c = a \cdot (b \cdot c)$  
> 2. (Identity) There exists $e \in G$ such that $a \cdot e = e \cdot a = a$.  
> 3. (Inverse) For every $a \in G$, there exists $a^{-1} \in G$ such that $a \cdot a^{-1} = e$.

---

## 2. 定理与证明

> **Theorem 1.1.**  
> In a group $(G, \cdot)$, the identity element is unique.

**Proof.**  
Suppose $e_1$ and $e_2$ are two identity elements in $G$.  
By definition, $e_1 \cdot e_2 = e_2$ (since $e_1$ is identity),  
and also $e_1 \cdot e_2 = e_1$ (since $e_2$ is identity).  
Thus $e_1 = e_2$.  
$\square$

---

## 3. 数学公式展示

- **行内公式**：$E = mc^2$  
- **独立公式**：

$$
\int_a^b f(x)\, dx = F(b) - F(a)
$$

---

## 4. 习题与解答

**Exercise 1.** Show that $(\mathbb{Z}, +)$ is a group.  

**Solution.**  
1. Associativity: $(a+b)+c = a+(b+c)$.  
2. Identity: $0$ is the identity.  
3. Inverse: For each $a$, $-a$ is the inverse.  
