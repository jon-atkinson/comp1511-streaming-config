# comp1511-streaming-config
This repo contains all information and resources to set up and operate a COMP1511 livestream. 

# Prerequisites
- The laptop you are using should be unmanaged (or you'll need a firm guarantee of no interruptions) and have OBS installed with full permissions unlocked
- If you are using a smartphone as a camera (at time of writing we're using an iphone 15 PM), you should make sure the phone has the paid version of OBS camera installed
    - the laptop will also need to have the OBS camera plugin installed and any requested permissions granted
- If using an hdmi camera:
    - ensure camera outputs a clean hdmi feed (no viewfinder markings)
    - ensure you have a working capture card
- Ensure you have ethernet connection between the laptop running OBS and the LDS port in the theatre

# Setting up Slide Sharing - each lecture
- On lecturers laptop, go to https://vdo.ninja
- Select "Remote Screenshare into OBS" and select appropriate option for the lecture
    - if selecting "Entire screen or Chrome Tab" and want video audio, etc., ensure the option for sharing audio at the bottom of the popup is checked
- Once the above popup has closed, you should see the shared view with a link above it
    - copy the link and send it to the OBS laptop
- Open OBS on the OBS laptop
    - select the "Slide Present View" scene
    - select the "Lecturer Slides" source from the Sources panel
    - hit the settings wheel in the sources panel
    - update the URL field to the url you created previously

# Primer on OBS Profiles and Scene Collections
OBS Profiles are names connected to groups of settings (i.e. resolution, framerate, etc.).
They are generally used to manage different functions, i.e. streaming/recording/4K streaming

OBS Scene Collections are the combinations of scenes and sources that make up the different views in OBS

This repository contains a COMP1511 Profile and Scene Collection that can be used to stream lectures

