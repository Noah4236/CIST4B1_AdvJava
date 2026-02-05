# CIST4B1_AdvJava
A repository to document my Java learning journey

About Me:
My name is Noah. I've been coding since middle school, and it's something I've always enjoyed. That being said, everything I did before college was pretty simple compared to what I learned recently. I want to transfer for SJSU for software engineering, and I'm hoping this class can help me with that.

Goals for This Course:
I want to get a better understanding of the coding process in general, but I also want to get better understanding of more specific things related to syntax and formatting. For example, I learned recently that there can only be one public class in a file. I want to gain a better understanding of things like that, because even if I am able to read and write code well, specific issues like that still trip me up. And of course, I want to build on the knowledge I already have from the advanced topics in this course.

In-Class Java Coding Warm Up
First class inheritance activity

	public class InheritanceTest {
		public static void main(String[] args) {
			Class2 test = new Class2();
			test.printA();
		}
	}

	public class Class1 {

		private int a;
		public Class1() {
			a = 10;
		}
		public void printA() {
			System.out.println(a);
		}
	}

	public class Class2 extends Class1{
		public Class2() {
			super();
		}
	}
