# Unitarian Universalist Church of Kent Virtual Services Runbook #

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0) ![Creative Commons License](https://i.creativecommons.org/l/by-sa/4.0/80x15.png).

## Table of Contents

+ [Organizational Tools](#organizational-tools)
+ [Team Roles](#team-roles)
    - [Greeter](#greeter)
    - [Projector](#projector)
    - [Director](#director)
    - [Worship Talent](#worship-talent)
    - [Recorder](#recorder)
    - [Slide Prep](#slide-prep)
+ [Rehearsals](#rehearsals)
    - [Test Run](#test-run)
    - [Final Rehersal](#final-rehersal)
+ [Projector Details](#projector-details)
    - [General Configuration](#general-configuration)
    - [Service Operations](#service-operations)
    - [Pre Service](#pre-service)
    - [During Service](#during-service)
    - [Greeting Rooms](#greeting-rooms)
    - [Virtual Coffee Hour](#virtual-coffee-hour)
+ [Director Details](#director-details)
    - [Rehearsal](#rehearsal)
    - [Before Service](#before-service)
    - [During Service](#during-service-1)
    - [Spotlighting:](#spotlighting-)
    - [Transitions:](#transitions-)
+ [Greeter Details](#greeter-details)
+ [Slide Prep Details](#slide-prep-details)
    - [Announcements](#announcements)
    - [Audio/Video Content](#audio-video-content)
    - [Slide Prep Guidelines for Readability and Accessibility](#slide-prep-guidelines-for-readability-and-accessibility)
    - [Style and Readability Guidelines](#style-and-readability-guidelines)


### Organizational Tools

Trello Board: Suggestions, issues should be logged here and the team should check and address periodically (collaborative space that doesn’t require a meeting to discuss items)

Google Hangouts: Chat for discussion, used on Sunday morning for backend communication

Signup Genius: Tech team scheduling

### Team Roles

#### Greeter
*Co-host in Zoom*

Responsibilities: 
* Monitors waiting room before and during service.
* Monitors video and audio feed and turns off as needed.
* Private chats with guests as possible to determine name and may update display name.

Notes:
* Helpful to have a separate computer for greeter and keep the view on Gallery.
* Greeter should decline breakout room for greeting during service to continue monitoring waiting room.

#### Projector
*Host in Zoom*

Responsibilities:
* Ability to show slides full screen not using webcam (OBS)
* Cam output is the slide deck and/or overlay scenes
* Creates/monitors breakout rooms for greeting and social hour
* Ensures all roles are co-hosts

Notes:
* Multiple monitors is preferred

#### Director
*Co-host in Zoom*

Responsibilities:
* Changes spotlight in Zoom to focus on appropriate participant
* Mute/unmute if necessary
* Also performs greeter role

#### Worship Talent
*Co-host in Zoom*

Responsibilities: 
* Leads portions of the serivce on camera. Includes:
    * Minister
    * Music Lead
    * Worship Associate
    * RE Leader
    * Time for all Ages guest
* Provides order of service

Notes:
* Needs working web cam, mic, sufficient lighting, internet speeds to support webcasting through Zoom

#### Recorder
*Co-host in Zoom*

Responsibilities:
* Needs ability to record service to local device (do not interact with Zoom meeting, as local changes in view are recorded)
* Edits and publishes recording to Google drive. 

Notes:
* Need 1 to 1.2 GB per service to store raw recording

#### Slide Prep

Responsibilities:
* Converts order of service into Google Slides, including song lyrics, responsive readings and prayers, other agenda points
* Inserting videos into correct place
* Building announcements (pre-service and post service) - create a loop video, insert as a slide - basic video editing needed



### Rehearsals

#### Test Run
Occurs on Saturday.
Includes Projector, Director, Worship Talent. 
Tech check - lighting, audio is working.
Slide and Video dry run, adjusting flow.
Director cues (when to spotlight.)

#### Final Rehersal
At least one hour before start of service.
Includes Projector, Director, Worship Talent, Greeter.
Test videos.
Finalize director cues.
Last minute changes.
Greeter join by 25 minutes until service.
Centering at 20 minutes until service
Open waiting room starting at 15 minutes until service
Recorder join by 5 minutes until service


Worship Talent Details

### Projector Details
*Windows-based Technical Details*

Requirements
* Open Broadcaster Software (OBS) 
* OBS Virtual Cam plugin
* Zoom Client 
* Multiple monitors or systems strongly encouraged

#### General Configuration
Install OBS and the OBS Virtual Cam plugin with at least 1 virtual camera. Define one or more OBS scenes to be used for service.

The main scene will be used to capture the slide display window and output the video to the virtual cam plugin.

The main portion of the scene will be a Window Capture source. Define the Window Capture source to capture the browser window that displays the service slides.


If the resolution of the virtual camera exceeds that of the window capture you can add an appropriately themed and licensed background (Creative Commons preferred) image source to the scene, ordered to be behind the window capture source.

You can also add an additional image source to a lower corner of the scene with the church logo.

For virtual choir video playback define a scene that is only a full size window capture of the slide window.

For announcements video, you can define a scene with the source of Media Source (where you can define loop, etc.) and just point to the file. It would be helpful to keep the file named generically (announcements.mp4) and in the same place on the computer. Replace the file weekly or as needed with updates.       

For post offering slides and optionally pre and post service announcement playback you can add a scene with donation details superimposed in a lower corner of the scene.

#### Service Operations
The projector system should have only a headset or muted speaker output to eliminate potential feedback. 
The projector mic must always be muted during the entire service.

#### Pre Service
As the Zoom Host roll, prep for service by:
* Start the meeting
* Ensure waiting room is enabled (... in participants list)
* Set name to “Projector”
* Admit any tech team and workshop talent members
* Promote all tech team and worship talent members to Co-host
* Turn off participant screen sharing feature (under screen share icon)
* Turn off participants can unmute themselves feature (... in participants list)
* Ensure advanced audio features (audio settings...advanced)  are configured to optimize music output and minimize CPU load by setting:
* Enable “Show in-meeting option to “Enable Original Sound from microphone”
* Make sure the “Original Sound” setting is turned on for the projector system
* Disable “Suppress Persistent Background Noise”
* Disable “Suppress Intermittent Background Noise”
* Set “Echo cancellation” to “Auto”
* Select “Turn on original sound” so that played back audio is left in original state (essential for playback of content that Hal mastered)

#### During Service
During service, advance the slides in time with the service. When spotlighted ensure that your microphone is always muted and decline all attempts by the Zoom client to enable the microphone when you are spotlighted.

When projecting slides, have the presenter notes turned on so that you can see previous and next slide previews in the notes window.

When there is embedded audio content or embedded video with audio content (such as virtual choir performances) share the Projector audio by going to Share Screen -> Advanced -> Music or Computer Sound Only

#### Greeting Rooms
For greeting breakout rooms, prepare the rooms by setting the number of breakout rooms such that there will be between 2 and 4 attendees per room. As the number of attendees increases during the initial portions of the service, adjust the number of breakout rooms accordingly. 

Greeting rooms are open for 3 to 5 minutes. Note that Zoom requires a one minute notification to attendees to close breakout rooms so take that time into account when timing the end of greeting time.

It is easiest to let Zoom randomly assign attendees to greeting rooms. For the first minute of greeting time you can optionally add late arriving attendees to breakout rooms. After that time has elapsed it is usually best to leave late arriving attendees in the main room.

#### Virtual Coffee Hour
Begin preparing the virtual coffee hour breakout rooms before the end of service. Aim for no more than 6 attendees per breakout room. 

Do not open the virtual coffee hour breakout rooms until at least a few minutes after the end of service. During the time between the end of service and the start of coffee hour monitor the population of the planned breakout rooms as attendees drop off. 

Adjust the room populations by moving people in low populated rooms (because their fellow attendees have dropped off) to other breakout rooms. Continue to aim for at least 4 and usually not more than 6 attendees per breakout room.

Monitor the population of the breakout rooms, as rooms drop to 2-3 attendees move all attendees from that room into another, more populated, room. Ensure that when you move attendees to other rooms that you move all attendees from their old room to the new room together so they can continue their ongoing conversations. 

If there are attendees still in the main room you can enable the “Attendees can unmute themselves” and allow free conversation in the main room.

### Director Details
#### Rehearsal

Make a physical copy of the order of service with director notes including who is ‘on camera’ at any given time, transitions, such as the breakout session, and any moment where there is switching between two cameras, such as during the offering or chalice lighting.

Ask any speaker who has not already spoken in our virtual service if they would like to be responsible for their muting and unmuting and offer to do that for them if that would make them more comfortable. Ideally, the Director should have as few microphones to manage as possible. Having more than one person managing a microphone causes a Mute/Unmute tug of war. If the speaker is new to Zoom, make sure they know what it looks like on their end when they are ‘on camera’.

Help troubleshoot with speakers about any lighting or sound issues.

Practice using More>Spotlight between cameras during the run through.

#### Before Service

Arrange Zoom with Speaker View, Participants, and Chat open. Practice some switching between cameras during the quick run through. Make sure that all speakers are co-hosts so that their names appear at the top of the list.

When the team is ready to allow guests to enter from the Waiting Room, make sure that Allow Participants to Unmute Themselves is unchecked. Have the camera set to Projector for the Announcements slideshow. As soon as the person who is recording the service arrives, click on their settings to Allow Record. They do not have to be a co-host and adding them as a co-host just clutters the list of speakers, despite them not speaking.

#### During Service

Being director means always knowing who is ‘on camera’ next. Because new names are constantly popping up in the Waiting Room in the Participants column, causing all the names below to jump around, clicking More>Spotlight on the correct name suddenly becomes much more challenging!


#### Spotlighting:

When possible, help the Greeter allow people in whose names you recognize or phone numbers, as those with phone numbers are incapable of bombing anyhow. Click More on the next speaker and keep the cursor hovering over Spotlight so that you have a static button to press. After a while, Projector, the music director, and service leader, having ‘spoken’ the most, will be the first people to appear along the top in Speaker View, giving you more static buttons.

#### Transitions:

Ideally, the music director should be Unmuted for the entire service to avoid problems with the microphone and to allow the music director to add improvised musical interludes when needed.

If you do join a Breakout room yourself, be sure to spotlight Projector first. Otherwise, Zoom will pick some random person who is not in a breakout room to be spotlighted. Also, don’t stay in the Breakout room until the last second, because when you return to the main room, Zoom will have reset your arrangements.

The goal is to show the transition slides each time but sometimes the Projector isn’t caught up yet and, in that case, you should not spotlight Projector but instead go onto the next speaker to make things look smoother.

It’s awkward watching someone struggle with lighting a chalice so I just spotlight the chalice lighting words during that whole scene.

After the service leader introduces the time for joys and concerns, spotlight the Joys and Concerns slide. Otherwise, we end up staring at the service leader staring at the screen, waiting for someone to type the first joy or concern.

If there is a live performance during the offering, switch between the musician and the offering slide at the end of a verse, and try to have a good balance of the length of time that the musician and the slide are shown.

Sometimes, a speaker forgets to turn off their microphone when they are done speaking. Make sure to turn it off so that there are no surprise background sounds later in the service.

### Greeter Details
As the Greeter you are responsible for admitting attendees from the waiting room into the service room and monitoring attendee cameras. 

Phone attendees can be automatically added as they do not have permission to unmute themselves and thus cannot interfere with service operations.

Video enabled attendees should be required to set their name to an understandable identifier.

During service setting your Zoom client to Gallery mode provides you with an easy to scroll through interface to check attendee camera content.

Throughout the service, regularly scan through the enabled attendee cameras and turn off the video of any attendee that is displaying inappropriate content via their camera.


### Slide Prep Details

#### Announcements
After the announcement slides are prepared a video of the slides must be recorded and looped. Record the presentation of the announcement slides, use video editing software to duplicate the playback out to about 30 minutes of run time. 

Note: if you have Microsoft Powerpoint, you can easily create a video of a slide deck by File>Export>Create a Video. Don’t Use Recorded Timings and Narrations, and set seconds spent on each slide to 7 seconds (or as desired). 

Insert a new slide into the beginning of the service slide deck with a layout of “Blank” and add the video. Expand the video to take up as much of the slide area as possible. Set the video to auto-play. 

Copy the announcement video slide to the end of the service slide deck so that it also plays after the service ends.

#### Audio/Video Content
When prepared audio/video content is provided insert a new slide in the appropriate place in the service slide deck. Set the slide layout to “Blank” and add the content. Expand the video to take up as much of the slide area as possible. Set the video to auto-play.

#### Slide Prep Guidelines for Readability and Accessibility
Using a standard template for slide format will greatly help! Don’t change headers and fonts and colors on every slide. Pick a template and let Powerpoint or Google Slides do the formatting for you. 

Color Scheme: 

No more than two colors (plus black and white)

Do not use gradients, these pixelate in the Zoom and appear grainy and obscure text

Text and Spacing: 

One or two fonts, sans serif. Be consistent. All headers one font, all text content one font. 

All headers and content should be the same font size whenever possible. Pick the largest font size possible for readability. 

Black font for text on a very light background is preferred. Alternatively, white text on a very dark background. Avoid monochromatic colors, like purple font on a light purple background. Consider that for folks with low vision or color blindness, two colors you choose that may appear very different to you, may appear the same to them. BOLD THE FONT. 

Line Spacing: 1.15 minimum for hymns; 1.5 for responses

#### Style and Readability Guidelines
One verse or one chorus per slide (yes this will create a lot of slides but the projector’s finger will not wear out clicking next slide!)

Keep headings and text in the same spot (don’t move them around forcing the viewer to figure out what is the title and what is the content)

Keep clip art style and size consistent and simple (for example, use all photos or all illustrations, limit to one image per slide)

Keep Header and Text style consistent: If you are using ALL CAPS for headers, make sure all slides have HEADERS IN ALL CAPS. 

Read here for more on low vision accessibility needs: https://www.w3.org/TR/low-vision-needs/
