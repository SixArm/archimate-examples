# ArchiMate summary

## ArchiMate terminology

ArchiMate terminology focuses on these categories of words, that range from high-level to low-level:

* Motivation words
* Strategy words
* Business words
* Application words
* Technology words
* Physical words
* Implementation words

### Motivation words

* Stakeholder: the role of an individual, team, or organization (or classes thereof) that represents their interests in the effects of the architecture.

* Driver: an external or internal condition that motivates an organization to define its goals and implement the changes necessary to achieve them.

* Assessment: the result of an analysis of the state of affairs of the enterprise with respect to some driver.

* Goal: a high-level statement of intent, direction, or desired end state for an organization and its stakeholders.

* Outcome: an end result.

* Principle: a statement of intent defining a general property that applies to any system in a certain context in the architecture.

* Requirement: a statement of need defining a property that applies to a specific system as described by the architecture.

* Constraint: a factor that limits the realization of goals.

* Meaning: the knowledge or expertise present in, or the interpretation given to, a concept in a particular context.

* Value: the relative worth, utility, or importance of a concept.

### Strategy words

* Resource: an asset owned or controlled by an individual or organization.

* Capability: an ability that an active structure element, such as an organization, person, or system, possesses.

* Value stream: a sequence of activities that create an overall result for a customer, stakeholder, or end user.

* Course of action: an approach or plan for configuring some capabilities and resources of
the enterprise, undertaken to achieve a goal.

### Business words

* Business actor: a business entity that is capable of performing behavior.

* Business role: the responsibility for performing specific behavior, to which an actor can be assigned, or the part an actor plays in a particular action or event.

* Business collaboration:  an aggregate of two or more business internal active structure elements that work together to perform collective behavior.

* Business interface: a point of access where a business service is made available to the
environment.

* Business process: a sequence of business behaviors that achieves a specific result such as a defined set of products or business services.

* Business function:  a collection of business behavior based on a chosen set of criteria (typically required business resources and/or competencies), closely aligned to an organization, but not necessarily explicitly governed by the organization.
  
* Business interaction: a unit of collective business behavior performed by (a collaboration of) two or more business actors, business roles, or business collaborations.


* Business event: an organizational state change.

* Business service: explicitly defined behavior that a business role, business actor, or business collaboration exposes to its environment.

* Business object: a concept used within a particular business domain.

* Contract: a formal or informal specification of an agreement between a provider and a consumer that specifies the rights and obligations associated with a product and establishes functional and non-functional parameters for interaction.

* Representation: a perceptible form of the information carried by a business object.

* Product: a coherent collection of services and/or passive structure elements, accompanied by a contract/set of agreements, which is offered as a whole to (internal or external) customers.

### Application words

* Application component: an encapsulation of application functionality aligned to implementation structure, which is modular and replaceable.

* Application collaboration: an aggregate of two or more application internal active structure elements that work together to perform collective application behavior.

* Application interface: a point of access where application services are made available to a user, another application component, or a node.

* Application function: automated behavior that can be performed by an application component.

* Application interaction: a unit of collective application behavior performed by (a collaboration of) two or more application components.

* Application process: a sequence of application behaviors that achieves a specific result.

* Application event: an application state change.

* Application service: an explicitly defined exposed application behavior.

* Data object: data structured for automated processing.

### Technology words

* Node: a computational or physical resource that hosts, manipulates, or interacts with other computational or physical resources.

* Device: a physical IT resource upon which system software and artifacts may be stored or deployed for execution.

* System software: software that provides or contributes to an environment for storing, executing, and using software or data deployed within it.

* Technology collaboration: an aggregate of two or more technology internal active structure elements that work together to perform collective technology behavior.

* Technology interface: a point of access where technology services offered by a node can be accessed.

* Path: a link between two or more nodes, through which these nodes can exchange data, energy, or material.

* Communication network: a set of structures that connects nodes for transmission, routing, and reception of data.

* Technology function: a collection of technology behavior that can be performed by a node.

* Technology process: a sequence of technology behaviors that achieves a specific result.

* Technology interaction: a unit of collective technology behavior performed by (a collaboration of) two or more nodes.

* Technology event: a technology state change.

* Technology service: an explicitly defined exposed technology behavior.

* Artifact: a piece of data that is used or produced in a software development process, or by deployment and operation of an IT system.

### Physical words

* Equipment: one or more physical machines, tools, or instruments that can create, use, store, move, or transform materials.
  
* Facility: a physical structure or environment.
  
* Distribution network: a physical network used to transport materials or energy.

* Material: tangible physical matter or energy.

### Implementation words

