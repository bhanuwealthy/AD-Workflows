## How use Travel Insurance before getting E-id?


```mermaid 
sequenceDiagram
    autonumber
    participant Hospital
    participant You
    participant InsuranceTeam
    
    
    You->>InsuranceTeam: Need help, emergency! Pls Send a request to nearest hospital in <your> location.
    
    
    InsuranceTeam->>You: Identifies nearest hospital, sends the nearest 2 or 3 hospital names
    

    You->>InsuranceTeam: <Hospital name> is the nearest to me.
    
    
    InsuranceTeam-->>Hospital: Pls accept this person for emrgency treatment!

    You->>Hospital: Visit and show the cc'ed email from Insurance.
    
    
    Hospital-->>InsuranceTeam: Confirms by phone/email.
    
    Hospital-->>You: Accepts & allows for treatment.
    rect rgb(191, 223, 255)
      Note right of You: Consult a doctor & rest of the hospital procedures.
    end

```

---

### @Burjeel 

Points to note:
- They will accept NextCare insurance, regular type.
- But they do not accept the `Travel Insurance` (sub category within NextCare)

```
Conclusion:
 Hospital & Insurance talked to each other & you, they both will agreed on a common point to 
 Pay the bill by patient and reimburse it later.
 ```
 
 ---

### @NMC


`GOP = Gaurantee of Payment letter`

```mermaid


graph LR
    A[Hospital] -- Pls send the GOP letter in addition to requested e-mail. --> B[Insurance]
    B -- Start the treatment and give the bill, we'll provide GOP--> A
    
```

```
Conclusion: Never ending loop.
 Hospital & Insurance talked to each other & you, they both will agreed on a common point to 
 Pay the bill by patient and reimburse it later.
 ```
 
 --- 
 
 ### Insurance claim process
 ```mermaid
 flowchart LR
 
    A[You send the original bill & docs] --> B[Insurance Evaluates] --> C[Reimburse]
 ```
 
 ```
Conclusion: No Guarantee you will get all the amount.
 
 ```
 
 
