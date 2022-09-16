package oop;

public class temperature {
	public static void main(String[] args) {
		
		int Fahrenheit, Celsius;  
		
        Celsius = 37;  
        Fahrenheit = ((Celsius*9)/5)+32; 
        //13 x 9 =117   
        //117 / 5 = 23.4
        //55.4
        System.out.println("Celcius is: " + Celsius);
        System.out.println("Temperature in Fahrenheit is: " + Fahrenheit); 
	}
}
