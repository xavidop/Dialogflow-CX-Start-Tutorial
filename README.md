# Dialogflow-CX-Start-Tutorial

### Content
- ##### [Introduction](#intro)
- ##### [Dialogflow CX Setup ](#Setup)
- ##### [Creating a simple welcome message](#welcomemessage)
- ##### [Creating a single-flow agent](#single-flow)
- ##### [Creating multiple-flow agent](#multiple-flow)
- ##### [How reuse information from previous conversation turns](#reuseinformatione)
- ##### [Testing the completed agent](#Testing)
- ##### [Conclusion](#conclu)


## <a name="intro"></a>Introduction

## <a name="Setup"></a>Dialogflow CX Setup 
1. To use services provided by Google Cloud, you need to create a project using [Google Cloud Console](https://console.cloud.google.com/) and enable the Dialogflow API.
2. Using [DF-CX console](https://dialogflow.cloud.google.com/cx/projects), choose the project you just created and click Create agent.<br>
3. Complete the form for basic agent settings:<br>
   *You can choose any name.<br>
   *Select your preferred location. <br>
   *Select your preferred time zone.<br>
   *Select the default language for your agent.<br>
4. Click Save.<br> 

## <a name="welcomemessage "></a>Exploring the created agent 
The created agent has a default Start Flow with a start page that comes with default welcome intent. Withing this default setting, the agent can handle a basic conversation with only a welcome message. 

![tt](images/agent_default.png)

To test your new agent:
1. Click the Test Agent button to open the simulator.
2. Enter hello in the text entry and press enter.
3. The agent responds with a default welcome response.
4. Close the simulator 

To edit the welcome response message:
1. Click the Build tab.
2. Select the Default Start Flow in the Flows section.
3. Click the Start node in the graph. This is the start page for the Default Start Flow.
4. Find the intent route with the Default Welcome Intent as an intent requirement and click it. This opens a panel to edit the intent route information.
5. Find the fulfillment section and delete all response messages, then add Hello, this is a demo virtual agent. How can I help you? as the only response.
Click Save. Close the intent route editing panel.

To test the updated welcome response message
1. Click the Test Agent button to open the simulator.
2. Enter hello in the text entry and press enter, the agent responds with your new message.





## <a name="single-flow "></a>Creating a single-flow agent

## <a name="multiple-flow "></a>Creating multiple-flow agent

## <a name="reuseinformation"></a>How reuse information from previous conversation turns?

## <a name="Testing"></a>Testing the completed agent

## <a name="conclu"></a>Conclusion


