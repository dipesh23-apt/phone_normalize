# phone_normalize

Normalizing the Phone Numbers present in diiferent different formats by removing any symbols apart from the digits.
<br/>
We use Regular Expression to remove any unwanted characters apart from the digits.
Eg. The numbers can be present in the database as:
    1234567890 <br/>
    123 456 7891 <br/>
    (123) 456 7892 <br/>
    (123)456-7893 <br/>
    123-456-7894 <br/>
    (123)-4567895 <br/>
   After updating the numbers:<br/>
   ![Code_CcTDt7BwkB](https://user-images.githubusercontent.com/80080241/117789326-d92d5580-b265-11eb-9d77-04d52fda7939.png)<br/>
 After the phone_numbers are normalized it get reflected in the postgres database.<br/>
 ![POWERPNT_0opjEFPQ5n](https://user-images.githubusercontent.com/80080241/117789450-fe21c880-b265-11eb-9796-38090acb9850.png)
