# Digi-X Engineering Internship Assessment

## upload-extract-display Code Explanation

### Upload

1. A HTML form is created in the HTML template where the user can upload the zip file containing the images. A PHP code is written at the top of index.php to connect with the HTML form.

2. When the user clicks the button "Upload", the HTML form will send a POST request and the PHP code will read said request.

3. The PHP code will scan the uploaded file for its directory and contents. The PHP code will proceed with extraction if the uploaded file is confirmed to be a zip file.

### Extract

1. The PHP code will create a path for the zip file to extract to and proceed to extract the zip file to said path, thus creating a new extracted file.

2. Once the extraction is complete, the ZipArchive module will be closed and the PHP code will proceed with displaying the images into the HTML template.

### Display

1. The PHP code will scan the directory of the extracted file and will loop through all the images in the file.

2. Every image is echoed into the HTML template where it is targeted towards until the loop ends.
