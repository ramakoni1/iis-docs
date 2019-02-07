---
title: ChunkInfo.CompareTo Method  (Microsoft.Web.Media.SmoothStreaming)
TOCTitle: CompareTo Method
ms:assetid: M:Microsoft.Web.Media.SmoothStreaming.ChunkInfo.CompareTo(System.Object)
ms:mtpsurl: https://msdn.microsoft.com/en-us/library/microsoft.web.media.smoothstreaming.chunkinfo.compareto(v=VS.95)
ms:contentKeyID: 46307641
ms.date: 05/31/2012
mtps_version: v=VS.95
f1_keywords:
- Microsoft.Web.Media.SmoothStreaming.ChunkInfo.CompareTo
dev_langs:
- CSharp
- JScript
- VB
- FSharp
- c++
api_location:
- Microsoft.Web.Media.SmoothStreaming.dll
api_name:
- Microsoft.Web.Media.SmoothStreaming.ChunkInfo.CompareTo
api_type:
- Managed
topic_type:
- apiref
- kbSyntax
product_family_name: VS
ROBOTS: INDEX,FOLLOW
---

# ChunkInfo.CompareTo Method

Compares a chunk to another object.

**Namespace:**  [Microsoft.Web.Media.SmoothStreaming](microsoft-web-media-smoothstreaming-namespace_1.md)  
**Assembly:**  Microsoft.Web.Media.SmoothStreaming (in Microsoft.Web.Media.SmoothStreaming.dll)

## Syntax

``` vb
'Declaration

Public Function CompareTo ( _
    chunk As Object _
) As Integer
'Usage

Dim instance As ChunkInfo
Dim chunk As Object
Dim returnValue As Integer

returnValue = instance.CompareTo(chunk)
```

``` csharp
public int CompareTo(
    Object chunk
)
```

``` c++
public:
virtual int CompareTo(
    Object^ chunk
) sealed
```

``` fsharp
abstract CompareTo : 
        chunk:Object -> int 
override CompareTo : 
        chunk:Object -> int 
```

``` jscript
public final function CompareTo(
    chunk : Object
) : int
```

#### Parameters

  - chunk  
    Type: [System.Object](https://msdn.microsoft.com/en-us/library/e5kfa45b\(v=vs.95\))  

#### Return Value

Type: [System.Int32](https://msdn.microsoft.com/en-us/library/td2s409d\(v=vs.95\))  
Integer value that indicates the result of the comparison, zero if equal, less than zero if earlier in time, greater than zero if later in time.

#### Implements

[IComparable.CompareTo(Object)](https://msdn.microsoft.com/en-us/library/4ah99705\(v=vs.95\))  

## Version Information

#### Silverlight

Supported in: 5  

#### Windows Phone

Supported in: Windows Phone OS 7.1, Windows Phone OS 7.0  

## See Also

#### Reference

[ChunkInfo Class](chunkinfo-class-microsoft-web-media-smoothstreaming_1.md)

[Microsoft.Web.Media.SmoothStreaming Namespace](microsoft-web-media-smoothstreaming-namespace_1.md)
