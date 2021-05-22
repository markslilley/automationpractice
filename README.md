# automationpractice
This is a Apache JMeter Script created to Performance Test the automationpractice.com website

The script is built to execute three scenarios :-
Contact Form
Create Account and Checkout
Login and Checkout

./jmeter -n -t jmeter/test_plan/CDS_Example_Script.jmx -Jvu=2000 -JDuration=3600 -Jrampup=60 -Jpacing=1020
