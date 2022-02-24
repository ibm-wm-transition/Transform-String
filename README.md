# Transform-String
## Getting Started
Following instructions will get you a copy of the specific String transform in your webMethods.io Integration tanent.

### Prerequisites
1. An account in [webmethod.io](https://www.softwareag.cloud/site/product/webmethods-io-integration.html) with webMethods.io Integration access.

### Importing the recipie to your webMethods.io Integration tanent:
1. Download the specific zip file which transform you want test, from this github page.
2. Log in to your webmethod.io account then go to `webMethods.io Integration`.
3. Select `Reciepes` the click on `Import`.
![image](https://user-images.githubusercontent.com/60179170/88805095-5d798500-d1cc-11ea-97de-dec146247ecc.png)
4. Then select the downloaded file and click on `open`.
![image](https://user-images.githubusercontent.com/60179170/89008067-9bd78700-d327-11ea-83bf-ea7133f4581e.png)
5. After that you will be able the workflow in your recipie list.<br/>
![image](https://user-images.githubusercontent.com/60179170/88959966-6f3c5480-d2c0-11ea-901c-dd374b132b98.png)
6. Click on that workflow and then select the project name where you want to import the workflow and click on `Done`.
![image](https://user-images.githubusercontent.com/60179170/88805882-5737d880-d1cd-11ea-8414-17324e86dcd6.png)
7. After that you will see a short description about that transform along with the workflow name. Click on `Import` here.
![image](https://user-images.githubusercontent.com/60179170/89008155-c88b9e80-d327-11ea-87e0-c7ffd6c79490.png)
Yeee now you have succesfully imported the work flow.

### Run the workflow:
1. Go to that specific project where you have imported the workflow. Hover over the workflow that you have imported and click on `edit`.
![image](https://user-images.githubusercontent.com/60179170/89008187-dc370500-d327-11ea-9dca-b44721372c52.png)
2. Click on the `edit` icon present in the top left corner.
![image](https://user-images.githubusercontent.com/60179170/88808530-a29fb600-d1d0-11ea-90e1-d4efeebfe853.png).
3. Now go to the workflow description and coppy the requested body. `only the JSON part`. And click `Done`. <b> If There is no request body present you can dirctly run the workflow (Step 8).</b>
![image](https://user-images.githubusercontent.com/60179170/89008231-f40e8900-d327-11ea-987f-9e52fbca9fef.png)
4. Now `double click` on the start .
![image](https://user-images.githubusercontent.com/60179170/88809305-9700bf00-d1d1-11ea-91a2-235dfaf46578.png).
5. From the list click on webhook.<br/>
![image](https://user-images.githubusercontent.com/60179170/89008115-b447a180-d327-11ea-8fbe-e0c48f8f8a92.png)
6. Click `Next`.<br/>
![image](https://user-images.githubusercontent.com/60179170/88910377-05995780-d27a-11ea-99cc-b472dac0f0ef.png)
7. Now paste the coppied data in to the body and click `Next` and then `Done`.
![image](https://user-images.githubusercontent.com/60179170/89008308-10122a80-d328-11ea-838e-817f2706a62c.png)
8. Now run the workflow it will give you output in the logger. Here you can see false as the string contain a blank space.<br/>
![image](https://user-images.githubusercontent.com/60179170/89008366-2c15cc00-d328-11ea-88f2-c6cb017fb354.png)

### Test With other input:
1. Open the weebhook and change the data inside the body. <b> Donot change the key value. ie. "data1" is key here  </b>.<br/>
![image](https://user-images.githubusercontent.com/60179170/89009092-81061200-d329-11ea-8cd8-e3f1658c3ff6.png)
2.  Now run the workflow it will give you output in the logger. 

--------
These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the license agreement. While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.
