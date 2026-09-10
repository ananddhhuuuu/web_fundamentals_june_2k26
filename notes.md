### API 
---
```Application programming interface that enables communication bw different applications```


### Webfundamentals
---

## client server architeture
    ```client sends an http request to server, server process the http request and send back http response ```

### http_methods
---
`GET` => fetch all resources  
`POST` => create an new resource  
`PUT` => update a resource  
`PATCH` => UPDATE a resource (partial update)  
`DELETE` => delete a resource  


### http_request_format
---

`url`  
`http_method`  
`Authorization`  
`body`  

### sample api end point
---

```
Employee

id  name    age   department  salary

1   haris    23          hr      25000
2   vipin    23          qa      25000
3   jithn    23          it      25000
4   rahul    23          hr      25000

```

```
http_request for adding employee

url: localhost:8000/employee/
method:POST
body:{
    "name":"vysak",
    "age":24,
    "department":"hr",
    "salary":45000
}



```
---
```
http_request for listing employee

url:localhost:8000/employee/
method:GET

```

---
```
http_request for fetching specific employee detail

url : localhost:8000/employee/4/
method:GET

```

```
http_request for updating an employee 

url:localhost:8000/employee/4/
method:PUT
body:{
    "name":"Rahul",
    "age":24,
    "department":"hr",
    "salary":30000
}

```

```
http_request for deleting  specific employee 

url:localhost:8000/employee/4/
method:DELETE
```

### Movie task

```
Movie

id      title      year     language        run_time


1          kgf1      2008      kannada           160
2          kgf2      2020      kannada           165
3          kgf3      2026      kannada           167
4          kgf4      2028      kannada           168
5          kgf5      2030      kannada           169
```

`http_request for adding new movie`
`http_request for list all movie`
`http_request for fetching movie detail`
`http_request for update movie`
`http_request for delete movie`

```
http_request for adding new movie

url:localhost:8000/movie/
method:POST
body:{
    "title":"kgf6",
    "year":2034,
    "language":"kannada",
    "run_time":170
}
```

```
http_request for list all movie

url:localhost:8000/movie
method:GET

```

```

http_request for fetching movie detail

url:localhost:8000/movie/3
method:GET

```

```
http_request for update movie

url:localhost:8000/movie/4
method:PUT
body:{
    "title":"vikram",
    "year":2022,
    "language":"tamil",
    "run_time":170
}

```

```
http_request for delete movie

url:localhost:8000/movie/2
method:DELETE

```

### Hospital task

```
patients

patient_id    patient_name    phone_number    assigned_doctor    department     appointment_date     status     consultation_fee     

1              indhu          1234567899       dr achu             ent           09-08-2026          completed         600

2              alandhu        3214567890       dr maalavika        dental        11-08-2026          completed         700

3              abeeeih        4321678907       dr subaash          physician     15-08-2026          pending           800

4              musuu          5324167889       dr shaahin          dental        19-08-2026          completed         750

5              yadhu          6748389399       dr krishnan         ent           22-08-2026          pending           800

```

```
http_request for adding new patients

url:localhost:8000/patients/
method:POST
body:{
    "patient_name":"soman",
    "phone_number":6778585890,
    "assigned_doctor":"dr raman",
    "department":"ent",
    "appointment_date":25-08-2026,
    "status":"completed",
    "consultation_fee":"250"
}

```

```

http_request for list all patients

url:localhost:8000/patients/
method:GET

```

```
http_request for fetching patients details

url:localhost:8000/patients/2/
method:GET

```

```
http_request for update patients

url:localhost:8000/patients/3/
method:PUT
body:{
    "patient_name":"rajan",
    "phone_number":6778005890,
    "assigned_doctor":"dr aman",
    "department":"ent",
    "appointment_date":29-08-2026,
    "status":"completed",
    "consultation_fee":"350"
}

```
http_request for delete patients

url:localhost:8000/patients/5/
method:DELETE