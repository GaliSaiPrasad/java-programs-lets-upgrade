# java-programs-lets-upgrade
package day3.a;

import java.util.Scanner;

public class main {
	public static void main(String[] args) {
		Scanner profile = new Scanner(System.in);

		System.out.print("Enter Your Name : ");
		String name = profile.next();

		System.out.print("Enter Your Age : ");
		int age = profile.nextInt();

		System.out.print("Enter Your Date of Birth : ");
		String birthDay = profile.next();

		System.out.print("Enter Your Month of Birth : ");
		int birthMonth = profile.nextInt();

		System.out.print("Enter Your Year of Birth : ");
		int birthYear = profile.nextInt();

		System.out.print("Enter Your Monthly Salary : ");
		int monthlySalary = profile.nextInt();

		System.out.println("Note: Please Enter Salary details if your montly salary is less than or equal to 5Lakhs ");

		if (monthlySalary == 500000) {
			System.out.println("Your Profile : ");
			System.out.println(name);
			System.out.println(age);
			System.out.println("Your Annual Salary is " + monthlySalary * 12);
			System.out.println("Your Tax Based on Your Annual Salary is " + 20 + "%");
		} else if (monthlySalary == 400000) {
			System.out.println("Your Profile : ");
			System.out.println(name);
			System.out.println(age);
			System.out.println("Your Annual Salary is " + monthlySalary * 12);
			System.out.println("Your Tax Based on Your Annual Salary is " + 15 + "%");
		} else if (monthlySalary == 300000) {
			System.out.println("Your Profile : ");
			System.out.println(name);
			System.out.println(age);
			System.out.println("Your Annual Salary is " + monthlySalary * 12);
			System.out.println("Your Tax Based on Your Annual Salary is " + 10 + "%");
		} else if (monthlySalary == 200000) {
			System.out.println("Your Profile : ");
			System.out.println(name);
			System.out.println(age);
			System.out.println("Your Annual Salary is " + monthlySalary * 12);
			System.out.println("Your Tax Based on Your Annual Salary is " + 5 + "%");
		} else {
			System.out.println("Your Profile : ");
			System.out.println(name);
			System.out.println(age);
			System.out.println("Your Annual Salary is " + monthlySalary * 12);
			System.out.println("Your Tax Based on Your Annual Salary is below" + 5 + "%");
		}
	}
}
