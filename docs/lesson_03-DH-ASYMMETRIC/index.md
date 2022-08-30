

## Lesson 3 - Key exchanges & Asymmetric encryption and hybrid encryption.

**Expected Duration:** 2 weeks


**Plan:**
* Read Chapters 5-6 of [RWC](https://www.manning.com/books/real-world-cryptography?a_aid=Realworldcrypto&a_bid=ad500e09)
  * Understand core concepts (🎉 send pull requests with definitions/documentation updates 🎉)
  * Read up on group theory and the related mathematical concepts 
* Complete 
  * Challenge Exercises 
* Meet-up: 1x Q&A, explainers & challenge response reviews @ Thursday, Aug 25, 5:30 pm CET (Central European Time)



---

**Challenge Exercises**

a. Explain your answers in English, such that anyone reading the answer for the first time can follow-along, preferably in a markdown file.

b. Prepare 1 or more implementations in 1 or more languages of your choice; for example: Python, Rust, Javascript. (if needed)

---

1. What is a MITM attack in the context of key exchanges? And why is it significant?

2. What is the difference between an active MITM, and a passive MITM?

3. What are some of the qualities of the group that Diffie Hellman (not elliptic curve) standards use, and how is it constructed from this? (what kind of set elements are they?)

4. What is the significance of the discrete logarithm problem, specific to Diffie Hellman?

5. Why are many standards of Diffie Hellman considered deprecated? What makes one of them useful?

6. Why do the other standards of Diffie Hellman have best practice 2048 bit prime number security while ECDH is 256 bit?



7. Explain the goal of asymmetric encryption and provide a real world example of what it's used for.

8. Using the same shared secret with everyone would be very bad, can you see why?

9. Explain the limitation of asymmetric encryption and why it occurs.

10. What is key encapsulation and why is it important?

11. Explain the million message attack. What is the most common implementation of RSA today?

12. Explain the three mathematic algorithm problems that these cryptographic primitives rely on page 121, Figure 6.13.

---

**Bonus questions!**

1. Explain Figure 6.9 on page 115 step by step how a hybrid encryption message is produced and sent.



