# Reviewing-Unallocated-Space-Extracting-Data-with-Tools-Digital-Investigation-Processes
## AIM:
To review unallocated space in a disk image, extract data using forensic tools, and understand the digital investigation process.

## DESIGN STEPS:
### Step 1:
Use tools like Autopsy or Sleuth Kit (blkls, icat) to identify and analyze unallocated space.

### Step 2:
Extract data from unallocated space and examine for hidden or deleted content.

### Step 3:
Document and interpret findings as part of the digital investigation process.

## PROGRAM:
Data Extraction and Investigation Tool Usage

bash sudo dd if=/dev/sda of=/home/kali/disk.img bs=512

bash mmls ~/disk.img

bash sudo ls -lh disk.img

bash strings disk.img | less
## OUTPUT:
Unallocated Space Analysis and Extracted Data Report
![image](https://github.com/user-attachments/assets/d6022b47-7e8f-48e3-8d0d-a34908cef33c)
![image](https://github.com/user-attachments/assets/f7544e29-58b7-45aa-8ba8-1af4b8dbb220)
![image](https://github.com/user-attachments/assets/cc80cf87-1d91-4dba-973d-ed2dc13c8284)
![image](https://github.com/user-attachments/assets/7d4bf5c1-5786-4252-9a10-051724cec8a8)
![image](https://github.com/user-attachments/assets/aaf08d5f-894e-4186-bea2-3af02a38507d)

## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.

