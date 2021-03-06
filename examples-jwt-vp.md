## Examples

Verifiable Credentials with JSON Web Tokens:

### Example Verifiable Presentation

	eyJhbGciOiJSUzI1NiJ9.eyJqdGkiOiJ1cm46dXVpZDphZWNkYThmZi1iOTQ4LTRlYmItYTBhZS02NDRiMzFlZjczYzgiLCJpc3MiOiJkaWQ6c292OjIxdERBS0NFUmg5NXVHZ0tiSk5IWXAiLCJpYXQiOjE1NjMxOTU5NzEsIm5iZiI6MTU2MzE5NTk3MSwidnAiOnsiQGNvbnRleHQiOlsiaHR0cHM6Ly93d3cudzMub3JnLzIwMTgvY3JlZGVudGlhbHMvdjEiXSwidHlwZSI6WyJWZXJpZmlhYmxlUHJlc2VudGF0aW9uIl0sInZlcmlmaWFibGVDcmVkZW50aWFsIjpbImV5SmhiR2NpT2lKU1V6STFOaUo5LmV5SnFkR2tpT2lKMWNtNDZkWFZwWkRwaE9EZGlaR1ppT0MxaE4yUm1MVFJpWkRrdFlXVXdaQzFrT0Rnek1UTXpOVE00Wm1VaUxDSnpkV0lpT2lKa2FXUTZjMjkyT2pJeGRFUkJTME5GVW1nNU5YVkhaMHRpU2s1SVdYQWlMQ0pwYzNNaU9pSmthV1E2YzI5Mk9qRjVkbGhpYldkUWIxVnROR1JzTmpaRU4wdG9lVVFpTENKdVltWWlPakUxTmpBM01URTBNVGtzSW1WNGNDSTZNVFUyTURjNU56Z3hPU3dpZG1NaU9uc2lRR052Ym5SbGVIUWlPbHNpYUhSMGNITTZMeTkzZDNjdWR6TXViM0puTHpJd01UZ3ZZM0psWkdWdWRHbGhiSE12ZGpFaUxDSm9kSFJ3Y3pvdkwzUnlZV1pwTG1acEwyTnlaV1JsYm5ScFlXeHpMM1l4SWwwc0luUjVjR1VpT2xzaVZtVnlhV1pwWVdKc1pVTnlaV1JsYm5ScFlXd2lMQ0pFY21sMlpYSnpUR2xqWlc1elpVTnlaV1JsYm5ScFlXd2lYU3dpWTNKbFpHVnVkR2xoYkZOMVltcGxZM1FpT25zaVpISnBkbVZ5YzB4cFkyVnVjMlVpT25zaWJHbGpaVzV6WlVOc1lYTnpJam9pZEhKMVkydHpJbjE5ZlgwLlpkSnhNMGtKYWtLQWZKSTJoM0RodmZfQUhVZ0M4LU55UVJyMkRNbmx6Q3hIWnlWRWppMHM1U2w4Y054NmFQd3dqRGFncDJLSEZ5Nk05ZU9OSHJycGRiNDlBdUtldHlKWlFVb0I1YVFnLXNDNUdNSFBWeWVUeHphemFEV3lzRWlDWlNYYzZHY2lyTERtSFhWV01VaWRLRGxHaDh2ZFV0ckhSMGF5VmJ4clhRLXpLYWtmbHRhUmF3UTRPSVJQSi0wZnNzb2pTRGJSTzZLbnJINk1RYnNsLWZ3VFJjWW5saWhOSUhwTlRFcFQ2OERBM1F6SFUxLVRBWDF4WTNKeDJ2WW9yaWhGZjAybW5uNWQzZ1c0R3YyS3NOYk5wZXdJQW1mTC1wLWFiT0ZObXQyY0x4RlVTTHNnYUU1dXBEdzJ4QUdUYzNsQXh2Yko3R200ZWFMOFNYVFEyQSJdfX0.e-5OGe4zboXBB5csM1is4oJVgsJT_GIcJvwU50gpLQKwva35gMY0ivbfv3WZx03vMMvByaJN-_XYhDKrr9E72nS9VbxDabZUWMqdnlEjK9vKCPjspEIHaOSH-zmXMyS6e1tLibBAhRx1MSr4H9hcOZNA6mSxs0E-J5Ne64ksOOQdf1byZC-v7rUSb37zYWqd8xBMWQ-Bz5p6oshQrRq5ISJEmtY07JIpA2X_A6CITgsnaYX_QNG67S1h0i_zj6iPAywLpLdJmo6EX0gA5yMN9MabhgZNMK2_1mIdWB-I3gcKHrhy9ojnVMlycxVqL-99Yv-SAFQXOxERiNdJIJSeFQ

