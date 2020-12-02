# Face-Recognition-using-Face_Recognition-library
## Face Localization is the first step towards Face Recognition
There are few steps to be performed to get ready for Face Recognition using face_recognition library.
1. Install the library using *pip install face_recognition* if you are using Windows.(Note: Change Runtime as GPU)
2. Import face_recognition library by running below given code
		*import face_recognition
3. Load your image file in a variable
		*image = face_recognition.load_image_file("your_image.jpg")
4. Get face locations in the image file. It will show you the position of all the faces present in image file
		*face_locations = face_recognition.face_locations(image)
5. Now print face location found in the image file
		*print(face_locations)
