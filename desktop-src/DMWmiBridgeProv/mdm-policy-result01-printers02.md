---
title: MDM_Policy_Result01_Printers02 class
description: The MDM\_Policy\_Result01\_Printers02 class represents the printer policies.
ms.assetid: f64fbb03-c62c-4f8e-97ad-e08e068a31d1
keywords:
- MDM_Policy_Result01_Printers02 class
- MDM_Policy_Result01_Printers02 class, described
topic_type:
- apiref
api_name:
- MDM_Policy_Result01_Printers02
- MDM_Policy_Result01_Printers02.InstanceID
- MDM_Policy_Result01_Printers02.ParentID
api_location:
- DMWmiBridgeProv.dll
api_type:
- DllExport
ms.topic: reference
ms.date: 05/31/2018
---

# MDM\_Policy\_Result01\_Printers02 class



The MDM\_Policy\_Result01\_Printers02 class represents the printer policies.

The following syntax is simplified from MOF code and includes all inherited properties.

## Syntax

``` syntax
[InPartition("local-system"), dynamic, provider("DMWmiBridgeProv")]
class MDM_Policy_Result01_Printers02
{
  string InstanceID;
  string ParentID;
  string PointAndPrintRestrictions;
  string PublishPrinters;
};
```

## Members

The **MDM\_Policy\_Result01\_Printers02** class has these types of members:

-   [Properties](#properties)

### Properties

The **MDM\_Policy\_Result01\_Printers02** class has these properties.

<dl> <dt>

**InstanceID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

</dd> <dt>

**ParentID**
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read-only
</dt> <dt>

Qualifiers: [**key**](/windows/desktop/WmiSdk/key-qualifier)
</dt> </dl>

</dd> <dt>

[PointAndPrintRestrictions](/windows/client-management/mdm/policy-csp-printers#printers-pointandprintrestrictions)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> <dt>

[PublishPrinters](/windows/client-management/mdm/policy-csp-printers#printers-publishprinters)
</dt> <dd> <dl> <dt>

Data type: **string**
</dt> <dt>

Access type: Read/write
</dt> </dl>

</dd> </dl>

## Requirements



| Requirement | Value |
|-------------------------------------|------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 10 \[desktop apps only\]<br/>                                                    |
| Minimum supported server<br/> | None supported<br/>                                                                      |
| Namespace<br/>                | Root\\cimv2\\mdm\\dmmap<br/>                                                             |
| MOF<br/>                      | <dl> <dt>DMWmiBridgeProv.mof</dt> </dl> |
| DLL<br/>                      | <dl> <dt>DMWmiBridgeProv.dll</dt> </dl> |



 

