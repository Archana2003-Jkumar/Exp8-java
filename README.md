# Exp8-java
Aim:
To code a program that acquires  the properties of other class using inheritence .
## Algorithm:
### Step1:
Import the required packages.

### Step2:
Create a method named animal and bird .

### Step3:
Using inheritence extend the animal method from bird class. 

### step4: 
Then display the result.
## Code:
```
1.Main class :
```
```
public class Main {
    public static void main(String[] args) {

        bird brd = new bird();
        brd.walk();
        brd.fly();
        brd.sng();
    }
}
```
```
2.Bird class :
```
```
class bird extends Animal {
    void fly() {
        System.out.print("I am flying ");
    }
    void sng() {
        System.out.print("I am Singing");
    }
}
```
```
3.Animal class :
```
```
class Animal{
    void walk(){
        System.out.println("I am walking");
    }
}

```
## Output:
![image](https://github.com/Archana2003-Jkumar/Exp8-java/assets/93427594/3504b92e-50ae-48b9-bd48-fbd06345b82f)

## Result:
Hence the program has been successfully executed.
