# LWC - Component to display PDF documents

![Pdf Viewer](img/pdfViewer-2.png)


## Topics
- [Setup](#setup)
- [Using the PDFViewer Component](#using)
- [Component code](#code)

<a name='setup'></a>
## Setup
![setup](img/pdfviewer-1.gif)


## Upload files

- Go to content home ```(instance_url/lightning/o/ContentDocument/home)``` and upload the PDF document
- Get the Id of the PDF document  (example: 0693h000007CVFZAA4)

### Demo
![Upload Files](img/pdfviewer-2.gif)



### Example urls
- [Content Home](https://mohansun-ea-02-dev-ed.lightning.force.com/lightning/o/ContentDocument/home)
- [View Link](https://mohansun-ea-02-dev-ed.lightning.force.com/lightning/r/ContentDocument/0693h000007CVFZAA4/view)
- [Download Link](https://mohansun-ea-02-dev-ed--c.documentforce.com/sfc/servlet.shepherd/document/download/0693h000007CVFZAA4)

<a name="using"></a>
##  Using the PDFViewer Component 
### Demo
![Demo - Using the PDFViewer](img/pdfviewer-3.gif)

<a name='code'></a>
## Component code
- [pdfViewer.html](src/force-app/main/default/lwc/pdfViewer/pdfViewer.html)
- [pdfViewer.js](src/force-app/main/default/lwc/pdfViewer/pdfViewer.js)
- [pdfViewer.js-meta.xml](src/force-app/main/default/lwc/pdfViewer/pdfViewer.js-meta.xml)
- [pdfViewer.css](src/force-app/main/default/lwc/pdfViewer/pdfViewer.css)


## References
- [Files Home](https://help.salesforce.com/articleView?id=sf.collab_files_using.htm&type=5)
- [PDF Viewer Lightning Web Component](https://github.com/annyhe/pdfViewer)
