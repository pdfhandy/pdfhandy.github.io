UnitePDF API - .Net Library
A library in VB.Net or C# for UnitePDF API. You can sign up for a developer account <a href="https://www.unitepdf.com/api-developer.aspx">here.</a>

Develop and build apps using PDF processing tasks like Compress PDF, Merge PDF, Split PDF, convert Office documents to PDF, PDF to JPG, Images to PDF, add Page Numbers, Rotate PDF, Decrypt Word document, Watermark PDF. Our API gives you the complete access to all our applications.

## **Requirements**
```
Minimum .NET Framework 4.5
```
## **Installation**

Getting Started with the .NET Client Library. Follow our <a href="https://www.unitepdf.com/get-started.aspx">installation guide.</a>

## **Basic Usage**

### **VB.Net**
```
'Initialize the client library
Dim client As New unitepdfapi
'Insert API key
client.APIKey = "your-api-key"
'Provide filepath for file conversion.
client.Doc2Pdf("path/to/file/inputfile.doc", "path/to/file/outputfile.pdf")
```
### **C#**
```
//Initialize the client library
unitepdfapi client = new unitepdfapi();
//Insert API key
client.APIKey = "your-api-key";
//Provide filepath for file conversion.
client.Doc2Pdf("path/to/file/inputfile.doc", "path/to/file/outputfile.pdf");
```

## **License**
The code is available as open source under the terms of the <a href="https://opensource.org/licenses/MIT">MIT License.</a>
