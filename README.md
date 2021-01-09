# Lab_9
public class Car {
    private String model;
    private int numDoors;
    private Boolean fullTime; 
    public Car(){
        super();
        model=""; 
        numDoors=4;
        fullTime=false;
    }
    public Car(String firma, int speed, String name, int n, Boolean f){
        super(firma, speed);   
        model=name; 
        numDoors=n;
        fullTime=f;
    }
   public static void main(String[] args) {
GarageCar myGarage=new GarageCar(); //создаем новый гараж
Car myCar1=new;
myGarage.addCar(myCar1); 
myGarage.printGarage(); 
if (myGarage.findCar(myCar1)) { 
System.out.println("Да");
}
else {
System.out.println("Нет");
}
}
}