* Work package: a series of actions identified and designed to achieve specific results within specified time and resource constraints.

* Deliverable: a precisely-defined result of a work package.

* Implementation event: a state change related to implementation or migration.

* Plateau: a relatively stable state of the architecture that exists during a limited period of time.

* Gap: a statement of difference between two plateaus.

## ArchiMate diagramming

ArchiMate diagramming focuses on these categories of elements, that range from high-level to low-level:

* Motivation elements
* Strategy elements
* Business elements
* Application elements
* Technology elements
* Physical elements
* Implementation elements

### Motivation elements

<table>
  <thead>
    <tr>
      <th>Element</th>
      <th>Definition</th>
      <th>Notation</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Stakeholder</td>
      <td>the role of an individual, team, or organization (or classes thereof) that represents their interests in the effects of the architecture.</td>
      <td><img width="104" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image095.png" /></td>
      <td>CEO at ACME</td>
    </tr>
    <tr>
      <td>Driver</td>
      <td>an external or internal condition that motivates an organization to define its goals and implement the changes necessary to achieve them.</td>
      <td><img width="104" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image097.png" /></td>
      <td>Customer satisfaction</td>
    </tr>
    <tr>
      <td>Assessment</td>
      <td>the result of an analysis of the state of affairs of the enterprise with respect to some driver.</td>
      <td><img width="104" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image099.png" /></td>
      <td>Net Promoter Score is 25</td>
    </tr>
    <tr>
      <td>Goal</td>
      <td>a high-level statement of intent, direction, or desired end state for an organization and its stakeholders.</td>
      <td><img width="105" height="47" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image101.png" /></td>
      <td>Increase customer satisfaction as measured by Net Promoter Score.</td>
    </tr>
    <tr>
      <td>Outcome</td>
      <td>an end result.</td>
      <td><img width="104" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image103.png" /></td>
      <td>Net Promoter Score is 30+ by end of quarter.</td>
    </tr>
    <tr>
      <td>Principle</td>
      <td>a statement of intent defining a general property that applies to any system in a certain context in the architecture.</td>
      <td><img width="103" height="47" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image105.png" /></td>
      <td>We speak directly with customers to learn from them.</td>
    </tr>
    <tr>
      <td>Requirement</td>
      <td>a statement of need defining a property that applies to a specific system as described by the architecture.</td>
      <td><img width="197" height="47" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image107.png" /></td>
      <td>Hire 5 customer service representatives</td>
    </tr>
    <tr>
      <td>Constraint</td>
      <td>a factor that limits the realization of goals.</td>
      <td><img width="198" height="47" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image108.png" /></td>
      <td>Hiring customer service representatives and training them takes time and costs money.</td>
    </tr>
    <tr>
      <td>Meaning</td>
      <td>the knowledge or expertise present in, or the interpretation given to, a concept in a particular context.</td>
      <td><img width="104" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image109.png" /></td>
      <td>Successful customer onboarding</td>
    </tr>
    <tr>
      <td>Value</td>
      <td>the relative worth, utility, or importance of a concept.</td>
      <td><img width="104" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image110.png" /></td>
      <td>A customer generates what they want twice as fast</td>
    </tr>
  </tbody>
</table>

### Strategy elements

<table>
  <thead>
    <tr>
      <th>Element</th>
      <th>Description</th>
      <th>Notation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Resource</td>
      <td>an asset owned or controlled by an individual or organization.</td>
      <td><img width="88" height="42" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image123.png" /></td>
    </tr>
    <tr>
      <td>Capability</td>
      <td>an ability that an active structure element, such as an organization, person, or system, possesses.</td>
      <td><img width="88" height="42" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image125.png" /></td>
    </tr>
    <tr>
      <td>Value stream</td>
      <td>a sequence of activities that &nbsp;create an overall result for a customer, stakeholder, or end user.</td>
      <td><img width="87" height="42" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image127.png" /><img width="75" height="35" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image128.png" /></td>
    </tr>
    <tr>
      <td>Course of action</td>
      <td>an approach or plan for configuring some capabilities and resources of the enterprise, undertaken to achieve a goal.</td>
      <td><img width="88" height="42" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image129.png" /></td>
    </tr>
  </tbody>
</table>

### Business elements

