package com.restapi;

import org.springframework.boot.autoconfigure.SpringBootApplication;

@SpringBootApplication
public class BuilderPatternInJavaApplication {

	public static void main(String[] args) {

	    Student student = Student.Builder.newInstance()
                              .setId(1)
                              .setName("Ram")
                              .setAddress("Noida")
                              .build();
	    System.out.println(student.toString());
	}

}
