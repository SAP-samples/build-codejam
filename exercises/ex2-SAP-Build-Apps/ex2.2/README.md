# Exercise 2.2 - Populate Dropdown with SAP Data (ES5)

In this exercise, we want to create a dropdown list for selecting the product, instead of an input field, to make it easier for the user.

![Process](/images/ex2.2/run-dropdown.png)

The data for the dropdown list will be coming from the [demo ES5 system](https://blogs.sap.com/2017/06/16/netweaver-gateway-demo-es5-now-in-beta/), a system used by developers working with SAP Fiori, SAP BTP and other SAP systems.

>You do not have to directly connect with the ES5 system. We have already created a destination, with the proper credentials.

You will do the following in the exercise:

- Set up a connection to the ES5 system (using the destination).

- Create a data variable to hold the retrieved data.

- Add and configure a dropdown list into the UI.

  
## Exercises

Perform all the steps in 👉 tutorial: 

- [Populate Dropdown with SAP Data (ES5)](https://developers.sap.com/tutorials/build-apps-workflow-es5.html)


## Summary

You have now learned how to to connect to a backend data source using an SAP BTP destination, how to add a more sophisticated control, and how to configure a dropdown list.

In the dropdown list binding, you also saw a more sophisticated formula that takes data and filters/massages it for the needs of a component.


### Questions for Discussion

- What other ways could you use formulas, especially for manipulating data?
  
- When you import a project inside an existing project, how does SAP Build Apps merge the contents in the project with the contents of the imported project?

- What ways could we improve the app we just built? 

- What types of data resources can you create?

- How would compare the usefulness of the Formula binding with the Object with properties binding? Did you notice anything about what happens when you go from Formula to Object with properties binding, as opposed to the other way around? 
  

## Further Study

- [Formula functions (reference)](https://docs.appgyver.com/docs/formula-functions)

- [No-code App Programming 101 — Part 5 — Functions pt. 2 (video)](https://www.youtube.com/watch?v=ndJqYw4wMmc)

- [Master SAP Build Apps by Adding Social Media Features to a Business App (video)](https://www.youtube.com/watch?v=VD_99hHU_L0)

## Next

Continue to 👉 [Exercise 2.3 - Check Status of Process from SAP Build App](../ex2.3/README.md)
