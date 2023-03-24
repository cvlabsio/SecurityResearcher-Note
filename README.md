
![image](https://user-images.githubusercontent.com/120234772/227476104-68f94c3d-7ff9-4e69-99fb-f4828486e289.png)


```kql      
// SecurityResearcher-Note : Covering topics
let SecurityResearcher-Note = datatable(id: int, value: string)
[
      1, "Malware analysis", 
      2, "Incident Response", 
      3, "Threat Hunting", 
      4, "New Attack techniques",
      5, "Critical vulnerabilities"
      6, "Kusto Query Language", 
];
SecurityResearcher-Note
| project id, value
```
