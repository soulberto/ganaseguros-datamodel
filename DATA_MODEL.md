# Modelo de datos implementado para Ganaseguros

Consideraciones:

- Los objetos personalizados implementados para el cliente y que complementan el model de datos de Insurance tiene el prefijo `clb_ins_`.
- Este modelo de datos se encuentra en construcción, por ende esta documentación en una referencia y esta en constante actualización.

## Nivel 0

![Modelo de datos](/images/Screenshot%202023-04-04%20at%209.14.31%20AM.png)

## Nivel 1

### Account

![Modelo de datos nivel 1 - Explosión de Account y sus relaciones](/images/Screenshot%202023-04-04%20at%209.27.46%20AM.png)

### Contact

![Modelo de datos nivel 1 - Explosión de Contact y sus relaciones](/images/Screenshot%202023-04-04%20at%209.32.52%20AM.png)

### Opportunity

![Modelo de datos nivel 1 - Explosión de Opportunity y sus relaciones](/images/Screenshot%202023-04-04%20at%209.35.33%20AM.png)

### Quote

![Modelo de datos nivel 1 - Explosión de Quote y sus relaciones](/images/Screenshot%202023-04-04%20at%209.40.35%20AM.png)

### Insurance Policy

![Modelo de datos nivel 1 - Explosión de Insurance Policy y sus relaciones](/images/Screenshot%202023-04-04%20at%209.44.51%20AM.png)

## Listado de objetos
- clb_ins_MedicalReport__c
- clb_ins_MedicalAttentionOrder__c
- InsurancePolicyCoverage
- FinServ__PolicyPaymentMethod__c
- ActionPlan
- InsurancePolicyMemberAsset
- PoliciesGroup__c
- InsurancePolicyParticipant
- InsurancePolicy
- Opportunity
- Quote
- FinServ__IdentificationDocument__c
- clb_ins_MedicalReport__c
- clb_ins_MedicalAttentionOrder__c
- QuoteLineItem
- Case
- Contact
- InsuranceProfile
- FinServ__Employment__c
- FinServ__FinancialAccount__c
- FinServ__Employment__c
- Policy_Transaction__c
- InsurancePolicyTransaction
- clb_ins_Liquidations__c
- vlocity_ins_fsc__InsurancePolicyPaymentScheduleEntry__c
- clb_ins_OpportunityFinancialInformation__c
- clb_ins_InsuranceProfileDiseaseDetails__c
- ClaimParticipant
- Codebtors__c
- vlocity_ins__Party__c
- InsurancePolicyAsset
- clb_ins_Cumulos__c
- Account
- clb_ins_PolicyRatingDetail__b
