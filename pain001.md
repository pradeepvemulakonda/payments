# CustomerCreditTransferInitiation - Version 10
Usage
The CustomerCreditTransferInitiation message can contain one or more customer credit transfer
instructions.
The CustomerCreditTransferInitiation message is used to exchange:
- One or more instances of a credit transfer initiation;
- Payment transactions that result in book transfers at the debtor agent or payments to another financial
institution;
- Payment transactions that result in an electronic cash transfer to the creditor account or in the
emission of a cheque.
The message can be used in a direct or a relay scenario:
- In a direct scenario, the message is sent directly to the debtor agent. The debtor agent is the account
servicer of the debtor.
- In a relay scenario, the message is sent to a forwarding agent. The forwarding agent acts as a
concentrating financial institution. It will forward the CustomerCreditTransferInitiation message to the
debtor agent.
The message can also be used by an initiating party that has authority to send the message on behalf
of the debtor. This caters for example for the scenario of a payments factory initiating all payments on
behalf of a large corporate.
The CustomerCreditTransferInitiation message can be used in domestic and cross-border scenarios.
The CustomerCreditTransferInitiation message must not be used by the debtor agent to execute the
credit transfer instruction(s). The FIToFICustomerCreditTransfer message must be used instead.

## GroupHeader:
Set of characteristics shared by all individual transactions included in the message.
### Attributes

| Element        | validation           | datatype  | description|
| ------------- |:-------------:| -----:|---------------------------:|
| MessageIdentification      | String(max:35) | $1600 ||
| col 2 is      | centered      |   $12 ||
| zebra stripes | are neat      |    $1 ||
