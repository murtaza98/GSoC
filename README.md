<div align="center">
    <a href="https://summerofcode.withgoogle.com/projects/#6134609332404224"><img src="https://i.imgur.com/Fl0y98b.png" width="650" alt="google-summer-of-code"></a>
    <br>
    <b> 
        <p>
        Integrating <a href="https://cloud.google.com/dialogflow">Dialogflow</a> and <a href="https://rasa.com/">RASA</a> with <a href="https://rocket.chat/">Rocket.Chat</a>
        </p>
    </b>
</div>

<p align="center">
    <code> 
        <a href="#project-abstract">Project Abstract</a>&nbsp;&nbsp;&nbsp;
        <a href="#work-product">Work Product</a>&nbsp;&nbsp;&nbsp;
        <a href="#working-demo">Working Demo</a>&nbsp;&nbsp;&nbsp;
        <a href="#pull-requests">Pull Requests</a>&nbsp;&nbsp;&nbsp;
        <a href="#mentor">Mentor</a>&nbsp;&nbsp;&nbsp;
        <a href="#links">Links</a>
    </code>
</p>

## Project Abstract

+ The goal for this project is to integrate chatbot platforms like Dialogflow and RASA with Rocket.Chat.

+ This integrations would be helpful for the **Livechat** feature of Rocket.Chat. 
    > Livechat is a package that adds the ability to embed a pop-up support chat to your website. For example when you want to interact with users visiting your website and help them with their problems, then this feature of RocketChat helps you with that. All you need to do embed a script on to your static website. 

+ With this new Integrations, you will be able to direct your site visitors to a Bot developed on Dialogflow and RASA. This is a very common approach which most of the businesses use now a days, where a visitor would first interact with a Bot. These bot can handle simple interactions like answering FAQ's for a business, to complex interactions like ordering a item. If these bots are not able to answer visitor questions, then the visitor would be transferred automatically to a online human agent who can address their query.  

## Work Product

The final product / deliverable for this project is in the form of **Rocket.Chat APP** which is now published on Rocket.Chat Marketplace 🚀. Here are a few screenshots of both these apps:

<div align="center">
    <img src="https://i.imgur.com/cxG00zo.png" alt="google-summer-of-code">
    <br>
    <b> 
        <p>
        Screenshot of Both Apps installed on Rocket.Chat Sever
        </p>
    </b>
</div>


## Working Demo

- **Rasa Integration Video Demo**

[![Watch the video](https://img.youtube.com/vi/ni38OV23J2U/maxresdefault.jpg)](https://youtu.be/ni38OV23J2U)


## Pull Requests

Following are a list of PR's which I submitted during the GSoC related to the GSoC Project.

| PR Link   | Description | Repository | Status | 
| :-----------: | :------------------------------------: |:-------------: | :------:|
| [PR #14](https://github.com/RocketChat/Apps.Dialogflow/pull/14) | Main PR for Dialogflow App. Major Highlights include:<br>1. Connection with Dialogflow's REST API<br>2. Add endpoints for advance features.  | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #6](https://github.com/RocketChat/Apps.Rasa/pull/6) | [NEW] Connect with Rasa Rest API and exchange messages + add endpoints | [Apps.Rasa](https://github.com/RocketChat/Apps.Rasa) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #33](https://github.com/RocketChat/Apps.Dialogflow/pull/33) | [NEW] add a action to trigger an event  | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #34](https://github.com/RocketChat/Apps.Dialogflow/pull/34) | [NEW] add a new action to send message as a bot user | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #1](https://github.com/RocketChat/Apps.Dialogflow/pull/1) | Handle Google Authentication| [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #8](https://github.com/RocketChat/Apps.Dialogflow/pull/8) | - Connect with Dialogflow's REST API <br> - Add endpoint to close chat| [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #9](https://github.com/RocketChat/Apps.Dialogflow/pull/9) | [NEW] Add new endpoint to perform handover | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #10](https://github.com/RocketChat/Apps.Dialogflow/pull/10) | [NEW] Auto handover on multiple fallbacks (Synchronous Handover) | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #11](https://github.com/RocketChat/Apps.Dialogflow/pull/11) | [NEW] [Optimization-Task] - Caching JWT used for Dialogflow authentication | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #13](https://github.com/RocketChat/Apps.Dialogflow/pull/13) | Merging multiple PR's  | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/tskv8MM.png" width=50 height=40> |
| [PR #37](https://github.com/RocketChat/Apps.Dialogflow/pull/37) | [NEW] Add support for audio file as a input | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/1r1keCi.png" width=50 height=40> |
| [PR #7](https://github.com/RocketChat/Apps.Rasa/pull/7) | Fix Minor Formatting Issue in Readme | [Apps.Rasa](https://github.com/RocketChat/Apps.Rasa) | <img src="https://i.imgur.com/1r1keCi.png" width=50 height=40> |
| [PR #2](https://github.com/RocketChat/Apps.Dialogflow/pull/2) | Connect with Dialogflow REST API| [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/ihaDyZS.png" width=50 height=40> |
| [PR #7](https://github.com/RocketChat/Apps.Dialogflow/pull/7) | Add Asynchronous-webhook support to close-chat | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/ihaDyZS.png" width=50 height=40> |
| [PR #12](https://github.com/RocketChat/Apps.Dialogflow/pull/12) | [IMPROVE] Update Readme and add endpoint docs  | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/ihaDyZS.png" width=50 height=40> |
| [PR #35](https://github.com/RocketChat/Apps.Dialogflow/pull/35) | [NEW] add support for Audio Input | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/ihaDyZS.png" width=50 height=40> |
| [PR #36](https://github.com/RocketChat/Apps.Dialogflow/pull/36) | [NEW] Add support for audio file attachments + Merge PR ( #33, #35 )  | [Apps.Dialogflow](https://github.com/RocketChat/Apps.Dialogflow) | <img src="https://i.imgur.com/ihaDyZS.png" width=50 height=40> |

<!-- Other PR's submitted during GSoC Period

| PR Link   | Description | Repository | Status | 
| :-----------: | :------------------------------------: |:-------------: | :------:| -->

## Mentor

**“One of the greatest values of mentors is the ability to see ahead what others cannot see and to help them navigate a course to their destination.”** *— John C. Maxwell*

*At the end of my GSoC journey, I 100% agree with this quote.* 

Special thanks to my mentor

- **RENATO BECKER** [@Github](https://github.com/renatobecker) [@LinkedIn](https://www.linkedin.com/in/renatobecker/)


## Links

- [My GSoC Proposal](https://docs.google.com/document/d/1sMoHVFK7bih6XIKlEb7X6QJoZ0wQXImkqwJqg4VKxpI/edit?usp=sharing)
- [My final Presentation PPT](https://docs.google.com/presentation/d/1g4TPIJd3OPtIU5hnx6KogI2CeuSg1-GiDzI2wJ2YjK0/edit?usp=sharing)
