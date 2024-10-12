using System;

class Car
{
    // Fields
    private string make;          // The car's make (e.g., Toyota)
    private string model;         // The car's model (e.g., Corolla)
    
    // Properties
    public string Make            // Public property for make
    {
        get { return make; }
        private set { make = value; }  // Only the constructor can set this property
    }

    public string Model           // Public property for model
    {
        get { return model; }
        private set { model = value; } // Only the constructor can set this property
    }

    // Constructor
    public Car(string make, string model)
    {
        Make = make;   // Set fields through properties
        Model = model;
    }

    // Method to display car information
    public void DisplayInfo()
    {
        Console.WriteLine($"Car Make: {Make}, Model: {Model}");
    }
}

class Program
{
    static void Main(string[] args)
    {
        // Creating an instance of the Car class using the constructor
        Car myCar = new Car("Toyota", "Corolla");

        // Accessing properties through the public method
        myCar.DisplayInfo();  // Output: Car Make: Toyota, Model: Corolla

        // Trying to modify the make and model outside the class will result in a compile-time error
        // myCar.Make = "Honda";  // This will cause an error due to the private setter
    }
}
