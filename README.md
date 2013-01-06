AccountApplicationXmlGenerationRepos
====================================

This Repository has got codes for alteration, addition and for getting information on Plivo Accounts and application 
,it also has a small sample code for dynamicXml generation


*Get Account Details:-

 AccountDetails.java class to provide city and name of the account holder.

*Modify an Account:-

 ModifyAccountDetail.java is used to modify the detail of an account by changing the "name"  and "city".

*Create a SubAccounts:-

 SubAccount.java takes "name" and "enabled" as parameter where name gives the name of  subaccount and enabled specifies if it is enabled or not


*Modify a Subaccount:-

 ModifyAccountDetail.java is used to modify "city" and "name" of particular account.

*Get Details Of a SubAccount:-
   
  DetailsOfSubAccount.java is used to get detail of particular "acc_id"


*Get Details of All SubAccount:-

  DetailsOfAllSubAccount provide details of all account in pages by providing the "limit" and "offset" as parameter.

Delete a SubAccount:-

  DeleteSubAccount.java is used to delete sub-account  by taking "acc_id" as parameter .


-------------------------------------------------------------------------------------------

Application

* Create an Application:- 

 CreateApplications.java- create application by taking name and answer url as parameter.

* Get details of all Application:-

  GetDetailOfApplication.java- it is taking parameter as limit and offset and providing the   details of application page wise.

* Get Details of a Single Application:-

   DetailsofSingleApplication.java-  Taking "acc_id" and providing details of the account holder.

* Modify an Application:-

   ModifyApplication.java- taking "acc_id" and "name" as parameter and modifying the same.

* Delete an Application:-
   
    DeleteApplication.java is used to delete account id by taking acc_id as parameter.

--------------------------------------------------------------------------------------

* DynamicXmlGeneration- creates an Xml, by initializing the Response,Dial and Number xml class from Plivo source, and finally call 
  a function in restAPI which uses JAXB 

output: <?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<Response><Dial callerId="123">
<Number>9686201581</Number></Dial>
</Response>
		

