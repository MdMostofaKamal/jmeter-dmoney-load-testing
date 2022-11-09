# jmeter-dmoney-load-testing
 This is a Jmeter Project where the DmoneyAPI is tested by creating test cases for Login , Creating users , Searching users and also performing Update and Delete operations. The ramp-up and the number of threads were kept as 1.Here login credentials can also be used from the csv file without explicitly writing it in the body.
 Steps to run this project:
 - Clone this project or download the .jmx file in the project directory
 - You can generate your own HTML summary report by running the following code in the terminal:
 
 ```
 jmeter -n -t Dmoneyapi.jmx -l Dmoney.csv -e -o Reports
  ```
  
  ![JMeter command](https://user-images.githubusercontent.com/47362218/200831876-fa2b482e-dc53-4974-a418-bbc8809ef54b.PNG)

  
 ## Dmoney project structure in Jmeter
  
  ![Dmoney whole Project Structure](https://user-images.githubusercontent.com/47362218/200823286-99674b13-b022-4d7c-84bd-81b86df50858.PNG)

## All test cases are passed that viewed from Jmeter view result tree

![All test cases are passed that can be viewd from jmeter result tree](https://user-images.githubusercontent.com/47362218/200823719-5e66920d-9858-472c-a6e8-f6ffc61b729a.PNG)

## Summary report in Jmeter

![Summary report](https://user-images.githubusercontent.com/47362218/200823981-3758c389-85b0-4189-8f0c-b651d35929c6.PNG)

## jmeter Generated Html reports

![jmeter generated html report ](https://user-images.githubusercontent.com/47362218/200824471-8b78973e-fe4a-4ed9-934d-99d2c6232f3a.png)
