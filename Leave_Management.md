# **Human Resource Management**



| [Employee](#employee) | [On Board](#on-board) | [Leave Management](#leave-management) | [Travel](#travel) | [Employee Retirement](#employee-retirement) | Loan | [Reissue](#reissue) | [Renewal](#renewal) |

<br> 


# **[Leave Management](#human-resource-management)**

| [Leave Request](#leave-request) | [Vacation Settlement](#vacation-settlement) | [Vacation Return](#vacation-return) | [Leave Reject Request](#leave-reject-request) |

<br>

## **[Leave Request:](#leave-management)**

The Leave Request is initiated from Case and Task Management for Employee by user and customer.

New request created in case and task management and then it will moved to ARCO Approval from case and task management.


| [ARCO Approval](#arco-approval) > [Customer Approval](#customer-approval) > [Under Processing](#under-processing) > [Customer Clearance](#customer-clearance) > [ARCO Clearance](#arco-clearance) > [Travel Arrangement](#travel-arrangements) > [Waiting for Travel](#waiting-for-travel) > [Rejected Request](#rejected-request) > [Completed](#completed-5) |

<br>


- ### **ARCO Approval:**

    - Initiated new Request from case and task management is moved to ARCO approval .

    - Waiting for get ARCO approval for the Leave Request.

    - ARCO approval is validate the residence status of employee in this stage. once ARCO Approved then it will move to Customer Approval.

      - *In The action field is following to,*

         **1-[Complete](#customer-approval)** - User complete this request and refer to [Customer Approval](#customer-approval) Stage.

        **2-[Reject](#rejected-request)** - User reject the request to [Rejected Request](#rejected-request) stage.

        **3-[Escape](#completed-5)** - User reject and complete the request as Escape to [completed](#completed-5) stage.

- ### **Customer Approval:**

    - In Case and Task Management, Vacation Process will move to Customer Approval stage, Customer or User will Approve from Case and Task Management.

    - Once Approved in Case and Task Management, it will moved to UnderProcessing Stage.

    - In this stage, waiting for the Customer Approval, Once customer approved then it moved to Under processing.

      - *In The action field is following to,*

          **1-[Reject](#rejected-request)** -  reject the request and complete to [Rejected Request](#rejected-request) stage.

          **2-[Complete](#under-processing)** - User refer this request and complete to [Under Processing](#under-processing) stage. for Vacation process.


- ### **Under Processing:**

    - The [Vacation Settlement](#vacation-settlement) process will create and begins from this **Under Processing** stage with System Integration. when the customer request the leave request in Case and Task Management.

    - If the employee request, for Visa and travel from ARCO, and then Visa and Travel process will start for the employee from this stage with system integration.

    - If the Employee not requested Visa and Travel from ARCO, Then it will moved directly to **Waiting for travel** stage.

    - **(Paid Vacation / Local Vacation / Vacation Encashment have apply to proceed for Vacation settlement.)**

    - **(Unpaid vacation is not Applicable to apply for Vacation settlement.)**

       - *In The action field is following to,*

         **1-[Reject](#rejected-request)** - and reject the request and refer [Rejected Request](#rejected-request) stage.

         **2-[Complete](#customer-clearance)** - user complete the task and refer the request for [Customer Clearance](#customer-clearance) stage.

- ### **Customer Clearance:**

    -    In Case and Task Management, Leave request Process will move to customer confirmation stage, Customer or User will Approve from Case and Task Management, Once Approved in Case and Task Management, it will moved to Approved for payment Stage.

    - In this stage, Waiting for customer clearance on settlement, Once customer clearance completed on settlement then it will move to ARCO clearance.

    - Customer Clearance is optional for employee, and it will process only who requested the Clearance for settlement in Case and task management. Otherwise this clearance stage will be skipped and moved to completed stage.

      - *In The action field is following to,*

        **1-[Complete](#arco-clearance)** -  complete the stage and refer the [ARCO Clearance](#arco-clearance) stage.

         **2-[Reject](#rejected-request)** - User reject the request and complete [Rejected Request](#rejected-request) stage.

- ### **Arco Clearance:**

    -   -  In Case and Task Management, Leave Request will move to Approved for Payment stage, User will Approve from Finance Department, Once Approved in Finance Department, it will moved to Visa Requested Stage in Case and Task Management.

    - In this stage, waiting to get ARCO Clearance on Settlement, Once ARCO complete the clearance then it will moved next stage.

    - ARCO Clearance is optional for employee, it will process only who requested the Clearance for settlement in Case and task management. Otherwise this clearance stage will be skipped and moved completed stage.

      - *In The action field is following to,*

        **1-[Complete](#waiting-for-travel)** - complete the request and refer [Waiting for Travel](#waiting-for-travel) stage.

        **2-[Reject](#rejected-request)**   - User reject the request to [Rejected Request](#rejected-request) stage.

- ### **Travel Arrangements:**

    - In this stage, waiting for Travel Arrangements for Employee, once Arrangements is completed then it will moved to **Waiting for Travel** stage.

    - Travel Arrangements is Applicable for who on accommodate in lodging.

    - Travel Arrangements is not applicable for who do not accommadate in Lodging. Otherwise this stage skippen and moved to Waiting for Travel stage.

      In case of the customer required Travel Arrangements by Arco. then Arco organize the Travel Arrangements for Employees.

      - *In The action field is following to,*

        **1-[Complete](#waiting-for-travel)** - User complete this task and refer the request into [Waiting for Travel](#waiting-for-travel) stage.

- ### **Waiting for Travel:**

    - In this stage, when employee went on vacation, Muqeem status will change as OutsideKingdom in Muqeem portal.

    - By system schedule will check if muqueeem status is OnVacation-OutSideKingdom, Complete the Vacation Process with Travel Date.

      - *In The action field is following to,*

        **1-[Complete](#completed-5)** - User complete the request and moved to [Completed](#completed-5) Stage.

        **2-[Reject](#rejected-request)**   - User reject the request to **[Rejected Request](#rejected-request)** stage. and holding for the requirements.

- ### **Rejected Request:**

    - In this stage, rejected request is reject and moved to completed stage.

      - *In The action field is following to,*

        **1-[Reject](#completed-5)** - User reject and complete the Request to [Completed](#completed-5) stage.

- ### **Completed:**

    - All completed Request has been moved to Completed Stage, after Travel process is completed for Employee Vacation.

    - Once Vacation Process Complete, Employee Status will change as OnVacation-OutSideKingdom and Vacation Return Process will Start.


| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#leave-request) |






<br>

## **[Vacation Settlement:](#leave-management)**

Vacation settlement is initiated from case and Task management by user or customer, and then payment is completes in Finance portal. once the payment is completed in finance portal. then settlement process will be complete.

If the Employee not required the settlement in Leave Request then this stage will complete without Payment.


| [Requested](#requested) > [Clearance Process](#clearance_process) > [Approval](#approval) > [Client_Confirmation](#client_confirmation) > [Payment](#payment) > [Client Rejection](#client-rejection) > [Completed](#complete-1) |

<br>

- ### **Requested:**

    - New request initiated from case and task management by user or customer. and then that Request is waiting for action,

    - In Case and Task Management, Vacation Process will move to Finance Approval stage.

       - *In The action field is following to,*

         **1-[Move to Clearance](#clearance_process)** - User complete the request and refer into [Clearance_Process](#clearance_process) stage.

- ### **Clearance_Process:**

    - In this stage, Clearance Process will start for employee in Clearance Module, once clearance completed then it will send Approval to Finance Departmet Approval.

      - *In The action field is following to,*

        **1-[Complete](#approval)** - User complete the task and refer the request for [Approval](#approval) stage.


- ### **Approval:**

    - In case of customer required settlement, then it will send for approval to client confirmation, otherwise it will moved to complete without payment.

      - *In The action field is following to,*

        **1-[Approve](#client_confirmation)** - User complete the request and refer to [Client Confirmation](#client_confirmation) stage.

        **2-[Re-Calculate Clearance](#clearance_process)** - user reject the request and return to [Clearance_Process](#clearance_process) stage.

- ### **Client_Confirmation:**

    - In Case and Task Management, Vacation Process will move to Client Confirmation stage, Customer or User will Approve from Case and Task Management.

    -  Once Approved in Case Management, then it will moved to Payment Stage.


         - *In The action field is following to,*

           **1-[Complete](#payment)** - User complete the request and approve with **Client_Confirmation** then refer the [Payment](#payment) stage.

            2-Reject - process will moved to Client Rejection stage.

- ### **Payment:**

    - In Case and Task Management, Vacation Process will move to Approval For Payment stage.

    - In this stage waiting for complete the payment, the payment is process in Finance Department, Once payment is Completed in Finance Department then it will moved to completed stage.

    - After payment is completed in Finance Department, then this request has been moved to **Completed** stage.

    - User can compare the Payment status of Vacation Settlement in between the **[Vacation Settlement](#vacation-settlement)** and  **Finance Department**.

       - *In The action field is following to,*

         **1-[Complete](#complete-1)** - User complete this request and move to [Complete](#complete-1) Stage.

         **2-[ReCalculate](#clearance_process)** - User reject the request and moved to [Clearance _Process](#clearance_process) stage.

- ### **Client Rejection:**

     - In Case and Task Management, Vacation Process will move to Customer Rejection stage.

     - Pending request is reject to **Client Rejection** and hold the  request,
     
        For Re-send to process the **Client Confirmation** and **Re Calculate Clearance** stage.

       - *In The action field is following to,*

         **1-[ReSend - CustomerConfirmation](#client_confirmation)** - User return the request, **Resend for Customer Confirmation** to [Client Confirmation](#client_confirmation) stage.

         **2-[Re Calculate Clearance](#clearance_process)** - User Return the request to [Clearance_Process](#clearance_process) stage. for **Re Calculate Clearance** on Vacation Settlement.

- ### **Complete:**

    - Completed Request is moved to Completed Stage, After the Vacation Settlement request completed. and use this all completed request for Tracking the status of the request.

    - Once Settlement Completed, if vacation requests for Visa then Visa process will start,
    
    - And if vacation requests for Ticket then Travel Ticket process will start for Employee.


| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#vacation-settlement) |



<br>

## **[Vacation Return:](#leave-management)**

- Employee should not be pending in vacation or retirement process.

- when employee **On Vacation**, muqeem status will be on-vacation Outside Kingdom status,

- If Employee arrived, muqeem status will change to the valid then vacation return process will move to **Return from Vacation** stage.

- If Exit Re Entry date is expired and muqeem is expired, then that request is moved to **Visa Expired** stage.

- If iqama expiry date is less then 10 days, the request will move to **Iqama Approval cancellation** stage,

- Then User will register "Left Not Return" in muqeem then move to the **Iqma Expiry** date.

| [On Vacation](#on-vacation) > [Waiting for Return](#waiting-for-return) > [Not Return](#not-return) > [Return from Vacation](#return-from-vacation) > [Visa Expired](#visa-expired) > [Iqama Approval Cancellation](#iqama-approval-cancellation) > [Iqama Expired](#iqama-expired) > [Left Not Return](#leftnotreturn) > [Completed](#completed-6) |

<br>


- ### **On Vacation:**

     - When the employee not return after requested return date, system will move to the **Waiting for Return stage**.

     -  In case of employee is on vacation, the Muqeem status will be update on-vacation **OutsideKingdom** status,

     - If Employee arrived, muqeem status will change to the valid then vacation return process will move to **Return from vacation** stage.

     - System will check the muqeem status requlary, until the employee return, and if vacation end date is mentioned then moved to **Return from Vacation** stage.

       - *In The action field is following to,*

         **1-[Complete](#return-from-vacation)** - User Complete the Request and refer [Return From Vacation](#return-from-vacation) stage.

- ### **Waiting for Return:**

    - In this stage, waiting for employees who do not return on requested return date, And if the employee arrived then it will moved to **Return from Vacation** stage.

    - The system check the Muqeem status on reqularly.

    - If Employee arrived, muqeem status will change to the valid then vacation return process will move to **Return from Vacation** stage.

    - Either User complete the request manually with employee check-in process, vacation and refer to **Return from Vacation** stage.

      - *In The action field is following to,*

        **1-[Return](#return-from-vacation)** - User decide to complete this request and refer [Return from Vacation](#return-from-vacation) stage.

- ### **Not Return:**

    - System integration is scheduled the Employee who didn’t arrive on the Date of Return into Lodging is refer to [Waiting For Return](#waiting-for-return) stage.

      - *In The action field is following to,*

        **1-[Move to  Waiting for Return](#waiting-for-return)** - User dicided and refer to [Waiting for Return](#waiting-for-return) stage.

- ### **Return From Vacation:**

   - If employee returned, Muqeem status will be Valid

   - If employee active in customer contract, employee status will changes to Working-WithCustomer and process will moved to completed stage

   - If employee not active in customer contract,CheckIn Process will create in Lodging module.

   - Once CheckIn Process Completed, Process will moved to Completed.


      - *In The action field is following to,*

          **1-[Complete](#completed-6)** - User Complete the request and refer to [Completed](#completed-6) Stage.

- ### **Visa Expired:**

    - In this stage, ERE Visa expired and received to extend the validation

    - If Exit Re Entry date is expired and muqeem is expired, then that request is moved to **Visa Expired** stage.

    - And then request moved Iqama Expiry.

        - *In The action field is following to,* decision

          **1-[Iqama Expired](#iqama-expired)** - User complete and refer the request with [Iqama Expiry](#iqama-expired) stage.

          **2-[Move_To_WaitingForReturn](#waiting-for-return)** - User decide to complete the request and refer the [Waiting For Return](#waiting-for-return) stage.


- ### **Iqama Approval Cancellation:**

     - If iqama expiry date is less then 10 days, the request will move to Iqama Approval cancellation stage.

     - User validate the Iqama validaty and moved to **Waiting For Return** stage.

        - *In The action field is following to,*

          **1-[Waiting for Return](#waiting-for-return)** - User complete the task and moved to [Waiting for Return](#waiting-for-return) stage.

- ### **Iqama Expired:**

    - User will register "Left Not Return" in muqeem then move to the **Iqma Expiry** date.

    - Validate the Iqama Expiry date and move to **Waiting for Return** stage. if the Iqama validation is expired.

       - *In The action field is following to,*

         **1-[Waiting for Return](#waiting-for-return)** - User complete the Task refer to [Waiting for Return](#waiting-for-return) stage.

- ### **LeftNotReturn:**

     - Employee Status will changed as LeftNotReturn-OutSideKingdom.

     - Retirement Process will start with as **LeftNotReturn** Category for clear the employee settlement.

     - Employees who lefted and do not return from on vacation are Listed for Tracking purposes.

- ### **Completed:**

     - Completed Request is moved to Completed Stage, After the Vacation Return process is completed. And use this data for Tracking the status of the request.

| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#vacation-return) |


<br>

## **[Leave Reject Request:](#leave-management)**

If the Employee reject the leave request in any stage, that reject process will start in **Waiting for Travel** stage only.

| [Vacation Settlement](#vacation-settlement-1) > [Visa Request](#visa-request) > [Travel Request](#travel-request) > [Completed](#completed-7) |

<br>

- ### **Vacation Settlement:**

    - If Vacation Settlement is completed for this request, this stage will start, otherwise it will move to next stage.

    - Waiting to cancel the settelement, and reject the settlement reqest in this stage. once completed the stage then it will move to Visa Request.

       - *In The action field is following to,*

          **1-[Complete](#visa-request)** - User complete the request and refer to [Visa Request](#visa-request) stage.

- ### **Visa Request:**

    - If Visa is completed for this request, this stage will start, otherwise it will move to next stage.

    - Waiting to reject and cancel the Visa Request in the Leave request, once completed the stage then it will move to Travel Request.

      - *In The action field is following to,*

        **1- [Complete](#travel-request)** - User complete the request and Moved to [Travel Request](#travel-request) stage.

- ### **Travel Request:**

     - If Vacation Settlement is completed for this request, this stage will start, otherwise it will move to next stage.

     - Waiting to reject and Cancel the Travel Request in leave request,  once completed the stage then it will move to Completed stage.

       - *In The action field is following to,*

         **1-[Complete](#completed-7)** - User complete the request and moved to [Completed](#completed-7) stage.

- ### **Completed:**

   - If these all stages is completes, then Leave reject request is completed.

   - Completed Request is moved to Completed Stage. And this data is using for Tracking the status of the Request.

| [Home](#human-resource-management) | [Main](#leave-management) | [Back](#leave-reject-request) |

