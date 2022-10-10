# gitskills
mport java.util.*;
public class SchoolSystem {
 int big;
 int medium;
 int small;
SchoolSystem(int big,int medium,int small){
	this.big=big;
	this.medium=medium;
	this.small=small;
}
boolean addStudent(int stuType) {
	if(stuType==1) {
		if(this.small<30)return true;
		else return false;
	}
	if(stuType==2) {
		if(this.medium<30)return true;
		else return false;
		}
	if(stuType==3) {
		if(this.medium<30)return true;
		else return false;
		}
	return false;
}
String parse(String input) {
	if(input=="SchoolSystem");
	return "true";
}
void print() {;
	print();
}
}
