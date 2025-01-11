# student-record-using-access-modifier-constructor-and-method
Public class StudentRecords {
Public String name;
String division;
private int age;
public StudentRecords(String sname) {
name = sname;
}

public void setDivision(String sdiv) {
division = sdiv;
}
public void setAge(int sage) {
age = sage;
}
Public void printStudent() {
System.out.println(&quot;Student Name: &quot; + name);
System.out.println(&quot;Student Division: &quot; + division);
System.out.println(&quot;Student Age: &quot; + age);
}
Public static void main(String[] args) {
StudentRecords student = new StudentRecords(&quot;John&quot;);
student.setDivision(&quot;A&quot;);
student.setAge(18);
student.printStudent();
}
}
OUTPUT:
Student Name: John
Student Division: A
Student Age: 18
