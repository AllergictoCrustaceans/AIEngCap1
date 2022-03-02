# Validation & Metrics Monitoring

## List of Python libraries used in this capstone project

[Link to the requirements.txt](./requirements.txt)
#

## Face Matching has X% match between Video Thumbnail + Cal ID

![](val_monitoring_ID_vid_match.png)

## Validation Results from Cal ID, Boarding Pass, and Face Video

This is the very long function that I created to validate the extract information. 
![Name, Dob, and Face Validation Function Pt. 1](revision_name_dob_face_val_function_1.png)

Continuation of the function... 

![Name, Dob, and Face Validation Function Cont. (Pt. 2)](revision_name_dob_face_val_function_2.png)


This is the function that stores a True/False value for the personValidation variable, once a person's face V. vid confidence is determined.

#

## Manifest Table Before Validation Checks
This is what the manifest table (CSV) looks like the following subjects in preparation for testing: 
![Manifest Table Before Validation Check](manifest_table_before_vali_checks.png)
#

## Link to Validation Checks
Here are the validation checks for each subject:

[My Validation Results](./my_results) (VALIDATION PASSED)

[Daniel Kaluuya's Results](./kaluuya_results) (VALIDATION PASSED)

[Ennio Morricone's Results](./morricone_results) (VIDEO IMAGE EXTRACTION FAILED -- did not continue to validate)

[Stephen Sondheim's Results](./sondheim_results) (VALIDATION FAILED)

[Hayley Williams' Results](./williams_results) (PERSON GROUP ERROR -- did not continue to validate)

[David Sinclair Results](./sinclair_results) (VALIDATION PASSED)

[Rachel Portman Results](./portman_results) (VALIDATION PASSED)

#
## Updated Manifest Table After Validation Checks
This is what the manifest table (CSV) looks like after the subjects were checked for validation: 

![Updated Manifest Table from Notebook](updated_manifest_table.png)
#

## Helper functions to validate Text Extraction, Face Recog Checks
![](val_monitoring_name_match_manifest_V_boarding_pass.png)

![](val_monitoring_name_dob_match_manifest_V_cal_ID.png)

![](val_monitoring_name_dob_match_manifest_V_cal_ID_2.png)

![](val_check_function.png)

![](show_kiosk_message_function.png)


## All Successful Validations

Unforunately, there were no successful validations, luggage validation was defaulted to FALSE (as stated on step 5 instructions)


![](luggage_val_false.png)

### Error Message of Failed Validations

![](val_monitoring_call_kiosk_message_function.png)

#

## Usage + Performance from Service Consumption Report

I used the Jupyter lab provided by Udacity, and when checking the cost management tab, it's disabled. 

![](cost_blanked_out.png)

![](service_consumption_report.png)

#

## Reflection 
[Capstone Reflection](./capstone1_reflection.pdf)