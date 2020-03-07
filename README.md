# dicom_operation
it consists of python scripts for extracting the dicom file into .jpeg/.png and csv(patient info.) 
Convert all DICOM (.dcm) images in a folder to JPG/PNG and extract all patients information in a '.csv' format in a go using python.

For image processing or image classification the most popular supported file system is JPG / PNG. So it's really difficult to work with a '.dcm' image. The following code will convert all your '.dcm' images in a folder to JPG or PNG just by specifying the folder path and also extract all information stored in DICOM file.

# pre_requisite
    pip install pydicom
    pip install opencv-python
    pip install pillow # optional 
    pip install pandas
    
# Scripts
    1.dicom_extraction (converter + extractor)
    2.only .jpg/.png extraction (converter)
    3.only .csv extraction (extractor)