<table>
  <thead>
    <tr>
      <td>Element</td>
      <td>Description</td>
      <td>Notation</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Business actor</td>
      <td>a business entity that is capable of performing behavior.</td>
      <td><img width="164" height="49" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image154.png"></td>
    </tr>
    <tr>
      <td>Business role</td>
      <td>the responsibility for performing specific behavior, to which an actor can be assigned, or the part an actor plays in a particular action or event.</td>
      <td><img width="191" height="49" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image155.png"></td>
    </tr>
    <tr>
      <td>Business collaboration</td>
      <td>an aggregate of two or more business internal active structure elements that work together to perform collective behavior.</td>
      <td><img width="185" height="51" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image156.png"></td>
    </tr>
    <tr>
      <td>Business interface</td>
      <td>a point of access where a business service is made available to the environment.</td>
      <td><img width="168" height="46" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image157.png"></td>
    </tr>
    <tr>
      <td>Business process</td>
      <td>a sequence of business behaviors that achieves a specific result such as a defined set of products or business services.</td>
      <td><img width="191" height="49" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image158.png"></td>
    </tr>
    <tr>
      <td>Business function</td>
      <td>a collection of business behavior based on a chosen set of criteria (typically required business resources and/or competencies), closely aligned to an organization, but not necessarily explicitly governed by the organization.</td>
      <td><img width="180" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image159.png"></td>
    </tr>
    <tr>
      <td>Business interaction</td>
      <td>a unit of collective business behavior performed by (a collaboration of) two or more business actors, business roles, or business collaborations.</td>
      <td><img width="180" height="49" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image160.png"></td>
    </tr>
    <tr>
      <td>Business event</td>
      <td>an organizational state change.</td>
      <td><img width="187" height="49" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image161.png"></td>
    </tr>
    <tr>
      <td>Business service</td>
      <td>explicitly defined behavior that a business role, business actor, or business collaboration exposes to its environment.</td>
      <td><img width="187" height="49" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image162.png"></td>
    </tr>
    <tr>
      <td>Business object</td>
      <td>a concept used within a particular business domain.</td>
      <td><img width="103" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image163.png"></td>
    </tr>
    <tr>
      <td>Contract</td>
      <td>a formal or informal specification of an agreement between a provider and a consumer that specifies the rights and obligations associated with a product and establishes functional and non-functional parameters for interaction.</td>
      <td><img width="103" height="47" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image164.png"></td>
    </tr>
    <tr>
      <td>Representation</td>
      <td>a perceptible form of the information carried by a business object.</td>
      <td><img width="103" height="62" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image165.png"></td>
    </tr>
    <tr>
      <td>Product</td>
      <td>a coherent collection of services and/or passive structure elements, accompanied by a contract/set of agreements, which is offered as a whole to (internal or external) customers.</td>
      <td><img width="103" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image166.png"></td>
    </tr>
  </tbody>
</table>

### Application elements

<table>
  <thead>
    <tr>
      <td>Element</td>
      <td>Definition</td>
      <td>Notation</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Application component</td>
      <td>an encapsulation of application functionality aligned to implementation structure, which is modular and replaceable.</td>
      <td><img width="212" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image182.png"></td>
    </tr>
    <tr>
      <td>Application collaboration</td>
      <td>an aggregate of two or more application internal active structure elements that work together to perform collective application behavior.</td>
      <td><img width="192" height="53" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image183.png"></td>
    </tr>
    <tr>
      <td>Application interface</td>
      <td>a point of access where application services are made available to a user, another application component, or a node.</td>
      <td><img width="189" height="54" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image184.png"></td>
    </tr>
    <tr>
      <td>Application function</td>
      <td>automated behavior that can be performed by an application component.</td>
      <td><img width="188" height="51" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image185.png"></td>
    </tr>
    <tr>
      <td>Application interaction</td>
      <td>a unit of collective application behavior performed by (a collaboration of) two or more application components.</td>
      <td><img width="191" height="52" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image186.png"></td>
    </tr>
    <tr>
      <td>Application process</td>
      <td>a sequence of application behaviors that achieves a specific result.</td>
      <td><img width="201" height="52" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image187.png"></td>
    </tr>
    <tr>
      <td>Application event</td>
      <td>an application state change.</td>
      <td><img width="201" height="52" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image188.png"></td>
    </tr>
    <tr>
      <td>Application service</td>
      <td>an explicitly defined exposed application behavior.</td>
      <td><img width="205" height="51" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image189.png"></td>
    </tr>
    <tr>
      <td>Data object</td>
      <td>data structured for automated processing.</td>
      <td><img width="106" height="50" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image190.png"></td>
    </tr>
  </tbody>
</table>

### Technology elements

