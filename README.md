# AI_generate_music  
I use 3 different kind of neural network to generate piano music and compare their differences. Moreover, you can also download youtube playlists as your dataset. However, the outcomes aren't very good becuase the audio_to_midi can't convert the mp3 to mid well.  
  
My environment:  
Windows 11  
Create environments in Anaconda  
Python 3.8.16  
CudaToolkit 11.2  
cudnn=8.1.0  
fluidsynth 2.2.4  
You can check this websites for details: https://leytton.blog.csdn.net/article/details/130383893?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2~default~CTRLIST~Rate-1-130383893-blog-128860443.235%5Ev36%5Epc_relevant_default_base3&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2~default~CTRLIST~Rate-1-130383893-blog-128860443.235%5Ev36%5Epc_relevant_default_base3&utm_relevant_index=2&ydreferer=aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0VqenExL2FydGljbGUvZGV0YWlscy8xMjg4NjA0NDM%2Fc3BtPTEwMDEuMjEwMS4zMDAxLjY2NjEuMSZ1dG1fbWVkaXVtPWRpc3RyaWJ1dGUucGNfcmVsZXZhbnRfdDAubm9uZS10YXNrLWJsb2ctMiU3RWRlZmF1bHQlN0VDVFJMSVNUJTdFUmF0ZS0xLTEyODg2MDQ0My1ibG9nLTEyOTEzMTI3OC4yMzUlNUV2MzYlNUVwY19yZWxldmFudF9kZWZhdWx0X2Jhc2UzJmRlcHRoXzEtdXRtX3NvdXJjZT1kaXN0cmlidXRlLnBjX3JlbGV2YW50X3QwLm5vbmUtdGFzay1ibG9nLTIlN0VkZWZhdWx0JTdFQ1RSTElTVCU3RVJhdGUtMS0xMjg4NjA0NDMtYmxvZy0xMjkxMzEyNzguMjM1JTVFdjM2JTVFcGNfcmVsZXZhbnRfZGVmYXVsdF9iYXNlMyZ1dG1fcmVsZXZhbnRfaW5kZXg9MQ%3D%3D&fbclid=IwAR0zi4N6KefOTJL0fWzo4-5R1Drv9ZCnE6MLL8o6OPQhAsJMiDHjLukxV-Q&ydreferer=aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L0VqenExL2FydGljbGUvZGV0YWlscy8xMjg4NjA0NDM%2Fc3BtPTEwMDEuMjEwMS4zMDAxLjY2NjEuMSZ1dG1fbWVkaXVtPWRpc3RyaWJ1dGUucGNfcmVsZXZhbnRfdDAubm9uZS10YXNrLWJsb2ctMiU3RWRlZmF1bHQlN0VDVFJMSVNUJTdFUmF0ZS0xLTEyODg2MDQ0My1ibG9nLTEyOTEzMTI3OC4yMzUlNUV2MzYlNUVwY19yZWxldmFudF9kZWZhdWx0X2Jhc2UzJmRlcHRoXzEtdXRtX3NvdXJjZT1kaXN0cmlidXRlLnBjX3JlbGV2YW50X3QwLm5vbmUtdGFzay1ibG9nLTIlN0VkZWZhdWx0JTdFQ1RSTElTVCU3RVJhdGUtMS0xMjg4NjA0NDMtYmxvZy0xMjkxMzEyNzguMjM1JTVFdjM2JTVFcGNfcmVsZXZhbnRfZGVmYXVsdF9iYXNlMyZ1dG1fcmVsZXZhbnRfaW5kZXg9MQ%3D%3D  
  
If you want to download youtube music online, you should pay attention for the following details !!  
Some libraries you need to pay attention:  
pip install youtube2midi  
pip uninstall youtube-dl    #The latest version can't be used !!  
pip install youtube-dl==2020.12.9   #Please download this version !!  
