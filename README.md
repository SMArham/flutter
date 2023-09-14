void main() {
  int length = 10; 
  int breadth = 10; 

  if (length == breadth) {
    print('It's a square.'); // Both length and breadth are equal
  } else {
    print('It's a rectangle.');
  }
}



void main() {
  int age1 = 10; 
  int age2 = 20; 

  if (age1 > age2) {
    print('Person 1 is the oldest.');
    print('Person 2 is the youngest.');
  } else if (age2 > age1) {
    print('Person 2 is the oldest.');
    print('Person 1 is the youngest.');
  } else {
    print('Both persons are of the same age.');
  }
}



void main() {
  int classesHeld = 16; 
  int classesAttended = 10; 

  double attendancePercentage = (classesAttended / classesHeld) * 100;

  print('Total classes held: $classesHeld');
  print('Classes attended: $classesAttended');
  print('Attendance Percentage: $attendancePercentage%');

  if (attendancePercentage >= 75) {
    print('The student is allowed to sit in the exam.');
  } else {
    print('The student is not allowed to sit in the exam due to low attendance.');
  }
}



void main() {
  int year = 2000; 

  if ((year % 4 == 0 && year % 100 != 0) || (year % 400 == 0)) {
    print('$year is a leap year.');
  } else {
    print('$year is not a leap year.');
  }
}



void main() {
  double temperature = 42;

  if (temperature < 0) {
    print('Freezing weather');
  } else if (temperature >= 0 && temperature <= 10) {
    print('Very Cold weather');
  } else if (temperature > 10 && temperature <= 20) {
    print('Cold weather');
  } else if (temperature > 20 && temperature <= 30) {
    print('Normal in Temp');
  } else if (temperature > 30 && temperature <= 40) {
    print('It\'s Hot');
  } else {
    print('It\'s Very Hot');
  }
}



void main() {
  String alphabet = 'a'; 

  
  alphabet = alphabet.toLowerCase();

  if (alphabet == 'a' || alphabet == 'e' || alphabet == 'i' || alphabet == 'o' || alphabet == 'u') {
    print('$alphabet is a vowel.');
  } else {
    print('$alphabet is a consonant.');
  }
}





void main() {
  int customerId = 1001;
  String customerName = 'James';
  int unitsConsumed = 800;
  double chargePerUnit;

  if (unitsConsumed <= 199) {
    chargePerUnit = 1.20;
  } else if (unitsConsumed >= 200 && unitsConsumed < 400) {
    chargePerUnit = 1.50;
  } else if (unitsConsumed >= 400 && unitsConsumed < 600) {
    chargePerUnit = 1.80;
  } else {
    chargePerUnit = 2.00;
  }

  double billAmount = unitsConsumed * chargePerUnit;

  print('Customer IDNO: $customerId');
  print('Customer Name: $customerName');
  print('Unit Consumed: $unitsConsumed');
  print('Amount Charges @Rs. $chargePerUnit per unit: ${billAmount.toStringAsFixed(2)}');
  print('Net Bill Amount: ${billAmount.toStringAsFixed(2)}');
}
