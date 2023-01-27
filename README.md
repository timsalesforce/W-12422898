# W-12422898 - Allegis Group, Inc. - Lookup field error in lightning:recordEditForm in Spring'23 orgs


## Repro steps
1. Clone repo and deploy to 242 scratch org (use "release": "preview" in scratch config as of 1/27/2023)
2. Login to org, and create a new Case
3. On the RH of the Case the nested recordEditForms are on the "nested" Aura Comp.
4. Observe that the second lookup field to Account is disabled with the message: 'Review this lookup configuration. Your Salesforce admin can help with this.'

