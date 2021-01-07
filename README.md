# Lead-Score-Logistic-Regression-
Problem Statement:
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

There are a lot of leads generated in the initial stage, but only a few of them come out as paying customers. In the middle stage, you need to nurture the potential leads well (i.e. educating the leads about the product, constantly communicating etc. ) in order to get a higher lead conversion.

X Education has appointed you to help them select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires you to build a model wherein you need to assign a lead score to each of the leads such that the customers with higher lead score have a higher conversion chance and the customers with lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

Goal:
Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

Data Dictionary:
Variables	Description
Prospect ID	            A unique ID with which the customer is identified.
Lead Number            	A lead number assigned to each lead procured.
Lead Origin           	The origin identifier with which the customer was identified to be a lead. Includes API, Landing Page Submission, etc.
Lead Source	            The source of the lead. Includes Google, Organic Search, Olark Chat, etc.
Do Not Email	          An indicator variable selected by the customer wherein they select whether of not they want to be emailed about the course or not.
Do Not Call	            An indicator variable selected by the customer wherein they select whether of not they want to be called about the course or not.
Converted	              The target variable. Indicates whether a lead has been successfully converted or not.
TotalVisits	             The total number of visits made by the customer on the website.
Total Time Spent on Website	        The total time spent by the customer on the website.
Page Views Per Visit	        Average number of pages on the website viewed during the visits.
Last Activity	Last activity performed by the customer.      Includes Email Opened, Olark Chat Conversation, etc.
Country	        The country of the customer.
Specialization	        The industry domain in which the customer worked before. Includes the level 'Select Specialization' which means the customer had not selected this option while filling the form.
How did you hear about X Education	        The source from which the customer heard about X Education.
What is your current occupation	            Indicates whether the customer is a student, umemployed or employed.
What matters most to you in choosing this course	      An option selected by the customer indicating what is their main motto behind doing this course.
Search	        Indicating whether the customer had seen the ad in any of the listed items.
Magazine	
Newspaper Article	
X Education Forums	
Newspaper	
Digital Advertisement	
Through Recommendations	        Indicates whether the customer came in through recommendations.
Receive More Updates About Our Courses	        Indicates whether the customer chose to receive more updates about the courses.
Tags	        Tags assigned to customers indicating the current status of the lead.
Lead Quality	        Indicates the quality of lead based on the data and intuition the the employee who has been assigned to the lead.
Update me on Supply Chain Content	        Indicates whether the customer wants updates on the Supply Chain Content.
Get updates on DM         Content	Indicates whether the customer wants updates on the DM Content.
Lead Profile	          A lead level assigned to each customer based on their profile.
City	        The city of the customer.
Asymmetrique Activity Index	        An index and score assigned to each customer based on their activity and their profile
Asymmetrique Profile Index	
Asymmetrique Activity Score	
Asymmetrique Profile Score	
I agree to pay the amount through cheque	          Indicates whether the customer has agreed to pay the amount through cheque or not.
a free copy of Mastering The Interview	            Indicates whether the customer wants a free copy of 'Mastering the Interview' or not.
Last Notable Activity	            The last notable acitivity performed by the student.

