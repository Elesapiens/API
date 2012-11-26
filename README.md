API
===

This is THE official API of the ELESAPIENS PLATAFORM which allow users to connect and get the contents by **REST**
this api has 2 branches **DATA METHODS** and **CONTENT METHODS** (created by [Raphadareangel](https://github.com/raphadareangel) [website](https://www.raphadareangel.com))
# Data Methods


from this methods you can get data wich compose our resources to create your own front

##elelogin

this method aloud to connect with plataform is tehe principal state the connection to the plataform

**PARAMETERS**

    user: String Format

    pass: String Format

**RETURN VALUE**
* **SUCCESS**

      ``user_id: String format``

* **FAILED**

      string with value "failed"


**CONNECTION TYPE**

    GET: only for derteminate time (2 Moths)

    POST

**RESPONSE FORMAT**

    XML
    HTML
    JSON

##eleprofile

this method aloud to get user profile data

**PARAMETERS**

    user: String Format

    pass: String Format

    user_id: INT(16)

**RETURN VALUE**
* **SUCCESS**

    user_id: String format

* **FAILED**

    string with value "failed"


**CONNECTION TYPE**

    GET: only for derteminate time (2 Moths)

    POST


**RESPONSE FORMAT**

    XML
    HTML
    JSON

##eleunit

this method aloud to get unit data

**PARAMETERS**

    user: String Format

    pass: String Format

    user_id: INT(16)

**RETURN VALUE**
* **SUCCESS**

    user_id: String format

* **FAILED**

    string with value "failed"


**CONNECTION TYPE**

    GET: only for derteminate time (2 Moths)

    POST

**RESPONSE FORMAT**

    XML
    HTML
    JSON


##elelibrary

this method aloud to get library data

**PARAMETERS**

    user: String Format

    pass: String Format

    user_id: INT(16)

**RETURN VALUE**
* **SUCCESS**

    user_id: String format

* **FAILED**

    string with value "failed"


**CONNECTION TYPE**

    GET: only for derteminate time (2 Moths)

    POST

**RESPONSE FORMAT**

    XML
    HTML
    JSON


# Content Methods

from this methods you can get access to our contents and we will provide our front

##eleresource

this method aloud to connect with plataform is tehe principal state the connection to the plataform

**URL**

    http://www.elesapiens.com:8080/eleresource/eleresource
    
**EXAMPLE**
    GET
    
    http://www.elesapiens.com:8080/eleresource/eleresource?user=xxxx&pass=xxxx&user_id=1

   

**PARAMETERS**

    user: String Format

    pass: String Format
    
    id_resource: String Format

**RETURN VALUE**
* **SUCCESS**
      
    HTML

* **FAILED**

    HTML ERROR


**CONNECTION TYPE**

    GET: only for derteminate time (2 Moths)

    POST  

**RESPONSE FORMAT**

    
    HTML
    

##eleunitfront

this method aloud to get user profile data

**URL**

    http://www.elesapiens.com:8080/eleunitfront/eleunitfront
    
**EXAMPLE**
    GET
    
    http://www.elesapiens.com:8080/eleunitfront/eleunitfront?user=xxxx&pass=xxxx&unit_id=1

**PARAMETERS**

    user: String Format

    pass: String Format

    unit_id: INT(16)

**RETURN VALUE**
* **SUCCESS**
      
    HTML

* **FAILED**

    HTML ERROR


**CONNECTION TYPE**

    GET: only for derteminate time (2 Moths)
    POST

**RESPONSE FORMAT**

    
    HTML
    

##elelibraryfront

this method aloud to get unit data
**URL**

    http://www.elesapiens.com:8080/elelibraryfront/elelibraryfront

**EXAMPLE**
    GET
    
    http://www.elesapiens.com:8080/elelibraryfront/elelibraryfront?user=xxxx&pass=xxxx4&user_id=1

**PARAMETERS**

    user: String Format

    pass: String Format

    user_id: INT(16)

**RETURN VALUE**
    * **SUCCESS**
        HTML

    * **FAILED**

        HTML ERROR


**CONNECTION TYPE**

    GET: only for derteminate time (2 Moths)

    POST

**RESPONSE FORMAT**

    
    HTML
    