<table>
  <thead>
    <tr>
      <td>Element</td>
      <td>Definition</td>
      <td>Notation</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Node</td>
      <td>a computational or physical resource that hosts, manipulates, or interacts with other computational or physical resources.</td>
      <td><img width="228" height="57" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image211.png"></td>
    </tr>
    <tr>
      <td>Device</td>
      <td>a physical IT resource upon which system software and artifacts may be stored or deployed for execution.</td>
      <td><img width="213" height="56" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image212.png"></td>
    </tr>
    <tr>
      <td>System software</td>
      <td>software that provides or contributes to an environment for storing, executing, and using software or data deployed within it.</td>
      <td><img width="217" height="54" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image213.png"></td>
    </tr>
    <tr>
      <td>Technology collaboration</td>
      <td>an aggregate of two or more technology internal active structure elements that work together to perform collective technology behavior.</td>
      <td><img width="206" height="57" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image214.png"></td>
    </tr>
    <tr>
      <td>Technology interface</td>
      <td>a point of access where technology services offered by a node can be accessed.</td>
      <td><img width="209" height="56" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image215.png"></td>
    </tr>
    <tr>
      <td>Path</td>
      <td>a link between two or more nodes, through which these nodes can exchange data, energy, or material.</td>
      <td><img width="207" height="54" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image216.png"></td>
    </tr>
    <tr>
      <td>Communication network</td>
      <td>a set of structures that connects nodes for transmission, routing, and reception of data.</td>
      <td><img width="208" height="54" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image217.png"></td>
    </tr>
    <tr>
      <td>Technology function</td>
      <td>a collection of technology behavior that can be performed by a node.</td>
      <td><img width="202" height="53" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image218.png"></td>
    </tr>
    <tr>
      <td>Technology process</td>
      <td>a sequence of technology behaviors that achieves a specific result.</td>
      <td><img width="212" height="53" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image219.png"></td>
    </tr>
    <tr>
      <td>Technology interaction</td>
      <td>a unit of collective technology behavior performed by (a collaboration of) two or more nodes.</td>
      <td><img width="204" height="53" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image220.png"></td>
    </tr>
    <tr>
      <td>Technology event</td>
      <td>a technology state change.</td>
      <td><img width="215" height="53" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image221.png"></td>
    </tr>
    <tr>
      <td>Technology service</td>
      <td>an explicitly defined exposed technology behavior.</td>
      <td><img width="213" height="53" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image222.png"></td>
    </tr>
    <tr>
      <td>Artifact</td>
      <td>a piece of data that is used or produced in a software development process, or by deployment and operation of an IT system.</td>
      <td><img width="201" height="53" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image223.png"></td>
    </tr>
  </tbody>
</table>

### Physical elements

<table>
  <thead>
    <tr>
      <td>Element</td>
      <td>Definition</td>
      <td>Notation</td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Equipment</td>
      <td>one or more physical machines, tools, or instruments that can create, use, store, move, or transform materials.</td>
      <td><img width="116" height="56" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image233.png"></td>
    </tr>
    <tr>
      <td>Facility</td>
      <td>a physical structure or environment.</td>
      <td><img width="116" height="56" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image235.png"></td>
    </tr>
    <tr>
      <td>Distribution network</td>
      <td>a physical network used to transport materials or energy.</td>
      <td><img width="221" height="52" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image237.png"></td>
    </tr>
    <tr>
      <td>Material</td>
      <td>tangible physical matter or energy.</td>
      <td><img width="107" height="51" src="https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image238.png"></td>
    </tr>
  </tbody>
</table>

## Implementation elements

<table>
  <thead>
    <tr>
      <td>Element</td>
      <td>Definition</td>
      <td>Notation</td>
    </tr>
  </thead>
  <tbody>
    <tr>
        <td>Work package</td>
        <td>a series of actions identified and designed to achieve specific results within specified time and resource constraints.</td>
        <td><img width="109" height="50" id="Picture 214" src=\"https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image252.png"></td>
    </tr>
    <tr>
        <td>Deliverable</td>
        <td>a precisely-defined result of a work package.</td>
        <td><img width="109" height="50" id="Picture 215" src=\"https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image253.png"></td>
    </tr>
    <tr>
        <td>Implementation event</td>
        <td>a state change related to implementation or migration.</td>
        <td><img width="202" height="50" id="Picture 216" src=\"https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image254.png"></td>
    </tr>
    <tr>
        <td>Plateau</td>
        <td>a relatively stable state of the architecture that exists during a limited period of time.</td>
        <td><img width="192" height="49" id="Picture 217" src=\"https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image255.png"></td>
    </tr>
    <tr>
      <td>Gap</td>
        <td>a statement of difference between two plateaus.</td>
        <td><img width="200" height="49" id="Picture 218" src=\"https://pubs.opengroup.org/architecture/archimate31-doc/ts_archimate_3.1-final_files/image256.png"></td>
    </tr>
  </tbody>
</table>
