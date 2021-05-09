## Available vaccination slot in centers near you (India)
Find vaccination slots near your locality in India. 

Add PINCODES and your Email ID. This piece of code help lets you search fro available COVID vaccination slots in the nearby locality. It uses COWIN public API to search Government database. 


Feel free to use the code , modify it and suggest improvements. 
Write to me at guptanikhil89@gmail.com if you need any help in setting this up with AWS for automated triggers.


Sample output 

{
   "centers":[
      {
         "center_id":647347,
         "name":"DGD Jhatikara",
         "address":"Jhatikara",
         "state_name":"Delhi",
         "district_name":"South West Delhi",
         "block_name":"Not Applicable",
         "pincode":110043,
         "lat":0,
         "long":0,
         "from":"09:00:00",
         "to":"17:00:00",
         "fee_type":"Free",
         "sessions":[
            {
               "session_id":"dce746d7-bfeb-4bd1-8630-e62d9c2b43c4",
               "date":"13-05-2021",
               "available_capacity":0,
               "min_age_limit":45,
               "vaccine":"COVAXIN",
               "slots":[
                  "09:00AM-11:00AM",
                  "11:00AM-01:00PM",
                  "01:00PM-03:00PM",
                  "03:00PM-05:00PM"
               ]
            },
            
        ]
    }  
   ]
}
