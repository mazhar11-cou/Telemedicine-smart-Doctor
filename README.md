# Team Name : Dark Lite
## Team Members: 

<img src="https://user-images.githubusercontent.com/57343793/103149312-852c4380-4792-11eb-95c2-a668e8318c22.jpg" alt="Girl in a jacket" width="250" height="250">

Name: Mazharul Hasan 

Email: mazhar11808006@gmail.com

phone: +8801631981121

## Project Title: Telemedicine-smart-Doctor

## Project Short Description: 
Telemedicine Smart Doctor Diagnose a patient by Machine Learning services by AWS. It takes Data from different medical organizations and stores medical information. In serious condition targets to remind and refer patients to the real doctor. The real doctor diagnostic results can help the system learns and improves the diagnostic accuracy with AWS Machine Learning. It will save money, time and strength of a people. At last we say, Telemadicine Smart Doctor make the world more safe.

# Project Details:

Whole information contain in this youtube link. 
https://youtu.be/P6DePARkTgc


## It is the best way to treat the diseases before they attack

My lab has built a Telemedicine Smart Doctor (Dr. Cloud) with Alexa Skill, Recognition, AWS IoT and Lambda in serverless architecture. Dr. Cloud can talk to patients interactively with Alexa skill, analyze the patient’s face with Rekognition, communicate to medical equipment through AWS IoT and use AR to provide visual instruction to the patient. The patient can do simple self-diagnostic at any time and anywhere!

## Alexa Telemedicine Smart Doctor Skill

This Alexa skill includes several workflows i.e. registration and diagnostic. The conversation is from a Medical School training script. The current response is not yet integration with AWS Machine Learning since we don’t have the suitable dataset in Bangladesh.

By AWS IoT, it can control Web Cam and communication with the receiver. Data stored in DynamoDB, which includes medical record and patient information. It also sends subtitles and user demo video to AR Virtual Assistant.


## Overall Structure of Telemadicine Samrt Doctor
![AWS photo demo](https://user-images.githubusercontent.com/57343793/103148607-ccfb9c80-478b-11eb-8e31-c8498b3860b5.jpg)

## Expalanation how to interect patient with Telemadicine Samrt Doctor

1. Patients interact with Telemedicine Smart Doctor by digital device like the Raspberry Pi, smart phone, tab, pad, pod etc.

2. Patient face detection is completely based on the environment, in the meanwhile we will use ML services like Amazon Recognition, Amazon Sazemaker etc.

3. The vital sign is real time displayed in the dashboard (An alert will be showed and an email notification will be sent if there is any abnormal data)

4. The diagnosis result will be stored on Amazon RDS with the name of the medical record.

5. The patient will get the diagnosis immediately and if the patient has a serious condition it will pass the online doctor by Amazon Alex.


## Conclusion

The running cost of Dr. Cloud is very low cost and highly scalable (100% serverless). All conversations, data and diagnostic results are stored in Amazon RDS. In serious condition targets to remind and refer patients to the real doctor. The real doctor diagnostic results can help the system learn and improves the diagnostic accuracy with AWS Machine Learning. It will save money, time and strength of a people. At last we say, Telemadicine Smart Doctor makes the world more safe.
