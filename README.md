# simple-ocr-microservice
Simple OCR microservice with Tesseract, PDFBox and Docker

Run the project by running the following command:

mvn clean install

then start the application which will start on default port 8080

you can run first get api to check application is up and running
GET -- http://localhost:8080/api/pdf/ping

This is a post api using which you can upload pdf document and it will print text after reding the pdf
POST -- http://localhost:8080/api/pdf/readPdf