# File Recovery using Autopsy

```
Register Number : 212222040121
Name : Praveen V
```
## AIM:

This experiment aims to demonstrate:

- Create a **Disk Partition**.  

- Adding, deleting, and recovering files using Autopsy.

- Understanding the forensic recovery of deleted data.

- Removing the disk partition after the process.

## Step1:Create a New Disk
  
- The new Disk Partition is created as **PRAVEEN V**.
  ![Screenshot 2025-03-19 221000](https://github.com/user-attachments/assets/9b603c47-c7da-4012-9b35-3953cfeea86c)


## Step2: Adding and Deleting Files for Recovery

## 1. Copy Files to the Partition:

- Open File Explorer → Navigate to the newly created drive (C: or D:).

- Transfer images or files into it.
![Screenshot 2025-03-19 224841](https://github.com/user-attachments/assets/b9fdc15b-f166-435b-9b0d-cd5d40da55de)



## 2. Delete Files:

- Select one or more files → Press Delete.

- Empty the Recycle Bin to permanently remove them.

## Step3: Recovering Deleted Files Using Autopsy

## 1.Launch Autopsy and Set Up a New Case:

- Run Autopsy as Administrator.

- Click Create New Case.
![Screenshot 2025-03-19 222716](https://github.com/user-attachments/assets/4028e969-add1-46c4-beb2-3f336c7dcd3d)

- Enter a case name (e.g., Autopsy1).
- Select a location for the case folder → Click Next → Finish.
  ![Screenshot 2025-03-19 223051](https://github.com/user-attachments/assets/2b476fe0-199c-4c25-96c2-63c78183bb6f)
- Add optional information
  ![Screenshot 2025-03-19 223141](https://github.com/user-attachments/assets/45ff54d1-1967-4671-8dbb-a865f55f0316)



## 2.Add the Partition as Evidence:

- Click Add Data Source → Choose Host.
   ![Screenshot 2025-03-19 223322](https://github.com/user-attachments/assets/3ad0612b-655b-406c-ab63-95912238b112)


- Select Local Disk → Click Next.
   ![Screenshot 2025-03-19 223337](https://github.com/user-attachments/assets/8ed1cda5-f34d-491b-8255-c59c62eadaa0)


- Choose Disk → Select the VHD drive (Drive1).
  ![Screenshot 2025-03-19 224001](https://github.com/user-attachments/assets/773c5a67-49c8-421c-b0be-8a19a0e173c8)


- Click Next → Keep the default settings → Click Finish.
  ![Screenshot 2025-03-19 224106](https://github.com/user-attachments/assets/3feb68c2-3a3a-4e21-b3b8-11f4dfac0990)


- Allow Autopsy to process the disk.

## 3.Extract Deleted Files:

- In the left panel, navigate to File Views → Deleted Files.

- Locate your deleted images.
  ![Screenshot 2025-03-19 225517](https://github.com/user-attachments/assets/66b60ab9-d3c0-409e-8298-e20cd4e2d9d0)


- Right-click an image → Click Extract File.

- Choose a folder for saving the recovered files (e.g., C:\image_recovery).

- The deleted images are now restored!
  ![Screenshot 2025-03-19 225556](https://github.com/user-attachments/assets/4d7bd91f-547f-4bdc-86c3-a695ab4848ad)
- Check the disk.
  ![{0A179D61-BB59-4CE5-AF4D-6A7CF218EC6E}](https://github.com/user-attachments/assets/1d889ef5-1453-4ede-90a4-78087fa8d755)
  
## Step 4: Removing the Disk Partition (Optional Cleanup)

## 1.Using Disk Management:

- Open Disk Management (Win + X → Disk Management).

- Identify the created partition.

- Right-click on the partition → Select Delete Volume.

## 2.Alternative Method via Settings:

- Click the Start button → Go to Settings.

- Select System → Click Storage.

- Click Advanced Storage Settings → Select Disks & Volumes.

- View the list of available disks.

- Select the created partition → Click Properties.

- Click the Delete option to remove it.

## Result:

This experiment successfully demonstrates the creation of a disk partition, the deletion and recovery of files using Autopsy, and the proper removal of the partition after completing the process.


  


