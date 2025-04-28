<a name="readme-top"></a>

<p align="center">
  <img src="/Resources/Images/SoundAmplifier-wide.jpg" height="200" />
  <h3 align="center">Sound Amplifier</h3>
</p>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
          <ul>
            <li><a href="#feature-sound-amplifier">Feature: Sound Amplifier</a></li>
              <ul>
                <li><a href="#headphones-connection">Headphones Connection</a></li>
                <li><a href="#voice-visualizer">Voice Visualizer</a></li>
                <li><a href="#sound-amplifier-settings">Sound Amplifier Settings</a></li>
                <li><a href="#speech-to-text">Speech To Text</a></li>
                <li><a href="#noise-reduction">Noise Reduction</a></li>
                <li><a href="#equalizer-and-balance">Equalizer and Balance</a></li>
                <li><a href="#loudness-protect">Loudness Protect</a></li>
              </ul>
          </ul>
          <ul>
            <li><a href="#feature-hearing-test">Feature: Hearing Test</a></li>
              <ul>
                <li><a href="#test-preparation">Test Preparation</a></li>
                <li><a href="#testing">Testing</a></li>
                <li><a href="#test-pause">Test Pause</a></li>
                <li><a href="#test-interruption">Test Interruption</a></li>
                <li><a href="#test-result">Test Result</a></li>
              </ul>
          </ul>
          <ul>
            <li><a href="#feature-tips-and-articles">Feature: Tips and Articles</a></li>
          </ul>
    </li>
    <li>
      <a href="#about-my-participation">About My Participation</a>
    </li>
    <li>
      <a href="#about-the-company">About The Company</a>
    </li>
  </ol>
</details>




## About The Project

**Sound Amplifier** is an application that provides a quick hearing test and offers personalized sound enhancement to help you hear more clearly and comfortably.

The development of the application began in January 2024. The creation of the basic functionality was completed in August 2024.  
The relatively long development time is related to frequent switching to other projects.  
The project has not been released due to the company reasons.

Team Composition:  
- 1 **Product** manager
- 1 **UI/UX** Designer
- 1-2 **iOS** Developers

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Feature: Sound Amplifier

The Sound Amplifier feature can be used for dialogue with another person. In this case, the person with hearing problems should wear headphones, and the other person should use the person's phone as a microphone.

#### Headphones Connection

Headphones can be connected automanically or using AirPlay.

| <img src="/Resources/Gifs/sa-headphones-0.gif" width="200"/> &nbsp;&nbsp; <img src="/Resources/Gifs/sa-headphones-1.gif" width="200"/> |
|:--:|
| *Automatically / AirPlay* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Voice Visualizer

Without applying any settings, the user will see the Voice Visualization.

https://github.com/user-attachments/assets/281ce15d-2725-4344-9eaa-6e5ef41d9f88

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Sound Amplifier Settings

There are a few settings for more comfortable use:
- Speech to Text
- Noise Reduction
- Equalizer and Balance
- Loudness Protection 

| <img src="/Resources/Images/sa-settings-0.PNG" width="200"/> &nbsp;&nbsp; <img src="/Resources/Images/sa-settings-1.PNG" width="200"/> |
|:--:|
| *Available Settings* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Speech To Text

https://github.com/user-attachments/assets/2bc61f6b-0a0b-4815-9e75-ca4f5b7163e7

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Noise Reduction

https://github.com/user-attachments/assets/88cff935-6be3-442c-9e7e-7fc69497fb3a

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Equalizer and Balance

Many people with hearing problems hear differently at different frequencies (for example, they hear low frequencies softly or hear high frequencies loudly), as well as hear differently with different ears.  
For this, there are Equalizer and Balance settings to adjust the sound.

https://github.com/user-attachments/assets/c863874c-7dd2-4a06-bd6a-aab3ac6a9f60

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Loudness Protect

For the sake of hearing safety, the user can activate and adjust the maximum sound volume.

| <img src="/Resources/Gifs/sa-loudness.gif" width="200"/> |
|:--:|
| *Loudness Protect setting* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Feature: Hearing Test

Hearing Test can help the user to find out how well they can hear at different frequencies. It can also help the user determine if they have any hearing impairments.  
The result of the test is an audiogram that can be used when making an appointment with a doctor, as well as many recommendations for preventing hearing loss.

| <img src="/Resources/Images/test-intro.PNG" width="200"/> |
|:--:|
| *Test Intro* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Test Preparation

To start testing, the user needs to make some preparations.

| <img src="/Resources/Gifs/test-config-headphones.gif" width="200"/> |
|:--:|
| *Headphones connection* |

To obtain a more accurate result, the test should be conducted in a quiet place.

| <img src="/Resources/Gifs/test-config-noise.gif" width="200"/> |
|:--:|
| *Loudness check* |

Before the test, you need to configure the devices so that the test is not interrupted and the sound quality is not modified.

| <img src="/Resources/Images/test-config-setup.PNG" width="200"/> |
|:--:|
| *Device setup* |

For the safety of hearing and the correct calculation of the hearing level, the volume on the device must be 50%.

