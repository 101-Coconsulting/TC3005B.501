# TC3005B.501
Portal web para que empresas puedan tener un flujo de solicitud de viajes por parte de los empleados que requieran algún tipo de apoyo por parte de la empresa. Ya sea en materia de reembolso, anticipo, reservaciones de hotel y/o de vuelos.

## Process State Diagram

The process of processing a travel request application is represented by the following state diagram from start to finish:

```mermaid
stateDiagram
  direction LR
  [*] --> First_Revision
  [*] --> Draft
  Draft --> First_Revision
  First_Revision --> Rejected
  First_Revision --> Second_Revision
  Second_Revision --> Rejected
  Second_Revision --> Trip_Quote
  Trip_Quote --> Travel_Agency_Attention
  Travel_Agency_Attention --> Trip_Expenses_Verification
  Trip_Expenses_Verification --> Voucher_Verification
  Voucher_Verification --> Finalized
  Voucher_Verification --> Trip_Expenses_Verification
  First_Revision --> Canceled
  Second_Revision --> Canceled
  Trip_Quote --> Canceled
  Travel_Agency_Attention --> Canceled
  Draft --> Canceled
  Finalized --> [*]
  Rejected --> [*]
  Canceled --> [*]
```
