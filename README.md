# life-cycle-in-React

A simple repo about life cycle methods of a component in React.

1.The componentDidMount() method (<b>this method is called when a component is mounted/placed on the DOM.</b>)

It is called once in the component life cycle and it signals that the component and all its sub-components have rendered properly. This is the best place to make API calls since, at this point, the component has been mounted and is available to the DOM.When one wants to fetch data or make an Ajax request.It is usually done inside this method.
