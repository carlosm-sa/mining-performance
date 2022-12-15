Blockchain is an emerging technology that offers great advantages such as global distribution of information and data immutability over time, but its mining process is known to be time consuming and highly resource demanding. There are different algorithms to mine blocks, being able to operate at different levels of complexity and also incurring different compute costs. This study used a custom and simple implementation of the MessageDigest Java class to evaluate the performance of MD5 version 2, SHA2, and SHA3 (the last two in modalities of 256 and 512-bits) when automatically creating a chain of a thousand blocks, measuring its average time for generation and proof of work verification, alongside to the count of incurred iterations. The SHA3 methods produced stronger hash values but performed slower than MD5 and SHA2, and the complexity level of 4 characters offered the best security level in terms of iteration count versus calculation time. Complexity levels of 5 and 6 characters offered greater security but with a drastic performance reduction, which is proper for critical security systems that do not process high volumes of information. These results are useful for those small to medium organizations that are planning to implement blockchain technologies and need a parameter for understanding exactly what ‘mining cost’ really means in terms of compute costs.

Key words: MD5, SHA, proof of work, nonce value, performance.

This application is a Netbeans project. You can download it and open it in Netbeans 12+.

To run the compiled project from the command line, go to the dist folder and
type the following:

java -jar "blockchain-mining.jar" 


This sofware is free to use for education purposes.

Author: Carlos Roberto Martínez
carlosm2@gmail.com
carlos.martinez@catolica.edu.sv
