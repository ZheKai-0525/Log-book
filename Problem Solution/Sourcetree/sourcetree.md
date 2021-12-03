# Sourcetree problem and solution

## Have a check before clone repos
1. Select tools and click on options

![Tools](https://github.com/ZheKai-0525/Newbee/blob/a4349688fe54193be377791ada23d9217f24f1a4/How%20to/Image/copy_urls.png)

2.  On general tab make sure you Default user information is correct
3.  On Authenthication make sure set your account to default

## How to clone repos on github (Local)?
1. Click on Clone button
![Clone repo](https://github.com/ZheKai-0525/Newbee/blob/34d4cad49270d9946c74df284e9a26993c8c4745/How%20to/Image/clone_repo.png)

2. Copy repos url from github (**Https method**)
    i)  Left click on  `Code` button
    ii) copy the link provided on **HTTPS** tab 
![copy url](https://github.com/ZheKai-0525/Newbee/blob/71d3914c8b4224082956119fbfdfc5d60fc9d0e3/How%20to/Image/copy_urls.png)

3. Paste the urls on Sourcetree
4. Select the location you want to store
5. Click `Clone` button
![Paste url](https://github.com/ZheKai-0525/Newbee/blob/9dbc3945e03f89b27beb19de05f46da42e73f94c/How%20to/Image/paste_url.png)

## Problem may face when clone repos 
#### Problem 1: This is not valid source path/URL
1. Your current repos are set as private, you need to generate a **Personal access tokens**
2. Left click profile picture and select settings 
![open setting ](https://github.com/ZheKai-0525/Newbee/blob/aafd8681bc7955601cafe987689764514c2175e9/How%20to/Image/generatekey_1.png)
3. Select developer settings
![developer settings](https://github.com/ZheKai-0525/Newbee/blob/1e4e5e79d2d15a53ce6cff496ca97a39c8d5bf44/How%20to/Image/generatekey_1.png)
4. Select the **Personal access tokens** on developer settings and click generate new token
![enter image description here](https://github.com/ZheKai-0525/Newbee/blob/8ae081654130c182d0a73cf5c90b3c255db33043/How%20to/Image/pat.png)
5. You may select the expiration date of the token.
6. Copy the **Personal access tokens** and paste it on your urls and adding  `@` infront of the github.com

		https://**Your personal access tokens**@github.com/ZheKai-0525/Newbee.git
