## Online Appendix of Paper Titled "A Formal Web Services Architecture Model for Changing PUSH/PULL Data Transfer"

---
### Abstract
---
Deciding how data should be transferred among Web services is an important part of their architecture design. 
Basically, each piece of data is transferred in either PUSH or PULL style.
The architect's selection of data transfer methods generally has a great impact on both the overall structure and performance of Web services.
However, little work has been done on helping architects to select suitable data transfer methods. 
In this paper, we present a formal model to abstract some parts of Web services architecture that are not affected by the selection of data transfer methods, and based on the model, we propose an architecture level refactoring for changing data transfer methods.
Also, we present an algorithm to generate prototypes of Web services from the architecture model and selected data transfer methods, and proved the correctness of the algorithm. 
Furthermore, we developed a tool that provides a graph-based UI for the refactoring and can generate deployable prototypes of Web services. 
To evaluate our method, we conducted case studies for several Web applications and confirmed that the generated prototypes can be used to estimate the performance.

---
### Appendix: Equivalence of JAX-RS Prototype and Data Transfer Architecture Model
---
The detailed proofs are [here](FACS2023_online_appendix.pdf).
