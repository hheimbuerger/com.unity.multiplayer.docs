---
id: Unity.Multiplayer.Tools.NetStats.MetricTypeEnumAttribute
title: Unity.Multiplayer.Tools.NetStats.MetricTypeEnumAttribute
---

## Class MetricTypeEnumAttribute

Use this attribute to declare an enum that represents custom metrics for
use with the Multiplayer Tools package. In particular, this attribute
can be used to declare custom metrics that can be displayed in the .

### Inheritance

System.Object

System.Attribute

MetricTypeEnumAttribute

### Implements

System.Runtime.InteropServices.\_Attribute

<!-- Commented out for user readability. Keep commented out for future updates.
##### Inherited Members

System.Attribute.Equals(System.Object)

System.Attribute.GetCustomAttribute(System.Reflection.Assembly,
System.Type)

System.Attribute.GetCustomAttribute(System.Reflection.Assembly,
System.Type, System.Boolean)

System.Attribute.GetCustomAttribute(System.Reflection.MemberInfo,
System.Type)

System.Attribute.GetCustomAttribute(System.Reflection.MemberInfo,
System.Type, System.Boolean)

System.Attribute.GetCustomAttribute(System.Reflection.Module,
System.Type)

System.Attribute.GetCustomAttribute(System.Reflection.Module,
System.Type, System.Boolean)

System.Attribute.GetCustomAttribute(System.Reflection.ParameterInfo,
System.Type)

System.Attribute.GetCustomAttribute(System.Reflection.ParameterInfo,
System.Type, System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.Assembly)

System.Attribute.GetCustomAttributes(System.Reflection.Assembly,
System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.Assembly,
System.Type)

System.Attribute.GetCustomAttributes(System.Reflection.Assembly,
System.Type, System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.MemberInfo)

System.Attribute.GetCustomAttributes(System.Reflection.MemberInfo,
System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.MemberInfo,
System.Type)

System.Attribute.GetCustomAttributes(System.Reflection.MemberInfo,
System.Type, System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.Module)

System.Attribute.GetCustomAttributes(System.Reflection.Module,
System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.Module,
System.Type)

System.Attribute.GetCustomAttributes(System.Reflection.Module,
System.Type, System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.ParameterInfo)

System.Attribute.GetCustomAttributes(System.Reflection.ParameterInfo,
System.Boolean)

System.Attribute.GetCustomAttributes(System.Reflection.ParameterInfo,
System.Type)

System.Attribute.GetCustomAttributes(System.Reflection.ParameterInfo,
System.Type, System.Boolean)

System.Attribute.GetHashCode()

System.Attribute.IsDefaultAttribute()

System.Attribute.IsDefined(System.Reflection.Assembly, System.Type)

System.Attribute.IsDefined(System.Reflection.Assembly, System.Type,
System.Boolean)

System.Attribute.IsDefined(System.Reflection.MemberInfo, System.Type)

System.Attribute.IsDefined(System.Reflection.MemberInfo, System.Type,
System.Boolean)

System.Attribute.IsDefined(System.Reflection.Module, System.Type)

System.Attribute.IsDefined(System.Reflection.Module, System.Type,
System.Boolean)

System.Attribute.IsDefined(System.Reflection.ParameterInfo, System.Type)

System.Attribute.IsDefined(System.Reflection.ParameterInfo, System.Type,
System.Boolean)

System.Attribute.Match(System.Object)

System.Attribute.System.Runtime.InteropServices.\_Attribute.GetIDsOfNames(System.Guid,
System.IntPtr, System.UInt32, System.UInt32, System.IntPtr)

System.Attribute.System.Runtime.InteropServices.\_Attribute.GetTypeInfo(System.UInt32,
System.UInt32, System.IntPtr)

System.Attribute.System.Runtime.InteropServices.\_Attribute.GetTypeInfoCount(System.UInt32)

System.Attribute.System.Runtime.InteropServices.\_Attribute.Invoke(System.UInt32,
System.Guid, System.UInt32, System.Int16, System.IntPtr, System.IntPtr,
System.IntPtr, System.IntPtr)

System.Attribute.TypeId

System.Object.Equals(System.Object, System.Object)

System.Object.GetType()

System.Object.MemberwiseClone()

System.Object.ReferenceEquals(System.Object, System.Object)

System.Object.ToString()
-->

## **Namespace**: Unity.Multiplayer.Tools.NetStats

### **Assembly**: Tools.dll

### Syntax

``` lang-csharp
[AttributeUsage(AttributeTargets.Enum)]
public class MetricTypeEnumAttribute : Attribute, _Attribute
```

### Properties

#### DisplayName

The custom display name to use for the metric enum. This can be set to
something different than the name of the enum to provide a nicer display
name in UIs like the inspector.

#### Declaration

``` lang-csharp
public string DisplayName { get; set; }
```

#### Property Value

| Type          | Description |
|---------------|-------------|
| System.String |             |

### Implements

System.Runtime.InteropServices.\_Attribute