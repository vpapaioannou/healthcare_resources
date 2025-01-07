A collection of resources for **Healthcare**. In case something is missing or a link is not working, please create an issue [here](https://github.com/vpapaioannou/healthcare_resources/issues)

# Communities

- [RSNA](https://www.rsna.org/): Radiological Society of North America
  - [RSNA MIRC](https://mircwiki.rsna.org/index.php?title=MIRC_Overview_-_CTP_and_TFS) Medical Imaging Resource Center (MIRC) project overview
  - [RSNA MIRC CTP](https://mircwiki.rsna.org/index.php?title=MIRC_CTP) Describes the RSNA MIRC Clinical Trials Processor (CTP), a stand-alone image processing application for imaging
  clinical trials data.
  - [RSNA Practice Tools](https://www.rsna.org/practice-tools)
- [ASTRO](https://www.astro.org/): American Society for Radiation Oncology

# DICOM - Digital Imaging and Communications in Medicine

- Wikipedia [DICOM](https://en.wikipedia.org/wiki/DICOM)
- [DICOM Standard Browser](https://dicom.innolitics.com/ciods/ct-image) Documentation of all DICOM headers accompanied by a DICOM headers viewer.
- [DICOM is easy blog](https://dicomiseasy.blogspot.com/) A blog on DICOM file format to get you started.
  - [Getting oriented using image plane module](https://dicomiseasy.blogspot.com/2013/06/getting-oriented-using-image-plane.html) Understand 3D images stored on DICOM and their orientation.
- [dcm2niix](https://github.com/rordenlab/dcm2niix) A command line (terminal) utility to convert files from DICOM to NIFTI format.
  - [dcm2niix: Gantry tilt error](https://github.com/rordenlab/dcm2niix/issues/232) Understand [dcm2niix](https://github.com/rordenlab/dcm2niix) error outputs.

# NIFTI - Neuroimaging Informatics Technology Initiative

- Wikipedia: [NIFTI](https://en.wikipedia.org/wiki/Neuroimaging_Informatics_Technology_Initiative)
- NIFTI Format
  - [NIFTI-1 explained](https://brainder.org/2012/09/23/the-nifti-file-format/)
  - [NIFTI-2 explained](https://brainder.org/2015/04/03/the-nifti-2-file-format/)

# Medical images View & Processing

- Coordination System: Images orientation can vary from file to file and it is important then to have a consistent orientation when processing them especially in batches.
  - [Coordinate systems explained I](https://www.brainvoyager.com/bv/doc/UsersGuide/CoordsAndTransforms/CoordinateSystems.html)
  - [Coordinate systems explained II](https://www.slicer.org/wiki/Coordinate_systems)
- [Understanding window width and window center](https://towardsdatascience.com/a-matter-of-grayscale-understanding-dicom-windows-1b44344d92bd) Window width and center affect what you
see in an image.
- [SimpleITK](https://simpleitk.org/): Open-source multi-dimensional image analysis in Python, R, Java, C#, Lua, Ruby, TCL and C++
  - [Read DICOM series from array](https://simpleitk.readthedocs.io/en/next/Examples/DicomSeriesFromArray/Documentation.html)
  - [SimpleITK does not save metadata](https://github.com/SimpleITK/SimpleITK/issues/346) Metadata issues with SimpleITK
- Viewers
  - [ITK-snap](http://www.itksnap.org/pmwiki/pmwiki.php): View and process NIFTI files.
    - [ITK-snap beginners short tutorial](http://www.itksnap.org/pmwiki/pmwiki.php%3Fn%3DDocumentation.TutorialSectionNewVersionTwo)
  - [Paraview](www.paraview.org) An [STL](https://en.wikipedia.org/wiki/STL_(file_format)) File viewer of 3D rendered objects.
  - [VTK](https://vtk.org/): Process images and create 3D computer graphics with the Visualization Toolkit
    - [PyScience - VTK](https://pyscience.wordpress.com/)
    - [A Comprehensive Guide To Visualizing and Analyzing DICOM Images in Python](https://hengloose.medium.com/a-comprehensive-starter-guide-to-visualizing-and-analyzing-dicom-images-in-python-7a8430fcb7ed)
  - Python Matplotlib
    - [Viewing 3D Volumetric Data With Matplotlib](https://www.datacamp.com/community/tutorials/matplotlib-3d-volumetric-data)
- Burnt-in Images Text
  - [Tesseract](https://github.com/tesseract-ocr/tesseract): Optical Character Recognition (OCR)
    - [Frequently Asked Questions](https://tesseract-ocr.github.io/tessdoc/tess3/FAQ-Old.html)
    - [Tesseract User Manual[(https://tesseract-ocr.github.io/tessdoc/Home.html)
    - [Tesseract OCR: Understanding the Contents of Documents, Beyond Their Text](https://medium.com/geekculture/tesseract-ocr-understanding-the-contents-of-documents-beyond-their-text-a98704b7c655)
    - [How to OCR with Tesseract, OpenCV and Python](https://nanonets.com/blog/ocr-with-tesseract/)
    - [Text Extraction from a Table Image, using PyTesseract and OpenCV](https://fazlurnu.com/2020/06/23/text-extraction-from-a-table-image-using-pytesseract-and-opencv/)
    - [Improving the quality of the output](https://tesseract-ocr.github.io/tessdoc/ImproveQuality.html)
    - [A list of useful control parameters and config files](https://tesseract-ocr.github.io/tessdoc/tess3/ControlParams.html)
    - [Using Config Files](https://github.com/tesseract-ocr/tesseract/blob/main/doc/tesseract.1.asc#config-files-and-augmenting-with-user-data)
    - [Command Line Usage](https://tesseract-ocr.github.io/tessdoc/Command-Line-Usage.html)
  - [PyTesseract](https://github.com/madmaze/pytesseract) Tesseract implementation in Python
    - [Tesseract Page Segmentation Modes (PSMs) Explained: How to Improve Your OCR Accuracy](https://pyimagesearch.com/2021/11/15/tesseract-page-segmentation-modes-psms-explained-how-to-improve-your-ocr-accuracy/)
    - [Language Translation and OCR with Tesseract and Python](https://pyimagesearch.com/2021/09/20/language-translation-and-ocr-with-tesseract-and-python/)
    - [Whitelisting and Blacklisting Characters with Tesseract and Python](https://pyimagesearch.com/2021/09/06/whitelisting-and-blacklisting-characters-with-tesseract-and-python/)
 
# Commercial and non-commercial de-identfication and anonymization tools

- [Carina AI DeIdentifier](https://www.carinaai.com/) The de-identifier I implemented from scratch including the algorithms and the user interface and is used by major healthcare players.
- [AWS De-identification](https://aws.amazon.com/blogs/machine-learning/de-identify-medical-images-with-the-help-of-amazon-comprehend-medical-and-amazon-rekognition/)
- [Google De-identification](https://cloud.google.com/healthcare/docs/how-tos/dicom-deidentify)
- [Free imaging software for anonymization](https://www.imaios.com/en/resources/blog/top-5-best-dicom-de-identification-tools)

# Spatial Patterns Analysis

- [UPenn Notebook on spatial data analysis](https://www.seas.upenn.edu/~tesmith/NOTEBOOK/index.html) Useful for examining (cellular) populations interactions and other applications.
- [Testing for inhomogeneity of spatial data](https://blog.valdosta.edu/andersonlab/2018/05/03/point-pattern-analysis-visualizing-and-testing-for-inhomogeneity-by-dr-anderson/)
  
