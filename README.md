# SIMRide by FYP20-S1-10



**Initial setup**

1. Install Node.js accordingly

2. Install react globally :
    ```
        npm install -g react-native-cli
    ```

3. To install Expo CLI :
    ```
        npm install -g expo-cli
    ```

4. Go to a designated location in your pc (make sure you have access to the repository):
    ```
        sudo git clone https://github.com/xshafqx/Carpool-World.git
        *input your laptop password
    ```

5. Go to your terminal :
    ```
        cd Carpool-World/Carpool-World/Carpool-World
        npm start
        w
    ```



**On your preferred editor, open the Carpool folder**

To create and push your new branch to github :
```
git pull origin
git checkout -b [name_of_your_new_branch]
git push origin [name_of_your_new_branch]
```


To see all the branches :
```
git branch -a
```


To commit changes to remote branch :
```
git status
git add .
git checkout
git commit -m "[your_message]"
git push origin [name_of_your_branch]
```


To switch branch :
```
git checkout [branch_name]
```


**Work progress**

In-Progress | Done
----------- | -----------
**Cancel confirmed ride [Shafiq doing now]** | Connected to Firebase 
**Design the app (UI/UX) [Vinny doing now]** | Registration authentication to Firebase 
Rate the driver and rider | Synced database to Firebase 
E-Wallet page | Logging into SIMRide 
Top-up E-Wallet | Logging out of SIMRide 
Transaction/booking history | Send data to Firebase 
ADMIN: review driver application | Made multiple tabs to act as pages 
Filter - by area/time | Retrieve data from Firebase 
Report user | Edit Profile - Account management 
ADMIN: Ban user (blacklist user) | View Profile - Account management 
Weekly pickup scheduler | Live chat, store chat, select user to chat with 
Automatic route planning (fastest) | View other profiles 
Balance low reminder | Update password - Account management
ADMIN: Audit/log | Stored chat history 
Connect APIs | Retrieving chats
Stripe API | Create a Booking
eNETS Open API | Display list of available rides
MapQuest Directions API | Apply to be driver: upload license image
MapQuest Traffic API | Apply to be driver: add driver details
Remove total from E-Wallet after ride | Join booking
Cash out for drivers | View My Bookings
