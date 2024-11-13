@@ -1 +1,52 @@
# UiPath-projects
## Exercise_14 lead generation process

## Aim:

To automate the extraction of specific data for lead generatrion using google maps and store the data in excel sheet

## Equipments Required:

UiPath Studio<br>
Excel file for storing extracted data<br>

#### Installed UiPath packages:

UiPath.PDF.Activities<br>
UiPath.IntelligentOCR.Activities<br>
UiPath.Excel.Activities<br>

## Procedure:

### Install UiPath and Required Packages:

Download and install UiPath Studio.<br>
Create a new project and install the necessary packages (PDF, OCR, Excel).<br>

### open the web browser

Use the open browser to open google maps.<br>
Choose an browser process the lead generation .<br>



### Write Data to Excel:

Use the Excel Applicationn Scope activity to open or create an Excel file.<br>
Write the extracted data (Invoice Number, Date, Total Amount) into specific cells using Write Cell activity.<br>

### Run and Test:

Run the workflow and verify that the data has been extracted correctly and saved into the Excel file.

## UiPath WorkFlow:
![Screenshot 2024-11-13 164410](https://github.com/user-attachments/assets/0f79676c-0c2c-4510-b710-f762adb33126)
![Screenshot 2024-11-13 164514](https://github.com/user-attachments/assets/34e02d28-7f3d-4f89-b1fc-f25c2a1d39fe)
![Screenshot 2024-11-13 164542](https://github.com/user-attachments/assets/2804fd10-dec9-462e-82d0-30ee2a69f3d4)
![Screenshot 2024-11-13 164608](https://github.com/user-attachments/assets/df2afedd-f894-486c-805b-851ed885d2e5)


## Result:

The automation successfully extracts the leads and stored it sucessfully in an ecxel sheet


