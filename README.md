# WS Pro Chrome Extension

## Instructions

### Installing Chrome Extension

1. Download the latest version from [here](https://alp-wspro.s3.amazonaws.com/release/chrome-extension-2020.12.11.26.zip)

PCA team download this version - [here](https://github.com/trilogy-group/cn-wspro-client-releases/releases/download/0.1.3/chrome-extension-0.1.3.zip).

2. Unzip `chrome-extension-2020.12.11.26.zip`. 
<img width="645" alt="shot1" src="https://user-images.githubusercontent.com/29868075/84779370-f29c3200-b001-11ea-9e96-b701c7dd53a9.png">

3. Go to url `chrome://extensions` in Chrome.
<img width="672" alt="image8" src="https://user-images.githubusercontent.com/29868075/84780140-d8af1f00-b002-11ea-8fc4-dd4c2d300cde.png">

4. Click `Load unpacked` and select the unzipped folder from step 2. 
<img width="672" alt="shot2" src="https://user-images.githubusercontent.com/29868075/84779472-10699700-b002-11ea-87e1-56ba4e8bd900.png">

5. Run the extension. Use your AD credentials to login. 
<img width="739" alt="shot3" src="https://user-images.githubusercontent.com/29868075/84779562-2d05cf00-b002-11ea-8841-c2f101244ade.png">


### Using Chrome Extension

1. Start by fetching a new task.
<img width="655" alt="shot4" src="https://user-images.githubusercontent.com/29868075/84780521-4ce9c280-b003-11ea-8074-b72dc8bb4dbb.png">

2. `Pause Task` will pause the task and push it to your backlog. You can click on the `Paused Tasks` button to fetch tasks paused by you and resume working on any of them. 
<img width="874" alt="shot-10" src="https://user-images.githubusercontent.com/29868075/84790126-a3a8c980-b00e-11ea-9ec0-49a16251d1eb.png">
<img width="874" alt="shot-11" src="https://user-images.githubusercontent.com/29868075/84790179-b15e4f00-b00e-11ea-8c23-78660a950718.png">


3. You will be presented with one or two buttons representing the valid states that the ticket assigned to you can be transitioned to. When you have finished working on the task (a task is a Jira ticket in a particular state) assigned to you - click on one of them, which will finish the task in ALP (and assign the Jira ticket back to the `ascheduler` (`ALP Scheduler`)) user and transition the Jira ticket to the correct state. After which, you may fetch a new task. **Do NOT change the assignee to `ascheduler` manually and do NOT do the state transition manually on Jira - the extension will automatically do it for you, when you click on the corresponding button.**
<img width="600" alt="Screenshot 2020-11-26 at 4 50 21 PM" src="https://user-images.githubusercontent.com/29868058/100344882-84738680-3007-11eb-9930-6586b9186d8b.png">

4. If any error pops up while fetching a new task or pausing a task or resuming a task or finishing a task, click on the refresh button in the extension to see if it resolves the error; before reaching out to the ALP team.
<img width="600" alt="refresh" src="https://user-images.githubusercontent.com/29868058/100344368-b59f8700-3006-11eb-9438-c90d0b337442.png">
