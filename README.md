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
```bash
lsblk
```

```bash
sudo dd if=/dev/sda of=/home/kali/a.png bs=512
```

```bash
mmls ~/a.png  (sleuth-kit)
sudo fdisk -l ~/a.png (GNU)

```
```bash
sudo ls -lh a.png
```
```bash
strings a.png | less

```

## OUTPUT:
![Screenshot 2025-04-23 205055](https://github.com/user-attachments/assets/0bfb4900-8d21-4365-a67c-6d0e4279e901)

![Screenshot 2025-04-23 205403](https://github.com/user-attachments/assets/1798ed59-354b-48ae-ad24-2364787fa308)

![Screenshot 2025-04-23 205624](https://github.com/user-attachments/assets/0f2ac951-39d7-4b54-9d56-9f71816ab273)

![Screenshot 2025-04-23 205707](https://github.com/user-attachments/assets/abb1ed4b-ed40-480a-ae25-0b1e923aa2ab)

![Screenshot 2025-04-23 205826](https://github.com/user-attachments/assets/46a7a897-1e03-4aab-b846-c99afd2d23f8)



## RESULT:
The unallocated space was successfully analyzed, data was extracted, and the digital investigation process was followed effectively.
