## How to Create a Batch Program

A batch is created when a customer would like to view and work with a list of flitered items. For testing and development, we will create a Q0# batch. 

In this example, we will be gathering a list of products that have a lead time greater than 30 days. 

### Copy and Paste

First, go to the development library (5DEV). There, copy the K3S_3Q01, which will be the outline program, found in the QRPGLESRC file from the 5MOD library and paste it into 5DEV.

<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-26 at 9.28.05 AM.png" width="600px" />

</p>

<p align="center">
  <img src="{{site.baseurl}}/Screen Shot 2020-02-26 at 9.33.34 AM.png" width="600px" />

</p>


This will prompt the CPYSRCF. This is a way to make sure the information is correct. Once viewed, click OK.


<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-26 at 9.38.29 AM.png" width="600px" />

</p>


### Edit the Program 

Edit the program as needed. In this batch, we will take any product that has a lead time greater than 30 days using fields found in the K_Product PF.

<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-26 at 10.03.12 PM.png" width="600px" />
                                                                                  
</p>

Once finished, be sure to edit any text documentation within the program. 


### Compile

Now we are ready to compile!

Right click on the program and compile prompt. Here, there will be an option to view advanced options. Be sure to have the correct Target Release option picked. 


<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-26 at 10.26.53 PM.png" width="600px" />
                                                                           
</p>

<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-26 at 10.31.13 PM.png" width="600px" />
  
</p>

Once attempting to compile, check the Commands log for any errors. 


### Test 

Log into R6, and click on "Batches" and then "Create Batch". There, choose the batch that was just programmed. Once it has finished running, check to make sure all data is correct. 

<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-27 at 10.46.03 AM.png" width="600px" />
  
</p>


### Data Check

In Access Client Solutions, run an SQL script to check your data. 

<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-27 at 11.12.39 AM.png" width="600px" />
  
</p>

<p align="center">

<img src="{{site.baseurl}}/Screen Shot 2020-02-27 at 11.10.59 AM.png" width="600px" />
  
</p>





