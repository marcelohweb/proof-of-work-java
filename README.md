# Proof of Work

This project is a simple proof of work implementation for academic purpose.

## Run

Make sure that java 8 is installed and is in the path variable.

	git clone https://github.com/marcelohweb/proof-of-work-java.git
	cd src
	javac ProofOfWork.java
	javac ProofOfWorkVerifier.java
	
## Mining:

	java ProofOfWork 00000 0000038b13568323e3886a7391f6346f555b247bb86f7d9532409874572c45bd 871714dcbae6c8193a2bb9b2a69fe1c0440399f38d94b3a0f1b447275a2991234 1392872245
	
Result:

<img src="http://66.7.213.120/~mswebcom/pow.png">

### Verifing:

	java ProofOfWorkVerifier 00000 0000038b13568323e3886a7391f6346f555b247bb86f7d9532409874572c45bd 871714dcbae6c8193a2bb9b2a69fe1c0440399f38d94b3a0f1b447275a2991234 1392872245 239327

Result:

<img src="http://66.7.213.120/~mswebcom/valid_block.png">