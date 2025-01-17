---
description: "Use the DIA SDK to access the Microsoft debug information."
title: "Overview (Debug Interface Access SDK)"
ms.date: "11/04/2016"
ms.topic: "reference"
dev_langs:
  - "C++"
helpviewer_keywords:
  - "user-defined types"
  - ".dbg files"
  - "modules"
  - "interfaces [DIA SDK]"
  - "DBG files"
  - "procedures [DIA SDK]"
  - "executable files"
  - "COM objects, in DIA SDK"
  - "compilands"
  - "executable images"
author: "mikejo5000"
ms.author: "mikejo"
manager: jmartens
ms.subservice: debug-diagnostics
---
# Overview (Debug Interface Access SDK)

Use the DIA SDK to access the Microsoft debug information. The DIA SDK provides a COM based API set that eliminates the need to rewrite your code whenever Microsoft changes the format of the debug information. The DIA SDK also allows you to read from a select set of previous versions of debug information, located in .pdb and .dbg files generated by Visual C++ versions 5.0 and later.

 Each interface in the DIA SDK represents a different COM object, except where stated otherwise. Additional interfaces, and thus additional objects, are created by means of explicit queries, such as [IDiaDataSource::openSession](../../debugger/debug-interface-access/idiadatasource-opensession.md) or [IDiaSession::findChildren](../../debugger/debug-interface-access/idiasession-findchildren.md), rather than by calling `QueryInterface` on existing interface pointers.

## See also
- [IDiaDataSource::openSession](../../debugger/debug-interface-access/idiadatasource-opensession.md)
- [IDiaSession::findChildren](../../debugger/debug-interface-access/idiasession-findchildren.md)
