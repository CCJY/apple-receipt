# Project status
| Branch | Build        | Quality | 
| ------------- | ------------- | ------------- |
| master | ![Build Status](https://shoshins.visualstudio.com/_apis/public/build/definitions/3ee635a9-029b-40d9-a9b6-93cc7737dbf9/1/badge)      | ![Code Quality](https://sonarcloud.io/api/project_badges/measure?project=apple-receipt-parser&metric=alert_status) |

# Nuget Packages Information

## Apple Receipt Models

### Description
Describes strongly-type representation of Apple Receipt Object.
[Apple Documentation](https://developer.apple.com/library/archive/releasenotes/General/ValidateAppStoreReceipt/Chapters/ReceiptFields.html)

### Nuget information 
[Link to package](https://www.nuget.org/packages/Apple.Receipt.Models/)

| Version | Downloads |
| ------------- | ------------- |
| ![NuGet](https://img.shields.io/nuget/v/Apple.Receipt.Models.svg) | ![NuGet](https://img.shields.io/nuget/dt/Apple.Receipt.Models.svg) |

### Installation:
* (Package manager): ```Install-Package Apple.Receipt.Models -Version 1.0.0```
* (.Net CI): ```dotnet add package Apple.Receipt.Models --version 1.0.0```
* (Packet CLI): ```paket add Apple.Receipt.Models --version 1.0.0```

## Apple Receipt Parser

### Description
Parser for Apple Receipt that represented in base64 and encoded with ASN.1
[Anatomy of a Receipt payload encoded with ASN.1](https://www.objc.io/issues/17-security/receipt-validation/)

### Nuget information 
[Link to package](https://www.nuget.org/packages/Apple.Receipt.Parser/)

| Version | Downloads |
| ------------- | ------------- |
| ![NuGet](https://img.shields.io/nuget/v/Apple.Receipt.Parser.svg) | ![NuGet](https://img.shields.io/nuget/dt/Apple.Receipt.Parser.svg) |

### Installation:
* (Package manager): ```Install-Package Apple.Receipt.Parser -Version 1.1.1```
* (.Net CI): ```dotnet add package Apple.Receipt.Parser --version 1.1.1```
* (Packet CLI): ```paket add Apple.Receipt.Parser --version 1.1.1```

## Apple Receipt Verificator

### Description
Apple Receipt Validator using Apple App Store. 
Two step verification: pre-validation that can be customized and App Store verification.
[Apple Receipt Validation with App Store documentation](https://developer.apple.com/library/archive/releasenotes/General/ValidateAppStoreReceipt/Chapters/ValidateRemotely.html)

### Nuget information 
[Link to package](https://www.nuget.org/packages/Apple.Receipt.Verificator/)

| Version | Downloads |
| ------------- | ------------- |
| ![NuGet](https://img.shields.io/nuget/v/Apple.Receipt.Verificator.svg) | ![NuGet](https://img.shields.io/nuget/dt/Apple.Receipt.Verificator.svg) |

### Installation:
* (Package manager): ```Install-Package Apple.Receipt.Verificator -Version 1.0.0```
* (.Net CI): ```dotnet add package Apple.Receipt.Verificator --version 1.0.0```
* (Packet CLI): ```paket add Apple.Receipt.Verificator --version 1.0.0```
