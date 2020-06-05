# Participants

|      Description                                     |      Definition                                                                                                                                                                                                                                    |
|------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     Debtor                                           |     Party that owes an amount of money to the (ultimate) creditor. In the   context of the payment model, the debtor is also the debit account owner.                                                                                              |
|     Creditor                                         |     Party to which an amount of money is due. In the   context of the payment model, the creditor is also the credit account owner.                                                                                                                |
|     Ultimate   Debtor                                |     Ultimate party that owes an amount of money to the (ultimate) creditor.                                                                                                                                                                        |
|     Ultimate   Creditor                              |     Ultimate party to which an amount of money is due.                                                                                                                                                                                             |
|     Debtor   Agent                                   |     Financial institution   servicing an account for the debtor.                                                                                                                                                                                   |
|     Creditor   Agent                                 |     Financial institution   servicing an account for the creditor.                                                                                                                                                                                 |
|     Forwarding   Agent                               |     Financial institution that receives the   instruction from the initiating party and forwards it to the next agent in   the payment chain for execution.                                                                                        |
|     Initiating   Party                               |     Party initiating the payment to an agent. In the   payment context, this can either be the debtor (in a credit transfer), the   creditor (in a direct debit), or a party that initiates the payment on behalf   of the debtor or creditor.     |
|     Account   Owner                                  |     Party that legally owns the account.                                                                                                                                                                                                           |
|     Account   Servicer                               |     Party that manages the account on behalf of the   account owner, that is manages the registration and booking of entries on the   account, calculates balances on the account and provides information about   the account.                    |
|     Payment   Clearing Agent (Instructing Agent)     |     Agent that instructs the next party in the payment chain to carry out   the payment/instruction.                                                                                                                                               |
|     Payment   Settlement Agent Instructed Agent)     |     Agent that executes the instruction upon the request of the previous party   in the chain (either an agreement party, or a clearing agent).                                                                                                    |
|     Intermediary   Agent                             |     Agent   between the debtor's agent and   the creditor's   agent. There can be several intermediary agents specified for the   execution of a payment.                                                                                          |

# Business Roles
|      Description             |      Definition                                                            |
|------------------------------|----------------------------------------------------------------------------|
|     Financial Institution    |     Organisation established primarily to provide   financial services.    |
|     Clearing System          |     Specifies the system which plays a role in the clearing process.       |
|     Party                    |     Entity involved in a payment.                                          |

|      Participants                 |      BusinessRole      Financial    Institution     |      BusinessRole      Clearing System     |      BusinessRole      Party     |
|-----------------------------------|-----------------------------------------------------|--------------------------------------------|----------------------------------|
|     Debtor                        |                                                     |                                            |     X                            |
|     Creditor                      |                                                     |                                            |     X                            |
|     Ultimate   Debtor             |                                                     |                                            |     X                            |
|     Ultimate   Creditor           |                                                     |                                            |     X                            |
|     Debtor   Agent                |     X                                               |     X                                      |                                  |
|     Creditor   Agent              |     X                                               |     X                                      |                                  |
|     Forwarding   Agent            |     X                                               |     X                                      |                                  |
|     Initiating   Party            |                                                     |                                            |     X                            |
|     Account   Owner               |     X                                               |                                            |     X                            |
|     Account   Servicer            |     X                                               |     X                                      |                                  |
|     Payment   Clearing Agent      |     X                                               |     X                                      |                                  |
|     Payment   Settlement Agent    |     X                                               |     X                                      |                                  |
|     Intermediary   Agent          |     X                                               |     X                                      |                                  |
