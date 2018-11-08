### Questions

> Read React's documentation on Lifting State Up.

**A.**
I have read React's documentation on lifting states up and followed its temperature converter app creation.

> Read Why does React emphasize on unidirectional data flow and Flux architecture? on Hashnode.

**A.**
I have read the article mentioned and understood more about unidirectional data flow.


> Why does React only allow information to be passed down in the hierarchy? What are the advantages and disadvantages of this approach? Discuss this topic with your mentor.

**A.**
 React does not encourage bi-directional binding to make sure you are following a clean data flow architecture. React's approach provides more control over data flow (from parent to child) and it avoids the possible unwanted "side effects" that produce a two-way data flow approach while handling data. In unidirectional data flow, data that changes in the child component will not necessarily produce changes on parent components or even higher on the app component, unless you really want to update something via a callback on a component of higher hierarchy, but in this case the logic would still belong to a parent component.



Advantages of top-bottom data flow
1. Easier to debug
2. More control over where data should change and not having changes in multiple (unwanted) places at once
3. Easier to control state updates. Application data and state are **NOT** manipulated from two ways
4. Suitable for complex applications
5. Predictable application state

Disadvantages of top-bottom data flow
1. Some rework around the higher level flows may have to occur later in the development
2. Point 1 could add risk and cost to the final design and implementation

###### *Submitted by Cesar Jimenez*
