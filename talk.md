---
marp: true
paginate: true
_class: lead
math: mathjax
style: |
  section {
    background-color: #14213d;
    color: #f5f5f5;
    }
    section h1 {
      color: #fca311
    }
    section h2 {
      color: #d90368
    }
    section h6 {
      color: #aaa
    }
    section table {
      color: #333;
      background-color: transparent;
    }
---

# Introduction to Information Theory

###### Information Theory is a branch of mathematics that has many applications in the field of computer science. Such as in cryptography, machine learning and project management.

---

# What is Information Theory?

Information theory is the study of how information can be efficiently stored, transmitted, processed.

## What is Information?

Information is what allows one mind to influence another. It is the data that is transmitted from one mind to another during a communication process.

---

# How to measure Information?

- Bits: measure of surprise, the more surprising an event is, the more information it contains.

## Information measure formula

$$I(x) = -log_2(p(x))$$

---

# WTF is this formula? Let's dissect it.
- $I(x)$ is the information contained in the event $x$.
- $p(x)$ is the probability of the event $x$.
- $log_2$ is the logarithm base 2.

To discover the information (I) contained in the event $x$, we need to know the probability of the event $x$ and apply it to the $log_2$ function.

---

# Example

Let's assume the probability to snow in 3 different brazilian cities: :snowflake: :snowflake: :brazil:

<br />

| City | Probability | Information |
|:----:|:-----------:|:-----------:|
|  São Paulo | 1% | $I(SP) = -log_2(0.01) = 6.6439$ bits. |
|  Rio de Janeiro | 0.001% | $I(RJ) = -log_2(0.0001) = 13.2877$ bits. |
| São Joaquim | 80% | $I(SJ) = -log_2(0.8) = 0.3219$ bits. |

---

- Notice that the more surprising an event is, the more information it contains. 

- No one would be surprised if it snowed in São Joaquim, but if it snowed in São Paulo or Rio de Janeiro, it would be a big surprise, would be an event with a lot of information.

---

# Entropy

Amount of disorder in a system.