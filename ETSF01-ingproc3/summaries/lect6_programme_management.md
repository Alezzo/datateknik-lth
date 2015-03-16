# Programme & Portfolio Management

## Project: Business case & contracts

A business case may be presented for several potential projects. It should show
that the benefits of the project will exceed development, implementation and 
operational costs. This is part of portfolio management. 

###Content of a business case:###

<dl>
  <dt>Introduction/background</dt>
  <dd>describes a problem to be solved or an oppertunity to be exploited.</dd>
  <dt>The proposed project</dt>
  <dd>a brief outline of the project scope.</dd>
  <dt>The market</dt>
  <dd>the project could be to develop a new product. The likely <em>demand for the
    product</em> is assessed.</dd>
  <dt>Organizational/Operational infrastructure</dt>
  <dd>describes how the structure of the organization will be afftected by the
    implementation of the project.</dd>
  <dt>Benefits</dt>
  <dd>These should be expressed in financial terms.</dd>
  <dt>Outline implementation plan</dt>
  <dd>how the project is going to be implemented.</dd>
  <dt>Costs</dt>
  <dd>the implementation plan will supply information to establish these.</dd>
  <dt>Financial plan</dt>
  <dd>combines costs and benefit data to establish value of project.</dd>
  <dt>Risks</dt>
  <dd>initial risk analysis to identify risks to project execution and to
    business aspects that affect profit.</dd>
  <dt>Management Plan</dt>
  <dd>Missing information but part of the business plan.
</dl>

### Selection of project approach

*steps from Step Wise chart*

- **2 Organization structure needed**
  - Make/buy/outsource
  - Make/reuse/
  - Make/share
  - ...

- **3 Process model**

### Buying from external suppliers

  Different buy-situations:
* **Bespoke system/component**
* **Outsourcing a task**
* **Commercial off-the-shelf (COTS)**
  - bought *as is*
  - customized

### Types of contract
* **Fixed price contracts**: fixed price, terms, requirements & delivery time
  - + known cost, supplier motivation
  - - higher price to absorb the additional risk, frozen requirements,
  *impossible* cost -- quality risk
* **Time and materails contracts**: fixed rate/unit of effort
  - + requirements changes, lack of price pressure
  - - customer liability due to uncertain cost & commitment, lack of incentive
      for supplier
* **Fixed price per delivered unit**: incremental delivery and payment => a
    series of contracts
  - + customer understanding price calculation, comparability between pricing
      schedules, emerging functionality can be accounted, supplier motivated to
      be cost-effective
  - - difficulties with SW size measurement - may need independent fixed price
      counter, changing requirements - how do you charge?

### Cost-benefit analysis (CBA) 

* **Identify all the costs which could be:**
  - development costs incl buy-ins
  - set-up incl recruitment and training
  - operational costs after set-up
* **Identify the value of benefits**
* **Check if benefits are greater than costs**

*Costs and benefits must be identified and expressed in the same unit..*

**Liftime of Return on Investment (ROI) for potential project**

* **Estimate timing costs and income**
* **Development incurs costs**
* **Release of system/product generates income - gradual pay off**
* **Include decommissioning cost**

Typical project life cycle cash flow
```
  |
i |
n |
c |                              *      *
o |                        *                     *
m |                     *                                *
e |                   *                                           *
---------------------*--------------------------------------------------*-----*-
e |*                *                                            time -> *   *
x | *              *                                                       *
p |  *            *
e |   *          *
n |     *       *
d |        *  *
i |
t |
u |
r |
e |
```

**Cost-benefit evaluation techniques**

* **Return on investment (ROI) or also known as Accounting Rate of Return (ARR) 
  = Net profit / total investment.**

  Also useful for company individual choices
  or features.
* **Net profit:** 
  - total income - total cost
* **Payback period:** 
  - time to break even

```
      average annual profit
ROI = --------------------- X 100
        total investment

      value in year t
NPV = ---------------
         (1 + r)^t
```

* **Net present-value**
  - Present value of future cash flow
* **Internal rate of return (IRR)**
  - Internal rate of return (IRR) is the discount rate that would produce an NPV
    of 0 for the project
  - Can be used to compare different investment opportunities
  - There is e.g. a Microsoft Excel function which can be used to calculate the
    IRR (or use a suitable technique from numerical analysis)

## Portfolio Management (PM) 

Porfolio project management provides an overview of all the projects that an
organisation is undertaking or is considering. The optimization coverage of 
product ranges and market segment are need & profit.

* **Predicting market**
* **Evaluating proposals for projects**
* **Checking for gaps & overlaps**

For potential projects
* **Balance total risk**
* **Resource sharing**
* **Dependencies between projects**

**Probability of**

```
               success
             high ^ 
                  |
                  |
                  |
    xxx           |               x  
  xxxxxxx         |              xxx
    xxx           |               x
----------------------------------------> Profit
low               |        xxxxxx   high
          xx      |       xxxxxxxx    
        xxxxxx    |        xxxxxx 
          xx      |
                  |
             low  |
```                  
                  
**Optimize Over Time**

```

-----------------
|  Project 1    |
-----------------

--------------------------------------------------------------------
|  Project 2                                                       |
--------------------------------------------------------------------

                --------------------------------
                |   Project 3                  |
                --------------------------------

                                      ---------------------------------------
                                      |   Project 4                         |
                                      ---------------------------------------
------------------------------------------------------------------------------>
                                                                        time t
```
**Issues with PM**

* **Will another project be more profitable?**
* **Hard to express benefits in financial terms**
* **Projects with the highest potential returns are often the most risky**

##Programme Management

**One definition:**  
*a group of projects that are managed in a* **_co-ordinated_** *way to* **_gain benefits_**
 *that would not be possible where the projects to be managed independently*
* **Business cycle programmes - common time & resources**
* **Strategic - with common goal**
* **Infrastructure programmes - e.g. IT support projects**
* **Research & developemt (R&D) development programmes - *safe* + *risky* projects**
* **Innovative partnerships - new technologies, precompetitive**

**Responsibilities of a program manager**
```
_________________________________________________
|                                               |
|   Stakeholders, sponsors                      |
|_______________________________________________|
                      /\ 
                     /  \        |*Vision
                      ||         |*Mandate
                 _____||_____    |*Cost estimates of projects
                 |  Program |   / *Risk for projects
                 |  Manager |   \ *Resources
                 -----||-----    |* ...
                      ||         |
                     \  /        |
                      \/
------------------------------------------------
|                                              |
|   Projects                                   |
|______________________________________________|
```

**Project Management at Programme Level**
```
High Level activity plan

  B                                            G 
  --------------                               --------------
  |Corporate   |_____________________________\ |Impl. corp  |
  |image design|                 /|\         / |interface   |
  --------------                  |            --------------
                                  |
A                 C               |            F
--------------    --------------  |            --------------
|System study|___\|Build common|__|___________\|Data        |
|/design     | | /|systems     |  |           /|migration   |
-------------- |  --------------  |            -------------- 
               |  D               |   E               /|\
               |  --------------  |   --------------   |
               |_\|Relocate    |_\|/_\|Training    |___|
                 /|offices     |     /|            |
                  --------------      -------------                  
```
To this activity plan, an Gantt chart is made to overview the plan.

