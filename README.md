# RotatePDF
This is a flaskAPI that accepts a pdf filepath, an angle of rotation and a page number.
It proceeds to rotate the given page number of the pdf by the angle given.

sample POST at /rotate endpoint


```
    "file_path": original.pdf,
    "angle_of_rotation": 90,
    "page_number": 2