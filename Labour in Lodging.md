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

| [Labour Checkin](#labour-checkin) | [Labour Checkout](#labou) |
## **Labour Checkin:**

When Ever Employee returned to Lodging, from below Listed category will start the Checkin process manually or start and complete by system integration.

<br>

### **In Checkin**:

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


- ### Waiting For Checkin:

   - Checkin Request will created for "Business Employee", who already **"End from Contract"** in Business.

   - The Checkin Request will create with Current Date.

   - In this stage, Employee Status is changed to "Waiting For Action-Lodging".

      <br>

   - **Once Checkin created for Employee, will update following action based on checkin types:**

      - _**End the Employee from on contract**_

         - _**Return From Customer**_, - Checkin will created, If the Employee Return from Customer and End the Employee from contract.

         - _**From Business**_, - Checkin will created, If the Employee Return from Business and End the Employee from contract.

         - _**In Contract**_, - Checkin will created from Contract, When Employee return from on contract and End from the contract.



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

## **Labour Checkout Request:**

### **Checkout Request will create by following source.**

* When Employee will delivered to customer, and same time check-out will create for Employee with based on contract.

* If Employee, delivered to customer, then check-out will create for Employee with based on contract.

<br>

* Check-Out will create automatically with system integration, When Employee will Return from On Vacation.

* Check-Out will create automatically with system integration, when Employee is Escaped from Customer or Employer on contract.

* System Integration will create the Check-Out process for Employee, When Employee request for Retirement.

* When Employee on Transfer, then Check-Out process will create with System Integration automtically.

<br>

* Check-Out will create for Employee with system integration, When the Employee is return from the Hospital.

* Checkout will Create from Labour Transfer with system integrtion, when Employee return from Labour Transfer.

<br>

### **Checkout Workflow stages:**

- ### Requested:

  - The newly required request will move to process into ***Waiting For Check-out*** stage.


- ### Waiting For Checkout:

  - When complete this stage, checkout date updated with current date.

  - Employee status will changed based on checkout type.

  - ___Once checkout updated for Employee, then will update the following action, based on checkout type.___

    - If The Employee delivered to Customer, then the process will complete with required stage.

    - If The Employee delivered to Business, then the process will complete with required stage.

    - When Labour Transfer is completed, then the process moved to required stage.

    - When Employee return from Hospital, Then process will moved to required stage.

      - In The Action fields are Following:

        ___1.Complete___ - User Will complete or Move the process with Required stage.




<br>
<br>
<br>

# **Labour Case**

**Rest**

- Rest Transaction will creates with SubCategory in different sources

- Rest Process will start based on subcatory as follows

 - ReservedFor VIP

   - Process starts with ReservedFor VIP stage.
   - Employee status changed to ReservedFor VIP.

 - Reserved For Sales

   - Process starts with ReservedFor Sales stage
   - Employee status changed to ReservedFor Sales

 - Other Subcategory

   - process starts with New stage
   - Employee status changed to Rest


   <br>
   <br>

- **New:**

  - Move to Rest Stage

- **Rest:**

  - User can move to following stage

- **ReservedFor VIP:**

  - Employee status changed to ReservedFor VIP

  - Complete-WaitingFor Action,employee status changed to Rest

- **ReservedFor Sales:**

   - Employee status changed to ReservedFor Sales

   - Complete-WaitingFor Action,employee status changed to Rest

"**Hourly Reserved(removed)**"

- **WaitingForAction:**

  - Ready to work =>employee status changed to Ready to work
  - Refuse to work =>Investigation process will start
  - Leave=> leave request will create with required data
  - Final Exit=> retirement request will create with required data

<br>

Investigation Process

- Transaction will creates with SubCategory in different sources
-Rest Process will start based on Return Reason(subcategory) as follows

--_**Request For Vacation**_

---Process starts with WaitingFor vacation stage

---Employee status changed to WaitingFor vacation

_**--Request for Exit**_

---Process starts with WaitingFor Exit stage

---Employee status changed to WaitingFor Exit

_**--Other Subcategory**_

---process starts with Under_Investigation stage
---Employee status changed to Under_Investigation

<br>

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

Register In MOL
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

UnRegister Muqueem
after employee return, employee already refister in mol, this stage starts,

Deport
--Employee status changed to Deport-Missing,
--Retirement request will create for settlement





<br>
<br>
<br>
<br>
<br>


Labor in Lodging
-Employee List who stays in Lodging
Labour in Marketing
-List of employee who are in "Ready to work" status
--Actions
---Investigation
---Rest
Profile search
-Card view of Employee List who stays in Lodging
-page with advance search
--User can reserve employee for 20  minutes (Ready to work employee)
--Once User reserve the employee , Employee status changed to "Reserved"
--User can Extend or expire the reservation
Sales Profile
-List of employee who are in "Ready to work" status
-List page with advance search
-Page sorted by profile minutes
(employee status time include ready to work, booked, reserved time)

Labour movement
===============
CheckIn Request
Checkin Request will Create by following source
-Arrival
--when new employee arrived to Lodging , create Lodging checkin without request
-ReturnFromCustomer,InContract,FromBusiness
--Request created from Contract when employee return from contract
VacationReturn
--Created from Vacation Request when return from vacation
EscapeReturn
LabourTransfer
--Created from labor transfer when return from transfer
JailReturn
HospitalReturn
CheckIn_Without_End_Contract
--Request will created from CheckIn Request for business employee who already end from contract(status in WaitingFroAction)

Flow
-Requested
--user can cancel the request which checkin type is CheckIn_Without_End_Contract
-WaitingForCheckIn
--Create the CheckIn with current date
--EMployee status changed as "Waiting forAction-Lodging"
--Once checkin created, will update following action based on checin type
---ReturnFromCustomer,InContract,FromBusiness
----End the employee from COntract
---VacationReturn,EscapeReturn,JailReturn,HospitalReturn,LabourTransfer
----move process to required stage

-UpdateWorkerStatus
--After check in created, user will process the employee to lodging
--if employee return from labour transfer, this stage will skip and employee status changed to prev employee status
--when complete the status user will select the return reason and sub category
--based on Return request employee status and process will start
--process will moved to confirmed stage

End of COntract
--EMployee Status updated to ReadyToWork
Request Vacation
--Investigation Process will start with Request Vacation
Request For exit
--Investigation Process will start with Waiting For exit
Customer from Customer
--Investigation Process will start with Investigation
Complaint from EMployee
--Investigation Process will start with Investigation
Sick
--Hospital process will start
Rest
--Rest Process will start
-Confirmed 
-Cancell
==========================

Checkout Request

-Checkout Request will Create by following source
--DeliveredToCustomer,FromBusiness
---Request created from Contract when employee deliver to contract
--Vacation,Escape,FinalExit,Transferd
---by this process, employee will checkout automatically with out checkout request
--LabourTransfer,Hospital
---Created from labor transfer when return from transfer

Checkout request have following stages
Request
--move the process to WaitingFor checkout stage
Waitingforcheckout
--when complete this stage, checkout date updated with current date
--Employee status will changed based on checkout type
--Once checkout updated, will update following action based on checkout type
---DeliveredToCustomer,FromBusiness
----Complete the process to required stage
---LabourTransfer,Hospital
----move process to required stage






Labour case:

Rest

-Rest Transaction will creates with SubCategory in different sources
-Rest Process will start based on subcatory as follows
--ReservedFor VIP
---Process starts with ReservedFor VIP stage
---Employee status changed to ReservedFor VIP
--Reserved FOr Sales
---Process starts with ReservedFor Sales stage
---Employee status changed to ReservedFor Sales
--Other Subcategory
---process starts with New stage
---Employee status changed to Rest

New
-move to Rest Stage

Rest
-user can move to following stage
ReservedFor VIP
--Employee status changed to ReservedFor VIP
--COmplete-WaitingFor Action,employee status changed to Rest
ReservedFor Sales
-Employee status changed to ReservedFor Sales
--COmplete-WaitingFor Action,employee status changed to Rest
HourlyReserved(removed)
WaitingForAction
-Ready to work =>employee status changed to Ready to work
-Refuse to work =>Investigation process will start
-Leave=> leave request will create with required data
-Final Exit=> retirement request will create with required data


InvestigationProcess
- Transaction will creates with SubCategory in different sources
-Rest Process will start based on Return Reason(subcategory) as follows
--Request FOr Vacation
---Process starts with WaitingFor vacation stage
---Employee status changed to WaitingFor vacation
--Request for Exit
---Process starts with WaitingFor Exit stage
---Employee status changed to WaitingFor Exit
--Other Subcategory
---process starts with Under_Investigation stage
---Employee status changed to Under_Investigation

Investigation flow
WaitingForAction
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



    

        

