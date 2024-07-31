---
timezone: Europe/Paris # 中欧标准时间 (UTC+2)
---

# Chloe
1. 自我介绍
    Hi I'm Chloe, Core contributor of ETHPanda & EIP Fun. Passionate about zk and privacy.
    Twitter：https://x.com/Chloe_zhuX
    TG：chloe_zhu

2. 你认为你会完成本次残酷学习吗？
    Ofc

3. 目前阶段对于 ZK 的了解？
    Had some brief overview of zk landscape/ projects/ tools. Would love to dig deep into the underlying tech.


## Notes

<!-- Content_START -->

### 2024.07.29

Video: [Computer Scientist Explains One Concept in 5 Levels of Difficulty | WIRED](https://www.youtube.com/watch?v=fOGdb1CTu5c)

Notes
- zkp is a way for prover to convince the verifier that some statement is true, yet reveal no additional info beyond the fact the statement is true
- 5 levels to explain zkp
    - **Child:** The prover proves that there is a puffin within a group of penguins in the photo through a hole to the verifier, without revealing the location of the puffin.
    - **Teen:** The prover proves he know the password to a box, without revealing the exact pwd.
    - **College student:**
        - NP-complete problems: a class of computational problems where an efficient, algorithmic solution has yet to be found
        - 3-colour problem: Prove that no blocks that share the border will have same colour. Make it impossible to put the pieces together and guess the whole map.
        - A probabilistic proof
        - zkp is not about making sth more efficient, but about doing things that can’t be done before, i.e. proving things without revealing any additional info
    - **Grad student:**
        - Proof is an interactive game.
        - Randomness can be useful for proving sth. The unpredictability can be utilized to generate proof and hide info.
        - Challenge: The main bottleneck lies on the prover
        - The power of MPC is to bring people together who are mutually distrustful
    - **Expert:**
        - Why zero-knowledge, not zero-data or zero-info; nuance between knowledge, data, and info
        - Transition from theoretical to applied zk

MoonMath
- Installed SageMath
    - /usr/local/bin/sage
    - [https://www.sagemath.org/index.html](https://www.sagemath.org/index.html)
    - SageMath is a free open-source mathematics software system licensed under the GPL. It builds on top of many existing open-source packages: NumPy, SciPy, matplotlib, Sympy, Maxima, GAP, FLINT, R and many more. Access their combined power through a common, Python-based language or directly via interfaces or wrappers.
- Walked through Chapter 1 intro

### 2024.07.30

<!-- Content_END -->