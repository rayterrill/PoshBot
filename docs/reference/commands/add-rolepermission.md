---
external help file: Builtin-help.xml
online version: 
schema: 2.0.0
---

# Add-RolePermission

## SYNOPSIS
Add a permission to a role.

## SYNTAX

```
Add-RolePermission -Bot <Object> [-Role] <String> [-Permission] <String>
```

## DESCRIPTION
{{Fill in the Description}}

## EXAMPLES

### -------------------------- EXAMPLE 1 --------------------------
```
!add-rolepermission --role 'itsm-modify' --permission 'itsm:create-ticket'
```

Add the \[itsm:create-ticket\] permission to the \[itsm-modify\] role.

## PARAMETERS

### -Bot
{{Fill Bot Description}}

```yaml
Type: Object
Parameter Sets: (All)
Aliases: 

Required: True
Position: Named
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Role
The name of the role to add a permission to.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 1
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

### -Permission
The name of the permission to add to the role.

```yaml
Type: String
Parameter Sets: (All)
Aliases: 

Required: True
Position: 2
Default value: None
Accept pipeline input: False
Accept wildcard characters: False
```

## INPUTS

## OUTPUTS

## NOTES

## RELATED LINKS

