### **Video7 \(Create and Display a Relationship\)**

1. You can generate Entity Diagram by going under "Data". You can click on "Add Entity Diagram". Then you can add Entities in it.

2. To add a relationship between Company and Contact, we created a `CompanyId` attribute in the Contact entity. The platform understands automatically that you mean to create a foreign key that references the Id in the Company Entity. It updates the data model accordingly. The Entity diagram will get updated automatically and display the updated relationship. Note: It is possible to view what SQL query will actually be executed and the type of Join that will be used.

3. In the Contact Details Web Screen, you can now add the `CompnayId` attribute in the Form Widget. The platform will automatically create a combo box with the associated Company Names. The platform infers that the Name attribute of the Company is the appropriate attribute to show in the combo box.

4. Thus, you can now associate a Contact with a Company on the UI. For every contact, you will be presented with the available Companies to choose from.


