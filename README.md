# Software Architecture Interview Questions and Answers from [FullStack.Cafe](https://www.fullstack.cafe)

> You could also find all the answers here 👉 https://www.fullstack.cafe/Software%20Architecture.

<p align="center">
  <a href="https://www.fullstack.cafe">
  <img src="https://user-images.githubusercontent.com/13550565/73042643-e53caa80-3e9c-11ea-9019-f70c2158c249.png">
  </a>
</p>

## Q1: What Is Scalability? ⭐⭐

**Answer:**

Scalability is the ability of a system, network, or process to handle a growing amount of load by adding more resources. The adding of resource can be done in two ways  
  

*   **Scaling Up**  
    This involves adding more resources to the existing nodes. For example, adding more RAM, Storage or processing power.
*   **Scaling Out**  
    This involves adding more nodes to support more users.

Any of the approaches can be used for scaling up/out a application, however the cost of adding resources (per user) may change as the volume increases. If we add resources to the system It should increase the ability of application to take more load in a proportional manner of added resources.  
  
An ideal application should be able to serve high level of load in less resources. However, in practical, linearly scalable system may be the best option achievable. Poorly designed applications may have really high cost on scaling up/out since it will require more resources/user as the load increases.  
  

🔗 **Source:** [fromdev.com](https://www.fromdev.com/2013/07/architect-interview-questions-and-answers.html)


## Q2: What Is A Cluster? ⭐⭐

**Answer:**

A cluster is group of computer machines that can individually run a software. Clusters are typically utilized to achieve high availability for a server software. Clustering is used in many types of servers for high availability.  

*   **App Server Cluster**  
    An app server cluster is group of machines that can run a application server that can be reliably utilized with a minimum of down-time.
*   **Database Server Cluster**  
    An database server cluster is group of machines that can run a database server that can be reliably utilized with a minimum of down-time.

🔗 **Source:** [fromdev.com](https://www.fromdev.com/2013/07/architect-interview-questions-and-answers.html)


## Q3: Why Do You Need Clustering? ⭐⭐

**Answer:**

*Clustering* is needed for achieving high availability for a server software. The main purpose of clustering is to achieve 100% availability or a zero down time in service. A typical server software can be running on one computer machine and it can serve as long as there is no hardware failure or some other failure. By creating a cluster of more than one machine, we can reduce the chances of our service going un-available in case one of the machine fails.  
  
Doing clustering does not always guarantee that service will be 100% available since there can still be a chance that all the machine in a cluster fail at the same time. However it in not very likely in case you have many machines and they are located at different location or supported by their own resources.  
  

🔗 **Source:** [fromdev.com](https://www.fromdev.com/2013/07/architect-interview-questions-and-answers.html)


## Q4: What is meant by the KISS principle? ⭐⭐

**Answer:**

**KISS**, a backronym for "keep it simple, stupid", is a design principle noted by the U.S. Navy in 1960. The KISS principle states that most systems work best if they are kept simple rather than made complicated; therefore simplicity should be a key goal in design, and that unnecessary complexity should be avoided.

🔗 **Source:** [stackoverflow.com](https://en.wikipedia.org/wiki/KISS_principle)


## Q5: What defines a software architect? ⭐⭐

**Answer:**

An **architect** is the captain of the ship, making the decisions that cross multiple areas of concern (navigation, engineering, and so on), taking final responsibility for the overall health of the ship and its crew (project and its members), able to step into any station to perform those duties as the need arises (write code for any part of the project should they lose a member). He has to be familiar with the problem domain, the technology involved, and keep an eye out on new technologies that might make the project easier or answer new customers' feature requests.

🔗 **Source:** [stackoverflow.com](https://softwareengineering.stackexchange.com/questions/13439/what-defines-a-software-architect)


## Q6: Why is it a good idea for “lower” application layers not to be aware of “higher” ones? ⭐⭐

**Answer:**

The fundamental motivation is this: 

_You want to be able to rip an entire layer out and substitute a completely different (rewritten) one, and NOBODY SHOULD (BE ABLE TO) NOTICE THE DIFFERENCE._ 

The most obvious example is ripping the bottom layer out and substituting a different one. This is what you do when you develop the upper layer(s) against a simulation of the hardware, and then substitute in the real hardware.

Also layers, modules, indeed architecture itself, are means of making computer programs easier to understand by humans. 

🔗 **Source:** [stackoverflow.com](https://softwareengineering.stackexchange.com/questions/13439/what-defines-a-software-architect)


## Q7: What Do You Mean By High Availability? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q8: What Is Middle Tier Clustering? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q9: What Is Load Balancing? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q10: What Is Sticky Session Load Balancing? What Do You Mean By "Session Affinity"? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q11: What Is Fail Over? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q12: What Is Session Replication? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q13: What Is ACID Property Of A System? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q14: How Do You Update A Live Heavy Traffic Site With Minimum Or Zero Down Time? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q15: What does SOLID stand for? What are its principles? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q16: How can you keep one copy of your utility code and let multiple consumer components use and deploy it? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q17: "People who like this also like... ". How would you implement this feature in an e-commerce shop? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q18: What are the DRY and DIE principles? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q19: Is it better to return NULL or empty values from functions/methods where the return value is not present? ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q20: Explain the Single Responsibility Principle?  ⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q21: What Is IP Address Affinity Technique For Load Balancing? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q22: What Is Sharding? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q23: What Is BASE Property Of A System? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q24: Why should you structure your solution by components? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q25: Why layering your application is important? Provide some bad layering example. ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q26: Defend the monolithic architecture. ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q27: Explain threads to your grandparents ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q28: How to handle exceptions in a layered application? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q29: What's the difference between principles YAGNI and KISS? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q30: What is GOD class and why should we avoid it? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q31: Could you provide an example of the Single Responsibility Principle? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q32: What is actor model in context of a programming language? ⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q33: What Is CAP Theorem? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q34: What Does Eventually Consistent Mean? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q35: What Is Shared Nothing Architecture? How Does It Scale? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q36: What are heuristic exceptions? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q37: Are you familiar with The Twelve-Factor App principles? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**


## Q38: Why is writing software difficult? What makes maintaining software hard? ⭐⭐⭐⭐⭐

 See 👉 **[Answer](https://www.fullstack.cafe/Software%20Architecture)**



