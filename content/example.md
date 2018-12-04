## Architecture

De architectuur wordt hieronder uitgelegd.

### Models
Voor elk model maken we een aparte klasse aan.
Bovenaan de klasse definiëren we de verschillende eigenschappen van het model.
Elke eigenschap willen we kunnen opvragen (get) of overschrijven (set).

Voorbeeld:
Een persoon heeft een voornaam, achternaam en leeftijd.
Hierbij is 'persoon' het model. Voornaam, achternaam en leeftijd zijn de eigenschappen die een persoon bezit.



```java
public class Person(){
    private String firstname;
    private String lastname;
    private int age;
    
    public User(String firstName, String lastName, int age){
        this.firstname = firstName;
        this.lastname = lastName;
        this.age = age;
    }
    
    public String getFirstName(){
       return firstname; 
    }
    
    public void setFirstName(String firstName){
        this.firstname = firstName;
    }
    
    public String getLastName(){
        return lastname; 
    }
        
    public void setLastName(String lastName){
        this.lastname = lastName;
    }
    
    public int getAge(){
        return age:
    }
    
    public void setAge(int age){
        this.age = age;
    }
}
```
