## **OutSystems Developer Terminology:**

These are some terms used in OutSystems Platform.

* **Preparation** - a preparation is always associated with a Web Screen. It has the logic to execute to render that Web Screen. It may also have the logic to execute after a Web Screen is submitted.

* **Web Screen** - This is a counter-part to the `SAIL UI Interface` or `User Input Task` in Appian. It can take input variables. You can have `if` expressions on a Web Screen to conditionally show or hide UI components based on the input variables. The logic for rendering a Web Screen depends on the input variables that it takes. This is shown by a Rectangle with blue border.

* **Web Block** - a re-usable screen that can be used in other Web Screens

* **NullIdentifier** - This is used for stating that the Identifier \(Id of some entity\) is null. This is a special variable.

* **Action** - An Action encapsulates custom logic to be executed on the server side. Multiple actions can be used in a **Preparation**. In a way, an Action is like a Smart Service in Appian. These are black-boxes whose implementation is usually hidden. Example: An Action maybe like "CreateOrUpdateContact", "DeleteContact" etc. An Action is shown by an Orange icon in the Service Studio.

* **Screen Action** - A screen action is used for things like submitting the data from a form to the server.

* **UI IF** - A UI If conditional allows you to conditionally display or hide a UI component.


