📖 Overview

The main aim of this project is to develop a comprehensive expense calculation system using ServiceNow.
This system helps users to track and manage their family expenses efficiently.
It includes features like expense categorization, budget setting, real-time tracking, and reporting.

Using the ServiceNow platform, this project provides an easy interface and ensures scalability for different family needs.
The goal is to help users make informed financial decisions and promote financial well-being.

Source Video File 

https://u.pcloud.link/publink/show?code=XZsVU95Zr2hXB2iqv3kkODd34igc0XtT9eBy

⚙️ Implementation Steps

Step 1 – Setting up ServiceNow Instance

Signed up for a developer account on the ServiceNow Developer website.

Requested a personal developer instance and received login credentials by email.

Logged into the ServiceNow instance and began configuration.


Step 2 – Creating a New Update Set

Searched for “Local Update Set” in the filter navigator.

Created a new update set named Family Expenses and made it current to store all configurations.


Step 3 – Creating Family Expenses Table

Created a new table called Family Expenses to store main expense details.

Added a new menu named Family Expenditure for easy access.


Step 4 – Adding Columns for Family Expenses Table

Fields created:

Number (String)

Date (Date)

Amount (Integer)

Expense Details (String, max length 800)



Step 5 – Auto-Generating Number Field

Enabled auto-generation for the Number field using “Get Next Padded Number.”

Created a Number Maintenance record with prefix MFE for Family Expenses.


Step 6 – Configuring the Form

Used Form Designer to rearrange fields.

Made the Number field read-only, and Date and Amount fields mandatory.


Step 7 – Creating Daily Expenses Table

Created another table called Daily Expenses under the same menu.

This stores individual daily expense details.


Step 8 – Adding Columns for Daily Expenses Table

Fields created:

Number (String)

Date (Date)

Expense (Integer)

Family Member Name (Reference)

Comments (String, max length 800)



Step 9 – Auto-Number for Daily Expenses

Configured Number field to be auto-generated using “Get Next Padded Number.”

Created a Number Maintenance record with prefix MFE.


Step 10 – Configuring Daily Expenses Form

Rearranged form layout and made Date and Family Member Name mandatory.

Number field set to read-only.


Step 11 – Creating Relationship Between Tables

Established a relationship between Family Expenses and Daily Expenses tables.

This links daily entries with their respective main family expense records.


Step 12 – Configuring Related List

Configured the Family Expenses form to display related Daily Expenses entries by date.


Step 13 – Creating Business Rule

Added a Business Rule to automatically update total amount and expense details in Family Expenses when a new daily expense is added or modified.


Step 14 – Final Relationship Query

Added a relationship query script to filter Daily Expenses records by matching dates with the parent Family Expenses record.


## Screenshots

![Image](https://github.com/user-attachments/assets/65f93583-b8ea-4aa8-baa4-7d0bc656ea85)
![Image](https://github.com/user-attachments/assets/17492fd4-2c92-44ca-851a-0fe565f9d4ef)
![Image](https://github.com/user-attachments/assets/21374cb7-df7f-44f4-9112-1abb8b49ad60)
![Image](https://github.com/user-attachments/assets/b5973e46-3d47-4d36-a520-88704de4a60d)
![Image](https://github.com/user-attachments/assets/299654e4-e58f-4b3a-bbb3-8a54dff332bb)
![Image](https://github.com/user-attachments/assets/2dd43b01-0698-4c51-a3b8-8b52eb54b6e0)
![Image](https://github.com/user-attachments/assets/a2674fcc-fd51-41dc-be7f-4985aa292598)
![Image](https://github.com/user-attachments/assets/a4dde43f-7c8d-4c36-9ab1-c348ad515d71)
![Image](https://github.com/user-attachments/assets/8303daea-9950-415b-b90d-1c0ca3fec47c)
![Image](https://github.com/user-attachments/assets/fa21f205-d750-4f7d-a286-1ee54e102c7d)
![Image](https://github.com/user-attachments/assets/6e96bf04-455b-4369-8dbc-ea036d44bc5a)
![Image](https://github.com/user-attachments/assets/8102ac94-5896-4230-a355-15e41a75ad77)
![Image](https://github.com/user-attachments/assets/902a5a10-69ac-47ce-94eb-79d067c46c81)
![Image](https://github.com/user-attachments/assets/eb7d2612-dc43-4c87-b1b2-a12c04bebf3f)
![Image](https://github.com/user-attachments/assets/0b382309-f5b4-4793-8eb1-571a0a7f4977)


🎥 Project Demo

  https://drive.google.com/file/d/1QBwREnmyJ05jNzaiGI6bfL7UKO3tAfuj/view?usp=drivesdk





✅ Conclusion

This project successfully demonstrates a Family Expense Calculation System built on ServiceNow.
It records daily expenses, calculates totals automatically, and provides clear report views.
By automating expense tracking, this project simplifies financial monitoring for families.




🙌 Acknowledgement

This project was completed under the Muthalvan Program as part of academic learning at Grace College of Engineering, Thoothukudi.
Special thanks to mentors and the ServiceNow Developer Community for guidance and support.




👨‍💻 Author

Our Team Name:
 KRISHNAN K
 ESAKKI PANDI RAJA M
 MANIKANDAN S
 MANIKANDA PRABHU M
 Department: Computer Science and Engineering (CSE)
 College: Grace College of Engineering, Thoothukudi
