# Three different SDLC methodologies
## **Waterfall Model**
Waterfall model is the very first model that is used in SDLC. It is also known as the linear sequential model.
In this model, the outcome of one phase is the input for the next phase. Development of the next phase starts only when the previous phase is complete.
* First, Requirement gathering and analysis is done. Once the requirement is freeze then only the System Design can start. Herein, the SRS document created is the output for the Requirement phase and it acts as an input for the System Design.
* In System Design Software architecture and Design, documents which act as an input for the next phase are created i.e. Implementation and coding.
* In the Implementation phase, coding is done and the software developed is the input for the next phase i.e. testing.
* In the testing phase, the developed code is tested thoroughly to detect the defects in the software. Defects are logged into the defect tracking tool and are retested once fixed. *Bug logging, Retest, Regression testing goes on until the time the software is in go-live state.
* In the Deployment phase, the developed code is moved into production after the sign off is given by the customer.
* Any issues in the production environment are resolved by the developers which come under maintenance.

![Image][1](https://github.com/afk95/GMT-456/blob/main/SDLC_Models_img/Waterfall-Model-1.jpg?raw=true)

> **Advantages of the Waterfall Model:**

- Waterfall model is the simple model which can be easily understood and is the one in which all the phases are done step by step.
- Deliverables of each phase are well defined, and this leads to no complexity and makes the project easily manageable.

> **Disadvantages of Waterfall model:**

- Waterfall model is time-consuming & cannot be used in the short duration projects as in this model a new phase cannot be started until the ongoing phase is completed.
- Waterfall model cannot be used for the projects which have uncertain requirement or wherein the requirement keeps on changing as this model expects the requirement to be clear in the requirement gathering and analysis phase itself and any change in the later stages would lead to cost higher as the changes would be required in all the phases.

## Prototype Model
The prototype model is a model in which the prototype is developed prior to the actual software.

Prototype models have limited functional capabilities and inefficient performance when compared to the actual software. Dummy functions are used to create prototypes. This is a valuable mechanism for understanding the customers’ needs.

Software prototypes are built prior to the actual software to get valuable feedback from the customer. Feedbacks are implemented and the prototype is again reviewed by the customer for any change. This process goes on until the model is accepted by the customer.

Once the requirement gathering is done, the quick design is created and the prototype which is presented to the customer for evaluation is built.

Customer feedback and the refined requirement is used to modify the prototype and is again presented to the customer for evaluation. Once the customer approves the prototype, it is used as a requirement for building the actual software. The actual software is build using the Waterfall model approach.

![Image](https://github.com/afk95/GMT-456/blob/main/SDLC_Models_img/Prototype-Model.jpg?raw=true)

> **Advantages of Prototype Model:**

- Prototype model reduces the cost and time of development as the defects are found much earlier.
- Missing feature or functionality or a change in requirement can be identified in the evaluation phase and can be implemented in the refined prototype.
- Involvement of a customer from the initial stage reduces any confusion in the requirement or understanding of any functionality.

> **Disadvantages of Prototype Model:**

- Since the customer is involved in every phase, the customer can change the requirement of the end product which increases the complexity of the scope and may increase the delivery time of the product.

## Agile Model

Agile Model is a combination of the Iterative and incremental model. This model focuses more on flexibility while developing a product rather than on the requirement.

In Agile, a product is broken into small incremental builds. It is not developed as a complete product in one go. Each build increments in terms of features. The next build is built on previous functionality.

In agile iterations are termed as sprints. Each sprint lasts for2-4 weeks. At the end of each sprint, the product owner verifies the product and after his approval, it is delivered to the customer.

Customer feedback is taken for improvement and his suggestions and enhancement are worked on in the next sprint. Testing is done in each sprint to minimize the risk of any failures.

![Image](https://github.com/afk95/GMT-456/blob/main/SDLC_Models_img/Agile-Model.jpg?raw=true)

> **Advantages of Agile Model:**

- It allows more flexibility to adapt to the changes.
- The new feature can be added easily.
- Customer satisfaction as the feedback and suggestions are taken at every stage.

> **Disadvantages:**

- Lack of documentation.
- Agile needs experienced and highly skilled resources.
If a customer is not clear about how exactly they want the product to be, then the project would fail.



[References](https://www.softwaretestinghelp.com/software-development-life-cycle-sdlc/)
