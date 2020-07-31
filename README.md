# Transform-String
## Getting Started
The transform feature lets you perform various operations on the input data in order to help you customize your workflow output or the data you send to the next action. This feature is available in all actions supported by webMethods.io Integration. 
Following instructions will get you a copy of the specific String transform in your webMethods.io Integration tanent.

### Prerequisites
1. An account in [webmethod.io](https://www.softwareag.cloud/site/product/webmethods-io-integration.html) with webMethods.io Integration access.

### Importing the recipie to your webMethods.io Integration tanent:
1. Download the specific zip file which transform you want test, from this github page.
2. Log in to your webmethod.io account then go to `webMethods.io Integration`.
3. Select `Reciepes` the click on `Import`.
![image](https://user-images.githubusercontent.com/60179170/88805095-5d798500-d1cc-11ea-97de-dec146247ecc.png)
4. Then select the downloaded file and click on `open`.
![image](https://user-images.githubusercontent.com/60179170/88959896-5895fd80-d2c0-11ea-97f7-e571b1b32174.png)
5. After that you will be able the workflow in your recipie list.<br/>
![image](https://user-images.githubusercontent.com/60179170/88959966-6f3c5480-d2c0-11ea-901c-dd374b132b98.png)
6. Click on that workflow and then select the project name where you want to import the workflow and click on `Done`.
![image](https://user-images.githubusercontent.com/60179170/88805882-5737d880-d1cd-11ea-8414-17324e86dcd6.png)
7. After that you will see a short description about that transform along with the workflow name. Click on `Import` here.
![image](https://user-images.githubusercontent.com/60179170/88960033-867b4200-d2c0-11ea-90f8-22865b41b2b9.png)
Yeee now you have succesfully imported the work flow.

### Run the workflow:
1. Go to that specific project where you have imported the workflow. Hover over the workflow that you have imported and click on `edit`.
![image](https://user-images.githubusercontent.com/60179170/88960106-a90d5b00-d2c0-11ea-9bfe-2ff078cfbe7c.png)
2. Click on the `edit` icon present in the top left corner.
![image](https://user-images.githubusercontent.com/60179170/88808530-a29fb600-d1d0-11ea-90e1-d4efeebfe853.png).
3. Now go to the workflow description and coppy the requested body. `only the JSON part`. And click `Done`. <b> If There is no request body present you can dirctly run the workflow (Step 8).</b>
![image](https://user-images.githubusercontent.com/60179170/88960202-c9d5b080-d2c0-11ea-9431-6c9c3a80e7d7.png)
4. Now `double click` on the start .
![image](https://user-images.githubusercontent.com/60179170/88809305-9700bf00-d1d1-11ea-91a2-235dfaf46578.png).
5. From the list click on webhook.<br/>
![image](https://user-images.githubusercontent.com/60179170/88810663-49855180-d1d3-11ea-914e-09f501278c2f.png)
6. Click `Next`.<br/>
![image](https://user-images.githubusercontent.com/60179170/88910377-05995780-d27a-11ea-99cc-b472dac0f0ef.png)
7. Now paste the coppied data in to the body and click `Next` and then `Done`.
![image](https://user-images.githubusercontent.com/60179170/88960286-eb369c80-d2c0-11ea-9b78-e0488bf25ada.png)
8. Now run the workflow it will give you output in the logger. Here you can see the data type of the input data.<br/>
![image](https://user-images.githubusercontent.com/60179170/88960372-06a1a780-d2c1-11ea-939a-75e3b69ef04c.png)

### Test With other input:
1. Open the weebhook and change the data inside the body. <b> Donot change the key value. ie. "data" is key here  </b>.<br/>
![image](https://user-images.githubusercontent.com/60179170/88960490-36e94600-d2c1-11ea-8988-8aa2a67f8c54.png)
2.  Now run the workflow it will give you output in the logger. 

