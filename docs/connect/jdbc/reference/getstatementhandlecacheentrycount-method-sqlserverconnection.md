---
description: "getStatementHandleCacheEntryCount Method (SQLServerConnection)"
title: "getStatementHandleCacheEntryCount Method (SQLServerConnection) | Microsoft Docs"
ms.custom: ""
ms.date: "01/19/2018"
ms.prod: sql
ms.prod_service: connectivity
ms.reviewer: ""
ms.technology: connectivity
ms.topic: reference
apiname: 
  - "SQLServerConnection.getStatementHandleCacheEntryCount"
apilocation: 
  - "sqljdbc.jar"
apitype: "Assembly"
ms.assetid:
author: David-Engel
ms.author: v-davidengel
---
# getStatementHandleCacheEntryCount Method (SQLServerConnection)
[!INCLUDE[Driver_JDBC_Download](../../../includes/driver_jdbc_download.md)]

 Returns the current number of pooled prepared statement handles.

## Syntax  
  
```  
  
public int getStatementHandleCacheEntryCount()  
```  

## Return Value
 An **int** that contains the current number of pooled prepared statement handles.

## Exceptions  
 [SQLServerException](../../../connect/jdbc/reference/sqlserverexception-class.md)  
 
## Remarks  
 This method is available from JDBC driver version 6.4 and onward.
 
## See Also  
 [SQLServerConnection Members](../../../connect/jdbc/reference/sqlserverconnection-members.md)   
 [SQLServerConnection Class](../../../connect/jdbc/reference/sqlserverconnection-class.md)  
  
  
