# Lab 9
## YANG
### Instructions
Review lesson 9 in the GitHub repository. Install pyang and PlantUML. Copy ~/iot/lesson9/intrusiondetection.yang to ~/demo. Run pyang to generate intrusiondetection.yin and intrusiondetection.uml. Run PlantUML to generate intrusiondetection.png. Document results to your GitHub repository.

## pyang
### cat intrusiondetection.yang
![image](https://github.com/user-attachments/assets/3594848f-64e1-4ca6-9f0b-d9adfc1908e7)
![image](https://github.com/user-attachments/assets/7f1e2d32-4281-4300-a87f-9337962513e5)
![image](https://github.com/user-attachments/assets/5364f493-16b5-40dd-915d-71f70996c92c)


### pyang -f yin -o intrusiondetection.yin intrusiondetection.yang
![image](https://github.com/user-attachments/assets/91fea375-080a-40ec-b729-fad778136e7b)

### cat intrusiondetection.yin
![image](https://github.com/user-attachments/assets/cc334464-b0f8-4291-82d1-627b8c562b46)
![image](https://github.com/user-attachments/assets/965ab525-ed84-460e-b0e1-464918e77e84)
![image](https://github.com/user-attachments/assets/b86ee566-55e2-4315-9cda-c83990f4b136)

### pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef
![image](https://github.com/user-attachments/assets/d84b9af3-db11-42ff-b545-0cd6c2f2082c)

### cat intrusiondetection.uml
![image](https://github.com/user-attachments/assets/7ef4ab33-7ad1-44e5-9d3e-ca1cbb9196a3)

## plantUML
### python3 -m plantuml intrusiondetection.uml
![image](https://github.com/user-attachments/assets/58353468-458f-4971-9436-008fb3ae65f6)

### PNG image
![image](https://github.com/user-attachments/assets/b5015cf9-ff81-4e05-b17f-56e8b86daf96)

