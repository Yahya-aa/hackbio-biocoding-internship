# hackbio-biocoding-internship # Group Members Classification

#This Python script defines a dictionary containing details of my group members and prints their information in an organized manner.

## Overview
#The script organizes data about members of my group, including their:
- Full names
- Slack usernames
- Email addresses
- Hobbies
- Country
- Preferred programming language

#Each group member's details are stored in a dictionary format for clarity and easy access. Using Python's `print` function, the script outputs each member's details in a well detailed and understandable manner.

## Structure
The script defines the data as a nested dictionary:
- Each key represents a member's identifier (e.g., "Yahya","Qanitat","Chinenyenwa","Omodara","Gbolahan","Deborah").
- Each value is another dictionary holding the details of the member.

### Dictionary code using python
Group_Members_Classification = {
"Yahya": {
    "Name": "Yahya Abdulrahman Babatunde",
    "Slack_username": "Yahya",
    "Email": "yahya.ope247@gmail.com",
    "Hobby": "Practically_nothing",
    "Country": "Nigerian",
    "Preferred_Programming_Language": "Python"
},
"Qanitat": {
    "Name": "Akinade Qanitat Adedoyinmola",
    "Slack_username": "Qanitat",
    "Email": "qanitatadedoyinmola@gmail.com",
    "Hobby": "sleeping",
    "Country": "Nigerian",
    "Preferred_Programming_Language": "Python"
},
"Chinenyenwa": {
    "Name": "Chinenyenwa Mba Oji", 
    "Slack_username": "Chinenyenwa",
    "Email": "mbaojichinenyenwa@gmail.com",
    "Hobby": "African_Fiction",
    "Country": "Nigerian",
    "Preferred_Programming_Language": "Python"
},
"Omodara": {
    "Name": "Ayomide Omodara Boluwatife", 
    "Slack_username": "Omodara",
    "Email": "ayoboluomodara@gmail.com",
    "Hobby": "Baking",
    "Country": "Nigerian",
    "Preferred_Programming_Language": "Python"
},
"Gbolahan": {
    "Name": "Adegboye Gbolahan", 
    "Slack_username": "Gbolahan",
    "Email": "adegboyegbolahan225@gmail.com",
    "Hobby": "Listening to music",
    "Country": "Nigerian",
    "Preferred_Programming_Language": "Python"
},
"Deborah": {
    "Name": "Olatosin Deborah", 
    "Slack_username": "Deborah",
    "Email": "deborah@gmail.com",
    "Hobby": "Baking",
    "Country": "Nigerian",
    "Preferred_Programming_Language": "Python"
}
}
print(Group_Members_Classification["Yahya"])
print(Group_Members_Classification["Qanitat"])
print(Group_Members_Classification["Chinenyenwa"])
print(Group_Members_Classification["Omodara"])
print(Group_Members_Classification["Gbolahan"])
print(Group_Members_Classification["Deborah"])

### OUTPUT
{'Name': 'Yahya Abdulrahman Babatunde', 'Slack_username': 'Yahya', 'Email': 'yahya.ope247@gmail.com', 'Hobby': 'Practically_nothing', 'Country': 'Nigerian', 'Preferred_Programming_Language': 'Python'}
{'Name': 'Akinade Qanitat Adedoyinmola', 'Slack_username': 'Qanitat', 'Email': 'qanitatadedoyinmola@gmail.com', 'Hobby': 'sleeping', 'Country': 'Nigerian', 'Preferred_Programming_Language': 'Python'}
{'Name': 'Chinenyenwa Mba Oji', 'Slack_username': 'Chinenyenwa', 'Email': 'mbaojichinenyenwa@gmail.com', 'Hobby': 'African_Fiction', 'Country': 'Nigerian', 'Preferred_Programming_Language': 'Python'}
{'Name': 'Ayomide Omodara Boluwatife', 'Slack_username': 'Omodara', 'Email': 'ayoboluomodara@gmail.com', 'Hobby': 'Baking', 'Country': 'Nigerian', 'Preferred_Programming_Language': 'Python'}
{'Name': 'Adegboye Gbolahan', 'Slack_username': 'Gbolahan', 'Email': 'adegboyegbolahan225@gmail.com', 'Hobby': 'Listening to music', 'Country': 'Nigerian', 'Preferred_Programming_Language': 'Python'}
{'Name': 'Olatosin Deborah', 'Slack_username': 'Deborah', 'Email': 'deborah@gmail.com', 'Hobby': 'Baking', 'Country': 'Nigerian', 'Preferred_Programming_Language': 'Python'}

#Output shows the details of each of my group members in a well readable and understandable manner

