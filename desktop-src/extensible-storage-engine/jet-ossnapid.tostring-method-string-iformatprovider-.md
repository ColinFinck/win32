---
description: "Learn more about: JET_OSSNAPID.ToString method (String, IFormatProvider)"
title: JET_OSSNAPID.ToString method (String, IFormatProvider)
TOCTitle: ToString method (String, IFormatProvider)
ms:assetid: M:Microsoft.Isam.Esent.Interop.JET_OSSNAPID.ToString(System.String,System.IFormatProvider)
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.jet_ossnapid.tostring(v=EXCHG.10)
ms:contentKeyID: 39512151
ms.date: 07/30/2014
ms.topic: reference
dev_langs:
- vb
- csharp
api_name: 
- Microsoft.Isam.Esent.Interop.JET_OSSNAPID.ToString
topic_type: 
- apiref
- kbSyntax
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET_OSSNAPID.ToString method (String, IFormatProvider)

Formats the value of the current instance using the specified format.

**Namespace:**  [Microsoft.Isam.Esent.Interop](./microsoft.isam.esent.interop-namespace.md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Function ToString ( _
    format As String, _
    formatProvider As IFormatProvider _
) As String
'Usage
Dim instance As JET_OSSNAPID
Dim format As String
Dim formatProvider As IFormatProvider
Dim returnValue As String

returnValue = instance.ToString(format, _
    formatProvider)
```

``` csharp
public string ToString(
    string format,
    IFormatProvider formatProvider
)
```

#### Parameters

  - format  
    Type: [System.String](/dotnet/api/system.string)  
    
    The [String](/dotnet/api/system.string) specifying the format to use. -or- null to use the default format defined for the type of the [IFormattable](/dotnet/api/system.iformattable) implementation.

<!-- end list -->

  - formatProvider  
    Type: [System.IFormatProvider](/dotnet/api/system.iformatprovider)  
    
    The [IFormatProvider](/dotnet/api/system.iformatprovider) to use to format the value. -or- null to obtain the numeric format information from the current locale setting of the operating system.

#### Return value

Type: [System.String](/dotnet/api/system.string)  
A [String](/dotnet/api/system.string) containing the value of the current instance in the specified format.  

#### Implements

[IFormattable.ToString(String, IFormatProvider)](/dotnet/api/system.iformattable.tostring#System_IFormattable_ToString_System_String_System_IFormatProvider_)  

## See also

#### Reference

[JET_OSSNAPID structure](./jet-ossnapid-structure.md)

[JET_OSSNAPID members](./jet-ossnapid-members.md)

[ToString overload](./jet-ossnapid.tostring-method.md)

[Microsoft.Isam.Esent.Interop namespace](./microsoft.isam.esent.interop-namespace.md)
