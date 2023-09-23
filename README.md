# Watchful Wings: Elevating Surveillance with AI-Infused Drones

### Hackathon Project by Tanishq Joshi and Nikita Singh

As security concerns are increasing in the world, it is of utmost importance that the
surveillance is done in an efficient way. In this project, we have developed an end-to-end
system for such surveillance from a drone using Machine Learning Technologies. We have
used various detection and recognition models and compared their performance in order
to find the best suitable model for the given use case. As the real world conditions may
vary a lot depending on the lighting conditions in which the drone is flying or the quality of
the video feed from the drone, it is of utmost importance that our system is robust and can
tackle all these situations well. Thus, we have employed various data augmentation and
fine tuning techniques in order to make our model robust so that it can perform well in all
situations.

![Screenshot from 2022-11-30 16-52-56](https://user-images.githubusercontent.com/69861341/204801854-ce81d50b-4ce8-4c7e-82ef-a942cf1da4a3.png)

# Steps to Run the Repository:

1. Clone the Repository
2. Create a photos folder which contains the photos of each individual in the database in seperate folders
3. Create a new Python Environment and activate that environment
4. Install all the dependencies that are required
5. Run the code using: python webstreaming_master.py --ip 127.0.0.1 --port 8080

# Structure of the repository:

1. notebook folder: It contains the ipynb files to individually test the detection and recognition algorithms, also contains files for finetuning.
2. report folder: It contains the complete report of our project 
3. templates folder: It contains the files for the web interface containing the front end code.
4. webstreaming_master.py: The python file contains the backend part integrating the model to web interface.
