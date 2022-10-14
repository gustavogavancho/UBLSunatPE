# UBLSunatPE
UBL 2.0/2.1 classes for SUNAT PE

[UBLSunatPE](https://www.nuget.org/packages/UBLSunatPE).

## Package Manager
Install-Package UBLSunatPE -Version 1.0.5

## DotNET CLI
dotnet add package UBLSunatPE --version 1.0.5

## Usage
Create invoice
```
var invoiceType = new InvoiceType
{
    //Cabeceras
    Cac = "urn:oasis:names:specification:ubl:schema:xsd:CommonAggregateComponents-2",
    Cbc = "urn:oasis:names:specification:ubl:schema:xsd:CommonBasicComponents-2",
    Ccts = "urn:un:unece:uncefact:documentation:2",
    Ds = "http://www.w3.org/2000/09/xmldsig#",
    Ext = "urn:oasis:names:specification:ubl:schema:xsd:CommonExtensionComponents-2",
    Qdt = "urn:oasis:names:specification:ubl:schema:xsd:QualifiedDatatypes-2",
    Udt = "urn:un:unece:uncefact:data:specification:UnqualifiedDataTypesSchemaModule:2",

    //ETC
};
```

## Documents
- InvoiceType
- DebitNoteType
- CreditNoteType
- VoidedDocumentsType
- SummaryDocumentsType
- DespatchAdviceType
