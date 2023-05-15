# Postman
Создать запросы в Postman.

Protocol: http
IP: 162.55.220.72
Port: 5005

EP_1
Method: GET
EndPoint: /get_method
request url params: 
 name: str
 age: int

response: 
[
    “Str”,
    “Str”
]

Результат:
![image](https://github.com/DmitryTort17/Postman/assets/131810987/4c86c47b-267d-4d73-a948-641a9b331302)

==================

EP_2
Method: POST
EndPoint: /user_info_3
request form data: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
 'age': age,
 'salary': salary,
 'family': {'children': [['Alex', 24], ['Kate', 12]],
 'u_salary_1_5_year': salary * 4}
}
Результат:
![image](https://github.com/DmitryTort17/Postman/assets/131810987/ffce339a-8899-4992-acb2-c4e9bf95e1ea)


==================

EP_3
Method: GET
EndPoint: /object_info_1
request url params: 
 name: str
 age: int
 weight: int

response: 
{'name': name,
 'age': age,
 'daily_food': weight * 0.012,
 'daily_sleep': weight * 2.5
}
Результат:
![image](https://github.com/DmitryTort17/Postman/assets/131810987/b00f1bd8-0dfb-454f-ab6a-8d3ead30651f)



==================

EP_4
Method: GET
EndPoint: /object_info_2
request url params: 
 name: str
 age: int
 salary: int

response: 
{'start_qa_salary': salary,
 'qa_salary_after_6_months': salary * 2,
 'qa_salary_after_12_months': salary * 2.7,
 'qa_salary_after_1.5_year': salary * 3.3,
 'qa_salary_after_3.5_years': salary * 3.8,
 'person': {'u_name': [user_name, salary, age],
 'u_age': age,
 'u_salary_5_years': salary * 4.2}
}
Результат:
![image](https://github.com/DmitryTort17/Postman/assets/131810987/fe1971e1-a111-48c1-8c3a-1cb619effb72)



==================

EP_5
Method: GET
EndPoint: /object_info_3
request url params: 
 name: str
 age: int
 salary: int

response: 
{'name': name,
'age': age,
'salary': salary,
'family': {'children': [['Alex', 24], ['Kate', 12]],
'pets': {'cat':{'name':'Sunny',
'age': 3},
'dog':{'name':'Luky',
'age': 4}},
'u_salary_1_5_year': salary * 4}
}
Результат:
![image](https://github.com/DmitryTort17/Postman/assets/131810987/663b6ca9-aac3-4c8f-a1a2-4473b137ed6b)



==================

EP_6
Method: GET
EndPoint: /object_info_4
request url params: 
 name: str
 age: int
 salary: int

response: 
{
'name': name,
'age': int(age),
'salary': [salary, str(salary * 2), str(salary * 3)]
}
Результат:
![image](https://github.com/DmitryTort17/Postman/assets/131810987/b7b9eb13-a383-47ef-b684-3dadea154556)


==================

EP_7
Method: POST
EndPoint: /user_info_2
request form data: 
 name: str
 age: int
 salary: int

response: 
{
'start_qa_salary': salary,
'qa_salary_after_6_months': salary * 2,
'qa_salary_after_12_months': salary * 2.7,
'qa_salary_after_1.5_year': salary * 3.3,
'qa_salary_after_3.5_years': salary * 3.8,
'person': {'u_name': [user_name, salary, age],
'u_age': age,
'u_salary_5_years': salary * 4.2}
}
Результат:
![image](https://github.com/DmitryTort17/Postman/assets/131810987/6972bce6-42e4-48ed-8972-2f69061d6ab6)


