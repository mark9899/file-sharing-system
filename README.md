File_Sharing_System A secure file-sharing system between two different types of users

Create a secure file-sharing system between two different types of users. For implementation - You need to create REST API’s for the following action. User 1: Operation User Action which could be done by an Ops User

Login
Upload File*
Only Ops User is allowed to upload pptx,docx and xlsx * Upload file must be only of pptx,docx, and xlsx type User 2: Client User Action which could be done by a Client User
Sign Up ( Return an encrypted URL )
Email Verify ( Verification Email will be sent to the user on the registered email )
Login
Download File
List all uploaded files Important Information ● You need to make sure when a person hits download API a secure encrypted URL is sent in response through which the file can be downloaded. ● This URL can be accessed only by a client user. ● If any other user tries to access it the URL access would be denied to that user.
Example- Client User Hits API- /download-fle/{{Assignment ID}} Response - {

“download-link” : “..../download-fle/moiasnciaduasnduoadosnoadaosid”, “message” : “success” }
