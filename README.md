# Employee-Face-Mask-Detection-Alert-System
Developed a Computer Vision project to detect employees entering into premises without mask in real time using OpenCV, Tensorflow and Keras library on kaggle face mask dataset. Integerated the Computer Vision Model with an alert system to recognise employees using face recognition library and notify authorities about violation of COVID-19 protocol through an email containing the name of employee and time of entering, at the same time keeping a log of all such violators in a CSV file containing the names and time. Also, used python's text-to-speech library for prompting an alert message to remind all such violators of wearing their masks.

### Employee-Image-Folder
Contains a single image of me, Jeff Bezos and Bill Gates!
!['Employee-Image'](https://github.com/sumitkumar109/Employee-Face-Mask-Detection-Alert-System/blob/main/Screenshots/Screenshot3.png?raw=true)

### Detecting-Face-Mask-In-Real-Time
The model trained on 1376 images using tensorflow, keras, Colab-GPU is used to detect Mask on an human face.
!['Mask-On'](https://github.com/sumitkumar109/Employee-Face-Mask-Detection-Alert-System/blob/main/Screenshots/Screenshot1.png?raw=true)

### Identifying-Employee-From-Image-Folder-Without-Mask
The faces without mask are identified using python's face-recognition library as an employee or as an unknown individual depending on the wheather their picture is contained or not in the Employee Image Folder.
!['Mask-Off'](https://github.com/sumitkumar109/Employee-Face-Mask-Detection-Alert-System/blob/main/Screenshots/Screenshot2.png?raw=true)

### Keeping-Log-Of-Policy-Violators
A record is added in an csv file containing name and date of arrival of the person, everytime the face mask policy is violated.
!['CSV-File'](https://github.com/sumitkumar109/Employee-Face-Mask-Detection-Alert-System/blob/main/Screenshots/Screenshot4.png?raw=true)

### Email-Notification-To-Administrator
An email containing name and time of arrival of the violator is send to the administrator to inform them about COVID policy violation.
!['Alert-Email'](https://github.com/sumitkumar109/Employee-Face-Mask-Detection-Alert-System/blob/main/Screenshots/Screenshot5.png?raw=true)
