## Event Engine 생성 방법(대 고객용 Production Event)

---

1. [EventEngine Admin Page로 이동](https://admin.eventengine.run/dashboard/events) 

2. `Create Event` Click

3. `Program & Blue Print` Page에서 다음처럼 입력하고 `Next Step` Click

   ```
   Program : AWS Default
   Blueprint : Standard Event with IAM
   Blueparint Version : $DEFAULT
   Region : ap-northeast-2
   Associated AWS Workshop Studio Content (optional) : 입력 안함
   ```

   ![image-20220502105022731](images/image-20220502105022731.png)

4. `Event Details` Page에서 다음처럼 입력하고  `Next Step Click`

   ```
   Name : Enterprise Boost Program - 1st Week Workshop
   GEO : APAC
   Event Modality : Virtual
   Type : Production Event
   Internal : Custom Facing
   Event Local Date & Time 
     Date/Time: 2022/5/3 9:00 AM (AM/PM 확인)
     Timezone : GMT+9
   Duration : 15
   
   Engagement Type : Immersion Day
   SFDC Opportunity/Campaign ID : 7014z000001osV4AAI
    
   ```

   ![image-20220502120853727](images/image-20220502120853727.png)

   ![image-20220502120904314](images/image-20220502120904314.png)



5. `Teams and Customers` 에서 다음처럼 입력 후 `Create Event` Click

   ```
   Customer Details
   ---
   Customer Name : Enterprise Boost Program - 1st Week Workshop(60 Accounts)
   Who should be able to join this event? : Allow all
   
   Team Details
   ---
   Number of Teams : 90
   Size of Teams : 1 
   
   Team Name Customizations
   ---
   Allow Team Naming : 체크
   Auto Approve Name Choices : 체크
   
   Surveys
   ---
   Enable Surveys : 체크
   
   ```

   ![image-20220502121201379](images/image-20220502121201379.png)



---

## Event Engine URL 생성 및 공유

---

1. `Export Team Hashes` Click하여 EE Hash URL을 Download

![image-20220502121648288](images/image-20220502121648288.png)

---

2. 경고 창에서 `yes` Click

![image-20220502121710000](images/image-20220502121710000.png)

---

3. Download csv file

![image-20220502121750721](images/image-20220502121750721.png)

---

4. 사용자별로 F열의 `team-hash-login` 주소를 전달

![image-20220502121930338](images/image-20220502121930338.png)

---

5. 각자 생성한 파일을 Event facilitator 에게 전달

---

### !!! 매우 중요 !!!

### 위의 HASH File은 절대 Public Web에 게시하거나 유출이 되어서는 안됩니다. 

### 유출 되서 Abuse가 될 경우 Event Engine을 만든 AWS 직원에게 경고와 함께 Justification 을 요구 할 수 있습니다.

 











