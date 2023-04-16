# Paycheck
 if ($Total_Hours_Worked <= 40) {
$Reg_Pay = 40 * $Pay_Rate;
$OT_Pay = 0; }
else {
$Reg_Pay= 40 * $Pay_R#!/usr/bin/perl # your code here
#Declare all variables
my $Pay_Rate;
my $Total_Hours_Worked; my $Reg_Pay;
my $OT_Pay;
my $Total_Pay;
my $Counter;
#Print welcome text
print "Welcome to Paycheck v2.0! This is an optimized version of Paycheck v1.0.This code uses\n less resources, yet performs more work. Specifically, you may now enter a variable pay rate\n for the worker in question. Additionally, this version calculates a biweekly total payment\n for the employee using the specified pay rate for both weeks.\n";
#Ask for employee pay rate
print "Please enter the pay rate for this employee. This hourly pay rate will be\n used to calculate both weeks of the hours worked by this employee.\n Employees can have hourly pay rates that include decimal values and not just\n whole dollar amounts and press Enter:\n";
#Accept user input for $Pay_Rate $Pay_Rate=<>;
print $Pay_Rate;
#Set up for loop
for (my $Counter=1; $Counter<=2; $Counter++)
#Accept input for hours worked
print "Please enter the total hours worked for week number $Counter.\n"; $Total_Hours_Worked = <>;
#Begin if statement ate;

 $OT_Pay=($Total_Hours_Worked - 40; }
$Total_Pay += ($Reg_Pay = $OT_Pay); $Total_Pay = sprintf "%.2f", $Total_Pay;
#print total pay for both weeks
print "The total biweekly pay for this employee is $Total_Pay." }
