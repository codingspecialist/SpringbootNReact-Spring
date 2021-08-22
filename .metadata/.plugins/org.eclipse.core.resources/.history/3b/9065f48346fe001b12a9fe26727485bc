package com.cos.firstapp;

import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;

@RestController
public class BananaController {

	private Banana banana;
	
	public BananaController(Banana banana) {
		this.banana = banana;
	}
	
	@GetMapping("/banana")
	public void 의존성주입테스트() {
		banana.생성();
	}
}