JWT Payload:

	{
		"jti": "urn:uuid:aecda8ff-b948-4ebb-a0ae-644b31ef73c8",
		"iss": "did:sov:21tDAKCERh95uGgKbJNHYp",
		"iat": 1563195971,
		"nbf": 1563195971,
		"vp": {
			"@context": [
				"https://www.w3.org/2018/credentials/v1"
			],
			"type": [
				"VerifiablePresentation"
			],
			"verifiableCredential": [
				 "eyJhbGciOiJSUzI1NiJ9.eyJqdGkiOiJ1cm46dXVpZDphODdiZGZiOC1hN2RmLTRiZDktYWUwZC1kODgzMTMzNTM4ZmUiLCJzdWIiOiJkaWQ6c292OjIxdERBS0NFUmg5NXVHZ0tiSk5IWXAiLCJpc3MiOiJkaWQ6c292OjF5dlhibWdQb1VtNGRsNjZEN0toeUQiLCJuYmYiOjE1NjA3MTE0MTksImV4cCI6MTU2MDc5NzgxOSwidmMiOnsiQGNvbnRleHQiOlsiaHR0cHM6Ly93d3cudzMub3JnLzIwMTgvY3JlZGVudGlhbHMvdjEiLCJodHRwczovL3RyYWZpLmZpL2NyZWRlbnRpYWxzL3YxIl0sInR5cGUiOlsiVmVyaWZpYWJsZUNyZWRlbnRpYWwiLCJEcml2ZXJzTGljZW5zZUNyZWRlbnRpYWwiXSwiY3JlZGVudGlhbFN1YmplY3QiOnsiZHJpdmVyc0xpY2Vuc2UiOnsibGljZW5zZUNsYXNzIjoidHJ1Y2tzIn19fX0.ZdJxM0kJakKAfJI2h3Dhvf_AHUgC8-NyQRr2DMnlzCxHZyVEji0s5Sl8cNx6aPwwjDagp2KHFy6M9eONHrrpdb49AuKetyJZQUoB5aQg-sC5GMHPVyeTxzazaDWysEiCZSXc6GcirLDmHXVWMUidKDlGh8vdUtrHR0ayVbxrXQ-zKakfltaRawQ4OIRPJ-0fssojSDbRO6KnrH6MQbsl-fwTRcYnlihNIHpNTEpT68DA3QzHU1-TAX1xY3Jx2vYorihFf02mnn5d3gW4Gv2KsNbNpewIAmfL-p-abOFNmt2cLxFUSLsgaE5upDw2xAGTc3lAxvbJ7Gm4eaL8SXTQ2A"
			]
		}
	}

### Example code (signing)

	VerifiableCredential verifiableCredential = new VerifiableCredential();
	verifiableCredential.getContext().add("https://trafi.fi/credentials/v1");
	verifiableCredential.getType().add("DriversLicenseCredential");
	verifiableCredential.setId("urn:uuid:a87bdfb8-a7df-4bd9-ae0d-d883133538fe");
	verifiableCredential.setIssuer("did:sov:1yvXbmgPoUm4dl66D7KhyD");
	verifiableCredential.setIssuanceDate(VerifiableCredential.DATE_FORMAT.parse("2019-06-16T18:56:59Z"));
	verifiableCredential.setExpirationDate(VerifiableCredential.DATE_FORMAT.parse("2019-06-17T18:56:59Z"));
	
	verifiableCredential.setCredentialSubject("did:sov:21tDAKCERh95uGgKbJNHYp");
	LinkedHashMap<String, Object> jsonLdCredentialSubject = verifiableCredential.getJsonLdCredentialSubject();
	LinkedHashMap<String, Object> jsonLdDriversLicense = new LinkedHashMap<String, Object> ();
	jsonLdDriversLicense.put("licenseClass", "trucks");
	jsonLdCredentialSubject.put("driversLicense", jsonLdDriversLicense);
	
	JwtVerifiableCredential jwtVerifiableCredential = JwtVerifiableCredential.fromVerifiableCredential(verifiableCredential);
	
	String jwtString1 = jwtVerifiableCredential.toJwt(AlgorithmIdentifiers.RSA_USING_SHA256, TestUtil.testRSAPrivateKey);
	System.out.println(jwtString1);
	
	String jwtPayload1 = jwtVerifiableCredential.getPayload().toJson();
	System.out.println(jwtPayload1);
	
	JwtVerifiablePresentation jwtVerifiablePresentation = JwtVerifiablePresentation.fromJwtVerifiableCredential(jwtVerifiableCredential);
	String jwtPayload2 = jwtVerifiablePresentation.getPayload().toJson();
	System.out.println(jwtPayload2);
	
	String jwtString2 = jwtVerifiablePresentation.toJwt(AlgorithmIdentifiers.RSA_USING_SHA256, TestUtil.testRSAPrivateKey);
	System.out.println(jwtString2);
