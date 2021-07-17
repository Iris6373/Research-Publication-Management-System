# Research-Publication-Management-System
* Research Publication Management system is developed to automate the task of receiving the user’s work and publishing the same by the approval of reviewers and editors.
JOURNAL HUB

# JOURNAL PUBLICATION SYSTEM 



## CONTENTS
- DESCRIPTION
- MODFICATIONS TO BE DONE
- USERNAMES AND PASSWORDS
- FLOW OF THE PROJECT
- SUMMARY



## DESCRIPTION
Using journal hub, the users(authors) can submit their journals on our website. The Editor can then view their journals and based on their work he can either approve it or disapprove it.
If Editor approves the author's journal, he can select any reviewers from the list of Reviewers who have been added by admin(directly to the database), those reviewers can view the journal
and can approve or disapprove the author's work. Anyone reviewer can approve or disapprove of the author's work. If anyone of the reviewers approves the author's journal then the author 
and editor receive an email that the author's journal has been accepted and approved. If it is disapproved then the author and editor receive an email that the author's work has been 
disapproved.
If Editor disapproves, then the author's work is directly disapproved and an email is sent to the author.
This Project help the authors to evaluate their work and know the opinions of editors and reviewers.



## MODIFICATIONS TO BE DONE
To use the email feature, modifications are required to be done in 'php.ini' and 'sendmail.ini' files.
To Make changes and Updates please refer the below link: 
	https://www.youtube.com/watch?v=9W644cyDyNM


## FLOW OF THE PROJECT
First, start with index.html from where we can navigate to all other pages.
Next, one can view sample journal given in homepage(index.html) or can signup/signin through their credentials.
Suppose if you are a new author than you can use signup Page and then Login using your Credentials, else log in directly usin valid username and password.
Then Author can either update his information or can submit his work or view the status of already submitted work.
If Author chooses to submit his work he can click on 'submit Manuscript' and then he can enter all the details and submit his 'pdf' file.
The Details and the submitted file is merged and sent to author's email and then he can logout.
Now, Editor can login and view all the files with 'Pending' status. Also, he can view the merged files in the 'Files to be checked' section. Then if he chooses to disapprove this file then the work of that respective author 
is directly disapproved and an email will be sent to the author notifying that his work has been rejected by the Editor. 
If Editor Approves then he can assign the reviewers for the author's work in Reviewers to be assigned and then he can log out of the system.
Then Reviewer can log in, if editor assigned that reviewer to check that work of author than he can check the work and either approve or disapprove the work, the editor and author will 
recieve an email regrading the Reviewers decision.At the end if anyone of reviewer approve the work of author gets approved and if anyone of the reviewers disapproves then file is dispproved.
The first reviewer to review the file can make this decision as we want the results to be as fast as possible.
Then the author can see how many of his works are approved or disapproved in his page and he will also be notified in the email.




## SUMMARY
- Please use valid email if you want to recieve mail
- General Flow: 
	SignUp->Login(Author)->Submit Manuscript->Upload File->Logout(Author)->Editor Login->Editor Approve/Disapprove
	-->>Editor Disapprove->Author's Work Disapproved->Mail Notified to author that his work is disapproved and changed in file status of the author.
	-->>Editor Approve->Select Reviewers->Logout(Editor)
		--->>>Reviewers(Login)->File Approve/Disapprove->Author and Editor is notified of the result.

# THANK YOU
