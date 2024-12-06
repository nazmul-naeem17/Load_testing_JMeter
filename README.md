# Load_testing_JMeter
Here I have tested 𝐧𝐞𝐰 𝐦𝐞𝐦𝐛𝐞𝐫 𝐥𝐨𝐠𝐢𝐧 𝐫𝐞𝐪𝐮𝐞𝐬𝐭 𝐢𝐧 𝐃𝐚𝐫𝐚𝐳 𝐰𝐞𝐛𝐬𝐢𝐭𝐞.</br>
#𝐂𝐫𝐞𝐚𝐭𝐞 𝐚 𝐓𝐞𝐬𝐭 𝐏𝐥𝐚𝐧</br>
Open JMeter.
Go to File > New to create a new test plan.</br>
#𝐀𝐝𝐝 𝐚 𝐓𝐡𝐫𝐞𝐚𝐝 𝐆𝐫𝐨𝐮𝐩</br>
Right-click on the Test Plan in the left tree panel.
Navigate to Add > Threads (Users) > Thread Group.</br>
𝐂𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐭𝐡𝐞 𝐭𝐡𝐫𝐞𝐚𝐝 𝐠𝐫𝐨𝐮𝐩:</br>
Number of Threads (Users): Number of virtual users. Here I have taken 100 𝙪𝙨𝙚𝙧𝙨.</br>
Ramp-Up Period (seconds): Time to start all threads. And here it is 1000𝙨𝙚𝙘.</br>
Loop Count: Number of times each user will execute the test. Here is 1.</br>
𝘈𝘥𝘥 𝘢 𝘚𝘢𝘮𝘱𝘭𝘦𝘳</br>
Right-click on the Thread Group.
Navigate to Add > Sampler > HTTP Request.</br>
Configure the sampler:</br>
Server Name or IP: The target server.
Path: The endpoint you want to test.</br>
𝘼𝙙𝙙 𝙇𝙞𝙨𝙩𝙚𝙣𝙚𝙧𝙨</br>
Right-click on the Thread Group (or Test Plan).
Navigate to Add > Listener, then select one or more listeners to visualize results:</br>
View Results Tree</br>
Summary Report</br>
Aggregate Report</br>
#𝐑𝐮𝐧 𝐭𝐡𝐞 𝐓𝐞𝐬𝐭</br>
Save your test plan (File > Save As).
Click the Start button (green triangle) on the toolbar.
Monitor results in the selected listeners.</br>
#𝐀𝐧𝐚𝐥𝐲𝐳𝐞 𝐑𝐞𝐬𝐮𝐥𝐭𝐬</br>
Open the Aggregate Report or Summary Report for performance metrics:
Throughput: Number of requests per second.
Average Response Time: Average time taken for requests.
Error Percentage: Percentage of failed requests.
Max Response Time: Maximum time taken for any request.
