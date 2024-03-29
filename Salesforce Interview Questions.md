# Salesforce Topics for interview

## Salesforce as a product ?

 - Questions 
	 - What is salesforce ?
	 - What is CRM ?
	 - What are its advantages over other products ? How it is different from other CRM products?
	 - What are different clouds ?
	 - What is its architecture ?
	 - What is multi - tenant ? 
	 - Why governance limits were introduced?
	 - What do you know about service cloud ?

## Apex Language

 - Questions
	 - Collections in apex?
	 - Access modifiers available in salesforce ?
	 - With sharing and without sharing keyword
	 - How to extend classes ? How to make them extensible ? How to make a method overridable ?
	 - difference between insert and database.insert ?
	 - Database class methods?
	 - Database dml methods and regular dml operations?
	 - Best practices for apex?
	 - What is execution context ? how many contexts are there ?
	 - What is System context and User context ?
## Order of execution
 - Question
	 - Workflow and validation rules ? Order of executions ? When validation rules run with automation tools ?
	 - Validation rule runs first or workfklow?

## Objects and Relationships
 - Questions
	 - What are different types of relationships available ? Self relationship ?
	 - Junction object ? Which master object does it inherit security from ?
	 - Self relationship ? Indirect relationship ?
	 - diff between lookup and master in context of security and permission ?
	 - Does one to one exist in salesforce?
	 - externalId and recordId ?
	 -  How to create rollup on lookup relationship?
	 - What will happen if one of the parent record in many to many relationship is deleted?
	 - Relationship between standard salesforce objects ?
	 - 

## Triggers

 - Questions
	 - What is trigger , Types of triggers ?
	 - Can we write a trigger on user ?
	 - When to use after triggers , and before ?
	 - Roll up summary trigger ?
	 - Can we make callout from apex triggers ? How to make callouts from apex?
	 - Can we use queueable in apex trigger ?
	 - Rollup summary with triggers ? How to implement that ? Try to write it as practice !?
	 - What is maximum depth reached error in trigger ? 
	 - Why do we use static in case of avoiding recursion?
	 - Where the static variable needs to be declared to avoid the recursion ? In Trigger or Class ?
	 - difference between trigger.old and trigger.oldMap ? 
	 - How to run record in system context in between of the trigger?
	 - Trigger context variables ?
## Automation tools
 - Questions
	 - Time based actions ? How many ways are there to do it based on time ? How to do in PBs?
	 - Can we do time based actions with flows?

## Process Builder

 - Questions
	 - What actions are available in process builder ?
	 - How to call apex methods from process builder ?
	 - In which context does process builder runs?
	 - Can we delete related records from process builder ?
	 - @Invokable?
	 - Checkbox box available on processbuilder ?What does it do?

## Flow

 - Question
	 - Can we do multiplication on flow screen ?
	 - Types of flow ?

## Workflow

 - Workflow evaluation criteria ?
 - can we create object with it?
 - workflow rule entry criteria's?
 - Types of workflow action available ?
 - Types of events for workflow ? 

## Apex Classes

 -  Questions
	 - How to delete apex class or trigger from Prod?
	 - How to check for user permissions in apex class ?
	 - How to check if record is locked in apex?
	 - How will you debug apex class ?
	 - What are other ways to debug?
## Batch Classes

 - Question
	 - Interfaces for batch Apex?
	 - Database.Stateful?
	 - Which state is maintained by stateful ?
	 - Limits of batches?
	 - How to handle failed records in the batches ? How to get count of those ?
	 - How call batch class from a batch classs?
	 - Can we call another batch class in execute method?
	 - Is writing finish method mandatory ?


## Asynchronous Operations in Apex

 - Future Methods
	 - Properties of future methods ?
	 - Why future method is void ?
	 - Limitations of future , How it is overcame with queueables?
	 - why cant we use list of sobj in future?
	 - Can we write future inside future method ? 
	 - How to handle mixed dml exception in future method?
	 - How to pass sObject as parameter in future ? What is a way for that ?
 - Schedulable
 - Queueable
## Approval Process
## Test Class

 - Questions
	 - How to test future methods and webService callouts ?
	 - How to test class written by other people ?
	 - what is testSetup annotation in unit test?
	 - How to declare test methods in test class ?
	 - System.runAs ?
	 - isTestRunning use cases for that ?
	
## Query
 - ### SOQL
	 - Question
		 - Inner query in soql ? how to query related objects and custom objects?
		 - How to query record type API name?
		 - Wrapper class ?	
		 - How to print time taken by SOQL query?
 - ### SOSL
	 - Question
		 - Where can we use SOSL ?
		 - Dynamic SOSL ?
		 - Write a SOSL query to find the 'Orange' in all objects ?
		 - What is return type of SOSL query?
		 - Can DML operations be performed on SOSL result?
		 - Which types of fields can it query on ?
		 - Example of SOSL implementation in salesforce ?
 - Question
	 - Types of DML operations available?
	 - What is mixed dml error ? What are setup and non setup objects ?
	 - How to resolve mixed dml error ? Ways for that ? Does System.runAs helps in this ? Does future method helps in this ?
	 - whoid and whatid?

