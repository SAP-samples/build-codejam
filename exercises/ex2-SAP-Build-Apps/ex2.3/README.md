# Exercise 2.3 - Check Status of Process from SAP Build App (optional)
 

In this exercise, we will create a record of the processes we trigger by storing each process instance's ID in the local device storage, and then use an SAP Build Process Automation API to check the status of the process.

You will also see how to create another page in your app, and to use the Navigation feature to go between the 2 pages.

![Process](/images/ex2.3/data-rerun.png)


## Exercises

Perform all the steps in 👉 tutorial: 

- [Check Status of Process from SAP Build App](https://developers.sap.com/tutorials/build-apps-workflow-check-status.html)


## Summary

You have now created a new page to keep track of the processes started by the user, and to let the user retrieve the current status of the process instance.



### Questions for Discussion

- What types of data do you think makes sense to store in on-device storage?

- Do you think for this use case that on-device storage makes sense?

- What other SAP Build Process Automation APIs are there -- see [SAP API Business Hub](https://api.sap.com/package/SAPProcessAutomation/all) -- and why might you use them? 

- To get the information about the process instance, we created a new data resource, and also used the "Create" method to make the API call. Could we have used the Trigger Workflow data resource we created in the earlier tutorial? Why or Why not?
   

## Further Study

* [SAP Build Process Automation APIs](https://api.sap.com/package/SAPProcessAutomation/all)
  
* [Navigation (Documentation)](https://docs.appgyver.com/docs/en/navigation)
* [No-code Power-up: Custom Flow Functions (video)](https://www.youtube.com/watch?v=L4DUOvNQ46M)

## Next

Continue to 👉 [Exercise 2.4 - Deploy SAP Build App to SAP BTP](../ex2.4/README.md)
