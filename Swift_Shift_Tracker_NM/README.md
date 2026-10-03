# SwiftShipTracker

Salesforce-based Swift Ship Tracker project.

## Repository structure

This repository is organized using the Salesforce DX folder structure. The uploaded project material is preserved as provided; no Apex/Flow/Agentforce source code has been rewritten or generated.

```text
SwiftShipTracker/
├── README.md
├── .gitignore
├── sfdx-project.json
├── force-app/
│   └── main/
│       └── default/
│           ├── classes/
│           ├── triggers/
│           ├── objects/
│           │   ├── Parcel__c/
│           │   ├── Delivery__c/
│           │   ├── Sender__c/
│           │   └── Receiver__c/
│           ├── flows/
│           ├── permissionsets/
│           ├── profiles/
│           ├── roles/
│           ├── tabs/
│           ├── applications/
│           ├── layouts/
│           ├── email/
│           ├── experiences/
│           └── agentforce/
├── manifest/
│   └── package.xml
└── docs/
    └── Swift Ship Tracker_ NM.pdf
```

## Source preservation

The Agentforce configuration supplied with the project is stored under `force-app/main/default/agentforce/SwiftShip_Tracker.txt` exactly as uploaded. The project PDF is retained under `docs/`.

No replacement Apex classes, triggers, flows, objects, or other source code have been fabricated where the uploaded material did not contain the corresponding source files.
