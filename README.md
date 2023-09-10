## **Limit Zero Chat**

This is a minimalist chat app, build for you one on one one-on-one chat or group chat.

Features Bullet points

*   Users shall register with their emails and username
*   A verification email with a verification link will be sent to the user.
*   When verification is done, the user can share a created session with a topic and description.
*   Every chat session will have a link and anyone with the link can join the chat if the session is made public.
*   When the chat is made private, the creator will need to add people's email if he wants to have access to the chat.
*   A chat session can be made public to allow users in, then made private to restrict new users.
*   A chat session can be closed/ended and everyone in the chat will have access to the chat but won't be able to send messages.

User  
    - Email  
    - username  
    - token

Chat session  
    - chatName  
    - chatDescription  
    - creator

Chat session members  
    - userid  
    - username  
    - user email  
    - is\_boss

Chat session settings  
    - session\_door = OPEN | CLOSE  
    - is\_archieved = FALSE | TRUE

Chat content  
    - session\_id  
    - member\_id  
    - content\_type = TEXT | LINK | Media

Chat content data  
    - chat\_content\_id  
    - text\_value  
    - link\_value  
    - media\_location
