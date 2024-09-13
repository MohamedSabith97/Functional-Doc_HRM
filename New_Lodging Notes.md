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


===========================================================================================================

Flow

-Requested

--user can cancel the request which checkin type is CheckIn_Without_End_Contract
==============================================
-WaitingForCheckIn

--Create the CheckIn with current date
--EMployee status changed as "Waiting forAction-Lodging"
--Once checkin created, will update following action based on checin type

---ReturnFromCustomer,InContract,FromBusiness
----End the employee from COntract

---VacationReturn,EscapeReturn,JailReturn,HospitalReturn,LabourTransfer
----move process to required stage
===========================================

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
==========================================
Sick

--Hospital process will start

Rest

--Rest Process will start


-Confirmed 

-Cancell

=================================================================================

Checkout Request

-Checkout Request will Create by following source
--DeliveredToCustomer,FromBusiness

---Request created from Contract when employee deliver to contract
--Vacation,Escape,FinalExit,Transferd

---by this process, employee will checkout automatically with out checkout request
--LabourTransfer,Hospital

---Created from labor transfer when return from transfer

===============================================================

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


=====================================================================================================
=====================================================================================================


Labour case:

Rest:

-Rest Transaction will creates with SubCategory in different sources
-Rest Process will start based on subcatory as follows

--ReservedFor VIP:

---Process starts with ReservedFor VIP stage
---Employee status changed to ReservedFor VIP

--Reserved FOr Sales:

---Process starts with ReservedFor Sales stage
---Employee status changed to ReservedFor Sales

--Other Subcategory:

---process starts with New stage
---Employee status changed to Rest

===============================================================================

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

====================================================================================

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

===================================================

Investigation flow

WaitingForAction

-Ready to work =>employee status changed to Ready to work
-Refuse to work =>Investigation process will start
-Leave=> leave request will create with required data
-Final Exit=> retirement request will create with required data

=======================================================

Dead

Request

-Status changed to Dead
-if employee working with customer, end the contract
-if employee in lodging, checkout from the lodging

Action

-Request move to Complete
-Retirement request will create for settlement

=====================================================

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

==========================================================

Hospital
status changed to sick
-if employee working with customer, end the contract

New
AdmittedTohospital
--when stage starts, checkout from lodging
--when stage end, checkin to lodging,move to required stage

================================================================

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

================================================================

RegisterInMOL

-Complete

--employee status changes Escaped-Escaped
--Retirement request will create for settlement

-Return

--process move to Return from Escape stage
-Deport
--process will move to Deport

================================================================

Return From Escape

--if employee returned to Customer,Employeestatus changed to working-withcustomer
---process will skip move to completed stage

--employee return to lodging, checkin request will creates
--Once checkin request complete, moved to complete stage

==================================================================

UnRegisterMuqueem

after employee return, employee already refister in mol, this stage starts,

=====================================================================

Deport

--Employee status changed to Deport-Missing,
--Retirement request will create for settlement

=====================================================================

Investigation Process
Dead
Jail
Hospital
Escape


