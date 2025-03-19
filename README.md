# ProcessAttendanceCSE95

This repository contains a script that can convert an excel sheet file with student attendances, and convert it to PDFs that can be uploaded and automatically graded on Gradescope.

### Workflow

In lab, take attendance using a spreadsheet like `CSE95_WI25_Attendance.xlsx`. Feed this spreadsheet into the `CSE95_WI25_Attendance_Gradescope.ipynb` notebook. The notebook will output a series of PDFs corresponding to each student that can be uploaded to gradescope

### Required files

On top of the attendance spreadsheet, `CSE95_WI25_Attendance_Gradescope.ipynb` also needs:
- The roster for the class (to match names to PIDs)
- A sample image of "yes" or "no" used to generate the PDF
- `handwritten.tiff` used to write text onto the PDF generated
