---
Module Name: PnP.PowerShell
title: Get-PnPOrgNewsSite
schema: 2.0.0
applicable: SharePoint Online
external help file: PnP.PowerShell.dll-Help.xml
online version: https://pnp.github.io/powershell/cmdlets/Get-PnPOrgNewsSite.html
---
 
# Get-PnPOrgNewsSite

## SYNOPSIS

**Required Permissions**

* SharePoint: Access to the SharePoint Tenant Administration site

Returns the list of all the configured organizational news sites.

## SYNTAX

```powershell
Get-PnPOrgNewsSite [-Connection <PnPConnection>] [<CommonParameters>]
```

## DESCRIPTION

Allows to retrieve list of all the configured organizational news sites.

## EXAMPLES

### EXAMPLE 1
```powershell
Get-PnPOrgNewsSite
```

Returns the list of all the configured organizational news sites.

## PARAMETERS

### -Connection
Optional connection to be used by the cmdlet. Retrieve the value for this parameter by either specifying -ReturnConnection on Connect-PnPOnline or by executing Get-PnPConnection.

```yaml
Type: PnPConnection
Parameter Sets: (All)

Required: False
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## RELATED LINKS

[Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp)

