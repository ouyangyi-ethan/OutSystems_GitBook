### **Video3 \(Create a Detail Screen for a Record\)**

1. Think of this as creating a Record Summary View in Appian.

2. You can link each Contact to the relevant `ContactDetail` screen.

3. The `ContactDetail` screen will take a Input Parameter called `ContactId` - to show the details of the clicked Contact. Think of it like a `Rule Parameter - ri!` in Appian. You can create multiple Input parameters for each Web Screen.

4. Instead of having something called a `a!recordLink()` , you can use the `Link to` feature from the UI, then select the destination web screen.

5. You need to provide the `CurrentRecord.ContactId` - which will be set to the property of the Link.


