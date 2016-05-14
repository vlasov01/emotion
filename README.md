# Webcam Emotion Analytics using MS Cognitive Service

# Inspiration

Everyone needs to know how others perceive you.

# What it does

Displays your face emotions in a digital format.

# How I built it

It is a web application, which is using a webcam and Azure Cognitive Services Emotion API provided.
The face emotion evaluation is done by Microsoft cloud service https://www.microsoft.com/cognitive-services/en-us/emotion-api . You need to get your key to use this service and replace string YOUR-EMOTION-API-KEY in index.html with its value.
I as well used webcam script from the following project https://github.com/jhuckaby/webcamjs/blob/master/webcam.min.js and based64-binary.js came from https://github.com/danguer/blog-examples/blob/master/js/base64-binary.js . You'll need to add these two scripts to the same folder where you going to host index.html.

# Challenges I ran into

It takes some tweaking to convert webcam image snapshot into jpg and upload it to Azure.

# What's next for Webcam Emotion Analytics using MS Cognitive Service

Create a better experience by adding better visualization of results and better support for web mobile. Perform analysis continuously in background and notify about emotional state changes over time. Add predefined rules, which will allow generate alert if the emotional state to negative.