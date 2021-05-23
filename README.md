# automationpractice
This is a Apache JMeter Script created to Performance Test the automationpractice.com website
<br />
<br />
<br />
The script is built to execute three scenarios :-<br />
Contact Form<br />
Create Account and Checkout<br />
Login and Checkout<br />
<br />
<br />
<ul>Dependencies</ul><br />
Random CSV Data Set - jmeter-plugins-random-csv-data-set-0.7.jar<br />
Weighted Switch Controller - jmeter-plugins-wsc-0.7.jar<br />
<br />
<br />
Example CLI command for execution<br />
./jmeter -n -t jmeter/test_plan/CDS_Example_Script.jmx -Jvu=2000 -Jduration=3600 -Jrampup=60 -Jpacing=1020 -l results.jtl
