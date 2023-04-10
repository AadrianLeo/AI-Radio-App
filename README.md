# ai_radio
![aiRadio](https://user-images.githubusercontent.com/81036521/177046575-c5661038-e571-4018-8fb1-704036f0e0d5.png)

#
# Introduction
AI Radio is an radio application with an AI assistant where you can command your application play song stop the song. search the radio song by categories by commands. AI assistant commands are made with the use of Alan AI. and Radio song and category are inputed from an Radio api links. This application is coded in flutter and Alan AI like API's are used.

APP is under developement

You can download the apk from the release [Ai Radio App](https://github.com/AadrianLeo/AI-Radio-App/releases/tag/v2.0.0)

You can even play it online on web : [web link](https://ai-radio.netlify.app/) web link may not work properly  due to radio station links HTTP and HTTPS mixed content error 

## Installation for developement

1. For flutter Installation.
        
    a. Open the visual studio code with administrator access (due to some linking issue)
        
        On the visual studeio icon > right click on the icon > select > run as administrator 
    
    b. Install the packages, to install the packages run the command in the terminal :
    
        flutter pub get
     
    c. Change the alan ai key in the code in folder, you can get the api key from the [Alan Ai Official website](https://alan.app/), and add the API key in the file,
    
        Folder Location : lib > pages > home_pages.dart
        
        Code change : In setupAlan function change the ALAN AI API KEy
        
     d. Copy and paste the file codes from the below scripts in the alan ai scripts : (File links : [AI_DATA](https://github.com/AadrianLeo/AI-Radio-App/blob/main/AI_DATA) , [AI_RADIO](https://github.com/AadrianLeo/AI-Radio-App/blob/main/AI_RADIO))
        
        After creating project in alan ai > click on add scrip > Name the script as AI_DATA > copy the script from the AI_DATA file > amd paste it over there
        
        Same for the AI_RADIO file
     
     e. To run the flutter application select an emulator or connect your mobile with the you laptop/pc with usb :
     
        If you are going with your mobile phone enable usb debugging in developer option.
      
     f. Now Run the flutter application. To run the flutter application run command :  🎉
         
        Flutter run
      
     g. Congratulation you are all set and got to go. 🤹‍ 
         
#

If the Ai does not work try deleting the chache data and closing the application and rerunning it again the problem will be fixed.

If you encounter any issues or bugs while using our website, please do not hesitate to write it in the discussion in releases. It is helping me learn and develop.
#
Have Fun.😉

#
