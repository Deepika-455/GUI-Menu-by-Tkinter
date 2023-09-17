# GUI-Menu-by-Tkinter

The project is a GUI application developed using Python's tkinter library, designed to offer a collection of features and utilities accessible through a user-friendly interface. The application provides several functionalities, including email sending, SMS sending, web browsing, speech recognition, and more. Here is a breakdown of the key features:

EC2 Instance Launch: This functionality allows users to launch Amazon EC2 instances using their AWS credentials. It employs the Boto3 library to interact with AWS services.

Email Sending: Users can send emails using their Gmail accounts. The application prompts users for the recipient's email address and the email message, then uses SMTP to send the email.

WhatsApp Message: Users can send a WhatsApp message to a specified recipient. The message and recipient's phone number are provided as input.

Camera Access: This feature opens the computer's camera and displays the video feed in a window using OpenCV. It provides a brief view from the camera.

YouTube Access: This option opens the default web browser to the YouTube website.

Google Chrome Launch: This button opens Google Chrome and navigates to a predefined URL (http://www.google.com).

Calculator Launch: Launches the Windows calculator application.

Facebook Access: Opens the default web browser to the Facebook website.

Notepad Launch: Opens the Windows Notepad application.

CodeChef Access: Opens the default web browser to the CodeChef website.

Speech to Text: Utilizes the SpeechRecognition library to recognize speech input from the user through the computer's microphone. It displays the recognized text in a GUI label.

Instagram Access: Opens the default web browser to the Instagram website.

Paint Launch: Opens the Windows Paint application.

Text-to-Speech (TTS): Utilizes the pyttsx3 library to convert text to speech. In the provided code, it says "Good morning" using TTS.

Task Management: Allows users to add and remove tasks using an input field and buttons. Tasks are displayed in a listbox.

SMS Sending: Users can send SMS messages using the Twilio API. The application prompts users for the message, sender's phone number, and recipient's phone number.

The project leverages various Python libraries and external services to provide these functionalities, making it a versatile and interactive GUI application with a range of utilities. It integrates AWS services, email sending, SMS messaging, web browsing, and multimedia features within a single interface.
