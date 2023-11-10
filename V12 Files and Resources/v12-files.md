# V12: File and Resources Verification Requirements

## V12.1 File Upload Requirements

## Scenario 2 : Verify compressed files

### 12.1.2

```gherkin
GIVEN the application has a file upload capability  
AND a maximum file size for file is defined  
WHEN a compressed file is uploaded in to the application  
AND the file is being decompressed  
AND the decompressed file exceeds the maximum permissible file size  
THEN file decompression activity stops  
AND the decompressed file is discarded
```

## Scenario 3 : Restriction for the number of files per user

### 12.1.3

```gherkin
GIVEN the application has a file upload capability  
AND a maximum file size for file is defined  
AND a maximum number of files per user is defined  
WHEN  a user uploads files in excess of what is permitted per use
THEN  the file upload fails  
```

## File Integrity Requirements

### 12.2.1

## Scenario 1 : validate file type

```gherkin
GIVEN the application has a file upload capability  
AND the expected file types are known based on the file content
WHEN the files are uploaded in to the application  
THEN the upload fails if the expected file content does not match the uploaded file content.  
```

## File execution requirements

```gherkin
AS the product owner
I want the application to securely handle files
SO that the application is hardened against cybersecurity attacks
```

## Scenario 6 : prevent execute functionality from un-trusted sources

### 12.3.6

```gherkin
GIVEN the application supports execute functionality  
AND the trusted Content Distribution Networks for the application are known  
AND the trusted javascript libraries for the application are known  
AND the trusted node npm libraries for the application are known  
AND the trusted server side DLLs for the application are known  
WHEN a request to execute is received from an un-trusted source
THEN the request is not serviced  
```

## Scenario 3 : prevent reflective file download

### 12.5.3

```gherkin
GIVEN the application has file upload capability  
AND the user submitted filename is ignored or validated  
AND the response content-type header is set to text/plain  
AND the content disposition has a fixed name  
WHEN reflected file download is attempted by a user
THEN the request fails  
```
