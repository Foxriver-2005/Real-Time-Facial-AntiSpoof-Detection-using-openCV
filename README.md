# Real-Time-Facial-AntiSpoof-Detection-using-openCV
This project enhances existing facial recognition systems by adding a layer of security that distinguishes between real-time individuals and static representations (images, videos, or 3D models). Specifically designed for facial recognition systems, this solution ensures that users must be physically present to log in, preventing unauthorized access through the use of photos or videos.

### Features
1. Real-Time Detection: Accurately identifies live faces versus static images or videos.
2. Custom Dataset: Trained on a unique dataset collected by the author, specifically tailored for this project.
3. Image Quality Assurance: Only captures and utilizes clear images, enhancing the reliability of the model.
4. OpenCV & cvZone Integration: Utilizes powerful computer vision libraries to achieve high performance.

5. ### Project Structure

#### Data Collection Script:

Captures facial images, ensuring that only non-blurry images are saved for training.
![Screenshot from 2024-01-22 15-50-49](https://github.com/user-attachments/assets/c8211712-c5c3-4fd3-9153-2fe903390ed3)

#### Data Splitting Script:

Splits the collected data into training, validation, and testing sets to ensure robust model evaluation.
![Screenshot from 2024-01-22 16-06-23](https://github.com/user-attachments/assets/bed5ae4f-ea2a-4d4c-a0a1-00aa0b5e9cab)

#### Training Script:

Trains the model on the prepared dataset, optimizing its ability to differentiate between real and fake representations.
![Screenshot from 2024-03-22 13-14-21](https://github.com/user-attachments/assets/ff8706b2-c91f-4058-9c1b-8da45901e7f0)
![Screenshot from 2024-03-22 13-14-11](https://github.com/user-attachments/assets/883ec8a8-9b32-4b92-855f-dcedd96de3a0)


#### Real-Time Detection Script:

Implements the trained model to perform live recognition, distinguishing between real-time faces and static images/videos.

![Screenshot from 2024-04-17 16-05-06](https://github.com/user-attachments/assets/70631e13-ca79-4d7d-96ca-26240e1e496c)