## Security Questions
 - ### Profile
 - ### Role
 - ### Security Model
 - ### Sharing Rules
	 - Questions
		 - Various options to whom we can share with sharing rules ?
 - ### Manual Sharing
	 - Questions 
		 - Use case for manual sharing ?
 - ### Custom Settings 
	 - Question : Use Case and configuration
 - ### Custom Metadata Type
	 - Question : Use case and configuration
 - Questions
	 - Can we share record to a perticular user ? 
	 - Difference between freezing the user and deactivating user ?
	 - What will happen if user has ip range out of set range ?

## Knowledge

 - Notes :
 - Questions : 
	 - What are knowledge articles
	 - What are data categories ?
	 - How to control visibility of knowledge?
## List views 
 - Questions 
	 - How to remove standard button from a list view?
	 - How to Change behavior of the standard button on list view ?
## Reports and Dashboards
 - Question 
	 - Report was deployed using change set and it is not visible in the next org what could be the reason ?
	 - What are types of reports ? 
	 - Dynamic reports?
## Deployment
 - Questions 
	 - Which deployment tools you have used ?
	 - Which types of rules are available ?
	 - How to resolve merge conflicts?
	 - What is ANT tool ? What are advantages of ANT tool ?
## Lightning

 - Questions
	 - Different types of events in lightning platform?
	 - What is $a ? other related stuff ?
	 - What is difference between application event and component events ?
	 - How to decide which type of event to use ? Can we use application event even if they are related ? Why are there 2 options ?
	 - Is Lightning Aura an MVC framework? 
	 - In MVCC which controller is server side and which is client side , name those?
	 - Lightning Base components provided by the salesforce
	 - Interfaces used while creating Aura components?
	 - What is helper js in aura ?
	 - What are types of components that are bundled with aura component ?
	 - What is cachable=true ? How does framework knows if data is same or not for cachable=true?
	 - @auraenabled and cachable ?
	 - How many ways are available for communication in lightning platform?
	 - How to call child component methods with parent component ?
	 - How to communicate between parent to child ?
	 - How child to grandparent communication works ?
	 - Fire an Lightning event? How to use that event ? Do we need to register application event ? How to fire the event ?
	 - How to communicate between siblings ? with or without messaging services ?
	 - What is lightning messaging service ? Use cases for that?
	 - What are different ways to call methods of apex class ?
	 - Lightning Data service ?

## Integration 

 - Questions 
	 - I have custom object , when saving it there is an external system which will perform some operations and let us know if we should save it. How to implement this?
	 - On button click it calls a web service , calling external system and returning a response , with more data it gives time out error ? How to resolve that ?
	 - Have you implemented integration in project ?
	 - Rest or soap api ? How do i know if it is rest or soap ?
	 - Authentication of API ? 
	 - OAuth 2.0 Integration ? How does OAuth 2 works ? How it works with salesforce ?
	 - Benefits of named credentials ? What are named credentials ?
	 - Use of state parameter in OAuth 2.0?
	 - What are Web services? have you worked on the web services?
	 - What is SSO ? How to implement in salesforce ?
	 - Authentication in salesforce ?
	 - What is connected app ?
	 - What is endpoint in salesforce ?

## Anonymous Questions

 - Questions
	 - How to override standard save button's Logic ?
	 - What is sales process?
	 - What is continuation ? 
	 - Omnichannel skill based routing ? What approach , How to implement it ?
	 - I am making a callout , it is executing fine when i am running with annonymous window , but it is not working when i am running it from isExecuting context ? What is issue?
	 - Which standard buttons can be overridden?
	 - How to call flows from the button?
	 - How to implement pagination? 
	 - standard controller and custom controller ?
	 - What is data skew ?
	 - what is .addError method ?
	 - What is Outbound message ?
	 - auto launch flow ? pause element?
	 - What are field sets?
	 - How to configure my domain ?
	 - Lightning and classic URL ?

## LWC 

 - Questions
	 - 	Lifecycle methods in LWC ? 
	 - LWC component lifecycle flow ?
	 - Project Structure of LWC bundle?
	 - What is bubbling what is capturing ?
	 - How to call child component methods with parent component ?
	 - How child to grandparent communication works ?
	 - What are callback funtions ?
	 - What are promises ?
	 - can callbacks be async ? Are callbacks async ?
	 - What are decorators ? Which are there ?
	 - What is 2 way binding ? What is binding in LWC ?
	 - What types of communication is available in LWC ?
	 - When does wire method executes ?
	 - can we call wire method from button click ?
	 - Which will execute first ? Either wire method or connected callback ?
	 - Which will execute first ? Either wire method or rendered callback ?
	 - Dynamically create a component can we do that ?
	 - What are different ways to call methods of apex class ?
	 - How to export LWC component to outside of salesforce ? How to display that outside?
	 - How to use LWC component inside Aura and VF?
	 - Why LWC when aura is available?
	 - How to import static resources in LWC ?
	 - What imports are there when we create a LWC component ?
	 - @wire scenarios , which method ran first how to handle that?
	 -  How to make LWC components only available on account page?
	 -  How to add properties to the lwc? Can we add list to the properties ?
	 - Can we call wire methods from lwc component ?
	 - How to create a record without using apex in LWC?
	 - Lightning UI and wire adapters ?
	 - How to get the userData in LWC?
	 - Data flow in LWC ? from parent to child ? or child to parent ?

## Limitations and Governance Limits

 - Questions?
	 - How many future methods can we call from a class?

## Visual Force 

 - Questions?
	 - render , reRender , renderAs what are these ?
	 - What are states in visualforce ?
