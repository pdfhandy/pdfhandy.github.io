PdfHandy API - .Net Library
A library in VB.Net or C# for PdfHandy API. You can sign up for a developer account <a href="https://www.pdfhandy.com/api-developer.aspx">here.</a>

Develop and build apps using PDF processing tasks like Split PDF, Merge PDF, Compress PDF, Convert Office documents to PDF, PDF to JPG, Merge JPG to PDF, add Page Numbers, Rotate PDF, Decrypt Word document, Watermark PDF. Our API gives you the complete access to all our applications.

## **Requirements**
```
Minimum .NET Framework 4.5
```
## **Installation**

Getting Started with the .NET Client Library. Follow our <a href="https://www.pdfhandy.com/get-started.aspx">installation guide.</a>

## **Basic Usage**

### **VB.Net**
```
'Initialize the client library
Dim client As New pdfhandy
'Insert API key
client.APIKey = "your-api-key"
'Provide filepath for file conversion.
client.Doc2Pdf("path/to/file/inputfile.doc", "path/to/file/outputfile.pdf")
```
### **C#**
```
//Initialize the client library
pdfhandy client = new pdfhandy();
//Insert API key
client.APIKey = "your-api-key";
//Provide filepath for file conversion.
client.Doc2Pdf("path/to/file/inputfile.doc", "path/to/file/outputfile.pdf");
```

## **License**
The code is available as open source under the terms of the <a href="https://opensource.org/licenses/MIT">MIT License.</a>
