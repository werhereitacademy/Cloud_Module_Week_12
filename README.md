# Cloud_Module_Week_12

1- Create a Resource Group
![RG_Create](https://github.com/user-attachments/assets/5483ce48-dc01-4b1d-9e26-7f578c34aa74)
- I entered the resource group creation page with the menu marked in the picture above.
- On the following page, I selected the Resource Group name and region in the marked fields and created my resource group by clicking the "review and create" button
  ![RG_Create02](https://github.com/user-attachments/assets/99742cb2-63ba-4653-a80b-d317b6ecae72)

2- Set Up a Virtual Network
 - Aşağıdaki resimde görüldüğü gibi; arama alanına "Virtual" yazarak gelen listededen "Virtual Networks" seçeneğinden "Create" seçeneğini seçtim.
    ![VNet01](https://github.com/user-attachments/assets/a367a346-3016-4f6c-9ac0-5c44f6831ed9)
 
 -  Sanal ağ oluşturma sayfasında "Temel bilgiler" kısmında Kaynak grubunu seçtim ve sanal ağımın adını verdim.
     ![VNet02](https://github.com/user-attachments/assets/54880b62-242a-435a-bac5-2221759d2d83)

 - Sanal ağ oluşturma sayfasında "IP Adresleri" sanal ağımın ip adres grubunu ayarladım. 10.1.0.0 / 16
     ![VNet03](https://github.com/user-attachments/assets/ac57abcd-354f-4204-8b76-d3b998c98724)

 - To create a default subnet, I created a 10.1.1.0/24 subnet using the settings in the menu in the picture.
     ![SubNet01](https://github.com/user-attachments/assets/16712f35-f02f-4996-a78e-83f311cc488a)

3- Deploy a Windows Virtual Machine
- I clicked on the virtual machines tab on the home page.
    ![VM01](https://github.com/user-attachments/assets/28bf47d6-dbbf-455b-bb3a-aca62b45105b)

- I selected the Azure virtual machine option under the create option shown in the picture.
    ![VM02](https://github.com/user-attachments/assets/83d9abdc-69bf-4126-bac0-a6f447be1fc4)

- In the "Basic Settings" section on the incoming virtual machine creation page, I filled in the Resource group, Virtual machine name, Region, Security type, Image options as shown in the picture.
    ![VM03](https://github.com/user-attachments/assets/ae0a22be-a4c0-4878-96aa-899e813fd164)

- On the "Networking" page, I selected the Virtual network, Subnet, General port as shown in the picture below.
    ![VM04](https://github.com/user-attachments/assets/262b0fea-ce26-4c99-b223-fcfc007914e6)

4- Attach a Data Disk to the VM
- From the "Disks" section I chose Create a new disk and add it
   ![Disk01](https://github.com/user-attachments/assets/65734248-8ab9-4a5c-b2db-470467075486)
 
- I chose the name of the disk, the source type, its size, the share, and the maximum share amount.
    ![disk02](https://github.com/user-attachments/assets/677c8527-2ecb-4565-ac78-987afdced17e)

5- Connect to the VM
- The information about the VM I created is below.
    ![VM_Last](https://github.com/user-attachments/assets/101b9f8c-c396-4783-8396-2360b60150a0)

- The remote desktop connection image I made according to this information is below.
    ![server01-rdp](https://github.com/user-attachments/assets/223f9952-940f-45ae-b199-7fde98e7af54)

* The source group image is in the picture below.
  ![RG_Topoloji](https://github.com/user-attachments/assets/a67c15d6-cccd-4c55-bc03-1b30bcf8101a)

* The source group json files I created are also located in the repository.
