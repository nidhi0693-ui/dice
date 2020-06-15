1. Simple a dice rolling application.

2. First we click a button and the very base functionality is that we have random dice rolls showing up.

3. We'll have the app component that renders a rolled dice component.

4. The parent component that manages the state of the dice basically keeping track of what the roles are and it will render two die components.

5. The die component is one of the component which doesn't have any state.

6. It's not a state full component all that it does is it accepts props and it will use that prop to display the correct face of the die.

7. So the state is going to be managed in the parent that is controlling the to die.

8. And so when the state changes it will re render these to die and pass and new props for eg - three or six etc.

9. This app just going to focus on two dice and then there needs to be a roll method and that roll method is going to be triggered by a click.

10. When you click on a button it should call that roll method which should then randomly get two new numbers from one to six.