| <img src="/Resources/Gifs/test-config-volume.gif" width="200"/> |
|:--:|
| *Volume check* |

All headphones have a calibration offset, which affects the sound volume calculation.  
It is known for Apple headphones, but not for headphones from other manufacturers, so the results may not be accurate for them.

| <img src="/Resources/Images/test-config-device.PNG" width="200"/> |
|:--:|
| *Headphones selection* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Testing

After everything is prepared, the user can start testing.  
The test is performed for each ear individually and at different frequencies (125, 250, 500, 1000, 2000, 4000, 8000).  
During the test, it is necessary to find out the value of the minimum sound that the user can hear at each frequency. To do this, the "Can hear - Can't hear" strategy was chosen, which seemed the most optimal and accurate.  
In the video, you can see the testing of the left ear (the values are exaggerated so that the generated sound for the desired frequency can be heard).

https://github.com/user-attachments/assets/c4bb4361-0061-4faf-b6dc-5cf45031ab17

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Test Pause

The test can be paused. It allows to:
- resume the test
- skip the current ear
- restart the current ear
- exit the test

| <img src="/Resources/Images/test-pause.PNG" width="200"/> &nbsp;&nbsp; <img src="/Resources/Gifs/test-resume.gif" width="200"/> &nbsp;&nbsp; <img src="/Resources/Gifs/test-skip.gif" width="200"/> |
|:--:|
| *Test Pause* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Test Interruption

The test can be interrupted by:
- headphones disconnection - the highest priority
- system volume change - lower priority
- loud place - lower priority
- suspension (call, alarm, lock the screen, move the app to background, etc) - the lowest priority 

| <img src="/Resources/Gifs/test-interruption-primary.gif" width="200"/> &nbsp;&nbsp; <img src="/Resources/Gifs/test-interruption-suspended.gif" width="200"/> |
|:--:|
| *Test Interruption* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

#### Test Result

After the test is done, the user can see the result of the test.

| <img src="/Resources/Gifs/test-result.gif" width="200"/> |
|:--:|
| *Test Result* |

The audiogram is the most important part of the test result, because it is what doctors use when making a diagnosis.  
There is a feature to convert an audiogram to PDF format and share it with others.  
An audiogram can also be saved in HealthKit so that the iOS system knows the state of your hearing and improves the user experience.  

| <img src="/Resources/Gifs/test-audiogram.gif" width="200"/> |
|:--:|
| *Audiogram* |

The user also receives a diagnosis of their hearing, information about the diagnosis, various recommendations, as well as information about similar diagnoses.

| <img src="/Resources/Gifs/test-diagnosis.gif" width="200"/> |
|:--:|
| *Diagnosis* |

The user also has access to the history of their results (results can be deleted).

| <img src="/Resources/Gifs/test-history.gif" width="200"/> |
|:--:|
| *History* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Feature: Tips and Articles

The application contains a large number of different tips and articles on the topic of hearing. This content can be updated remotely without updating the app.

| <img src="/Resources/Gifs/tips.gif" width="200"/> &nbsp;&nbsp; <img src="/Resources/Gifs/tips-search.gif" width="200"/> |
|:--:|
| *Tips and Articles* |

<p align="right">(<a href="#readme-top">back to top</a>)</p>




## About My Participation

Responsibilities:
- Participation in the creation of the project **from scratch**
- Full research and feature development
- Tasks decomposition, delegation and sprints management

Skills and Technologies:
- Swift
- MVVM+RxSwift, RxCocoa, RxDataSources
- UIKit, CAAnimation
- AudioKit, AudioKitEX, SoundpipeAudioKit, SporthAudioKit, AVFAudio, AVFoundation
- Firebase, Mixpanel, Amplitude, localise.biz
- Bitrise, Fastlane, Git, Sourcetree, Figma
- Jira, Flow (Po­mo­­doro timer)

<p align="right">(<a href="#readme-top">back to top</a>)</p>




## About The Company

Uniapps is a young product company that appeared in 2022 and was originally a startup. After a year and a half-ish of hard work and several successful applications, the company had received the resources to grow and thrive.

Other projects of the company I've worked on:
- <p align="left">
    <img align="center" src="https://github.com/sharojke/sharojke/blob/main/Resources/Companies/Uniapps/WatchFacesClub.PNG" height="35" />
    <a href="https://github.com/sharojke/Uniapps-WatchFacesClub"> Watch Faces Club </a>
  </p>
- <p align="left">
    <img align="center" src="https://github.com/sharojke/sharojke/blob/main/Resources/Companies/Startup1/Startup1-WatchFaces2.png" height="35" />
    <a href="https://github.com/sharojke/Startup1-WatchFaces2"> Watch Faces #2 </a>
  </p>
- <p align="left">
    <img align="center" src="https://github.com/sharojke/sharojke/blob/main/Resources/Companies/Startup1/Startup1-WatchFaces1.png" height="35" />
    <a href="https://github.com/sharojke/Startup1-WatchFaces1"> Watch Faces #1 </a>
  </p>
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>
