<a name='assembly'></a>
# Afg.Umzug.Jobs

## Contents

- [Helpers](#T-Afg-Umzug-Jobs-Helpers 'Afg.Umzug.Jobs.Helpers')
  - [CINVGrouping(CINVlst)](#M-Afg-Umzug-Jobs-Helpers-CINVGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.CINVGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [CRTNGrouping(CRTNlst)](#M-Afg-Umzug-Jobs-Helpers-CRTNGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.CRTNGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [CreateIonXML(validLst)](#M-Afg-Umzug-Jobs-Helpers-CreateIonXML-System-Collections-Generic-List{Afg-Umzug-Data-Models-ION_Bod}- 'Afg.Umzug.Jobs.Helpers.CreateIonXML(System.Collections.Generic.List{Afg.Umzug.Data.Models.ION_Bod})')
  - [GroupValidTransactions(lst,tranType)](#M-Afg-Umzug-Jobs-Helpers-GroupValidTransactions-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},System-String- 'Afg.Umzug.Jobs.Helpers.GroupValidTransactions(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact},System.String)')
  - [HOLDGrouping(HOLDlst)](#M-Afg-Umzug-Jobs-Helpers-HOLDGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.HOLDGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [PBLDGrouping(PBLDlst)](#M-Afg-Umzug-Jobs-Helpers-PBLDGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.PBLDGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [PINVGrouping(PINVlst)](#M-Afg-Umzug-Jobs-Helpers-PINVGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.PINVGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [PRODGrouping(PRODlst)](#M-Afg-Umzug-Jobs-Helpers-PRODGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.PRODGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [PURCGrouping(PURClst)](#M-Afg-Umzug-Jobs-Helpers-PURCGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.PURCGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [PropertiesToTuples(o)](#M-Afg-Umzug-Jobs-Helpers-PropertiesToTuples-System-Object- 'Afg.Umzug.Jobs.Helpers.PropertiesToTuples(System.Object)')
  - [RTRNGrouping(RTRNlst)](#M-Afg-Umzug-Jobs-Helpers-RTRNGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.RTRNGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [RWRKGrouping(RWRKlst)](#M-Afg-Umzug-Jobs-Helpers-RWRKGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.RWRKGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [SHIPGrouping(SHIPlst)](#M-Afg-Umzug-Jobs-Helpers-SHIPGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.SHIPGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [SPURGrouping(SPURlst)](#M-Afg-Umzug-Jobs-Helpers-SPURGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.SPURGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [STRNGrouping(STRNlst)](#M-Afg-Umzug-Jobs-Helpers-STRNGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.STRNGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [SUGEGrouping(SUGElst)](#M-Afg-Umzug-Jobs-Helpers-SUGEGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.SUGEGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [TRNSGrouping(TRNSlst)](#M-Afg-Umzug-Jobs-Helpers-TRNSGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.TRNSGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
  - [USGEGrouping(USGElst)](#M-Afg-Umzug-Jobs-Helpers-USGEGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}- 'Afg.Umzug.Jobs.Helpers.USGEGrouping(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact})')
- [UpdateUmzugFromDCS](#T-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS')
  - [WhenAllEx(tasks,reportProgressAction)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-WhenAllEx-System-Collections-Generic-ICollection{System-Threading-Tasks-Task},System-Action{System-Collections-Generic-ICollection{System-Threading-Tasks-Task}}- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS.WhenAllEx(System.Collections.Generic.ICollection{System.Threading.Tasks.Task},System.Action{System.Collections.Generic.ICollection{System.Threading.Tasks.Task}})')

<a name='T-Afg-Umzug-Jobs-Helpers'></a>
## Helpers `type`

##### Namespace

Afg.Umzug.Jobs

<a name='M-Afg-Umzug-Jobs-Helpers-CINVGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### CINVGrouping(CINVlst) `method`

##### Summary

Groups the CINV transactions together by their InvLocation

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the CINV transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| CINVlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all CINV transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-CRTNGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### CRTNGrouping(CRTNlst) `method`

##### Summary

Groups the CRTN transactions together by their RepNo

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the CRTN transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| CRTNlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all CRTN transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-CreateIonXML-System-Collections-Generic-List{Afg-Umzug-Data-Models-ION_Bod}-'></a>
### CreateIonXML(validLst) `method`

##### Summary

Creates the xml from the list list of valid transaction using the [PropertiesToTuples](#M-Afg-Umzug-Jobs-Helpers-PropertiesToTuples-System-Object- 'Afg.Umzug.Jobs.Helpers.PropertiesToTuples(System.Object)') function

##### Returns

The [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') that contains the transactions in the correct xml format

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| validLst | [System.Collections.Generic.List{Afg.Umzug.Data.Models.ION_Bod}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.List 'System.Collections.Generic.List{Afg.Umzug.Data.Models.ION_Bod}') | The [List\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.List`1 'System.Collections.Generic.List`1') with the valid list of transaction that are to be sent to ION |

<a name='M-Afg-Umzug-Jobs-Helpers-GroupValidTransactions-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},System-String-'></a>
### GroupValidTransactions(lst,tranType) `method`

##### Summary

Takes the list of transactions and sends them the the grouping method according the their Transaction type.

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the given Transaction type

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| lst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') |
| tranType | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | A [String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') of the Transaction type we will group on |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.Exception](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Exception 'System.Exception') | An exception is thrown if we receive and invalid Transaction type |

<a name='M-Afg-Umzug-Jobs-Helpers-HOLDGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### HOLDGrouping(HOLDlst) `method`

##### Summary

Groups the HOLD transactions together by their QALot

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the HOLD transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| HOLDlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all HOLD transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-PBLDGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### PBLDGrouping(PBLDlst) `method`

##### Summary

Groups the PBLD transactions together by their NewPalletId

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the PBLD transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| PBLDlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all PBLD transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-PINVGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### PINVGrouping(PINVlst) `method`

##### Summary

Groups the PBLD transactions together by their PINum

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the PINV transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| PINVlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all PINV transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-PRODGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### PRODGrouping(PRODlst) `method`

##### Summary

Groups the PROD transactions together by their ManufacturingOrder

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the PROD transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| PRODlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all PROD transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-PURCGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### PURCGrouping(PURClst) `method`

##### Summary

Groups the PURC transactions together by their PurchaseOrder

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the PURC transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| PURClst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all PURC transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-PropertiesToTuples-System-Object-'></a>
### PropertiesToTuples(o) `method`

##### Summary

Creates the attribute tuples from the object properties by taking the property name and the value.

##### Returns

A tuple array, [](#!-Tuple<String, Object>[] 'Tuple<String, Object>[]') with the values and the names

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| o | [System.Object](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Object 'System.Object') | Commonly [ION_Bod](#T-Afg-Umzug-Data-Models-ION_Bod 'Afg.Umzug.Data.Models.ION_Bod') is the object passed in. |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.ArgumentNullException](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.ArgumentNullException 'System.ArgumentNullException') |  |

<a name='M-Afg-Umzug-Jobs-Helpers-RTRNGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### RTRNGrouping(RTRNlst) `method`

##### Summary

Groups the RTRN transactions together by their ControlNo

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the RTRN transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| RTRNlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all RTRN transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-RWRKGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### RWRKGrouping(RWRKlst) `method`

##### Summary

Groups the RWRK transactions together by their ControlNo

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the RWRK transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| RWRKlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all RWRK transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-SHIPGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### SHIPGrouping(SHIPlst) `method`

##### Summary

Groups the SHIP transactions together by their ControlNo

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the SHIP transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| SHIPlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all SHIP transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-SPURGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### SPURGrouping(SPURlst) `method`

##### Summary

Groups the SPUR transactions together by their PurchaseOrder

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the SPUR transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| SPURlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all SPUR transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-STRNGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### STRNGrouping(STRNlst) `method`

##### Summary

Groups the STRN transactions together by their TransferNo

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the STRN transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| STRNlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all STRN transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-SUGEGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### SUGEGrouping(SUGElst) `method`

##### Summary

Groups the SUGE transactions together by their ManufacturingOrder

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the SUGE transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| SUGElst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all SUGE transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-TRNSGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### TRNSGrouping(TRNSlst) `method`

##### Summary

Groups the TRNS transactions together by their TransferNo

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the TRNS transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| TRNSlst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all TRNS transactions |

<a name='M-Afg-Umzug-Jobs-Helpers-USGEGrouping-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact}-'></a>
### USGEGrouping(USGElst) `method`

##### Summary

Groups the USGE transactions together by their ManufacturingOrder

##### Returns

Returns the [XDocument](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Xml.Linq.XDocument 'System.Xml.Linq.XDocument') for the USGE transaction

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| USGElst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | A list of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') with generic type [Umzug_Transact](#T-Afg-Umzug-Data-Models-Umzug_Transact 'Afg.Umzug.Data.Models.Umzug_Transact') with all USGE transactions |

<a name='T-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS'></a>
## UpdateUmzugFromDCS `type`

##### Namespace

Afg.Umzug.Jobs.BackgroundJobs

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-WhenAllEx-System-Collections-Generic-ICollection{System-Threading-Tasks-Task},System-Action{System-Collections-Generic-ICollection{System-Threading-Tasks-Task}}-'></a>
### WhenAllEx(tasks,reportProgressAction) `method`

##### Summary

Takes a collection of tasks and completes the returned task when all tasks have completed. If completion
takes a while a progress lambda is called where all tasks can be observed for their status.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tasks | [System.Collections.Generic.ICollection{System.Threading.Tasks.Task}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.ICollection 'System.Collections.Generic.ICollection{System.Threading.Tasks.Task}') |  |
| reportProgressAction | [System.Action{System.Collections.Generic.ICollection{System.Threading.Tasks.Task}}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Action 'System.Action{System.Collections.Generic.ICollection{System.Threading.Tasks.Task}}') |  |
