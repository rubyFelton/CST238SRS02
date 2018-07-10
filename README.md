# CST238SRS02  
Target Alarm Range  

You've been tasked with creating a mobile UI for an industrial baking oven.  

The app will connect to an oven allowing employees to monitor the oven's state and adjust the oven settings.  

Purpose:  
  - Learn to implement interfield dependencies.  
  - Learn to differentiate between initial and running states.  
  - Learn to handle configuration data.  
  
Specification:  

Create an app that controls an oven's temperature.  

The app will have 3 input temperatures. The maximum, minimum, and target temperature.  The app must also output the current oven temperature.  

If the temperature exceeds the range of inputs, obtain the attention of the user.  

Ensure valid field and form entry for target using the range [200, 500]F or [90, 240]C.  

Your app should handle both Farenheit and Celcius values based upon configuration.  

You may use any method of input/output you want for adjusting set points.  

Consider allowing for multiple input methods.  For example, you may want the user to enter data using an entry field for accurate input and sliders for quick input.  The choice of how to make the input easy, clear, and accurate is a balancing act.  


