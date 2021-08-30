# PDYP-TextToSpeech

This is an application that integrates with Google Cloud that will take a file that is in Google Cloud storage and produce an MP3 file of the text (Text-to-speech).

To run the app, run `PDYPMain` main method and pass in your credential file path followed by the file name that is to be read. 

Commands:

1. `mvn clean`
2. `mvn compile exec:java -Dexec.mainClass="PDYPMain" \
  -Dexec.args="<credentialsPath> <textFileInStorage>"`

