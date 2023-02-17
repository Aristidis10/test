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
- [IgnoreErroredJobs](#T-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs 'Afg.Umzug.Jobs.ActiveJobs.IgnoreErroredJobs')
  - [#ctor(repository,ionHttpClient,logger)](#M-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}- 'Afg.Umzug.Jobs.ActiveJobs.IgnoreErroredJobs.#ctor(Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository,Afg.Ion.Client.IonHttpClient,Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug})')
  - [Ignore(token,context,id)](#M-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs-Ignore-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-String- 'Afg.Umzug.Jobs.ActiveJobs.IgnoreErroredJobs.Ignore(System.Threading.CancellationToken,Hangfire.Server.PerformContext,System.String)')
  - [Ignore(token,context,lstIds)](#M-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs-Ignore-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-Collections-Generic-IEnumerable{System-String}- 'Afg.Umzug.Jobs.ActiveJobs.IgnoreErroredJobs.Ignore(System.Threading.CancellationToken,Hangfire.Server.PerformContext,System.Collections.Generic.IEnumerable{System.String})')
- [ResendAllErroredJobs](#T-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs 'Afg.Umzug.Jobs.ActiveJobs.ResendAllErroredJobs')
  - [#ctor(repository,ionHttpClient,logger)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}- 'Afg.Umzug.Jobs.ActiveJobs.ResendAllErroredJobs.#ctor(Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository,Afg.Ion.Client.IonHttpClient,Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug})')
  - [Resend(token,context)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs-Resend-System-Threading-CancellationToken,Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.ActiveJobs.ResendAllErroredJobs.Resend(System.Threading.CancellationToken,Hangfire.Server.PerformContext)')
  - [SendListToIon(lst,context)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs-SendListToIon-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.ActiveJobs.ResendAllErroredJobs.SendListToIon(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact},Hangfire.Server.PerformContext)')
- [ResendErroredJobs](#T-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs 'Afg.Umzug.Jobs.ActiveJobs.ResendErroredJobs')
  - [#ctor(repository,ionHttpClient,logger)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}- 'Afg.Umzug.Jobs.ActiveJobs.ResendErroredJobs.#ctor(Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository,Afg.Ion.Client.IonHttpClient,Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug})')
  - [Resend(token,context,id)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-Resend-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-String- 'Afg.Umzug.Jobs.ActiveJobs.ResendErroredJobs.Resend(System.Threading.CancellationToken,Hangfire.Server.PerformContext,System.String)')
  - [Resend(token,context,ids)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-Resend-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-Collections-Generic-IEnumerable{System-String}- 'Afg.Umzug.Jobs.ActiveJobs.ResendErroredJobs.Resend(System.Threading.CancellationToken,Hangfire.Server.PerformContext,System.Collections.Generic.IEnumerable{System.String})')
  - [SendListToIon(lst,context)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-SendListToIon-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.ActiveJobs.ResendErroredJobs.SendListToIon(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact},Hangfire.Server.PerformContext)')
- [ResendTransactionByDates](#T-Afg-Umzug-Jobs-ActiveJobs-ResendTransactionByDates 'Afg.Umzug.Jobs.ActiveJobs.ResendTransactionByDates')
  - [#ctor(dbService)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendTransactionByDates-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService- 'Afg.Umzug.Jobs.ActiveJobs.ResendTransactionByDates.#ctor(Afg.Umzug.Data.Services.AfgWMSM3DataService)')
  - [Resend(dateStart,dateEnd,token,context)](#M-Afg-Umzug-Jobs-ActiveJobs-ResendTransactionByDates-Resend-System-DateTime,System-DateTime,System-Threading-CancellationToken,Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.ActiveJobs.ResendTransactionByDates.Resend(System.DateTime,System.DateTime,System.Threading.CancellationToken,Hangfire.Server.PerformContext)')
- [Startup](#T-Afg-Umzug-Jobs-Startup 'Afg.Umzug.Jobs.Startup')
  - [AddUmzugJobs(services)](#M-Afg-Umzug-Jobs-Startup-AddUmzugJobs-Microsoft-Extensions-DependencyInjection-IServiceCollection- 'Afg.Umzug.Jobs.Startup.AddUmzugJobs(Microsoft.Extensions.DependencyInjection.IServiceCollection)')
  - [SetupReocurringJobs()](#M-Afg-Umzug-Jobs-Startup-SetupReocurringJobs 'Afg.Umzug.Jobs.Startup.SetupReocurringJobs')
- [UpdateDCSFromUmzug](#T-Afg-Umzug-Jobs-BackgroundJobs-UpdateDCSFromUmzug 'Afg.Umzug.Jobs.BackgroundJobs.UpdateDCSFromUmzug')
  - [#ctor(dbService,repository)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateDCSFromUmzug-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService,Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateDCSFromUmzug.#ctor(Afg.Umzug.Data.Services.AfgWMSM3DataService,Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository)')
  - [Update(token,context)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateDCSFromUmzug-Update-System-Threading-CancellationToken,Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateDCSFromUmzug.Update(System.Threading.CancellationToken,Hangfire.Server.PerformContext)')
- [UpdateIonFromUmzug](#T-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug 'Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug')
  - [#ctor(repository,ionHttpClient,logger)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug.#ctor(Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository,Afg.Ion.Client.IonHttpClient,Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug})')
  - [GetListToExportAsync()](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-GetListToExportAsync 'Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug.GetListToExportAsync')
  - [SendListToIon(lst,context)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-SendListToIon-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug.SendListToIon(System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact},Hangfire.Server.PerformContext)')
  - [Update(token,context)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-Update-System-Threading-CancellationToken,Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug.Update(System.Threading.CancellationToken,Hangfire.Server.PerformContext)')
- [UpdateUmzugFromDCS](#T-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS')
  - [#ctor(dbService,logger,repository)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS},Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS.#ctor(Afg.Umzug.Data.Services.AfgWMSM3DataService,Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS},Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository)')
  - [SyncDatabaseAsync(cancellationToken,performContext)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-SyncDatabaseAsync-System-Threading-CancellationToken,Hangfire-Server-PerformContext- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS.SyncDatabaseAsync(System.Threading.CancellationToken,Hangfire.Server.PerformContext)')
  - [WhenAllEx(tasks,reportProgressAction)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-WhenAllEx-System-Collections-Generic-ICollection{System-Threading-Tasks-Task},System-Action{System-Collections-Generic-ICollection{System-Threading-Tasks-Task}}- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS.WhenAllEx(System.Collections.Generic.ICollection{System.Threading.Tasks.Task},System.Action{System.Collections.Generic.ICollection{System.Threading.Tasks.Task}})')
- [UpdateUmzugFromIon](#T-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromIon 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromIon')
  - [#ctor(dbService,repository)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromIon-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService,Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromIon.#ctor(Afg.Umzug.Data.Services.AfgWMSM3DataService,Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository)')
  - [Update(token,context,objectFromIon)](#M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromIon-Update-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-M3Response}- 'Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromIon.Update(System.Threading.CancellationToken,Hangfire.Server.PerformContext,System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.M3Response})')

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

<a name='T-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs'></a>
## IgnoreErroredJobs `type`

##### Namespace

Afg.Umzug.Jobs.ActiveJobs

<a name='M-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}-'></a>
### #ctor(repository,ionHttpClient,logger) `constructor`

##### Summary

Constructor for IgnoreErroredJobs

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| repository | [Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |
| ionHttpClient | [Afg.Ion.Client.IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') | The injection of the Ion Client of type [IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') |
| logger | [Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}](#T-Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug} 'Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}') | The injection of the logger of type [ILogger\`1](#T-Microsoft-Extensions-Logging-ILogger`1 'Microsoft.Extensions.Logging.ILogger`1') |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs-Ignore-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-String-'></a>
### Ignore(token,context,id) `method`

##### Summary

Ignores the error for a transaction being sent to ION

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |
| id | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The id that is to be ignored of type [String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-IgnoreErroredJobs-Ignore-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-Collections-Generic-IEnumerable{System-String}-'></a>
### Ignore(token,context,lstIds) `method`

##### Summary

Ignores the error for a transaction being sent to ION

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |
| lstIds | [System.Collections.Generic.IEnumerable{System.String}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{System.String}') | The list of Id's that are to be ingored of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') |

<a name='T-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs'></a>
## ResendAllErroredJobs `type`

##### Namespace

Afg.Umzug.Jobs.ActiveJobs

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}-'></a>
### #ctor(repository,ionHttpClient,logger) `constructor`

##### Summary

Constructor for ResendAllErroredJobs

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| repository | [Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |
| ionHttpClient | [Afg.Ion.Client.IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') | The injection of the Ion Client of type [IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') |
| logger | [Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}](#T-Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug} 'Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}') | The injection of the logger of type [ILogger\`1](#T-Microsoft-Extensions-Logging-ILogger`1 'Microsoft.Extensions.Logging.ILogger`1') |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs-Resend-System-Threading-CancellationToken,Hangfire-Server-PerformContext-'></a>
### Resend(token,context) `method`

##### Summary

Resends all errored transactions

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendAllErroredJobs-SendListToIon-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},Hangfire-Server-PerformContext-'></a>
### SendListToIon(lst,context) `method`

##### Summary

Sends the list of valid transactions to ION

##### Returns

A successful response message

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| lst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | The list of valid transactions to send ot ION of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.Exception](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Exception 'System.Exception') | TWhen an unacceptable status code is received |

<a name='T-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs'></a>
## ResendErroredJobs `type`

##### Namespace

Afg.Umzug.Jobs.ActiveJobs

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}-'></a>
### #ctor(repository,ionHttpClient,logger) `constructor`

##### Summary

Constructor for ResendErroredJobs

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| repository | [Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |
| ionHttpClient | [Afg.Ion.Client.IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') | The injection of the Ion Client of type [IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') |
| logger | [Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}](#T-Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug} 'Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}') | The injection of the logger of type [ILogger\`1](#T-Microsoft-Extensions-Logging-ILogger`1 'Microsoft.Extensions.Logging.ILogger`1') |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-Resend-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-String-'></a>
### Resend(token,context,id) `method`

##### Summary

Resend the transactions with the specified id

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |
| id | [System.String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') | The id that is the be resent of type [String](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.String 'System.String') |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-Resend-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-Collections-Generic-IEnumerable{System-String}-'></a>
### Resend(token,context,ids) `method`

##### Summary

Resends the transactions with the specifiec id

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |
| ids | [System.Collections.Generic.IEnumerable{System.String}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{System.String}') | The list of ids that are resent of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendErroredJobs-SendListToIon-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},Hangfire-Server-PerformContext-'></a>
### SendListToIon(lst,context) `method`

##### Summary

Sends the list of valid transactions to ION

##### Returns

A successful response message

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| lst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | The list of valid transactions to send ot ION of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.Exception](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Exception 'System.Exception') | TWhen an unacceptable status code is received |

<a name='T-Afg-Umzug-Jobs-ActiveJobs-ResendTransactionByDates'></a>
## ResendTransactionByDates `type`

##### Namespace

Afg.Umzug.Jobs.ActiveJobs

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendTransactionByDates-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService-'></a>
### #ctor(dbService) `constructor`

##### Summary

Constructor for ResendTransactionByDates

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| dbService | [Afg.Umzug.Data.Services.AfgWMSM3DataService](#T-Afg-Umzug-Data-Services-AfgWMSM3DataService 'Afg.Umzug.Data.Services.AfgWMSM3DataService') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |

<a name='M-Afg-Umzug-Jobs-ActiveJobs-ResendTransactionByDates-Resend-System-DateTime,System-DateTime,System-Threading-CancellationToken,Hangfire-Server-PerformContext-'></a>
### Resend(dateStart,dateEnd,token,context) `method`

##### Summary

Resends the transactions between a set of dates

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| dateStart | [System.DateTime](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.DateTime 'System.DateTime') | The start date of type [DateTime](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.DateTime 'System.DateTime') from which to get transactions |
| dateEnd | [System.DateTime](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.DateTime 'System.DateTime') | The end date of type [DateTime](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.DateTime 'System.DateTime') from which to get transactions |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

<a name='T-Afg-Umzug-Jobs-Startup'></a>
## Startup `type`

##### Namespace

Afg.Umzug.Jobs

<a name='M-Afg-Umzug-Jobs-Startup-AddUmzugJobs-Microsoft-Extensions-DependencyInjection-IServiceCollection-'></a>
### AddUmzugJobs(services) `method`

##### Summary

Adds all the Job services to the service collection

##### Returns

The service collection

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| services | [Microsoft.Extensions.DependencyInjection.IServiceCollection](#T-Microsoft-Extensions-DependencyInjection-IServiceCollection 'Microsoft.Extensions.DependencyInjection.IServiceCollection') | A collection of services of type [IServiceCollection](#T-Microsoft-Extensions-DependencyInjection-IServiceCollection 'Microsoft.Extensions.DependencyInjection.IServiceCollection') |

<a name='M-Afg-Umzug-Jobs-Startup-SetupReocurringJobs'></a>
### SetupReocurringJobs() `method`

##### Summary

Setup of reocurring jobs that run in the background

##### Parameters

This method has no parameters.

<a name='T-Afg-Umzug-Jobs-BackgroundJobs-UpdateDCSFromUmzug'></a>
## UpdateDCSFromUmzug `type`

##### Namespace

Afg.Umzug.Jobs.BackgroundJobs

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateDCSFromUmzug-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService,Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository-'></a>
### #ctor(dbService,repository) `constructor`

##### Summary

Constructor for UpdateDCSFromUmzug

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| dbService | [Afg.Umzug.Data.Services.AfgWMSM3DataService](#T-Afg-Umzug-Data-Services-AfgWMSM3DataService 'Afg.Umzug.Data.Services.AfgWMSM3DataService') | The injection of the database service of type [AfgWMSM3DataService](#T-Afg-Umzug-Data-Services-AfgWMSM3DataService 'Afg.Umzug.Data.Services.AfgWMSM3DataService') |
| repository | [Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateDCSFromUmzug-Update-System-Threading-CancellationToken,Hangfire-Server-PerformContext-'></a>
### Update(token,context) `method`

##### Summary

Method that updates DCS from the CosmoDb

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

<a name='T-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug'></a>
## UpdateIonFromUmzug `type`

##### Namespace

Afg.Umzug.Jobs.BackgroundJobs

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-#ctor-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository,Afg-Ion-Client-IonHttpClient,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug}-'></a>
### #ctor(repository,ionHttpClient,logger) `constructor`

##### Summary

Conatructor for UpdateIonFromUmzug

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| repository | [Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |
| ionHttpClient | [Afg.Ion.Client.IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') | The injection of the Ion Client of type [IonHttpClient](#T-Afg-Ion-Client-IonHttpClient 'Afg.Ion.Client.IonHttpClient') |
| logger | [Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}](#T-Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug} 'Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateIonFromUmzug}') | The injection of the logger of type [ILogger\`1](#T-Microsoft-Extensions-Logging-ILogger`1 'Microsoft.Extensions.Logging.ILogger`1') |

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-GetListToExportAsync'></a>
### GetListToExportAsync() `method`

##### Summary

Gets the list of jobs that need to be sent to ION

##### Returns

The list of jobs that will be sent to ION of type [List\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.List`1 'System.Collections.Generic.List`1')

##### Parameters

This method has no parameters.

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-SendListToIon-System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-Umzug_Transact},Hangfire-Server-PerformContext-'></a>
### SendListToIon(lst,context) `method`

##### Summary

Sends the list of valid transactions to ION

##### Returns

A successful response message

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| lst | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.Umzug_Transact}') | The list of valid transactions to send ot ION of type [IEnumerable\`1](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable`1 'System.Collections.Generic.IEnumerable`1') |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

##### Exceptions

| Name | Description |
| ---- | ----------- |
| [System.Exception](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Exception 'System.Exception') | TWhen an unacceptable status code is received |

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateIonFromUmzug-Update-System-Threading-CancellationToken,Hangfire-Server-PerformContext-'></a>
### Update(token,context) `method`

##### Summary

Method that sends the jobs in Umzug into ION

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

<a name='T-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS'></a>
## UpdateUmzugFromDCS `type`

##### Namespace

Afg.Umzug.Jobs.BackgroundJobs

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService,Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS},Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository-'></a>
### #ctor(dbService,logger,repository) `constructor`

##### Summary

Constructor for UpdateUmzugFromDCS

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| dbService | [Afg.Umzug.Data.Services.AfgWMSM3DataService](#T-Afg-Umzug-Data-Services-AfgWMSM3DataService 'Afg.Umzug.Data.Services.AfgWMSM3DataService') | The injection of the database service of type [AfgWMSM3DataService](#T-Afg-Umzug-Data-Services-AfgWMSM3DataService 'Afg.Umzug.Data.Services.AfgWMSM3DataService') |
| logger | [Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS}](#T-Microsoft-Extensions-Logging-ILogger{Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS} 'Microsoft.Extensions.Logging.ILogger{Afg.Umzug.Jobs.BackgroundJobs.UpdateUmzugFromDCS}') | The injection of the logger of type [ILogger\`1](#T-Microsoft-Extensions-Logging-ILogger`1 'Microsoft.Extensions.Logging.ILogger`1') |
| repository | [Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-SyncDatabaseAsync-System-Threading-CancellationToken,Hangfire-Server-PerformContext-'></a>
### SyncDatabaseAsync(cancellationToken,performContext) `method`

##### Summary

Updates the CosmoDb from the DCS database

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| cancellationToken | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| performContext | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromDCS-WhenAllEx-System-Collections-Generic-ICollection{System-Threading-Tasks-Task},System-Action{System-Collections-Generic-ICollection{System-Threading-Tasks-Task}}-'></a>
### WhenAllEx(tasks,reportProgressAction) `method`

##### Summary

Takes a collection of tasks and completes the returned task when all tasks have completed. If completion
takes a while a progress lambda is called where all tasks can be observed for their status.

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| tasks | [System.Collections.Generic.ICollection{System.Threading.Tasks.Task}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.ICollection 'System.Collections.Generic.ICollection{System.Threading.Tasks.Task}') | A collection of tasks |
| reportProgressAction | [System.Action{System.Collections.Generic.ICollection{System.Threading.Tasks.Task}}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Action 'System.Action{System.Collections.Generic.ICollection{System.Threading.Tasks.Task}}') | A Action object of the collection of tasks |

<a name='T-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromIon'></a>
## UpdateUmzugFromIon `type`

##### Namespace

Afg.Umzug.Jobs.BackgroundJobs

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromIon-#ctor-Afg-Umzug-Data-Services-AfgWMSM3DataService,Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository-'></a>
### #ctor(dbService,repository) `constructor`

##### Summary

Constructor for UpdateUmzugFromIon

##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| dbService | [Afg.Umzug.Data.Services.AfgWMSM3DataService](#T-Afg-Umzug-Data-Services-AfgWMSM3DataService 'Afg.Umzug.Data.Services.AfgWMSM3DataService') | The injection of the database service of type [AfgWMSM3DataService](#T-Afg-Umzug-Data-Services-AfgWMSM3DataService 'Afg.Umzug.Data.Services.AfgWMSM3DataService') |
| repository | [Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') | The injection of the transaction repository of type [UmzugDCSTransactRepository](#T-Afg-Umzug-Data-Repositories-UmzugDCSTransactRepository 'Afg.Umzug.Data.Repositories.UmzugDCSTransactRepository') |

<a name='M-Afg-Umzug-Jobs-BackgroundJobs-UpdateUmzugFromIon-Update-System-Threading-CancellationToken,Hangfire-Server-PerformContext,System-Collections-Generic-IEnumerable{Afg-Umzug-Data-Models-M3Response}-'></a>
### Update(token,context,objectFromIon) `method`

##### Summary

Updates the CosmoDb from the response from Ion

##### Returns



##### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| token | [System.Threading.CancellationToken](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Threading.CancellationToken 'System.Threading.CancellationToken') |  |
| context | [Hangfire.Server.PerformContext](#T-Hangfire-Server-PerformContext 'Hangfire.Server.PerformContext') |  |
| objectFromIon | [System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.M3Response}](http://msdn.microsoft.com/query/dev14.query?appId=Dev14IDEF1&l=EN-US&k=k:System.Collections.Generic.IEnumerable 'System.Collections.Generic.IEnumerable{Afg.Umzug.Data.Models.M3Response}') |  |
