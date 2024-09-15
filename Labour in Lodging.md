# **Lodging**

| [Labour in Lodging](#labour-in-lodging) | [Labour in Movement](#labour-movement) | [Labour Cases](#labour-cases)|

# Labour in Lodging

| [Labour in Lodging](#labour-in-lodging-1) | [Labour in Marketing](#labour-in-marketing) | [Lodging Profile Search](#lodging-profile-search) | [Ind Sales Profiles](#ind-sales-profiles) |


## **Labour in Lodging:**

Labour in lodging is a status view, and List to view the number of employees in lodging with work category wise.

And Take action to create ID Card for employee.

And Use to take printout as below List for Employee, as like

      * Food Report,
      * Temporary Iqama,
      * New Arrival request,
      * Check in and Check Out.

 - Intituitional Quarantine - Employee status as Intituitional Quarantine, updated from New Employee request.

 - Under Documentation - Employee status as Under Documentation, updated from New Employee request.

 - Under Training - Employee status as Under Training, updated from New Employee Request.

 - Waiting For Action - Employee status as Waiting For Action, updated from New Employee Request.

 -  Reserved For VIP - Employee status as Reserved For VIP, updated from New Employee Request.

 - Refuse to Work - Employee status as Refuse to Work, updated from New Employee Request.

 - Ready to Work - Employee status as Ready to Work, updated from New Employee Request.

 - Booked - 

 - In transist - 

 - Vacation Requested - Employee status as Vacation Requested, updated from Employee Leave Request.

 - Final Exit requested - Employee status as Final Exit requested, updated from Employee Retirement.

Waiting For TravelFinal Exit requested, updated from (Employee Leave Request or Employee Retirement).

<br>

## **Labour in Marketing:**

List to view the Employees status information with who are waiting for **"Ready to Work"** status.

Tracking purpose for Employee status with Lodging Locations.


- In require to take on Action as:

   * **_Investigation_**

      Process will start for Employee to send for Investigation.

   * **_Rest_**

      Process will start for Employee to send for Rest.

<br>

## **Lodging Profile Search:**

- User can view the Employee List as Card View, who resides in Lodging Locations.

- User can review the status and Information of Employee, with Advance Search.

- User can Reserve the selected Employees for a Short period.

   - User can Reserve the Employee for minimum 15 minutes. In spite of the Employee in **"Ready to work"** status.

   - And User can also extent the Reservation time period. If he required.

   - If User did Reservation on Employee profile, and Employee Profile status changed to as **"Reserved"**.


<br>


## **Ind Sales Profiles:**

- User can review, The List of Employee who are waiting in **"Ready to Work"** status.

- User can review the Information and status of Employee, with Advance Search.

- User can review the Employee profile information with Advance search.

- List to view the Employee profile, with ordered and sorted by Profile Minutes.

    - **"Profile Minutes"** - it will Calculate the Time period for every Employee profile status, since the profile listed into Sales Profile List.

    - Employee profile status will sorted list and order the Profile of lead Duration time in this Employee profile status.

    - Time calculation for Employee status are including  **"Ready to Work" status, "Booked" status, "Reserved" status.**

<br>
<br>
<br>


# Labour Movement

| [Labour Check-in](#labour-checkin) | [Labour Check-out](#labou) |

## **Labour Check-in:**

When Ever Employee returned to Lodging, from below Listed category will start the Checkin process manually or start and complete by system integration.

<br>

### **In Check-in**:

   The Checkin request will create from the following sources.

  - _**Employee Arrival**_,

      When New Employee arrived to Lodging, Lodging Checkin will create without Request.

 - _**Return from Customer \ In Contract \ From Business**_,

     Checkin will start for Employee from Contract, When Employee return from contract.

 - _**Vacation Return**_,

     Checkin created from Employee Vacation Request, After Employee returned from on Vacation.

 - _**EscapeReturn \ LabourTransfer**_,

     Checkin will create based on Labour Transfer, If the Employee tranfered to other organization and Return to Lodging.

     Checkin will created, when Employee return after Escaped from Lodging or customer.

 - _**JailReturn \ HospitalReturn**_,

      If Employee returned from Jail or Hospital, then Checkin will create without End the Contract.

 - _**Business**_,

      Request will created from CheckIn Request for business employee who already end from contract.(status will be "Waiting For Action")

<br>

### **Workflow Stages in Labour Movements**,


- ### Requested:

   - Checkin request will move to _**"Waiting For Action"**_ from Requested.

   - User can cancel the checkin request to Employee,  When the checkin type of Employee is **"CheckIn_Without_End_Contract"**.


- ### Waiting For Check-in:

   - Check-in Request will created for "Business Employee", who already **"End from Contract"** in Business.

   - The Check-in Request will create with Current Date.

   - In this stage, Employee Status is changed to "Waiting For Action-Lodging".

      <br>

   - **Once Check-in created for Employee, will update following action based on check-in types:**

      - _**End the Employee from on contract**_

         - _**Return From Customer**_, - Check-in will created, If the Employee Return from Customer and End the Employee from contract.

         - _**From Business**_, - Check-in will created, If the Employee Return from Business and End the Employee from contract.

         - _**In Contract**_, - Check-in will created from Contract, When Employee return from on contract and End from the contract.


      - _**And process will move to Required stages**_

         - _**Vacation Return**_, - Checkin will created from Employee Leave Request, when Employee return from Vacation and then move to Required stage.

         - _**Escape Return**_, - Checkin will created, when Employee return after Escaped from Lodging or customer and then move to Required stage .

         - _**Jail Return**_, - Checkin will created, when Employee return from Jail to Lodging and then move to Required stage .

         - _**Hospital Return**_, Checkin will created, when Employee return from Hospital to Lodging and then move to Required stage.

         - _**Labour Transfer**_, Checkin will create based on Labour Transfer, when Employee Return to Lodging for Transfer and then move to Required stage.


- ### Update Worker Status:

  - Once Checkin is created for Employee, then user will start the process for Employee to Lodging.

  - If Employee Return from Labour Transfer, then this stage will skip and Employee Status is Changed to _**"Prev Employee Status"**_.

  - When Complete the status user will select the "**Return Reason**" and "**Sub Category**"

  - Based on Return Request Employee status and process will start.

     - End of Contract

       - Once Employee End the contract with cutomer then Employee Status updated to "**Ready To Work**".

     - Request Vacation

       - Employee Require for Vacation, Investigation Process will start with Request Vacation.

     - Request For exit

       - Employee Require for Exit, and then Investigation Process will start with Waiting For Exit.

     - Customer from Customer

       - Employee Require for Exit, Investigation Process will start with Investigation.

     - Complaint from Employee

       - Investigation Process will start with Investigation.

     - Sick

       - Hospital process will Start.

     - Rest

       - Rest Process will start.

  - And process will moved to confirmed stage.


- ### Confirmed:


- ### Cancel:

<br>

## **Labour Check-out Request:**

### **Check-out Request will create by following source.**

* When Employee will delivered to customer, and same time check-out will create for Employee with based on contract.

* If Employee, delivered to customer, then check-out will create for Employee with based on contract.

<br>

* Check-Out will create automatically with system integration, When Employee will Return from On Vacation.

* Check-Out will create automatically with system integration, when Employee is Escaped from Customer or Employer on contract.

* System Integration will create the Check-Out process for Employee, When Employee request for Retirement.

* When Employee on Transfer, then Check-Out process will create with System Integration automtically.

<br>

* Check-Out will create for Employee with system integration, When the Employee is return from the Hospital.

* Check-out will Create from Labour Transfer with system integrtion, when Employee return from Labour Transfer.

<br>

### **Check-out Workflow stages:**

- ### Requested:

  - The newly required request will move to process into ***Waiting For Check-out*** stage.


- ### Waiting For Check-out:

  - When complete this stage, checkout date updated with current date.

  - Employee status will changed based on checkout type.

  - ___Once check-out updated for Employee, then will update the following action, based on checkout type.___

    - If The Employee delivered to Customer, then the process will complete with required stage.

    - If The Employee delivered to Business, then the process will complete with required stage.

    - When Labour Transfer is completed, then the process moved to required stage.

    - When Employee return from Hospital, Then process will moved to required stage.

      - In The Action fields are Following:

        ___1.Complete___ - User Will complete or Move the process with Required stage.


<br>
<br>


# **Labour Case**

### _**Rest**_

 Rest Transaction will creates with Sub-Category from different sources

Rest Process will start based on sub-category as follows:

****Reserved For VIP***

   - Process starts with Reserved for VIP stage.
   - Employee status changed to "**Reserved For VIP**".

<br>

****Reserved For Sales***

   - Process starts with Reserved for Sales stage
   - Employee status changed to **Reserved For Sales**

<br>

****Other Subcategory***

   - Process starts with ***New*** stage
   - Employee status changed to **Rest**

   <br>
   <br>


### ***Rest Workflow:***

- ### **New:**

  - Newly initiated Request is moved to Rest or Reserved for VIP.

       * _In The Action fields are Following:_

         ***1.Rest*** - User move to **Rest** stage

         ***2.Reserved For VIP*** - User move to *Reserved For VIP* status.

- ### **Rest:**

  - User can move to following stage.

     *  _In The Action fields are Following:_

        ***1.Reserved For VIP*** - User move to **Reserved For VIP** status

        ***2.Waiting For Action*** - User moved to **Waiting for Action** stage

- ### **Reserved For VIP:**

  - Employee status changed to Reserved for VIP

  - Complete-Waiting For Action, employee status changed to Rest

     * _In The Action fields are Following:_

       **1.Complete** -

       **2.Move to Hourly** -

- ### **Reserved For Sales:**

   - Employee status changed to Reserved for Sales

   - Complete - Waiting For Action, employee status changed to Rest

    ("**Hourly Reserved (removed)**")

- ### **Waiting For Action:**


  - If Employee moved to "**Ready to work**" then employee status changed to **Ready to work** category.

  - If Employee ***"Refuse to work"*** then Investigation process will start for the Employee and status changed to **Rufuse to Work** category.

  - If Employee request for Vacation, Then Leave Request will create for with Required Data if Employee eligible.

  - If Employee request for Retirment(Final Exit), then retirement request will create for Employee with required data.


    * In The Action fields are Following:

       ***1.Ready to Work*** - User move to process with Required stage.

       ***2.Refuse to Work*** - User move to process with **Refuse To Work** stage.

       ***3.Leave*** - User move to process with **Leave Request** stage.

       ***4.Final Exit*** - User move to process with **Retirement** stage.




<br>
<br>
<br>
<br>

Investigation Process

- Transaction will creates with Sub-Category in different sources.

- Rest Process will start based on Return Reason(sub-category) as follows,

--Request For Vacation

---Process starts with Waiting For vacation stage
---Employee status changed to Waiting For vacation

--Request for Exit

---Process starts with Waiting For Exit stage
---Employee status changed to Waiting For Exit

--Other Subcategory

---process starts with Under_Investigation stage
---Employee status changed to Under_Investigation

Investigation flow

Waiting For Action

-Ready to work =>employee status changed to Ready to work
-Refuse to work =>Investigation process will start
-Leave=> leave request will create with required data
-Final Exit=> retirement request will create with required data

Dead
Request
-Status changed to Dead
-if employee working with customer, end the contract
-if employee in lodging, checkout from the lodging
Action
-Request move to Complete
-Retirement request will create for settlement

Jail
-Status changed to absent
-if employee working with customer, end the contract
-if employee in lodging, checkout from the lodging

Request
-move to Action stage
Action
-Return=> checkin request will create
--checkin requested completed, move to completed stage
-Final exit=> -Retirement request will create for settlement

Hospital
status changed to sick
-if employee working with customer, end the contract

New
AdmittedTohospital
--when stage starts, checkout from lodging
--when stage end, checkin to lodging,move to required stage

Escape
Escape request will created from indivudal module or by user
EMployee staus changed to missing-missing

Missed
-after 10 days , employee will moved to Escaped stage by schedule
-employee status changes Missing-Escaped
-user also can do manual action

Escaped,
-after 20 days , employee will moved to RegisteredInMOL stage by schedule
-employee status changes Escaped-Escaped
-user also can do manual action

RegisterInMOL
-Complete
--employee status changes Escaped-Escaped
--Retirement request will create for settlement
-Return
--process move to Return from Escape stage
-Deport
--process will move to Deport

Return From Escape
--if employee returned to Customer,Employeestatus changed to working-withcustomer
---process will skip move to completed stage
--employee return to lodging, checkin request will creates
--Once checkin request complete, moved to complete stage

UnRegisterMuqueem
after employee return, employee already refister in mol, this stage starts,

Deport
--Employee status changed to Deport-Missing,
--Retirement request will create for settlement




Investigation Process
Dead
Jail
Hospital
Escape


