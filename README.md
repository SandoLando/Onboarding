# Onboarding
Onboarding automation created using Selenium with Python.

This is still a work in progress and I will not post the actual code here for security concerns.

The program consists of a single class, ThirdParty, with a method for every third-party application that we need to enroll new users into when onboarding them into the company.

Selenium is doing most of the heavy lifting in this program, being used to find key HTML/CSS tags to target and send the necessary login credentials and user information to the required fields. Also using Selenium's Google Chrome drivers libraries to create the window where the information is being entered.

I have finished the work for most of the applications needed, but have currently hit a snag in logging into one of the third party applications. I think the issue may be with the application verifying the location or perhaps the authenticity of the Selenium driver window. 

I have tried to figure out a way to open the Selenium driver window so that it has the same IP or properties as a "regular" Google Chrome window, but have not been successful as of yet... 
