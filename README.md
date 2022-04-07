# phase5-3

                           DEPLOYE APPLICATION ON CLOUD
MAIN:
package com.example.demo;

import org.springframework.boot.SpringApplication;
import org.springframework.boot.autoconfigure.SpringBootApplication;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@SpringBootApplication
@RestController
public class SpringBootAwsApplication {
	@GetMapping("/")
	public String home() {
		return "Welcome to AWS First Deployment...     DEPLOY SPRINGBOOT TO AWS";
	}
	public static void main(String[] args) {
		SpringApplication.run(SpringBootAwsApplication.class, args);
	}

}


SPRINGBOOT APPLICATION TEST:
package com.example.demo;

import org.junit.jupiter.api.Test;
import org.springframework.boot.test.context.SpringBootTest;

@SpringBootTest
class SpringBootAwsApplicationTests {

	@Test
	void contextLoads() {
	}

}


