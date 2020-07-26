# Automating-real-world-tasks-with-python

Project Problem Statement

scenario is regarding an online fruit store, and need to develop a system that will update the catalog information with data provided by the suppliers. When each supplier has new products for the store, they give an image and a description of each product.

Given a bunch of images and descriptions of each of the new products, the codes will:

>> Upload the new products to your online store. Images and descriptions are uploaded separately, using two different web endpoints.
        >>> Images are resized to (600 x 400) and convereted to "JPEG" format before uploading          ------> changeimage.py
        >>> These modified images are uploaded to the web server that is handling the fruit catalog     ------> supplier_image_upload.py
        >>> Process the text files from the supplier, the scripts turn the data into a JSON dictionary  ------> run.py
            by adding all the required fields and uploading it to catalog web page
        
>> Send a report back to the supplier, letting them know what are imported.
        >>> Generate a PDF report           ------> reports.py
        >>> Send the report through email   ------> report_email.py
